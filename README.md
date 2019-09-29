<!-- vscode-markdown-toc -->
* 1. [一、基础篇](#)
	* 1.1. [面向对象](#-1)
		* 1.1.1. [什么是面向对象](#-1)
		* 1.1.2. [平台无关性](#-1)
		* 1.1.3. [值传递](#-1)
		* 1.1.4. [封装、继承、多态](#-1)
	* 1.2. [Java基础知识](#Java)
		* 1.2.1. [基本数据类型](#-1)
		* 1.2.2. [自动拆装箱](#-1)
		* 1.2.3. [String](#String)
		* 1.2.4. [熟悉Java中各种关键字](#Java-1)
		* 1.2.5. [集合类](#-1)
		* 1.2.6. [枚举](#-1)
		* 1.2.7. [IO](#IO)
		* 1.2.8. [Java反射与javassist](#Javajavassist)
		* 1.2.9. [动态代理](#-1)
		* 1.2.10. [序列化](#-1)
		* 1.2.11. [注解](#-1)
		* 1.2.12. [JMS](#JMS)
		* 1.2.13. [JMX](#JMX)
		* 1.2.14. [泛型](#-1)
		* 1.2.15. [单元测试](#-1)
		* 1.2.16. [正则表达式](#-1)
		* 1.2.17. [常用的Java工具库](#Java-1)
		* 1.2.18. [API&SPI](#APISPI)
		* 1.2.19. [异常](#-1)
		* 1.2.20. [时间处理](#-1)
		* 1.2.21. [编码方式](#-1)
		* 1.2.22. [语法糖](#-1)
	* 1.3. [阅读源代码](#-1)
	* 1.4. [Java并发编程](#Java-1)
		* 1.4.1. [并发与并行](#-1)
		* 1.4.2. [线程](#-1)
		* 1.4.3. [线程池](#-1)
		* 1.4.4. [线程安全](#-1)
		* 1.4.5. [锁](#-1)
		* 1.4.6. [死锁](#-1)
		* 1.4.7. [synchronized](#synchronized)
		* 1.4.8. [volatile](#volatile)
		* 1.4.9. [sleep 和 wait](#sleepwait)
		* 1.4.10. [wait 和 notify](#waitnotify)
		* 1.4.11. [notify 和 notifyAll](#notifynotifyAll)
		* 1.4.12. [ThreadLocal](#ThreadLocal)
		* 1.4.13. [写一个死锁的程序](#-1)
		* 1.4.14. [写代码来解决生产者消费者问题](#-1)
	* 1.5. [并发包](#-1)
		* 1.5.1. [阅读源代码，并学会使用](#-1)
* 2. [二、底层篇](#-1)
	* 2.1. [JVM](#JVM)
		* 2.1.1. [JVM内存结构](#JVM-1)
		* 2.1.2. [Java内存模型](#Java-1)
		* 2.1.3. [垃圾回收](#-1)
		* 2.1.4. [JVM参数及调优](#JVM-1)
		* 2.1.5. [Java对象模型](#Java-1)
		* 2.1.6. [HotSpot](#HotSpot)
		* 2.1.7. [虚拟机性能监控与故障处理工具](#-1)
	* 2.2. [类加载机制](#-1)
	* 2.3. [编译与反编译](#-1)
* 3. [三、 进阶篇](#-1)
	* 3.1. [Java底层知识](#Java-1)
		* 3.1.1. [字节码、class文件格式](#class)
		* 3.1.2. [CPU缓存，L1，L2，L3和伪共享](#CPUL1L2L3)
		* 3.1.3. [尾递归](#-1)
		* 3.1.4. [位运算](#-1)
	* 3.2. [设计模式](#-1)
		* 3.2.1. [了解23种设计模式](#23)
		* 3.2.2. [会使用常用设计模式](#-1)
		* 3.2.3. [不用synchronized和lock，实现线程安全的单例模式](#synchronizedlock)
		* 3.2.4. [实现AOP](#AOP)
		* 3.2.5. [实现IOC](#IOC)
		* 3.2.6. [nio和reactor设计模式](#nioreactor)
	* 3.3. [网络编程知识](#-1)
		* 3.3.1. [tcp、udp、http、https等常用协议](#tcpudphttphttps)
		* 3.3.2. [http/1.0 http/1.1 http/2之间的区别](#http1.0http1.1http2)
		* 3.3.3. [http/3](#http3)
		* 3.3.4. [Java RMI，Socket，HttpClient](#JavaRMISocketHttpClient)
		* 3.3.5. [cookie 与 session](#cookiesession)
		* 3.3.6. [用Java写一个简单的静态文件的HTTP服务器](#JavaHTTP)
		* 3.3.7. [了解nginx和apache服务器的特性并搭建一个对应的服务器](#nginxapache)
		* 3.3.8. [用Java实现FTP、SMTP协议](#JavaFTPSMTP)
		* 3.3.9. [进程间通讯的方式](#-1)
		* 3.3.10. [什么是CDN？如果实现？](#CDN)
		* 3.3.11. [DNS？](#DNS)
		* 3.3.12. [反向代理](#-1)
	* 3.4. [框架知识](#-1)
		* 3.4.1. [Servlet](#Servlet)
		* 3.4.2. [Hibernate](#Hibernate)
		* 3.4.3. [Spring](#Spring)
		* 3.4.4. [Spring MVC](#SpringMVC)
		* 3.4.5. [Spring Boot](#SpringBoot)
		* 3.4.6. [Spring Security](#SpringSecurity)
	* 3.5. [Spring Cloud](#SpringCloud)
	* 3.6. [应用服务器知识](#-1)
		* 3.6.1. [JBoss](#JBoss)
		* 3.6.2. [tomcat](#tomcat)
		* 3.6.3. [jetty](#jetty)
		* 3.6.4. [Weblogic](#Weblogic)
	* 3.7. [工具](#-1)
		* 3.7.1. [git & svn](#gitsvn)
		* 3.7.2. [maven & gradle](#mavengradle)
		* 3.7.3. [Intellij IDEA](#IntellijIDEA)
* 4. [四、 高级篇](#-1)
	* 4.1. [新技术](#-1)
		* 4.1.1. [Java 8](#Java8)
		* 4.1.2. [Java 9](#Java9)
		* 4.1.3. [Java 10](#Java10)
		* 4.1.4. [Java 11](#Java11)
		* 4.1.5. [Spring 5](#Spring5)
		* 4.1.6. [Spring Boot 2.0](#SpringBoot2.0)
	* 4.2. [http/2](#http2)
	* 4.3. [http/3](#http3-1)
	* 4.4. [性能优化](#-1)
	* 4.5. [线上问题分析](#-1)
		* 4.5.1. [dump获取](#dump)
		* 4.5.2. [dump分析](#dump-1)
		* 4.5.3. [dump分析及获取工具](#dump-1)
		* 4.5.4. [自己编写各种outofmemory，stackoverflow程序](#outofmemorystackoverflow)
		* 4.5.5. [Arthas](#Arthas)
		* 4.5.6. [常见问题解决思路](#-1)
		* 4.5.7. [使用工具尝试解决以下问题，并写下总结](#-1)
	* 4.6. [编译原理知识](#-1)
		* 4.6.1. [编译与反编译](#-1)
		* 4.6.2. [Java代码的编译与反编译](#Java-1)
		* 4.6.3. [Java的反编译工具](#Java-1)
		* 4.6.4. [即时编译器](#-1)
		* 4.6.5. [词法分析，语法分析（LL算法，递归下降算法，LR算法），语义分析，运行时环境，中间代码，代码生成，代码优化](#LLLR)
	* 4.7. [操作系统知识](#-1)
		* 4.7.1. [Linux的常用命令](#Linux)
		* 4.7.2. [进程间通信](#-1)
		* 4.7.3. [进程同步](#-1)
		* 4.7.4. [缓冲区溢出](#-1)
		* 4.7.5. [分段和分页](#-1)
		* 4.7.6. [虚拟内存与主存](#-1)
		* 4.7.7. [虚拟内存管理](#-1)
		* 4.7.8. [换页算法](#-1)
	* 4.8. [数据库知识](#-1)
		* 4.8.1. [MySql 执行引擎](#MySql)
		* 4.8.2. [MySQL 执行计划](#MySQL)
		* 4.8.3. [索引](#-1)
		* 4.8.4. [SQL优化](#SQL)
		* 4.8.5. [数据库事务和隔离级别](#-1)
		* 4.8.6. [数据库锁](#-1)
		* 4.8.7. [连接](#-1)
		* 4.8.8. [数据库主备搭建](#-1)
		* 4.8.9. [binlog](#binlog)
		* 4.8.10. [redolog](#redolog)
		* 4.8.11. [内存数据库](#-1)
		* 4.8.12. [分库分表](#-1)
		* 4.8.13. [读写分离](#-1)
		* 4.8.14. [常用的nosql数据库](#nosql)
		* 4.8.15. [分别使用数据库锁、NoSql实现分布式锁](#NoSql)
		* 4.8.16. [性能调优](#-1)
		* 4.8.17. [数据库连接池](#-1)
	* 4.9. [数据结构与算法知识](#-1)
		* 4.9.1. [简单的数据结构](#-1)
		* 4.9.2. [树](#-1)
		* 4.9.3. [堆](#-1)
		* 4.9.4. [图](#-1)
		* 4.9.5. [排序算法](#-1)
		* 4.9.6. [深度优先和广度优先搜索](#-1)
		* 4.9.7. [全排列、贪心算法、KMP算法、hash算法](#KMPhash)
		* 4.9.8. [海量数据处理](#-1)
		* 4.9.9. [两个栈实现队列，和两个队列实现栈](#-1)
	* 4.10. [大数据知识](#-1)
		* 4.10.1. [Zookeeper](#Zookeeper)
		* 4.10.2. [Solr，Lucene，ElasticSearch](#SolrLuceneElasticSearch)
		* 4.10.3. [Storm，流式计算，了解Spark，S4](#StormSparkS4)
		* 4.10.4. [Hadoop，离线计算](#Hadoop)
		* 4.10.5. [分布式日志收集flume，kafka，logstash](#flumekafkalogstash)
		* 4.10.6. [数据挖掘，mahout](#mahout)
	* 4.11. [网络安全知识](#-1)
		* 4.11.1. [XSS](#XSS)
		* 4.11.2. [CSRF](#CSRF)
		* 4.11.3. [注入攻击](#-1)
		* 4.11.4. [文件上传漏洞](#-1)
		* 4.11.5. [加密与解密](#-1)
		* 4.11.6. [DDOS攻击](#DDOS)
		* 4.11.7. [SSL、TLS，HTTPS](#SSLTLSHTTPS)
		* 4.11.8. [用openssl签一个证书部署到apache或nginx](#opensslapachenginx)
* 5. [五、架构篇](#-1)
	* 5.1. [分布式](#-1)
		* 5.1.1. [分布式事务](#-1)
		* 5.1.2. [Dubbo](#Dubbo)
		* 5.1.3. [分布式数据库](#-1)
		* 5.1.4. [分布式文件系统](#-1)
		* 5.1.5. [分布式缓存](#-1)
		* 5.1.6. [限流降级](#-1)
		* 5.1.7. [算法](#-1)
	* 5.2. [微服务](#-1)
		* 5.2.1. [ServiceMesh](#ServiceMesh)
		* 5.2.2. [Docker & Kubernets](#DockerKubernets)
		* 5.2.3. [Spring Boot](#SpringBoot-1)
		* 5.2.4. [Spring Cloud](#SpringCloud-1)
	* 5.3. [高并发](#-1)
		* 5.3.1. [分库分表](#-1)
		* 5.3.2. [CDN技术](#CDN-1)
		* 5.3.3. [消息队列](#-1)
	* 5.4. [监控](#-1)
		* 5.4.1. [监控什么](#-1)
		* 5.4.2. [监控手段](#-1)
		* 5.4.3. [监控数据采集](#-1)
		* 5.4.4. [Dapper](#Dapper)
	* 5.5. [负载均衡](#-1)
	* 5.6. [DNS](#DNS-1)
	* 5.7. [CDN](#CDN-1)
* 6. [六、 扩展篇](#-1)
	* 6.1. [云计算](#-1)
	* 6.2. [搜索引擎](#-1)
	* 6.3. [权限管理](#-1)
	* 6.4. [区块链](#-1)
		* 6.4.1. [比特币](#-1)
		* 6.4.2. [以太坊](#-1)
		* 6.4.3. [超级账本](#-1)
	* 6.5. [人工智能](#-1)
		* 6.5.1. [常用框架](#-1)
	* 6.6. [IoT](#IoT)
	* 6.7. [量子计算](#-1)
	* 6.8. [AR & VR](#ARVR)
	* 6.9. [其他语言](#-1)
* 7. [六、 推荐书籍](#-1)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->
[全套思维导图](/mind-map.md)     
  

##  1. <a name=''></a>一、基础篇

###  1.1. <a name='-1'></a>面向对象

####  1.1.1. <a name='-1'></a>什么是面向对象

[面向对象、面向过程](/basics/java-basic/object-oriented-vs-procedure-oriented.md)

[面向对象的三大基本特征](/basics/java-basic/characteristics.md)和[五大基本原则](/basics/java-basic/principle.md)  

[类、对象、引用](/basics/java-basics/class-object-reference.md)    


####  1.1.2. <a name='-1'></a>平台无关性

[Java如何实现的平台无关性的](/basics/java-basic/platform-independent.md)

[JVM还支持哪些语言（Kotlin、Groovy、JRuby、Jython、Scala）](/basics/java-basic/jvm-language.md)

####  1.1.3. <a name='-1'></a>值传递

[值传递、引用传递](/basics/java-basic/java-pass-by.md)

[为什么说Java中只有值传递](/basics/java-basic/java-pass-by.md)

####  1.1.4. <a name='-1'></a>封装、继承、多态

[什么是多态](/basics/java-basic/polymorphism.md)、[方法重写与重载](/basics/java-basic/overloading-vs-overriding.md)

Java的继承与实现

[Java的继承与组合](/basics/java-basic/inheritance-composition.md)

[构造函数与默认构造函数](/basics/java-basic/constructor.md)

[类变量、成员变量和局部变量](/basics/java-basic/variable.md)

[成员变量和方法作用域](/basics/java-basic/scope.md)

###  1.2. <a name='Java'></a>Java基础知识

####  1.2.1. <a name='-1'></a>基本数据类型

[7种基本数据类型：整型、浮点型、布尔型、字符型](/basics/java-basic/basic-data-types.md)

[整型中byte、short、int、long的取值范围](/basics/java-basic/integer-scope.md)

[什么是浮点型？](/basics/java-basic/float.md)

[什么是单精度和双精度？](/basics/java-basic/single-double-float.md)

[为什么不能用浮点型表示金额？](/basics/java-basic/float-amount.md)

####  1.2.2. <a name='-1'></a>自动拆装箱

[什么是包装类型、什么是基本类型、什么是自动拆装箱](/basics/java-basic/boxing-unboxing.md)

[Integer的缓存机制](/basics/java-basic/integer-cache.md)

####  1.2.3. <a name='String'></a>String

[字符串的不可变性](/basics/java-basic/final-string.md)

[JDK 6和JDK 7中substring的原理及区别](/basics/java-basic/substring.md)

[replaceFirst、replaceAll、replace区别](/basics/java-basic/diff-in-replaceFirst-replace-replaceAll.md)

[String对“+”的重载](/basics/java-basic/string-append.md)

[字符串拼接的几种方式和区别](/basics/java-basic/string-concat.md)

[String.valueOf和Integer.toString的区别](/basics/java-basic/value-of-vs-to-string.md)

[switch对String的支持](/basics/java-basic/switch-string.md)

[字符串池、常量池（运行时常量池、Class常量池）、intern](/basics/java-basic/stringPool-constantPool.md)

####  1.2.4. <a name='Java-1'></a>熟悉Java中各种关键字

transient、instanceof、volatile、synchronized、final、static、const 原理及用法。

####  1.2.5. <a name='-1'></a>集合类

常用集合类的使用

[ArrayList和LinkedList和Vector的区别](/basics/java-basic/arraylist-vs-linkedlist-vs-vector.md) 

[SynchronizedList和Vector的区别](/basics/java-basic/synchronizedlist-vector.md)、

[HashMap、HashTable、ConcurrentHashMap区别](/basics/java-basic/HashMap-HashTable-ConcurrentHashMap.md)

[Set和List区别？](/basics/java-basic/set-vs-list.md)

[Set如何保证元素不重复?](/basics/java-basic/set-repetition.md)

[Java 8中stream相关用法](/basics/java-basic/stream.md)、

apache集合处理工具类的使用、

不同版本的JDK中HashMap的实现的区别以及原因

[Collection和Collections区别](/basics/java-basic/Collection-vs-Collections.md)

[Arrays.asList获得的List使用时需要注意什么](/basics/java-basic/Arrays-asList.md)

[Enumeration和Iterator区别](/basics/java-basic/Enumeration-vs-Iterator.md)

[fail-fast 和 fail-safe](/basics/java-basic/fail-fast-vs-fail-safe.md)

[CopyOnWriteArrayList](/basics/java-basic/CopyOnWriteArrayList.md)

[ConcurrentSkipListMap](/basics/java-basic/ConcurrentSkipListMap.md)

####  1.2.6. <a name='-1'></a>枚举

[枚举的用法](/basics/java-basic/enum-usage.md)

[枚举的实现](/basics/java-basic/enum-impl.md)

[枚举与单例](/basics/java-basic/enum-singleton.md)、Enum类

[Java枚举如何比较](/basics/java-basic/enum-compare.md)

[switch对枚举的支持](/basics/java-basic/enum-switch.md)

[枚举的序列化如何实现](/basics/java-basic/enum-serializable.md)

[枚举的线程安全性问题](/basics/java-basic/enum-thread-safe.md)

####  1.2.7. <a name='IO'></a>IO

[字符流、字节流](/basics/java-basic/byte-stream-vs-character-stream.md)、[输入流、输出流](/basics/java-basic/input-stream-vs-output-stream.md)

[同步、异步](/basics/java-basic/synchronized-vs-asynchronization.md)、[阻塞、非阻塞](/basics/java-basic/block-vs-non-blocking.md)、[Linux 5种IO模型](/basics/java-basic/linux-io.md)

[BIO、NIO和AIO的区别、三种IO的用法与原理](/basics/java-basic/bio-vs-nio-vs-aio.md)、netty

####  1.2.8. <a name='Javajavassist'></a>Java反射与javassist

[反射](/basics/java-basic/reflection.md)与工厂模式、 [反射有什么作用](/basics/java-basic/usage-of-reflection.md)

[Class类](/basics/java-basic/Class.md)

`java.lang.reflect.*`

####  1.2.9. <a name='-1'></a>动态代理

[静态代理](/basics/java-basic/static-proxy.md)、[动态代理](/basics/java-basic/dynamic-proxy.md)

[动态代理和反射的关系](/basics/java-basic/dynamic-proxy-vs-reflection.md)

[动态代理的几种实现方式](/basics/java-basic/dynamic-proxy-implementation.md)

[AOP](/basics/java-basic/aop-vs-proxy.md)

####  1.2.10. <a name='-1'></a>序列化

[什么是序列化与反序列化](/basics/java-basic/serialize.md)、为什么序列化、[序列化底层原理](/basics/java-basic/serialize-principle.md)、[序列化与单例模式](/basics/java-basic/serialize-singleton.md)、protobuf、为什么说序列化并不安全

####  1.2.11. <a name='-1'></a>注解

[元注解](/basics/java-basic/meta-annotation.md)、[自定义注解](/basics/java-basic/custom-annotation.md)、Java中常用注解使用、注解与反射的结合

[如何自定义一个注解？](/basics/java-basic/create-annotation.md)

[Spring常用注解](/basics/java-basic/annotation-in-spring.md)

####  1.2.12. <a name='JMS'></a>JMS

什么是Java消息服务、JMS消息传送模型

####  1.2.13. <a name='JMX'></a>JMX

`java.lang.management.*`、 `javax.management.*`

####  1.2.14. <a name='-1'></a>泛型

泛型与继承、类型擦除、[泛型中K T V E ？ object等的含义](/basics/java-basic/k-t-v-e.md)、泛型各种用法

限定通配符和非限定通配符、上下界限定符extends 和 super

[List<Object>和原始类型List之间的区别?](/basics/java-basic/genericity-list.md)

[List<?>和List<Object>之间的区别是什么?](/basics/java-basic/genericity-list-wildcard.md)

####  1.2.15. <a name='-1'></a>单元测试

junit、mock、mockito、内存数据库（h2）

####  1.2.16. <a name='-1'></a>正则表达式

`java.lang.util.regex.*`

####  1.2.17. <a name='Java-1'></a>常用的Java工具库

`commons.lang`, `commons.*...` `guava-libraries` `netty`

####  1.2.18. <a name='APISPI'></a>API&SPI

API、[API和SPI的关系和区别](/basics/java-basic/api-vs-spi.md)

[如何定义SPI](/basics/java-basic/create-spi.md)、[SPI的实现原理](/basics/java-basic/spi-principle.md)

####  1.2.19. <a name='-1'></a>异常

异常类型、正确处理异常、自定义异常

Error和Exception

异常链、try-with-resources

finally和return的执行顺序

####  1.2.20. <a name='-1'></a>时间处理

时区、冬令时和夏令时、时间戳、Java中时间API

格林威治时间、CET,UTC,GMT,CST几种常见时间的含义和关系

SimpleDateFormat的线程安全性问题

Java 8中的时间处理

如何在东八区的计算机上获取美国时间

####  1.2.21. <a name='-1'></a>编码方式

Unicode、有了Unicode为啥还需要UTF-8

GBK、GB2312、GB18030之间的区别

UTF8、UTF16、UTF32区别

URL编解码、Big Endian和Little Endian

如何解决乱码问题

####  1.2.22. <a name='-1'></a>语法糖

Java中语法糖原理、解语法糖

语法糖：switch 支持 String 与枚举、泛型、自动装箱与拆箱、方法变长参数、枚举、内部类、条件编译、 断言、数值字面量、for-each、try-with-resource、Lambda表达式、

###  1.3. <a name='-1'></a>阅读源代码

String、Integer、Long、Enum、BigDecimal、ThreadLocal、ClassLoader & URLClassLoader、ArrayList & LinkedList、 HashMap & LinkedHashMap & TreeMap & CouncurrentHashMap、HashSet & LinkedHashSet & TreeSet

###  1.4. <a name='Java-1'></a>Java并发编程

####  1.4.1. <a name='-1'></a>并发与并行

什么是并发

什么是并行

并发与并行的区别

####  1.4.2. <a name='-1'></a>线程

线程的实现、线程的状态、优先级、线程调度、创建线程的多种方式、守护线程

线程与进程的区别

####  1.4.3. <a name='-1'></a>线程池

自己设计线程池、submit() 和 execute()、线程池原理

为什么不允许使用Executors创建线程池

####  1.4.4. <a name='-1'></a>线程安全

[死锁？](/basics/java-basic/deadlock-java-level.md)、死锁如何排查、线程安全和内存模型的关系

####  1.4.5. <a name='-1'></a>锁

CAS、乐观锁与悲观锁、数据库相关锁机制、分布式锁、偏向锁、轻量级锁、重量级锁、monitor、

锁优化、锁消除、锁粗化、自旋锁、可重入锁、阻塞锁、死锁

####  1.4.6. <a name='-1'></a>死锁

死锁的原因

死锁的解决办法

####  1.4.7. <a name='synchronized'></a>synchronized

[synchronized是如何实现的？](/basics/java-basic/synchronized.md)

synchronized和lock之间关系、不使用synchronized如何实现一个线程安全的单例

synchronized和原子性、可见性和有序性之间的关系

####  1.4.8. <a name='volatile'></a>volatile

happens-before、内存屏障、编译器指令重排和CPU指令重排

volatile的实现原理

volatile和原子性、可见性和有序性之间的关系

有了symchronized为什么还需要volatile

####  1.4.9. <a name='sleepwait'></a>sleep 和 wait

####  1.4.10. <a name='waitnotify'></a>wait 和 notify

####  1.4.11. <a name='notifynotifyAll'></a>notify 和 notifyAll

####  1.4.12. <a name='ThreadLocal'></a>ThreadLocal

####  1.4.13. <a name='-1'></a>写一个死锁的程序

####  1.4.14. <a name='-1'></a>写代码来解决生产者消费者问题

###  1.5. <a name='-1'></a>并发包

####  1.5.1. <a name='-1'></a>阅读源代码，并学会使用

Thread、Runnable、Callable、ReentrantLock、ReentrantReadWriteLock、Atomic*、Semaphore、CountDownLatch、、ConcurrentHashMap、Executors

##  2. <a name='-1'></a>二、底层篇

###  2.1. <a name='JVM'></a>JVM

####  2.1.1. <a name='JVM-1'></a>JVM内存结构

class文件格式、运行时数据区：堆、栈、方法区、直接内存、运行时常量池、

堆和栈区别

Java中的对象一定在堆上分配吗？

####  2.1.2. <a name='Java-1'></a>Java内存模型

计算机内存模型、缓存一致性、MESI协议

可见性、原子性、顺序性、happens-before、

内存屏障、synchronized、volatile、final、锁

####  2.1.3. <a name='-1'></a>垃圾回收

GC算法：标记清除、引用计数、复制、标记压缩、分代回收、增量式回收

GC参数、对象存活的判定、垃圾收集器（CMS、G1、ZGC、Epsilon）

####  2.1.4. <a name='JVM-1'></a>JVM参数及调优

-Xmx、-Xmn、-Xms、Xss、-XX:SurvivorRatio、

-XX:PermSize、-XX:MaxPermSize、-XX:MaxTenuringThreshold

####  2.1.5. <a name='Java-1'></a>Java对象模型

oop-klass、对象头

####  2.1.6. <a name='HotSpot'></a>HotSpot

即时编译器、编译优化

####  2.1.7. <a name='-1'></a>虚拟机性能监控与故障处理工具

jps, jstack, jmap、jstat, jconsole, jinfo, jhat, javap, btrace、TProfiler

Arthas

###  2.2. <a name='-1'></a>类加载机制

classLoader、类加载过程、双亲委派（破坏双亲委派）、模块化（jboss modules、osgi、jigsaw）

###  2.3. <a name='-1'></a>编译与反编译

什么是编译（前端编译、后端编译）、什么是反编译

JIT、JIT优化（逃逸分析、栈上分配、标量替换、锁优化）

编译工具：javac

反编译工具：javap 、jad 、CRF

##  3. <a name='-1'></a>三、 进阶篇

###  3.1. <a name='Java-1'></a>Java底层知识

####  3.1.1. <a name='class'></a>字节码、class文件格式

####  3.1.2. <a name='CPUL1L2L3'></a>CPU缓存，L1，L2，L3和伪共享

####  3.1.3. <a name='-1'></a>尾递归

####  3.1.4. <a name='-1'></a>位运算

用位运算实现加、减、乘、除、取余

###  3.2. <a name='-1'></a>设计模式

设计模式的六大原则：

开闭原则（Open Close Principle）、里氏代换原则（Liskov Substitution Principle）、依赖倒转原则（Dependence Inversion Principle）

接口隔离原则（Interface Segregation Principle）、迪米特法则（最少知道原则）（Demeter Principle）、合成复用原则（Composite Reuse Principle）

####  3.2.1. <a name='23'></a>了解23种设计模式

创建型模式：单例模式、抽象工厂模式、建造者模式、工厂模式、原型模式。

结构型模式：适配器模式、桥接模式、装饰模式、组合模式、外观模式、享元模式、代理模式。

行为型模式：模版方法模式、命令模式、迭代器模式、观察者模式、中介者模式、备忘录模式、解释器模式（Interpreter模式）、状态模式、策略模式、职责链模式(责任链模式)、访问者模式。

####  3.2.2. <a name='-1'></a>会使用常用设计模式

单例的七种写法：懒汉——线程不安全、懒汉——线程安全、饿汉、饿汉——变种、静态内部类、枚举、双重校验锁

工厂模式、适配器模式、策略模式、模板方法模式、观察者模式、外观模式、代理模式等必会

####  3.2.3. <a name='synchronizedlock'></a>不用synchronized和lock，实现线程安全的单例模式

####  3.2.4. <a name='AOP'></a>实现AOP

####  3.2.5. <a name='IOC'></a>实现IOC

####  3.2.6. <a name='nioreactor'></a>nio和reactor设计模式

###  3.3. <a name='-1'></a>网络编程知识

####  3.3.1. <a name='tcpudphttphttps'></a>tcp、udp、http、https等常用协议

三次握手与四次关闭、流量控制和拥塞控制、OSI七层模型、tcp粘包与拆包

####  3.3.2. <a name='http1.0http1.1http2'></a>http/1.0 http/1.1 http/2之间的区别

http中 get和post区别

常见的web请求返回的状态码

404、302、301、500分别代表什么

####  3.3.3. <a name='http3'></a>http/3

####  3.3.4. <a name='JavaRMISocketHttpClient'></a>Java RMI，Socket，HttpClient

####  3.3.5. <a name='cookiesession'></a>cookie 与 session

cookie被禁用，如何实现session

####  3.3.6. <a name='JavaHTTP'></a>用Java写一个简单的静态文件的HTTP服务器

####  3.3.7. <a name='nginxapache'></a>了解nginx和apache服务器的特性并搭建一个对应的服务器

####  3.3.8. <a name='JavaFTPSMTP'></a>用Java实现FTP、SMTP协议

####  3.3.9. <a name='-1'></a>进程间通讯的方式

####  3.3.10. <a name='CDN'></a>什么是CDN？如果实现？

####  3.3.11. <a name='DNS'></a>DNS？

什么是DNS 、记录类型:A记录、CNAME记录、AAAA记录等

域名解析、根域名服务器

DNS污染、DNS劫持、公共DNS：114 DNS、Google DNS、OpenDNS

####  3.3.12. <a name='-1'></a>反向代理

正向代理、反向代理

反向代理服务器

###  3.4. <a name='-1'></a>框架知识

####  3.4.1. <a name='Servlet'></a>Servlet

生命周期

线程安全问题

filter和listener

web.xml中常用配置及作用

####  3.4.2. <a name='Hibernate'></a>Hibernate

什么是OR Mapping

Hibernate的缓存机制

Hibernate的懒加载

Hibernate/Ibatis/MyBatis之间的区别

####  3.4.3. <a name='Spring'></a>Spring 

Bean的初始化

AOP原理

实现Spring的IOC

spring四种依赖注入方式

####  3.4.4. <a name='SpringMVC'></a>Spring MVC

什么是MVC

Spring mvc与Struts mvc的区别

####  3.4.5. <a name='SpringBoot'></a>Spring Boot

Spring Boot 2.0、起步依赖、自动配置、

Spring Boot的starter原理，自己实现一个starter

####  3.4.6. <a name='SpringSecurity'></a>Spring Security

###  3.5. <a name='SpringCloud'></a>Spring Cloud

服务发现与注册：Eureka、Zookeeper、Consul

负载均衡：Feign、Spring Cloud Loadbalance

服务配置：Spring Cloud Config

服务限流与熔断：Hystrix

服务链路追踪：Dapper

服务网关、安全、消息

###  3.6. <a name='-1'></a>应用服务器知识

####  3.6.1. <a name='JBoss'></a>JBoss

####  3.6.2. <a name='tomcat'></a>tomcat

####  3.6.3. <a name='jetty'></a>jetty

####  3.6.4. <a name='Weblogic'></a>Weblogic

###  3.7. <a name='-1'></a>工具

####  3.7.1. <a name='gitsvn'></a>git & svn

####  3.7.2. <a name='mavengradle'></a>maven & gradle

####  3.7.3. <a name='IntellijIDEA'></a>Intellij IDEA

常用插件：Maven Helper 、FindBugs-IDEA、阿里巴巴代码规约检测、GsonFormat

Lombok plugin、.ignore、Mybatis plugin

##  4. <a name='-1'></a>四、 高级篇

###  4.1. <a name='-1'></a>新技术

####  4.1.1. <a name='Java8'></a>Java 8

lambda表达式、Stream API、时间API

####  4.1.2. <a name='Java9'></a>Java 9

Jigsaw、Jshell、Reactive Streams

####  4.1.3. <a name='Java10'></a>Java 10

局部变量类型推断、G1的并行Full GC、ThreadLocal握手机制

####  4.1.4. <a name='Java11'></a>Java 11

ZGC、Epsilon、增强var、

####  4.1.5. <a name='Spring5'></a>Spring 5

响应式编程

####  4.1.6. <a name='SpringBoot2.0'></a>Spring Boot 2.0

###  4.2. <a name='http2'></a>http/2

###  4.3. <a name='http3-1'></a>http/3

###  4.4. <a name='-1'></a>性能优化

使用单例、使用Future模式、使用线程池、选择就绪、减少上下文切换、减少锁粒度、数据压缩、结果缓存

###  4.5. <a name='-1'></a>线上问题分析

####  4.5.1. <a name='dump'></a>dump获取

线程Dump、内存Dump、gc情况

####  4.5.2. <a name='dump-1'></a>dump分析

分析死锁、分析内存泄露

####  4.5.3. <a name='dump-1'></a>dump分析及获取工具

jstack、jstat、jmap、jhat、Arthas

####  4.5.4. <a name='outofmemorystackoverflow'></a>自己编写各种outofmemory，stackoverflow程序

HeapOutOfMemory、 Young OutOfMemory、MethodArea OutOfMemory、ConstantPool OutOfMemory、DirectMemory OutOfMemory、Stack OutOfMemory Stack OverFlow

####  4.5.5. <a name='Arthas'></a>Arthas

jvm相关、class/classloader相关、monitor/watch/trace相关、

options、管道、后台异步任务

文档：https://alibaba.github.io/arthas/advanced-use.html

####  4.5.6. <a name='-1'></a>常见问题解决思路

内存溢出、线程死锁、类加载冲突

####  4.5.7. <a name='-1'></a>使用工具尝试解决以下问题，并写下总结

当一个Java程序响应很慢时如何查找问题、

当一个Java程序频繁FullGC时如何解决问题、

如何查看垃圾回收日志、

当一个Java应用发生OutOfMemory时该如何解决、

如何判断是否出现死锁、

如何判断是否存在内存泄露

使用Arthas快速排查Spring Boot应用404/401问题

使用Arthas排查线上应用日志打满问题

利用Arthas排查Spring Boot应用NoSuchMethodError

###  4.6. <a name='-1'></a>编译原理知识

####  4.6.1. <a name='-1'></a>编译与反编译

####  4.6.2. <a name='Java-1'></a>Java代码的编译与反编译

####  4.6.3. <a name='Java-1'></a>Java的反编译工具

javap 、jad 、CRF

####  4.6.4. <a name='-1'></a>即时编译器

####  4.6.5. <a name='LLLR'></a>词法分析，语法分析（LL算法，递归下降算法，LR算法），语义分析，运行时环境，中间代码，代码生成，代码优化

###  4.7. <a name='-1'></a>操作系统知识

####  4.7.1. <a name='Linux'></a>Linux的常用命令

####  4.7.2. <a name='-1'></a>进程间通信

####  4.7.3. <a name='-1'></a>进程同步

生产者消费者问题、哲学家就餐问题、读者写者问题

####  4.7.4. <a name='-1'></a>缓冲区溢出

####  4.7.5. <a name='-1'></a>分段和分页

####  4.7.6. <a name='-1'></a>虚拟内存与主存

####  4.7.7. <a name='-1'></a>虚拟内存管理

####  4.7.8. <a name='-1'></a>换页算法

###  4.8. <a name='-1'></a>数据库知识

####  4.8.1. <a name='MySql'></a>MySql 执行引擎

####  4.8.2. <a name='MySQL'></a>MySQL 执行计划

如何查看执行计划，如何根据执行计划进行SQL优化

####  4.8.3. <a name='-1'></a>索引

Hash索引、B树索引（B+树、和B树、R树）

普通索引、唯一索引

覆盖索引、最左前缀原则、索引下推

####  4.8.4. <a name='SQL'></a>SQL优化

####  4.8.5. <a name='-1'></a>数据库事务和隔离级别

事务的隔离级别、事务能不能实现锁的功能

####  4.8.6. <a name='-1'></a>数据库锁

行锁、表锁、使用数据库锁实现乐观锁、

####  4.8.7. <a name='-1'></a>连接

内连接，左连接，右连接

####  4.8.8. <a name='-1'></a>数据库主备搭建

####  4.8.9. <a name='binlog'></a>binlog 

####  4.8.10. <a name='redolog'></a>redolog

####  4.8.11. <a name='-1'></a>内存数据库

h2

####  4.8.12. <a name='-1'></a>分库分表

####  4.8.13. <a name='-1'></a>读写分离

####  4.8.14. <a name='nosql'></a>常用的nosql数据库

redis、memcached

####  4.8.15. <a name='NoSql'></a>分别使用数据库锁、NoSql实现分布式锁

####  4.8.16. <a name='-1'></a>性能调优

####  4.8.17. <a name='-1'></a>数据库连接池

###  4.9. <a name='-1'></a>数据结构与算法知识

####  4.9.1. <a name='-1'></a>简单的数据结构

栈、队列、链表、数组、哈希表、

栈和队列的相同和不同之处

栈通常采用的两种存储结构

####  4.9.2. <a name='-1'></a>树

二叉树、字典树、平衡树、排序树、B树、B+树、R树、多路树、红黑树

####  4.9.3. <a name='-1'></a>堆

大根堆、小根堆

####  4.9.4. <a name='-1'></a>图

有向图、无向图、拓扑

####  4.9.5. <a name='-1'></a>排序算法

稳定的排序：冒泡排序、插入排序、鸡尾酒排序、桶排序、计数排序、归并排序、原地归并排序、二叉排序树排序、鸽巢排序、基数排序、侏儒排序、图书馆排序、块排序

不稳定的排序：选择排序、希尔排序、Clover排序算法、梳排序、堆排序、平滑排序、快速排序、内省排序、耐心排序

各种排序算法和时间复杂度 

####  4.9.6. <a name='-1'></a>深度优先和广度优先搜索 

####  4.9.7. <a name='KMPhash'></a>全排列、贪心算法、KMP算法、hash算法

####  4.9.8. <a name='-1'></a>海量数据处理

分治，hash映射，堆排序，双层桶划分，Bloom Filter，bitmap，数据库索引，mapreduce等。

####  4.9.9. <a name='-1'></a>两个栈实现队列，和两个队列实现栈

###  4.10. <a name='-1'></a>大数据知识

####  4.10.1. <a name='Zookeeper'></a>Zookeeper

基本概念、常见用法

####  4.10.2. <a name='SolrLuceneElasticSearch'></a>Solr，Lucene，ElasticSearch

在linux上部署solr，solrcloud，，新增、删除、查询索引

####  4.10.3. <a name='StormSparkS4'></a>Storm，流式计算，了解Spark，S4

在linux上部署storm，用zookeeper做协调，运行storm hello world，local和remote模式运行调试storm topology。

####  4.10.4. <a name='Hadoop'></a>Hadoop，离线计算

HDFS、MapReduce

####  4.10.5. <a name='flumekafkalogstash'></a>分布式日志收集flume，kafka，logstash

####  4.10.6. <a name='mahout'></a>数据挖掘，mahout

###  4.11. <a name='-1'></a>网络安全知识

####  4.11.1. <a name='XSS'></a>XSS

XSS的防御

####  4.11.2. <a name='CSRF'></a>CSRF

####  4.11.3. <a name='-1'></a>注入攻击

SQL注入、XML注入、CRLF注入

####  4.11.4. <a name='-1'></a>文件上传漏洞

####  4.11.5. <a name='-1'></a>加密与解密

对称加密、非对称加密、哈希算法、加盐哈希算法

MD5，SHA1、DES、AES、RSA、DSA

彩虹表

####  4.11.6. <a name='DDOS'></a>DDOS攻击

DOS攻击、DDOS攻击

memcached为什么可以导致DDos攻击、什么是反射型DDoS

如何通过Hash碰撞进行DOS攻击

####  4.11.7. <a name='SSLTLSHTTPS'></a>SSL、TLS，HTTPS

####  4.11.8. <a name='opensslapachenginx'></a>用openssl签一个证书部署到apache或nginx

##  5. <a name='-1'></a>五、架构篇

###  5.1. <a name='-1'></a>分布式

数据一致性、服务治理、服务降级

####  5.1.1. <a name='-1'></a>分布式事务

2PC、3PC、CAP、BASE、 可靠消息最终一致性、最大努力通知、TCC

####  5.1.2. <a name='Dubbo'></a>Dubbo

服务注册、服务发现，服务治理

http://dubbo.apache.org/zh-cn/

####  5.1.3. <a name='-1'></a>分布式数据库

怎样打造一个分布式数据库、什么时候需要分布式数据库、mycat、otter、HBase

####  5.1.4. <a name='-1'></a>分布式文件系统

mfs、fastdfs

####  5.1.5. <a name='-1'></a>分布式缓存

缓存一致性、缓存命中率、缓存冗余

####  5.1.6. <a name='-1'></a>限流降级

Hystrix、Sentinal

####  5.1.7. <a name='-1'></a>算法

共识算法、Raft协议、Paxos 算法与 Raft 算法、拜占庭问题与算法

2PC、3PC

###  5.2. <a name='-1'></a>微服务

SOA、康威定律

####  5.2.1. <a name='ServiceMesh'></a>ServiceMesh

sidecar

####  5.2.2. <a name='DockerKubernets'></a>Docker & Kubernets

####  5.2.3. <a name='SpringBoot-1'></a>Spring Boot

####  5.2.4. <a name='SpringCloud-1'></a>Spring Cloud

###  5.3. <a name='-1'></a>高并发

####  5.3.1. <a name='-1'></a>分库分表

####  5.3.2. <a name='CDN-1'></a>CDN技术

####  5.3.3. <a name='-1'></a>消息队列

ActiveMQ

###  5.4. <a name='-1'></a>监控

####  5.4.1. <a name='-1'></a>监控什么

CPU、内存、磁盘I/O、网络I/O等

####  5.4.2. <a name='-1'></a>监控手段

进程监控、语义监控、机器资源监控、数据波动

####  5.4.3. <a name='-1'></a>监控数据采集

日志、埋点

####  5.4.4. <a name='Dapper'></a>Dapper

###  5.5. <a name='-1'></a>负载均衡

tomcat负载均衡、Nginx负载均衡

四层负载均衡、七层负载均衡

###  5.6. <a name='DNS-1'></a>DNS

DNS原理、DNS的设计

###  5.7. <a name='CDN-1'></a>CDN

数据一致性

##  6. <a name='-1'></a>六、 扩展篇

###  6.1. <a name='-1'></a>云计算

IaaS、SaaS、PaaS、虚拟化技术、openstack、Serverlsess

###  6.2. <a name='-1'></a>搜索引擎

Solr、Lucene、Nutch、Elasticsearch

###  6.3. <a name='-1'></a>权限管理

Shiro

###  6.4. <a name='-1'></a>区块链

哈希算法、Merkle树、公钥密码算法、共识算法、Raft协议、Paxos 算法与 Raft 算法、拜占庭问题与算法、消息认证码与数字签名

####  6.4.1. <a name='-1'></a>比特币

挖矿、共识机制、闪电网络、侧链、热点问题、分叉

####  6.4.2. <a name='-1'></a>以太坊

####  6.4.3. <a name='-1'></a>超级账本

###  6.5. <a name='-1'></a>人工智能

数学基础、机器学习、人工神经网络、深度学习、应用场景。

####  6.5.1. <a name='-1'></a>常用框架

TensorFlow、DeepLearning4J

###  6.6. <a name='IoT'></a>IoT

###  6.7. <a name='-1'></a>量子计算

###  6.8. <a name='ARVR'></a>AR & VR

###  6.9. <a name='-1'></a>其他语言

Groovy、Python、Go、NodeJs、Swift、Rust

##  7. <a name='-1'></a>六、 推荐书籍

《深入理解Java虚拟机》 
《Effective Java》 
《深入分析Java Web技术内幕》 
《大型网站技术架构》 
《代码整洁之道》 
《架构整洁之道》 
《Head First设计模式》 
《maven实战》 
《区块链原理、设计与应用》 
《Java并发编程实战》 
《鸟哥的Linux私房菜》 
《从Paxos到Zookeeper》 
《架构即未来》

##  8. <a name='-1'></a>七、 知识星球、左耳听风学习

[架构](/basics/java-basic/architecture.md)





