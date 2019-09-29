### replaceFirst      

`String replaceFirst(String regex, String replacement)`   

替换掉第一次出现的字符、字符串，基于正则表达式       

### replaceAll       

`replaceAll(String regex, String replacement)`      

替换所有满足条件的字符或字符串，基于正则表达式    

### replace     

`replace(char oldChar, char newChar)`    

也是替换所有满足条件的字符、字符串，但是不基于正则表达式        


### replace(CharSequence target, CharSequence replacement)与replaceAll源码分析    
 #### replace源码   
```
   /**
     * Replaces each substring of this string that matches the literal target
     * sequence with the specified literal replacement sequence. The
     * replacement proceeds from the beginning of the string to the end, for
     * example, replacing "aa" with "b" in the string "aaa" will result in
     * "ba" rather than "ab".
     *
     * @param  target The sequence of char values to be replaced
     * @param  replacement The replacement sequence of char values
     * @return  The resulting string
     * @since 1.5
     */
    public String replace(CharSequence target, CharSequence replacement) {
        return Pattern.compile(target.toString(), Pattern.LITERAL).matcher(
                this).replaceAll(Matcher.quoteReplacement(replacement.toString()));
    }
```      

`Pattern.compile(target.toString(), Pattern.LITERAL)` 返回一个Pattern类型的对象，调用该对象的`matcher`方法返回一个Matcher类型的对象，该对象的replaceAll方法可以做到替换      

#### replaceAll源码    
```
    public String replaceAll(String regex, String replacement) {
        return Pattern.compile(regex).matcher(this).replaceAll(replacement);
    }
```     
对比replace的代码，replaceAll中的为`Pattern.compile(regex)`，入参为`regex`，而replace的为`Pattern.compile(target.toString(), Pattern.LITERAL)`   

`Pattern.compile()`构造方法如下   
```
 public static Pattern compile(String regex) {
        return new Pattern(regex, 0);
    }
```    
`Pattern(regex, 0)`代码如下  
```
    private Pattern(String p, int f) {
        pattern = p;
        flags = f;

        // to use UNICODE_CASE if UNICODE_CHARACTER_CLASS present
        if ((flags & UNICODE_CHARACTER_CLASS) != 0)
            flags |= UNICODE_CASE;

        // Reset group index count
        capturingGroupCount = 1;
        localCount = 0;

        if (pattern.length() > 0) {
            compile();
        } else {
            root = new Start(lastAccept);
            matchRoot = lastAccept;
        }
    
```    
再看`compile()` 
```
 if (has(LITERAL)) {
            // Literal pattern handling
            matchRoot = newSlice(temp, patternLength, hasSupplementary);
            matchRoot.next = lastAccept;
        } else {
            // Start recursive descent parsing
            matchRoot = expr(lastAccept);
            // Check extra pattern characters
            if (patternLength != cursor) {
                if (peek() == ')') {
                    throw error("Unmatched closing ')'");
                } else {
                    throw error("Unexpected internal error");
                }
            }
        }

```   
重点看这句，如果`has(LITERAL)` 就不走正则校验