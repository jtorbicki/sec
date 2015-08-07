# Software Engineer Cookbook
### Knowledge base that helps me to stay in touch with the reality. Use with caution ;)

## Backend

### The Java language
- What is Java
  * http://en.wikipedia.org/wiki/Java_%28programming_language%29
- New in Java 5
  * http://docs.oracle.com/javase/1.5.0/docs/relnotes/features.html
- New in Java 6
  * http://www.oracle.com/technetwork/java/javase/features-141434.html
- New in Java 7
  * http://docs.oracle.com/javase/7/docs/technotes/guides/language/enhancements.html#javase7
- New in Java 8
  * http://www.javacodegeeks.com/2012/12/java-far-sight-look-at-jdk-8.html
  * http://www.learncomputer.com/java-8-new-features/
- Java SE vs EE vs ME
  * http://stackoverflow.com/questions/2857376/difference-between-java-se-ee-me

### Basic Java
- Java Basics Tutorial
  * http://java-success.blogspot.com.au/
- Java Collections
  * http://docs.oracle.com/javase/tutorial/collections/index.html
- Hashtable \ HashMap (Buckets, Collisions etc.)
  * http://en.wikipedia.org/wiki/Hash_table
- Java Collections Matrix
  * https://docs.google.com/spreadsheet/pub?key=0Aq3e8BiuZY2wdFpHSlV0QzVmV1lUNHJidGd2b0Zrb3c
- bits operations
  * http://docs.oracle.com/javase/tutorial/java/nutsandbolts/op3.html
- Regular Expressions
  * http://www.javacodegeeks.com/2012/02/regular-expressions-in-java-soft.html
  
### Java Best Practices
- Checked vs Runtime Exceptions
  * http://johnpwood.net/2008/04/21/java-checked-exceptions-vs-runtime-exceptions/
  * http://www.javacodegeeks.com/2012/03/why-should-you-use-unchecked-exceptions.html 
- java Optional
  * http://www.oracle.com/technetwork/articles/java/java8-optional-2175753.html
- null value
  * http://stackoverflow.com/questions/2707322/what-is-null-in-java
- Null Pointer Exception
  * http://www.javacodegeeks.com/2012/06/avoid-null-pointer-exception-in-java.html
- equals() and hashCode()
  * http://stackoverflow.com/questions/27581/overriding-equals-and-hashcode-in-java
  * http://web.archive.org/web/20110622072109/http://java.sun.com/developer/Books/effectivejava/Chapter3.pdf
- Log4j vs SLF4j
  * http://stackoverflow.com/questions/2063883/is-log4j-being-abandoned-in-favor-of-slf4j
- Java memes which refuse to die
  * http://www.javacodegeeks.com/2012/08/java-memes-which-refuse-to-die.html
- DateFormat
  * http://www.javacodegeeks.com/2010/07/java-best-practices-dateformat-in.html
  * (use an alternative to SimpleDateFormat like FastDateFormat from commons-lang / Joda)
- Java Memory Leaks
  * http://stackoverflow.com/questions/6470651/creating-a-memory-leak-with-java
  
### Java Concurency
- Tutorial
  * https://docs.google.com/open?id=0B2EZFIvnYfEpZGQ0OTgxNTktYThkZC00MWMwLTg4MzctNmNlNGNmMTU1ZGI4
- Java Memory Model
  * http://www.youtube.com/watch?v=WTVooKLLVT8&feature=gv
- volatile keyword
  * https://www.ibm.com/developerworks/java/library/j-jtp06197/
- Fork \ Join
  * http://www.javacodegeeks.com/2011/02/java-forkjoin-parallel-programming.html
  * http://www.oracle.com/technetwork/articles/java/fork-join-422606.html
  
### Advanced Java
- invoke dynamic
  * http://www.javaworld.com/article/2860079/scripting-jvm-languages/invokedynamic-101.html?page=2
- Java class loading
  * http://www.parleys.com/#st=5&id=1985&sl=0
  * http://www.techjava.de/topics/2008/01/java-class-loading/
- NoClassDefFoundError vs ClassNotFoundException
  * http://stackoverflow.com/questions/1457863/what-is-the-difference-between-noclassdeffounderror-and-classnotfoundexception
- Custom class loaders
  * http://stackoverflow.com/questions/3550175/why-do-we-need-user-defined-classloader-in-java
- Java byte code
  * http://arhipov.blogspot.com/2011/01/java-bytecode-fundamentals.html
  * http://www.ibm.com/developerworks/ibm/library/it-haggar_bytecode/
  * http://en.wikipedia.org/wiki/Java_bytecode_instruction_listings
- Accessing Memory in Java
  * http://robaustin.wikidot.com/how-to-write-to-direct-memory-locations-in-java
- Garbage Collector
  * http://www.oracle.com/technetwork/java/javase/gc-tuning-6-140523.html
  * http://www.infoq.com/presentations/Understanding-Java-Garbage-Collection (Doubling the memory will decrease the GC CPU usage by 2 - 53:00 min)
  * http://www.javaworld.com/javaworld/jw-10-2012/121010-jvm-performance-optimization-garbage-collection.html
  * http://www.infoq.com/articles/azul_gc_in_detail
- JIT
  * http://en.wikipedia.org/wiki/Just-in-time_compilation
- on heap \ off heap storage
  * http://stackoverflow.com/questions/6091615/difference-between-on-heap-and-off-heap
  * http://docs.oracle.com/javase/6/docs/api/java/nio/ByteBuffer.html
- How to analyze a thread dump
  * http://architects.dzone.com/articles/how-analyze-java-thread-dumps
- Finding and Solving Deadlocks in Multi-Threaded Java Code
  * http://vimeo.com/46669351
  * http://vimeo.com/46671447
  * http://vimeo.com/46690606
  
### Dependency Injection
- Loose Coupling
  * http://www.codeproject.com/Articles/13831/Dependency-Injection-for-Loose-Coupling
- CDI
  * http://www.theserverside.com/news/1373391/Dependency-Injection-in-Java-EE-6-Part-1
- Spring Core
  * http://static.springsource.org/spring/docs/current/spring-framework-reference/html/spring-core.html
- Guice
  * http://code.google.com/p/google-guice/wiki/Motivation
- Spring IoC vs Guice
  * http://www.javacodegeeks.com/2012/06/spring-vs-guice-one-critical-difference.html
  
### Web applications
- JAR, WAR, EAR
  * http://geekexplains.blogspot.com/2008/06/jar-war-and-ear-what-are-these-files.html
- Web Server vs Web Container vs Application Server
  * http://geekexplains.blogspot.dk/2008/06/web-server-web-container-application.html
- Asynchronous processing support in Servlet 3.0
  * http://www.javaworld.com/javaworld/jw-02-2009/jw-02-servlet3.html
  
### Enterprise Applications
- Java EE vs Spring
  * http://stackoverflow.com/questions/7076144/ejb-3-1-or-spring-3-when-to-choose-which-one
  * http://www.phillyjug.skookle.com/file_download/32

### Java EE
- https://docs.oracle.com/javaee/7/tutorial/
- Full application
  * http://www.javacodegeeks.com/2012/06/full-webapplication-jsf-ejb-jpa-jaas.html
  * http://www.javacodegeeks.com/2012/06/full-webapplication-jsf-ejb-jpa-jaas_19.html
- EJB 3.1
  * http://en.wikipedia.org/wiki/Enterprise_JavaBeans
- JBoss Seam
  * http://www.seamframework.org/

### Spring
- http://static.springsource.org/spring/docs/current/spring-framework-reference/htmlsingle/spring-framework-reference.html

### MVC
- http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller

### View (Server side)
- JSF 2.0 / Wicket / Tapestry , Spring MVC / Struts , GWT / Vaadin , Grails / Play , Django , JavaFX
  * http://www.parleys.com/#st=5&id=3084
- Component vs Action Based Frameworks
  * http://stackoverflow.com/questions/1247627/java-component-based-vs-request-based-frameworks
- Double form submission
  * http://stackoverflow.com/questions/218907/how-to-handle-multiple-submissions-server-side
  * http://en.wikipedia.org/wiki/Post/Redirect/Get
  * http://stackoverflow.com/questions/2830542/prevent-double-submission-of-forms-in-jquery
- Spring MVC tutorial
  * http://viralpatel.net/blogs/tutorial-spring-3-mvc-introduction-spring-mvc-framework/
- JSF 2.0 + Spring + Hibernate
  * http://blog.pariyani.com/archives/7
- Mojarra vs MyFaces
  * http://stackoverflow.com/questions/4530746/mojarra-or-myfaces-jsf2-0-starter
- JSTL
  * http://en.wikipedia.org/wiki/JavaServer_Pages_Standard_Tag_Library
- Expression Languages
  * http://docs.oracle.com/javaee/1.4/tutorial/doc/JSPIntro7.html
- OGNL, MVEL, JBoss EL, SPEL
- OGNL vs SPEL
  * http://stackoverflow.com/questions/4661769/benefits-to-using-spring-el-over-ognl
- Scalatra
  * http://www.scalatra.org
  * http://www.javacodegeeks.com/2012/09/getting-started-with-scala-and-scalatra.html
- Web Resource Optimizer for Java
  * https://code.google.com/p/wro4j/

### Javascript
- Node.js
  * https://openshift.redhat.com/community/blogs/get-chatty-with-nodejs-and-html5
  * http://code.google.com/p/v8/
  * http://en.wikipedia.org/wiki/Nodejs
  * http://basho.com/blog/technical/2011/03/18/follow-up-to-riak-nodejs-webinar/
- this
  * http://bjorn.tipling.com/all-this  
- Equality
  * http://geekswithblogs.net/brians/archive/2010/07/03/quality-equality-with-javascript-quotquot-gt-quotquot.aspx
- Objects tutorial
  * http://helephant.com/2008/08/17/how-javascript-objects-work/
- OOP
  * http://stackoverflow.com/questions/907225/object-oriented-javascript-best-practices
- Javascript style
  * http://dojotoolkit.org/reference-guide/1.7/developer/styleguide.html
- Inheritance in Javascript
  * http://bolinfest.com/javascript/inheritance.php
- Anonymous functions
  * http://helephant.com/2008/08/23/javascript-anonymous-functions/
- Module pattern
  * http://www.adequatelygood.com/2010/3/JavaScript-Module-Pattern-In-Depth
- Design Patterns
  * http://addyosmani.com/resources/essentialjsdesignpatterns/book/
- More Design Patterns
  * http://shichuan.github.io/javascript-patterns/
- array methods
  * https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/Array
- functional iteration, filtering etc.
  * http://stackoverflow.com/questions/3010840/loop-through-array-in-javascript
- Design Patterns in Javascript
  * http://net.tutsplus.com/tutorials/javascript-ajax/digging-into-design-patterns-in-javascript
- Javascript Closure compiler
  * https://developers.google.com/closure/compiler/
- Crockford
  * http://www.youtube.com/watch?v=hQVTIJBZook
  * http://www.crockford.com/
- CoffeeScript
  * http://en.wikipedia.org/wiki/CoffeeScript
- Dart
  * http://www.dartlang.org/

### RDBMS (Relational Databases)
- Transactions (ACID)
  * http://en.wikipedia.org/wiki/Database_transaction 
- Transaction Isolation
  * http://en.wikipedia.org/wiki/Isolation_%28database_systems%29
- Read phenomena
  * http://en.wikipedia.org/wiki/Isolation_(database_systems)#Read_phenomena
- Concurrency control
  * http://en.wikipedia.org/wiki/Lock_(database)
  * http://en.wikipedia.org/wiki/Optimistic_locking (Optimistic and Pesimistic locking)
- Locking
  * http://en.wikibooks.org/wiki/Java_Persistence/Locking
- Transaction propagation VS demarcation
  * http://stackoverflow.com/questions/2754160/question-about-spring-transaction-propagation
  * http://docs.oracle.com/cd/E26180_01/Platform.94/ATGProgGuide/html/s1205transactiondemarcation01.html
- SQL Joins
  * http://www.codeproject.com/Articles/33052/Visual-Representation-of-SQL-Joins
  * http://en.wikipedia.org/wiki/Join_%28SQL%29
- JPQL
  * http://en.wikipedia.org/wiki/Java_Persistence_Query_Language 
- JTA
  * http://en.wikipedia.org/wiki/Java_Transaction_API
- JPA vs EJB3 vs Hibernate vs JDO
  * http://en.wikipedia.org/wiki/Java_Data_Objects
- JDBC (Difference between statements)
  * http://crunchify.com/what-are-the-difference-between-jdbcs-statement-preparedstatement-and-callablestatement/
- Database design practices
  * http://www.javacodegeeks.com/2012/02/20-database-design-best-practices.html
- Normalization
  * http://en.wikipedia.org/wiki/Database_normalization
- Denormalization
  * http://en.wikipedia.org/wiki/Denormalization
- Slick
  * http://parleys.com/play/51c2e20de4b0d38b54f46243/chapter11/about
- jOOQ
  * http://www.jooq.org/
- Database index
  * http://en.wikipedia.org/wiki/Database_index
- Two phase commit
  * http://en.wikipedia.org/wiki/Two-phase_commit_protocol

### Hibernate
- http://docs.jboss.org/hibernate/orm/4.1/manual/en-US/html_single/
- http://www.javacodegeeks.com/2012/05/tutorial-hibernate-jpa-part-1.html
- Hibernate object life cycle
  * http://learningviacode.blogspot.dk/2012/02/hibernate-object-life-cycle.html
- Hibernate identity generator
  * http://blog.eyallupu.com/2011/01/hibernatejpa-identity-generators.html
- Hibernate inheritance mapping
  * http://docs.jboss.org/hibernate/orm/4.1/manual/en-US/html_single/#d5e3306
- Hibernate caching
  * http://www.tutorialspoint.com/hibernate/hibernate_caching.htm
- Hibernate List vs Bag vs Set
  * http://stackoverflow.com/questions/1916350/list-vs-set-vs-bag-in-nhibernate
- HibernateTemplate vs SessionFactory
  * http://blog.springsource.org/2007/06/26/so-should-you-still-use-springs-hibernatetemplate-andor-jpatemplate/
- SQL vs HQL
  * http://stackoverflow.com/questions/4162838/hql-vs-sql-hibernate-netbeans-hql-editor

### NoSQL and NewSQL
- SQL vs NoSQL vs NewSQL
  * http://www.parleys.com/#st=5&id=3061&sl=0
- NoSQL
  * http://en.wikipedia.org/wiki/NoSQL 
  * http://www.javacodegeeks.com/2012/05/future-of-nosql-with-java-ee.html 
- MongoDB
  * http://www.mongodb.org/display/DOCS/Java+Tutorial
  * http://blog.serverdensity.com/automating-partitioning-sharding-and-failover-with-mongodb/
- HBase
  * http://hbase.apache.org/
  * http://www.informationweek.com/software/information-management/hbase-hadoops-next-big-data-chapter/232901601
- Apache Cassandra
  * http://cassandra.apache.org/
- Hector
  * http://hector-client.github.com/hector/build/html/index.html
- Hector vs ?others?
  * http://stackoverflow.com/questions/6151078/about-java-cassandra-client-which-one-is-better-how-about-cql
- Distributed deletes in Cassandra
  * http://spyced.blogspot.com/2010/02/distributed-deletes-in-cassandra.html
- HBase vs Cassandra
  * http://ria101.wordpress.com/2010/02/24/hbase-vs-cassandra-why-we-moved/
- VoltDB
  * http://voltdb.com/newsql

### Big Data
- CAP
  * http://en.wikipedia.org/wiki/CAP_theorem
  * http://thislongrun.blogspot.com/2015/03/the-confusing-cap-and-acid-wording.html
- Eventual Consistency
  * http://en.wikipedia.org/wiki/Eventual_consistency
  * http://wiki.ubc.ca/images/e/ec/EventualConsistency.pdf
- w + r > n
- Database sharding
  * http://www.codefutures.com/database-sharding/
- Vector clock
  * http://basho.com/blog/technical/2010/04/05/why-vector-clocks-are-hard/
- MapReduce
  * http://code.google.com/edu/parallel/mapreduce-tutorial.html
  * http://basho.com/blog/technical/2011/03/30/why-mapreduce-is-easy/
- Hadoop
  * http://cscarioni.blogspot.com/2010/11/hadoop-basics.html
  * http://radar.oreilly.com/2011/01/what-is-hadoop.html
  * http://wiki.apache.org/hadoop/HadoopIsNot
- Hive vs Pig
  * http://stackoverflow.com/questions/3356259/difference-between-pig-and-hive-why-have-both
  * http://developer.yahoo.com/blogs/hadoop/posts/2010/01/comparing_pig_latin_and_sql_fo/
- ZooKeeper
  * http://zookeeper.apache.org/

### Polyglot Persistence
- http://martinfowler.com/bliki/PolyglotPersistence.html

### XML / JSON
- JSON
  * http://www.javacodegeeks.com/2012/05/json-for-polymorphic-java-object.html
  * http://wiki.fasterxml.com/JacksonHome
- XML
  * http://www.javacodegeeks.com/2012/07/approaches-to-xml-part-1-xml-is-not.html
- SAX vs DOM 
  * http://vbains.blogspot.dk/2012/05/sax-vs-dom-parsers.html
- XSLT 
  * http://en.wikipedia.org/wiki/XSLT
- XML Schema 
  * http://en.wikipedia.org/wiki/XML_schema
- DTD vs Schema 
  * http://www.sitepoint.com/xml-dtds-xml-schema/
- XPath
  * http://en.wikipedia.org/wiki/XPath

### Java and XML
- JAXB vs XMLBeans
  * http://stackoverflow.com/questions/335156/which-one-is-better-for-schema-to-code-generation-xmlbeans-or-jaxb
  * http://stackoverflow.com/questions/1362030/jaxb-vs-apache-xmlbeans
  * http://java.dzone.com/articles/how-does-jaxb-compare-xmlbeans

### Java and JSON
- http://stackoverflow.com/questions/338586/a-better-java-json-library

### SOA
- http://en.wikipedia.org/wiki/Service-oriented_architecture
- SOA Gotchas
  * http://www.javacodegeeks.com/2012/08/top-5-soa-gotchas-and-how-to-avoid-them.html
- SOAP vs REST
  * http://stackoverflow.com/questions/409338/examples-of-the-best-soap-rest-rpc-web-apis-and-why-do-you-like-them-and-what
  * http://www.infoq.com/articles/rest-soap-when-to-use-each
- JMS
  * http://en.wikipedia.org/wiki/Java_Message_Service
- JMS vs MDB
  * http://stackoverflow.com/questions/5655673/difference-between-jms-consumer-and-message-driven-beans
- MOM
  * http://en.wikipedia.org/wiki/Message-oriented_middleware
- JAX-RPC
  * http://en.wikipedia.org/wiki/Java_API_for_XML-based_RPC
- Apache CXF
  * http://cxf.apache.org/ 

### Web-services

### SOAP
- http://en.wikipedia.org/wiki/SOAP
- Contract First vs Contract Last
  * http://static.springsource.org/spring-ws/sites/2.0/reference/html/why-contract-first.html
- JAX-WS + Weblogic 10.3
  * http://blog.inflinx.com/2010/10/09/jax-ws-using-weblogic-10-3
- SAAJ
  * http://en.wikipedia.org/wiki/SOAP_with_Attachments_API_for_Java
- Why stateful web service is a Bad Practice
  * http://stackoverflow.com/questions/988819/stateful-webservice
- WS-Security
  * http://en.wikipedia.org/wiki/WS-Security
  * http://cxf.apache.org/docs/ws-security.html
- Possible WS attacks
  * http://ws-attacks.org/

### REST
- http://en.wikipedia.org/wiki/Representational_State_Transfer
- JAX-RS
  * http://en.wikipedia.org/wiki/Java_API_for_RESTful_Web_Services
- JAX-RS Tutorials
  * http://www.mkyong.com/tutorials/jax-rs-tutorials/
- Jersey
  * http://www.javacodegeeks.com/2012/03/restful-web-applications-with-jersey.html
- RESTEasy
  * http://www.javacodegeeks.com/2012/06/resteasy-tutorial-part-1-basics.html
- Spring MVC vs Jersey
  * http://www.infoq.com/articles/springmvc_jsx-rs
- PUT vs POST in REST
  * http://stackoverflow.com/questions/630453/put-vs-post-in-rest
- RESTful Authentication
  * http://stackoverflow.com/questions/319530/restful-authentication
  * http://blog.synopse.info/post/2011/05/24/How-to-implement-RESTful-authentication
- REST Security
  * http://stackoverflow.com/questions/454355/security-of-rest-authentication-schemes
  * http://stackoverflow.com/questions/7551/best-practices-for-securing-a-rest-api-web-service
  * http://www.javacodegeeks.com/2012/12/authentication-against-a-restful-service-with-spring-security.html
- REST Best Practices
  * http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
  
### Security
- Web application security
  * http://docs.oracle.com/javaee/6/tutorial/doc/bncat.html 
- JAAS
  * http://en.wikipedia.org/wiki/Java_Authentication_and_Authorization_Service
- Spring Security
  * http://static.springsource.org/spring-security/site/ 
  * http://www.javacodegeeks.com/2012/08/spring-security-two-security-realms-in.html
- Spring Security vs JAAS
  * http://stackoverflow.com/questions/7299652/spring-security-and-java-authentication-and-authorization-servicejaas
- Spring Security: Custom Authenticators
  * http://tedyoung.me/2011/06/21/spring-security-custom-authenticators/
- Password storage
  * http://crackstation.net/hashing-security.htm
  * http://www.javacodegeeks.com/2012/05/secure-password-storage-donts-dos-and.html
  * http://www.javacodegeeks.com/2012/08/bcrypt-salt-its-bare-minimum.html
- BCrypt
  * http://en.wikipedia.org/wiki/Bcrypt

### Web app attacks
- XSS
  * http://www.veracode.com/security/xss
- SQL injection
  * http://stackoverflow.com/questions/9596424/how-much-safe-from-sql-injection-if-using-hibernate

### Testing
- Spock
  * http://code.google.com/p/spock/
- Geb
  * http://www.gebish.org/
- JUnit 4 vs TestNG
  * http://www.mkyong.com/unittest/junit-4-vs-testng-comparison/
- Mockito vs Easymock
  * http://stackoverflow.com/questions/2864796/easymock-vs-mockito-design-vs-maintainability
  * http://stackoverflow.com/questions/3127518/mockito-preferrable-over-easymock
- PowerMock
  * http://stackoverflow.com/questions/6036450/powermock-mockito-vs-mockito-alone
- DbUnit
  * http://www.dbunit.org/
- Arquillian
  * http://docs.jboss.org/arquillian/reference/1.0.0.Alpha2/en-US/html_single/
- Tutorial
  * http://www.javacodegeeks.com/2012/06/java-ee-6-testing-part-i-ejb-31.html
- Maven Integration tests
  * http://www.javacodegeeks.com/2012/07/integration-tests-with-maven-3-failsafe.html
- Cucumber
  * http://cukes.info/
- Selenium
  * http://docs.seleniumhq.org/

### Building
- Ant vs Maven vs Gradle vs Ivy
  * http://stackoverflow.com/questions/80622/maven-or-ant 
  * http://stackoverflow.com/questions/1163173/why-use-gradle-instead-of-ant-or-maven 
- Maven archetypes, Maven MOJO
- Jenkins vs CruiseControl
  * http://stackoverflow.com/questions/604385/what-is-the-difference-between-hudson-and-cruisecontrol-for-java-projects

### Version Control
- CVS
- SVN
- Git
  * http://www.javacodegeeks.com/2013/05/git-explained-for-beginners.html
- Git branching
  * http://nvie.com/posts/a-successful-git-branching-model
- Git inside out
  * https://codewords.recurse.com/issues/two/git-from-the-inside-out

### Polyglot Programming
- http://blog.enfranchisedmind.com/posts/not-too-stupid-for-polyglotism/
- http://polyglotprogramming.com/
- Scala vs. Groovy vs. Clojure
  * http://stackoverflow.com/questions/1314732/scala-vs-groovy-vs-clojure

### Groovy
- http://www.ibm.com/developerworks/views/java/libraryview.jsp?search_by=practically+groovy
- http://mrhaki.blogspot.dk/search/label/Groovy%3AGoodness
- http://www.youtube.com/watch?v=bqS8l12xG-Y

### Scala
- http://www.scala-lang.org/node/1305
- http://www.naildrivin5.com/scalatour
- Scala vs Java performance
  * http://stackoverflow.com/questions/5901452/scala-vs-java-performance-and-memory
- DI in Scala
  * http://scabl.blogspot.dk/2013/02/cbdi.html
- Partial Functions
  * http://sandrasi-sw.blogspot.com/2012/03/understanding-scalas-partially-applied.html

### Kotlin
- http://kotlinlang.org/

### Design
- Design Patterns
  * http://en.wikipedia.org/wiki/Software_design_pattern
- Builder vs Abstract Factory
  * http://stackoverflow.com/questions/757743/what-is-the-difference-between-builder-design-pattern-and-factory-design-pattern
- Singleton
  * http://en.wikipedia.org/wiki/Singleton_pattern#The_solution_of_Bill_Pugh
- Anti-patterns
  * http://en.wikipedia.org/wiki/Anti-pattern
- Integration Patterns
  * http://www.enterpriseintegrationpatterns.com/toc.html
- How to design a good API
  * http://www.youtube.com/watch?v=aAb7hSCtvGw

### Clustering
- Tomcat clustering
  * http://www.ramkitech.com/search/label/tomcat%20clustering
- Sticky session vs session replication
  * http://stackoverflow.com/questions/6367812/sticky-sessions-and-session-replication
- memcached-session-manager
  * http://code.google.com/p/memcached-session-manager/

### Caching
- memcached
  * http://memcached.org/ 
- Terracotta
  * http://terracotta.org/
- Distributed cache vs Replicated cache
  * https://docs.jboss.org/author/pages/viewpage.action?pageId=5832844

### Business Buzz
- PaaS
  * http://www.ibm.com/developerworks/java/library/j-paasshootout/
- Cloud
  * http://www.javacodegeeks.com/2012/07/all-that-cloud-amazon-google-app-engine.html
- CRM
  * http://en.wikipedia.org/wiki/Customer_relationship_management
- ERP
  * http://en.wikipedia.org/wiki/Enterprise_resource_planning
- BPM 
  * http://www.bpmn-introduction.com
  * http://en.wikipedia.org/wiki/Business_process_modelling
  * http://en.wikipedia.org/wiki/Business_Process_Model_and_Notation
- BPEL
  * http://en.wikipedia.org/wiki/Business_Process_Execution_Language
  * http://incubator.apache.org/hise/WS-HumanTask_v1.pdf
- BPMS (Jboss jBPM, Activity, AquaLogic BPM, Oracle BPM, Tibco Staffware/Iprocess)
  * http://www.javabeat.net/2011/06/creating-an-activiti-development-environment/
  * http://www.activiti.org/
  * http://bpmn20inaction.blogspot.dk/
  * http://devbackyard.blogspot.pt/
  * http://www.jboss.org/jbpm
  * http://salaboy.com/2011/01/19/jbpm5-vs-activiti5-dumb-question/#more-1534
  * http://blog.athico.com/2011/01/recent-jbpm-5-blogs-articles-videos-and.html
  * http://www.theserverside.com/news/1363804/Getting-Started-with-jBPM-and-Spring
- ESB
  * http://en.wikipedia.org/wiki/Enterprise_service_bus
  * http://synapse.apache.org/
- SOA vs BPM vs ESB
  * http://eknowinf.wordpress.com/2011/08/22/eai-vs-esb-vs-soa-vs-bpm/

### Database hardware setup
- http://www.sohoconsult.ch/raid/raid.html
- http://www.bigdbahead.com/?p=158

### Tools and libs
- Google Guava
  * http://code.google.com/p/guava-libraries/
- Quartz Scheduler
  * http://static.springsource.org/spring/docs/current/spring-framework-reference/htmlsingle/spring-framework-reference.html#scheduling-quartz
- Apache POI
- Jasper Reports
  * http://jasperforge.org/projects/jasperreports/
- VisualVM
  * http://visualvm.java.net/
- UML (Magic Draw 15, Enterprise Architect)
- jRebel
- Weblogic and Java EE
  * http://stackoverflow.com/questions/3166283/weblogic-11g-and-javaee-6

### Configuration
- Deployment Descriptors
  * http://en.wikipedia.org/wiki/Deployment_descriptor
  * http://pic.dhe.ibm.com/infocenter/wasinfo/v7r0/index.jsp?topic=%2Fcom.ibm.websphere.express.doc%2Finfo%2Fexp%2Fae%2Ftrun_app_deploymtdesc.html
- JNDI
  * http://en.wikipedia.org/wiki/Java_Naming_and_Directory_Interface
- JMX
  * http://docs.oracle.com/javase/tutorial/jmx/index.html

## Frontend

### View (Client side)
- Client side MVC
  * http://paulhammant.com/2012/02/13/client-side-mvc-frameworks-compared/
- Angular JS
  * http://angularjs.org/
- Angular JS Presentation
  * http://www.youtube.com/watch?v=1CpiB3Wk25U
- Angular scope inheritance
  * http://stackoverflow.com/questions/14049480/what-are-the-nuances-of-scope-prototypal-prototypical-inheritance-in-angularjs
- Angular UI
  * http://angular-ui.github.io/
- Angular tricks
  * http://blog.tomaka17.com/2012/12/random-tricks-when-using-angularjs/
- Angular style guide
  * https://github.com/mgechev/angularjs-style-guide
- Angular Advanced tutorial
  * http://www.thinkster.io/angularjs/GtaQ0oMGIl
- Angular promises
  * http://markdalgleish.com/2013/06/using-promises-in-angularjs-views/ 
- jQuery
  * http://15daysofjquery.com/category/tutorials/
- jQuery and Ajax
  * http://net.tutsplus.com/tutorials/javascript-ajax/5-ways-to-make-ajax-calls-with-jquery/
- jQuery vs Dojo
  * http://stackoverflow.com/questions/394601/which-javascript-framework-jquery-vs-dojo-vs
- $(document).ready vs. $(window).load
  * http://4loc.wordpress.com/2009/04/28/documentready-vs-windowload/
- Apache Flex
  * http://en.wikipedia.org/wiki/Apache_Flex

### HTML5
- HTML5
  * http://en.wikipedia.org/wiki/HTML5
  * http://www.lordofthejars.com/2011/11/your-big-daddys-got-no-place-to-stay.html
- Bootstrap
  * http://twitter.github.io/bootstrap/
  * http://usman.it/free-responsive-admin-template/
- Bootstrap grid system
  * http://www.helloerik.com/the-subtle-magic-behind-why-the-bootstrap-3-grid-works
- Boilerplate
  * http://html5boilerplate.com/
- Fonts + Icons
  * http://fortawesome.github.io/Font-Awesome/
- HTML5 Canvas
  * http://www.html5canvastutorials.com/
- WebGL
  * http://net.tutsplus.com/tutorials/webgl-essentials-part-i/
- Good UI
  * http://www.goodui.org/

### CSS
- CSS selectors
  * http://net.tutsplus.com/tutorials/html-css-techniques/the-30-css-selectors-you-must-memorize/
- LESS
  * http://lesscss.org/
- SASS
  * http://sass-lang.com/

## Other

### HTTP
- HTTP Protocol
  * http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol
- HTTPS
  * http://stackoverflow.com/questions/323200/is-a-https-query-string-secure
  * http://en.wikipedia.org/wiki/HTTP_Secure
- HTTP caching
  * https://developers.google.com/speed/articles/caching
- XMLHttpRequest
  * http://en.wikipedia.org/wiki/XMLHttpRequest
- AJAX
  * http://en.wikipedia.org/wiki/Ajax_%28programming%29
- Reverse AJAX
  * http://www.ibm.com/developerworks/web/library/wa-reverseajax1/index.html
- JSONP / CORS
  * http://en.wikipedia.org/wiki/JSONP    
  * http://en.wikipedia.org/wiki/Cross-origin_resource_sharing
  * http://www.html5rocks.com/en/tutorials/cors/

### Networking
- TCP/IP
  * http://www.thegeekstuff.com/2011/11/tcp-ip-fundamentals/
- Throughput
  * http://en.wikipedia.org/wiki/Throughput

### Linux
- http://www.ibm.com/developerworks/training/kp/l-kp-command/index.html

### Emacs
- http://tuxradar.com/content/emacs-tutorial-beginners

### Intelij IDEA
- http://www.javacodegeeks.com/2011/11/whats-cool-in-intellijidea-part-i.html

### Algorithms
- External Sort
  * http://en.wikipedia.org/wiki/External_sorting
- Quick sort
  * http://en.wikipedia.org/wiki/Quicksort
- Heap sort
  * http://en.wikipedia.org/wiki/Heapsort
- Videos
  * https://www.youtube.com/results?search_query=algorithms+xoax+dotnet
- Depth-First Search
- Breadth-First Search
- Topological Sort
- Dijkstra's Algorithm
- Strings in Java
- Key-Indexed Counting
- LSD Radix Sort
- 3-way Radix Quicksort
- R-way Tries
- Ternary Search Tries
- Introduction to Substring Search
- Brute-Force Substring Search
- Knuth-Morris-Pratt
- Boyer-Moore
- Rabin-Karp

### Interview
- http://www.javacodegeeks.com/2012/02/some-interview-questions-to-hire-java.html
- http://www.javacodegeeks.com/2012/03/here-is-main-reason-why-you-suck-at.html
- http://www.javacodegeeks.com/2012/08/how-employers-measure-passion-in.html
- http://www.javacodegeeks.com/2012/08/why-you-didnt-get-interview.html
- http://www.javacodegeeks.com/2012/08/why-you-didnt-get-job.html
- http://stackoverflow.com/questions/2114212/questions-every-good-java-java-ee-developer-should-be-able-to-answer
- http://stackoverflow.com/questions/64856/senior-java-ee-interview-questions
- http://www.javacodegeeks.com/2012/08/blind-dating-for-geeks-questions.html

### Resources
- Google Code University
  * http://code.google.com/edu/
- Java Code Geeks
  * http://www.javacodegeeks.com
- Other
  * http://www.mkyong.com/featured/top-20-java-websites/
  * http://www.javacodegeeks.com/p/resources.html
