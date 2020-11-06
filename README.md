# Awesome CTI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, libraries, software, and projects CTI has used, is using, or researched.

## Contents

- [Solutions](#solutions)
  * [Bean Mapping](#bean-mapping)
  * [Build](#build)
  * [Bytecode Manipulation](#bytecode-manipulation)
  * [Caching](#caching)
  * [CLI](#cli)
  * [Cluster Management](#cluster-management)
  * [Code Analysis](#code-analysis)
  * [Code Coverage](#code-coverage)
  * [Code Generators](#code-generators)
  * [Configuration](#configuration)
  * [CSV](#csv)
  * [Database](#database)
  * [Data Structures](#data-structures)
  * [Dependency Injection](#dependency-injection)
  * [Development](#development)
  * [Version Control](#version-control)
  * [Distributed Applications](#distributed-applications)
  * [Distribution](#distribution)
  * [Document Processing](#document-processing)
  * [Functional Programming](#functional-programming)
  * [Game Development](#game-development)
  * [Geospatial](#geospatial)
  * [GUI](#gui)
  * [High Performance](#high-performance)
  * [HTTP Clients](#http-clients)
  * [IDE](#ide)
  * [JSON](#json)
  * [JVM and JDK](#jvm-and-jdk)
  * [Logging](#logging)
  * [Machine Learning](#machine-learning)
  * [Messaging](#messaging)
  * [Miscellaneous](#miscellaneous)
  * [Native](#native)
  * [Networking](#networking)
  * [ORM](#orm)
  * [PaaS](#paas)
  * [PDF](#pdf)
  * [Performance analysis](#performance-analysis)
  * [Platform](#platform)
    + [Other](#other)
  * [Processes](#processes)
  * [Reactive libraries](#reactive-libraries)
  * [REST Frameworks](#rest-frameworks)
  * [Science](#science)
  * [Security](#security)
  * [Serialization](#serialization)
  * [Server](#server)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
    + [Asynchronous](#asynchronous)
    + [BDD](#bdd)
    + [Fixtures](#fixtures)
    + [Frameworks](#frameworks)
    + [Matchers](#matchers)
    + [Miscellaneous](#miscellaneous-1)
    + [Mocking](#mocking)
    + [Parameterization](#parameterization)
  * [Utility](#utility)
  * [Version Managers](#version-managers)
  * [Web Crawling](#web-crawling)
  * [Web Frameworks](#web-frameworks)
- [Resources](#resources)
  * [Awesome Lists](#awesome-lists)
  * [Communities](#communities)
  * [Frontends](#frontends)
  * [Influential Books](#influential-books)
  * [Podcasts and Screencasts](#podcasts-and-screencasts)
  * [Twitter](#twitter)
  * [Websites](#websites)
- [Contributing](#contributing)

## Solutions

### Bean Mapping

*Frameworks that ease bean mapping.*


- [Dozer](https://github.com/DozerMapper/dozer) - Mapper that copies data from one object to another using annotations and API or XML configuration.
- [MapStruct](https://github.com/mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach.


### Build

*Tools that handle the build cycle and dependencies of an application.*

- [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
- [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

*Libraries to manipulate bytecode programmatically.*

- [ASM](https://asm.ow2.io/) - All-purpose, low-level bytecode manipulation and analysis.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) - Java 8 Jar & Android APK reverse engineering suite.
- [Javassist](https://jboss-javassist.github.io/javassist) - Tries to simplify bytecode editing.


### Caching

*Libraries that provide caching facilities.*

- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.

### CLI

*Libraries for everything related to the CLI.*

- [Homebrew](https://brew.sh) - The missing package manager for macOS (or Linux).
- [iTerm2](https://www.iterm2.com) - iTerm2 is a replacement for Terminal and the successor to iTerm. It works on Macs with macOS 10.12 or newer. iTerm2 brings the terminal into the modern age with features you never knew you always wanted.
- [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) - Plugin-enabled framework for drastically more powerful zsh command line. Zsh is based on bash, but [offers many improvements](https://sunlightmedia.org/bash-vs-zsh/), oh-my-zsh is a popular, open-source project with active community support.
- [picocli](https://picocli.info/) - Powerful and easy to use library for developing command line applications.

### Cluster Management

*Frameworks that can dynamically manage applications inside of a cluster.*



### Code Analysis

*Tools that provide metrics and quality measurements.*

- [Checkstyle](https://github.com/checkstyle/checkstyle) - Static analysis of coding conventions and standards.
- [Error Prone](https://github.com/google/error-prone) - Catches common programming mistakes as compile-time errors.
- [PMD](https://github.com/pmd/pmd) - Source code analysis for finding bad coding practices.
- [SonarJava](https://github.com/SonarSource/sonar-java) - Static analyzer for SonarQube & SonarLint.

### Code Coverage

*Frameworks and tools that enable code coverage metrics collection for test suites.*

- [JaCoCo](http://eclemma.org/jacoco) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

*Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness.*

- [Auto](https://github.com/google/auto) - Generates factory, service, and value classes.
- [Lombok](https://projectlombok.org) - Code generator that aims to reduce verbosity.


### Configuration

*Libraries that provide external configuration.*

- [config](https://github.com/typesafehub/config) - Configuration library for JVM languages.
- [owner](https://github.com/lviggiano/owner) - Reduces boilerplate of properties.
- [Typesafe Config](https://github.com/lightbend/config) - Powerful, yet simple, configuration library for JVM languages using [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) (Human-Optimized Config Object Notation).

### CSV

*Frameworks and libraries that simplify reading/writing CSV data.*

- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records.

### Database

*Everything that simplifies interactions with the database.*

- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), 
- [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) - High-performance JDBC connection pool.
- [jOOQ](https://www.jooq.org) - Generates typesafe code based on SQL schema.
- [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
- [OrientDB](https://orientdb.com/orientdb) - Embeddable distributed database written on top of Hazelcast.
- [Querydsl](http://www.querydsl.com) - Typesafe unified queries.

### Data Structures

*Efficient and specific data structures.*

- [Apache Avro](https://avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
- [Apache Thrift](https://thrift.apache.org) - Data interchange format that originated at Facebook.
- [Protobuf](https://github.com/google/protobuf) - Google's data interchange format.
- [SBE](https://github.com/real-logic/simple-binary-encoding) - Simple Binary Encoding, one of the fastest message formats around.


### Dependency Injection

*Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm.*

- [Apache DeltaSpike](https://deltaspike.apache.org) - CDI extension framework.
- [Dagger2](https://dagger.dev/) - Compile-time injection framework without reflection.
- [Guice](https://github.com/google/guice) - Lightweight and opinionated framework that completes Dagger.


### Development

*Augmentation of the development process at a fundamental level.*

- [AspectJ](https://eclipse.org/aspectj) - Seamless aspect-oriented programming extension.
- [DCEVM](https://dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime.
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition.
- [JRebel ![c]](https://zeroturnaround.com/software/jrebel) - Instantly reloads code and configuration changes without redeploys.
- [Manifold](https://manifold.systems) - Re-energizes Java with powerful features like type-safe metaprogramming, structural typing and extension methods.


### Version Control

*GUI and command line tools for version control.*

- [Fork](https://git-fork.com) - A cross-platform, powerful, and intuitive git GUI client that is **FREE**.
- [Tortoise HG](https://tortoisehg.bitbucket.io) - A free and functional client for Mercurial (Hg).


### Distributed Applications

*Libraries and frameworks for writing distributed and fault-tolerant applications.*

- [Apache Storm](https://storm.apache.org) - Realtime computation system.
- [Apache ZooKeeper](https://zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
- [Atomix](http://atomix.io/) - Fault-tolerant distributed coordination framework.
- [Hazelcast ![c]](https://hazelcast.org) - Highly scalable in-memory datagrid with a free open-source version.
- [Hystrix](https://github.com/Netflix/Hystrix) - Provides latency and fault tolerance.
- [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
- [Quasar](https://www.paralleluniverse.co/quasar) - Lightweight threads and actors for the JVM.


### Distribution

*Tools that handle the distribution of applications in native formats.*

- [Bintray ![c]](https://bintray.com) - Version control for binaries that handle publishing. Compatible with Maven or Gradle, with a free plan for open-source software as well as several business plans.
- [Capsule](http://www.capsule.io) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
- [Central Repository](https://search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
- [JitPack](https://jitpack.io) - Easy-to-use package repository for GitHub. Builds Maven/Gradle projects on demand and publishes ready-to-use packages.
- [Nexus ![c]](https://www.sonatype.com/nexus/solution-overview) - Binary management with proxy and caching capabilities.
- [packr](https://github.com/libgdx/packr) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and Mac OS X.


### Document Processing

*Libraries that assist with processing office document formats.*

- [Apache POI](https://poi.apache.org/) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).


### Functional Programming

*Libraries that facilitate functional programming.*

- [jOOλ](https://github.com/jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.

### Game Development

*Frameworks that support the development of games.*

- [FXGL](https://almasb.github.io/FXGL) - JavaFX Game Development Framework.
- [libGDX](https://libgdx.badlogicgames.com) - All-round cross-platform, high-level framework.
- [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.

### Geospatial

*Libraries for working with geospatial data and algorithms.*


- [GeoTools](http://geotools.org) - Library that provides tools for geospatial data.
- [GraphHopper](https://github.com/graphhopper/graphhopper) - Road-routing engine. Used as a Java library or standalone web service.
- [Spatial4j](https://github.com/locationtech/spatial4j) - General-purpose spatial/geospatial library.

### GUI

*Libraries to create modern graphical user interfaces.*

- [JavaFX](https://openjfx.io/) - The successor of Swing.
- [JFormDesigner](https://www.formdev.com/) - Professional GUI designer for Java Swing user interfaces with support for 3rd party layouts MigLayout and FormLayout.
- [JIDE](http://jidesoft.com/) - Provides a collection of custom swing components and utilities.
- [Scene Builder](https://gluonhq.com/open-source/scene-builder) - Visual layout tool for JavaFX applications.
- [SWT](https://www.eclipse.org/swt) - The Standard Widget Toolkit, a graphical widget toolkit.

### High Performance

*Everything about high-performance computation, from collections to specific libraries.*

- [Disruptor](https://lmax-exchange.github.io/disruptor) - Inter-thread messaging library.
- [Koloboke](https://github.com/leventov/Koloboke) - Hash sets and hash maps.

### HTTP Clients

*Libraries that assist with creating HTTP requests and/or binding responses.*

- [OkHttp](https://square.github.io/okhttp) - HTTP+SPDY client.
- [Play WS](https://github.com/playframework/play-ws) - Typesafe client with reactive streams and caching.
- [Retrofit](https://square.github.io/retrofit) - Typesafe REST client.


### IDE

*Integrated development environments that try to simplify several aspects of development.*

- [Eclipse](https://www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- [NetBeans](https://netbeans.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.



### JSON

*Libraries for serializing and deserializing JSON to and from Java objects.*

- [Gson](https://github.com/google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types.
- [Jackson](https://github.com/FasterXML/jackson) - Similar to GSON, but offers performance gains if you need to instantiate the library more often.


### JVM and JDK

*Current implementations of the JVM/JDK.*

- [Adopt Open JDK](https://adoptopenjdk.net) - OpenJDK builds which allows to choose between HotSpot and OpenJ9.
- [Amazon Corretto](https://aws.amazon.com/corretto/) - An OpenJDK distribution supported by Amazon.
- [Graal](https://github.com/oracle/graal) - Polyglot embeddable JVM.
- [Open JDK](https://openjdk.java.net) - Open JDK distributed by Oracle.
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview) - RedHat's OpenJDK distribution.
- [Zulu](https://www.azul.com/downloads/zulu) - OpenJDK builds for Windows, Linux, and Mac OS X.

### Logging

*Libraries that log the behavior of an application.*

- [Apache Log4j 2](https://logging.apache.org/log4j) - Complete rewrite with a powerful plugin and configuration architecture.
- [Kibana](https://www.elastic.co/products/kibana) - Analyzes and visualizes log files. Some features require payment.
- [Logback](https://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
- [Logstash](https://www.elastic.co/products/logstash) - Tool for managing log files.
- [SLF4J](https://www.slf4j.org) - Abstraction layer/simple logging facade.

### Machine Learning

*Tools that provide specific statistical algorithms for learning from data.*

- [Apache Spark](https://spark.apache.org) - Data analytics cluster-computing framework.
- [Tribuo](https://tribuo.org/) - Multi-class classification, regression, clustering, anomaly detection and multi-label classification.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization.


### Messaging

*Tools that help send messages between clients to ensure protocol independency.*

- [Aeron](https://github.com/real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport.
- [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
- [EventBus](https://github.com/greenrobot/EventBus) - Simple publish/subscribe event bus.
- [JeroMQ](https://github.com/zeromq/jeromq) - Implementation of ZeroMQ.
- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) - RabbitMQ client.
- [Smack](https://github.com/igniterealtime/Smack) - Cross-platform XMPP client library.

### Miscellaneous

*Everything else.*

- [Codename One](https://www.codenameone.com) - Cross-platform solution for writing native mobile apps.
- [JavaCV](https://github.com/bytedeco/javacv) - Java interface to OpenCV, FFmpeg, and more.
- [Java Object Diff](https://github.com/SQiShER/java-object-diff) - Compare Java objects with a very usable out-of-the-box configuration.
- [Maven Wrapper](https://github.com/takari/maven-wrapper) - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven.
- [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
- [Polyglot for Maven](https://github.com/takari/polyglot-maven) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML.

### Native
*For working with platform-specific native libraries.*

- [JavaCPP](https://github.com/bytedeco/javacpp) - Provides efficient and easy access to native C++.
- [JNA](https://github.com/java-native-access/jna) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries.
- [JNR](https://github.com/jnr/jnr-ffi) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama).

### Networking

*Libraries for building network servers.*

- [Finagle](https://github.com/twitter/finagle) - Extensible RPC system for constructing high-concurrency servers. It implements uniform client and server APIs for several protocols, and is protocol-agnostic to simplify implementation of new protocols.
- [gRPC](https://github.com/grpc/grpc-java) - RPC framework based on protobuf and HTTP/2.
- [KryoNet](https://github.com/EsotericSoftware/kryonet) - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo.
- [MINA](https://mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
- [Netty](https://netty.io) - Framework for building high-performance network applications.

### ORM

*APIs that handle the persistence of objects.*

- [Ebean](https://ebean-orm.github.io) - Provides simple and fast data access.
- [Hibernate](http://hibernate.org/orm) - Robust and widely used, with an active community.
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - Simple database and CSV mapper.

### PaaS

*Java platform as a service.*

- [AWS Lambda ![c]](https://aws.amazon.com/lambda) - Serverless computation.
- [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
- [Jelastic ![c]](https://jelastic.com) - Supports Tomcat, Jetty, GlassFish, JBoss, TomEE and WildFly.

### PDF

*Tools to help with PDF file creation.*


### Performance analysis

*Tools for performance analysis, profiling and benchmarking.*

- [JMH](http://openjdk.java.net/projects/code-tools/jmh) - a Java harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM.
- [JProfiler ![c]](https://www.ej-technologies.com/products/jprofiler/overview.html) - Database profiling for JDBC, JPA and NoSQL, with JEE support.
- [VisualVM](https://visualvm.github.io/) - Lightweight performance and memory monitor.


### Platform

*Frameworks that are suites of multiple libraries encompassing several categories.*


#### Other

- [Spring](https://spring.io/projects) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Processes

*Libraries that help the management of operating system processes.*

- [zt-exec](https://github.com/zeroturnaround/zt-exec) - Provides a unified API to Apache Commons Exec and ProcessBuilder.


### Reactive libraries

*Libraries for developing reactive applications.*

- [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
- [RxJava](https://github.com/ReactiveX/RxJava) - Allows for composing asynchronous and event-based programs using observable sequences.
- [vert.x](http://vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

*Frameworks specifically for creating RESTful services.*

- [Dropwizard](https://dropwizard.github.io/dropwizard) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
- [Spark](http://sparkjava.com) - Sinatra inspired framework.
- [Swagger](https://swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

*Libraries for scientific computing, analysis and visualization.*

- [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
- [JFreeChart](http://www.jfree.org/jfreechart) - 2D chart library for Swing, JavaFX and server-side applications.
- [XChart](https://github.com/knowm/XChart) - A light-weight library for plotting data. Many customizable chart types are available.


### Security

*Libraries that handle security, authentication, authorization or session management.*

- [Apache Shiro](https://shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.


### Serialization

*Libraries that handle serialization with high efficiency.*

- [FlatBuffers](https://github.com/google/flatbuffers) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it.
- [Kryo](https://github.com/EsotericSoftware/kryo) - Fast and efficient object graph serialization framework.
- [MessagePack](https://github.com/msgpack/msgpack-java) - Efficient binary serialization format.

### Server

*Servers specifically used to deploy applications.*

- [Apache Tomcat](https://tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
- [Jetty](https://www.eclipse.org/jetty) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
- [WildFly](http://www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support.

### Template Engine

*Tools that substitute expressions in a template.*

- [Handlebars.java](https://jknack.github.io/handlebars.java) - Logicless and semantic Mustache templates.
- [Thymeleaf](http://www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

*Tools that test from model to the view.*

#### Asynchronous

*Tools that simplify testing asynchronous services.*


#### BDD

*Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD.*

- [Cucumber](https://github.com/cucumber/cucumber-jvm) - Provides a way to describe features in a plain language which customers can understand.

#### Fixtures

*Everything related to the creation and handling of random data.*

- [Beanmother](https://github.com/keepcosmos/beanmother) - Sets up beans from YAML fixtures.
- [Fixture Factory](https://github.com/six2six/fixture-factory) - Generates fake objects from a template.
- [JFairy](https://github.com/Codearte/jfairy) - Fake data generator.
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.
- [Java Faker](https://github.com/DiUS/java-faker) - A port of Ruby's fake data generator.

#### Frameworks

*Provide environments to run tests for a specific use case.*

- [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
- [JUnit](http://junit.org) - Common testing framework.


#### Matchers

*Libraries that provide custom matchers.*

- [AssertJ](https://joel-costigliola.github.io/assertj) - Fluent assertions that improve readability.

#### Miscellaneous

*Other stuff related to testing.*



#### Mocking

*Tools which mock collaborators to help testing single, isolated units.*

- [JMockit](http://jmockit.github.io) - Integration testing, API mocking and faking, and code coverage.
- [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API.

#### Parameterization

*Simplifies the writing of parameterized tests.*


### Utility

*Libraries which provide general utility functions.*

- [Gephi](https://github.com/gephi/gephi) - Cross-platform for visualizing and manipulating large graph networks.
- [Guava](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more.
- [JGit](https://eclipse.org/jgit) - A lightweight, pure Java library implementing the Git version control system.

### Version Managers

*Utilities that help create the development shell environment and switch between different Java versions.*

- [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports Mac OS X, Linux and Windows.

### Web Crawling

*Libraries that analyze the content of websites.*

- [jsoup](https://jsoup.org) - Scrapes, parses, manipulates and cleans HTML.


### Web Frameworks

*Frameworks that handle the communication between the layers of a web application.*

- [Play](https://www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.

## Resources

### Awesome Lists

*Awesome lists related to the Java & JVM ecosystem.*


### Communities

*Active discussions.*

- [r/java](https://www.reddit.com/r/java) - Subreddit for the Java community.
- [stackoverflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.
- [VirtualJUG](https://virtualjug.com) - Virtual Java User Group.

### Frontends

*Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one.*

### Influential Books

*Books that made a big impact and are still worth reading.*


- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)

### Podcasts and Screencasts

*Something to look at or listen to while programming.*

- [Java Off Heap](http://www.javaoffheap.com)
- [Marco Behler's Screencasts](https://www.marcobehler.com/series) - Screencasts about modern Java development.
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### Twitter

- [intellijidea](https://twitter.com/intellijidea) - In addition to IntelliJ updates they share Java-related webinars and talks.
- [java](https://twitter.com/java) - The official Java twitter account shares plenty of interesting update news and presentations.

### Websites

*Sites to read.*

- [Java Annotated Monthly (Trisha Gee)](https://blog.jetbrains.com/author/trishagee/) - Summarizes new Java ecosystem libraries, talks, and other updates each month.

## Contributing

Contributions are very welcome!

Please have a look at the [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) guidelines.

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
