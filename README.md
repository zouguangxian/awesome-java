# Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Java frameworks, libraries and software.

## Contents

- [Projects](#projects)
  - [Bean Mapping](#bean-mapping)
  - [Build](#build)
  - [Bytecode Manipulation](#bytecode-manipulation)
  - [Caching](#caching)
  - [CLI](#cli)
  - [Cluster Management](#cluster-management)
  - [Code Analysis](#code-analysis)
  - [Code Coverage](#code-coverage)
  - [Code Generators](#code-generators)
  - [Compiler-compiler](#compiler-compiler)
  - [Computer Vision](#computer-vision)
  - [Configuration](#configuration)
  - [Constraint Satisfaction Problem Solver](#constraint-satisfaction-problem-solver)
  - [CSV](#csv)
  - [Data Structures](#data-structures)
  - [Database](#database)
  - [Date and Time](#date-and-time)
  - [Dependency Injection](#dependency-injection)
  - [Development](#development)
  - [Distributed Applications](#distributed-applications)
  - [Distributed Transactions](#distributed-transactions)
  - [Distribution](#distribution)
  - [Document Processing](#document-processing)
  - [Financial](#financial)
  - [Formal Verification](#formal-verification)
  - [Functional Programming](#functional-programming)
  - [Game Development](#game-development)
  - [Geospatial](#geospatial)
  - [GUI](#gui)
  - [High Performance](#high-performance)
  - [HTTP Clients](#http-clients)
  - [Hypermedia Types](#hypermedia-types)
  - [IDE](#ide)
  - [Imagery](#imagery)
  - [Introspection](#introspection)
  - [Job Scheduling](#job-scheduling)
  - [JSON](#json)
  - [JVM and JDK](#jvm-and-jdk)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microservice](#microservice)
  - [Miscellaneous](#miscellaneous)
  - [Mobile Development](#mobile-development)
  - [Monitoring](#monitoring)
  - [Native](#native)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [ORM](#orm)
  - [PaaS](#paas)
  - [PDF](#pdf)
  - [Performance analysis](#performance-analysis)
  - [Platform](#platform)
  - [Processes](#processes)
  - [Reactive libraries](#reactive-libraries)
  - [REST Frameworks](#rest-frameworks)
  - [Science](#science)
  - [Search](#search)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server](#server)
  - [Template Engine](#template-engine)
  - [Testing](#testing)
  - [Utility](#utility)
  - [Version Managers](#version-managers)
  - [Web Crawling](#web-crawling)
  - [Web Frameworks](#web-frameworks)
  - [Workflow Orchestration Engines](#workflow-orchestration-engines)
- [Resources](#resources)
  - [Related Awesome Lists](#awesome-lists)
  - [Communities](#communities)
  - [Frontends](#frontends)
  - [Influential Books](#influential-books)
  - [Podcasts and Screencasts](#podcasts-and-screencasts)
  - [People](#people)
  - [Websites](#websites)

## Projects

### Bean Mapping

_Frameworks that ease bean mapping._

- [dOOv](https://github.com/doov-io/doov) - Provides fluent API for typesafe domain model validation and mapping. It uses annotations, code generation and a type safe DSL to make bean validation and mapping fast and easy.

   ![](https://img.shields.io/github/stars/doov-io/doov) ![](https://img.shields.io/github/last-commit/doov-io/doov) ![](https://img.shields.io/github/issues/doov-io/doov) ![](https://img.shields.io/github/issues-pr/doov-io/doov) ![](https://img.shields.io/github/license/doov-io/doov) ![](https://img.shields.io/github/forks/doov-io/doov) ![](https://img.shields.io/github/contributors/doov-io/doov)

- [JMapper](https://github.com/jmapper-framework/jmapper-core) - Uses byte code manipulation for lightning-fast mapping. Supports annotations and API or XML configuration.

   ![](https://img.shields.io/github/stars/jmapper-framework/jmapper-core) ![](https://img.shields.io/github/last-commit/jmapper-framework/jmapper-core) ![](https://img.shields.io/github/issues/jmapper-framework/jmapper-core) ![](https://img.shields.io/github/issues-pr/jmapper-framework/jmapper-core) ![](https://img.shields.io/github/license/jmapper-framework/jmapper-core) ![](https://img.shields.io/github/forks/jmapper-framework/jmapper-core) ![](https://img.shields.io/github/contributors/jmapper-framework/jmapper-core)

- [MapStruct](https://github.com/mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach.

   ![](https://img.shields.io/github/stars/mapstruct/mapstruct) ![](https://img.shields.io/github/last-commit/mapstruct/mapstruct) ![](https://img.shields.io/github/issues/mapstruct/mapstruct) ![](https://img.shields.io/github/issues-pr/mapstruct/mapstruct) ![](https://img.shields.io/github/license/mapstruct/mapstruct) ![](https://img.shields.io/github/forks/mapstruct/mapstruct) ![](https://img.shields.io/github/contributors/mapstruct/mapstruct)

- [ModelMapper](https://github.com/modelmapper/modelmapper) - Intelligent object mapping library that automatically maps objects to each other.

   ![](https://img.shields.io/github/stars/modelmapper/modelmapper) ![](https://img.shields.io/github/last-commit/modelmapper/modelmapper) ![](https://img.shields.io/github/issues/modelmapper/modelmapper) ![](https://img.shields.io/github/issues-pr/modelmapper/modelmapper) ![](https://img.shields.io/github/license/modelmapper/modelmapper) ![](https://img.shields.io/github/forks/modelmapper/modelmapper) ![](https://img.shields.io/github/contributors/modelmapper/modelmapper)

- [Orika](https://github.com/orika-mapper/orika) - JavaBean-mapping framework that recursively copies (among other capabilities) data from one object to another.

   ![](https://img.shields.io/github/stars/orika-mapper/orika) ![](https://img.shields.io/github/last-commit/orika-mapper/orika) ![](https://img.shields.io/github/issues/orika-mapper/orika) ![](https://img.shields.io/github/issues-pr/orika-mapper/orika) ![](https://img.shields.io/github/license/orika-mapper/orika) ![](https://img.shields.io/github/forks/orika-mapper/orika) ![](https://img.shields.io/github/contributors/orika-mapper/orika)

- [reMap](https://github.com/remondis-it/remap) - Lambda and method handle-based mapping which requires code and not annotations if objects have different names.

   ![](https://img.shields.io/github/stars/remondis-it/remap) ![](https://img.shields.io/github/last-commit/remondis-it/remap) ![](https://img.shields.io/github/issues/remondis-it/remap) ![](https://img.shields.io/github/issues-pr/remondis-it/remap) ![](https://img.shields.io/github/license/remondis-it/remap) ![](https://img.shields.io/github/forks/remondis-it/remap) ![](https://img.shields.io/github/contributors/remondis-it/remap)

- [Selma](https://github.com/xebia-france/selma) - Annotation processor-based bean mapper.

   ![](https://img.shields.io/github/stars/xebia-france/selma) ![](https://img.shields.io/github/last-commit/xebia-france/selma) ![](https://img.shields.io/github/issues/xebia-france/selma) ![](https://img.shields.io/github/issues-pr/xebia-france/selma) ![](https://img.shields.io/github/license/xebia-france/selma) ![](https://img.shields.io/github/forks/xebia-france/selma) ![](https://img.shields.io/github/contributors/xebia-france/selma)


### Build

_Tools that handle the build cycle and dependencies of an application._

- [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
- [Bazel](https://bazel.build) - Tool from Google that builds code quickly and reliably.
- [Buck](https://github.com/facebook/buck) - Encourages the creation of small, reusable modules consisting of code and resources.

   ![](https://img.shields.io/github/stars/facebook/buck) ![](https://img.shields.io/github/last-commit/facebook/buck) ![](https://img.shields.io/github/issues/facebook/buck) ![](https://img.shields.io/github/issues-pr/facebook/buck) ![](https://img.shields.io/github/license/facebook/buck) ![](https://img.shields.io/github/forks/facebook/buck) ![](https://img.shields.io/github/contributors/facebook/buck)

- [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

_Libraries to manipulate bytecode programmatically._

- [ASM](https://asm.ow2.io) - All-purpose, low-level bytecode manipulation and analysis.
- [Byte Buddy](https://bytebuddy.net) - Further simplifies bytecode generation with a fluent API.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) - Java 8 Jar & Android APK reverse engineering suite. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/Konloch/bytecode-viewer) ![](https://img.shields.io/github/last-commit/Konloch/bytecode-viewer) ![](https://img.shields.io/github/issues/Konloch/bytecode-viewer) ![](https://img.shields.io/github/issues-pr/Konloch/bytecode-viewer) ![](https://img.shields.io/github/license/Konloch/bytecode-viewer) ![](https://img.shields.io/github/forks/Konloch/bytecode-viewer) ![](https://img.shields.io/github/contributors/Konloch/bytecode-viewer)

- [Byteman](https://byteman.jboss.org) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting. (LGPL-2.1-or-later)
- [cglib](https://github.com/cglib/cglib) - Bytecode generation library.

   ![](https://img.shields.io/github/stars/cglib/cglib) ![](https://img.shields.io/github/last-commit/cglib/cglib) ![](https://img.shields.io/github/issues/cglib/cglib) ![](https://img.shields.io/github/issues-pr/cglib/cglib) ![](https://img.shields.io/github/license/cglib/cglib) ![](https://img.shields.io/github/forks/cglib/cglib) ![](https://img.shields.io/github/contributors/cglib/cglib)

- [Javassist](https://github.com/jboss-javassist/javassist) - Tries to simplify bytecode editing.

   ![](https://img.shields.io/github/stars/jboss-javassist/javassist) ![](https://img.shields.io/github/last-commit/jboss-javassist/javassist) ![](https://img.shields.io/github/issues/jboss-javassist/javassist) ![](https://img.shields.io/github/issues-pr/jboss-javassist/javassist) ![](https://img.shields.io/github/license/jboss-javassist/javassist) ![](https://img.shields.io/github/forks/jboss-javassist/javassist) ![](https://img.shields.io/github/contributors/jboss-javassist/javassist)

- [Mixin](https://github.com/SpongePowered/Mixin) - Manipulate bytecode at runtime using real Java code.

   ![](https://img.shields.io/github/stars/SpongePowered/Mixin) ![](https://img.shields.io/github/last-commit/SpongePowered/Mixin) ![](https://img.shields.io/github/issues/SpongePowered/Mixin) ![](https://img.shields.io/github/issues-pr/SpongePowered/Mixin) ![](https://img.shields.io/github/license/SpongePowered/Mixin) ![](https://img.shields.io/github/forks/SpongePowered/Mixin) ![](https://img.shields.io/github/contributors/SpongePowered/Mixin)

- [Perses](https://github.com/nicolasmanic/perses) - Dynamically injects failure/latency at the bytecode level according to principles of chaos engineering.

   ![](https://img.shields.io/github/stars/nicolasmanic/perses) ![](https://img.shields.io/github/last-commit/nicolasmanic/perses) ![](https://img.shields.io/github/issues/nicolasmanic/perses) ![](https://img.shields.io/github/issues-pr/nicolasmanic/perses) ![](https://img.shields.io/github/license/nicolasmanic/perses) ![](https://img.shields.io/github/forks/nicolasmanic/perses) ![](https://img.shields.io/github/contributors/nicolasmanic/perses)


### Caching

_Libraries that provide caching facilities._

- [cache2k](https://cache2k.org) - In-memory high performance caching library.
- [Caffeine](https://github.com/ben-manes/caffeine) - High-performance, near-optimal caching library.

   ![](https://img.shields.io/github/stars/ben-manes/caffeine) ![](https://img.shields.io/github/last-commit/ben-manes/caffeine) ![](https://img.shields.io/github/issues/ben-manes/caffeine) ![](https://img.shields.io/github/issues-pr/ben-manes/caffeine) ![](https://img.shields.io/github/license/ben-manes/caffeine) ![](https://img.shields.io/github/forks/ben-manes/caffeine) ![](https://img.shields.io/github/contributors/ben-manes/caffeine)

- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.
- [Infinispan](https://infinispan.org) - Highly concurrent key/value datastore used for caching.

### CLI

_Libraries for everything related to the CLI._

- [ASCII Table](https://github.com/vdmeer/asciitable) - Library to draw tables in ASCII.

   ![](https://img.shields.io/github/stars/vdmeer/asciitable) ![](https://img.shields.io/github/last-commit/vdmeer/asciitable) ![](https://img.shields.io/github/issues/vdmeer/asciitable) ![](https://img.shields.io/github/issues-pr/vdmeer/asciitable) ![](https://img.shields.io/github/license/vdmeer/asciitable) ![](https://img.shields.io/github/forks/vdmeer/asciitable) ![](https://img.shields.io/github/contributors/vdmeer/asciitable)

- [Airline](https://github.com/airlift/airline) - Annotation-based framework for parsing Git-like command-line arguments.

   ![](https://img.shields.io/github/stars/airlift/airline) ![](https://img.shields.io/github/last-commit/airlift/airline) ![](https://img.shields.io/github/issues/airlift/airline) ![](https://img.shields.io/github/issues-pr/airlift/airline) ![](https://img.shields.io/github/license/airlift/airline) ![](https://img.shields.io/github/forks/airlift/airline) ![](https://img.shields.io/github/contributors/airlift/airline)

- [args4j](http://args4j.kohsuke.org) - Small library to parse command-line arguments.
- [Jansi](https://github.com/fusesource/jansi) - ANSI escape codes to format console output.

   ![](https://img.shields.io/github/stars/fusesource/jansi) ![](https://img.shields.io/github/last-commit/fusesource/jansi) ![](https://img.shields.io/github/issues/fusesource/jansi) ![](https://img.shields.io/github/issues-pr/fusesource/jansi) ![](https://img.shields.io/github/license/fusesource/jansi) ![](https://img.shields.io/github/forks/fusesource/jansi) ![](https://img.shields.io/github/contributors/fusesource/jansi)

- [Java ASCII Render](https://github.com/indvd00m/java-ascii-render) - Graphical primitives for the console.

   ![](https://img.shields.io/github/stars/indvd00m/java-ascii-render) ![](https://img.shields.io/github/last-commit/indvd00m/java-ascii-render) ![](https://img.shields.io/github/issues/indvd00m/java-ascii-render) ![](https://img.shields.io/github/issues-pr/indvd00m/java-ascii-render) ![](https://img.shields.io/github/license/indvd00m/java-ascii-render) ![](https://img.shields.io/github/forks/indvd00m/java-ascii-render) ![](https://img.shields.io/github/contributors/indvd00m/java-ascii-render)

- [JCommander](http://jcommander.org) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
- [jbock](https://github.com/jbock-java/jbock) - Reflectionless command line parser.

   ![](https://img.shields.io/github/stars/jbock-java/jbock) ![](https://img.shields.io/github/last-commit/jbock-java/jbock) ![](https://img.shields.io/github/issues/jbock-java/jbock) ![](https://img.shields.io/github/issues-pr/jbock-java/jbock) ![](https://img.shields.io/github/license/jbock-java/jbock) ![](https://img.shields.io/github/forks/jbock-java/jbock) ![](https://img.shields.io/github/contributors/jbock-java/jbock)

- [Jexer](https://gitlab.com/klamonte/jexer) - Advanced console (and Swing) text user interface (TUI) library, with mouse-draggable windows, built-in terminal window manager, and sixel image support. Looks like [Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision).
- [JLine](https://github.com/jline/jline3) - Includes features from modern shells like completion or history.

   ![](https://img.shields.io/github/stars/jline/jline3) ![](https://img.shields.io/github/last-commit/jline/jline3) ![](https://img.shields.io/github/issues/jline/jline3) ![](https://img.shields.io/github/issues-pr/jline/jline3) ![](https://img.shields.io/github/license/jline/jline3) ![](https://img.shields.io/github/forks/jline/jline3) ![](https://img.shields.io/github/contributors/jline/jline3)

- [JOpt Simple](https://jopt-simple.github.io/jopt-simple/) - Fluent parser that uses the POSIX#getopt and GNU#getopt_long syntaxes.
- [picocli](https://picocli.info) - ANSI colors and styles in usage help with annotation-based POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.
- [Text-IO](https://github.com/beryx/text-io) - Aids the creation of full console-based applications.

   ![](https://img.shields.io/github/stars/beryx/text-io) ![](https://img.shields.io/github/last-commit/beryx/text-io) ![](https://img.shields.io/github/issues/beryx/text-io) ![](https://img.shields.io/github/issues-pr/beryx/text-io) ![](https://img.shields.io/github/license/beryx/text-io) ![](https://img.shields.io/github/forks/beryx/text-io) ![](https://img.shields.io/github/contributors/beryx/text-io)

- [Lanterna](https://github.com/mabe02/lanterna) - Easy console text-GUI library, similar to curses. (LGPL-3.0-only)

   ![](https://img.shields.io/github/stars/mabe02/lanterna) ![](https://img.shields.io/github/last-commit/mabe02/lanterna) ![](https://img.shields.io/github/issues/mabe02/lanterna) ![](https://img.shields.io/github/issues-pr/mabe02/lanterna) ![](https://img.shields.io/github/license/mabe02/lanterna) ![](https://img.shields.io/github/forks/mabe02/lanterna) ![](https://img.shields.io/github/contributors/mabe02/lanterna)


### Cluster Management

_Frameworks that can dynamically manage applications inside of a cluster._

- [Apache Aurora](https://aurora.apache.org) - Mesos framework for long-running services and cron jobs.
- [Singularity](http://getsingularity.com) - Mesos framework that makes deployment and operations easy. It supports web services, background workers, scheduled jobs, and one-off tasks.

### Code Analysis

_Tools that provide metrics and quality measurements._

- [Checkstyle](https://github.com/checkstyle/checkstyle) - Static analysis of coding conventions and standards. (LGPL-2.1-or-later)

   ![](https://img.shields.io/github/stars/checkstyle/checkstyle) ![](https://img.shields.io/github/last-commit/checkstyle/checkstyle) ![](https://img.shields.io/github/issues/checkstyle/checkstyle) ![](https://img.shields.io/github/issues-pr/checkstyle/checkstyle) ![](https://img.shields.io/github/license/checkstyle/checkstyle) ![](https://img.shields.io/github/forks/checkstyle/checkstyle) ![](https://img.shields.io/github/contributors/checkstyle/checkstyle)

- [Error Prone](https://github.com/google/error-prone) - Catches common programming mistakes as compile-time errors.

   ![](https://img.shields.io/github/stars/google/error-prone) ![](https://img.shields.io/github/last-commit/google/error-prone) ![](https://img.shields.io/github/issues/google/error-prone) ![](https://img.shields.io/github/issues-pr/google/error-prone) ![](https://img.shields.io/github/license/google/error-prone) ![](https://img.shields.io/github/forks/google/error-prone) ![](https://img.shields.io/github/contributors/google/error-prone)

- [Infer](https://github.com/facebook/infer) - Modern static analysis tool for verifying the correctness of code.

   ![](https://img.shields.io/github/stars/facebook/infer) ![](https://img.shields.io/github/last-commit/facebook/infer) ![](https://img.shields.io/github/issues/facebook/infer) ![](https://img.shields.io/github/issues-pr/facebook/infer) ![](https://img.shields.io/github/license/facebook/infer) ![](https://img.shields.io/github/forks/facebook/infer) ![](https://img.shields.io/github/contributors/facebook/infer)

- [jQAssistant](https://jqassistant.org) - Static code analysis with Neo4J-based query language. (GPL-3.0-only)
- [NullAway](https://github.com/uber/NullAway) - Eliminates NullPointerExceptions with low build-time overhead.

   ![](https://img.shields.io/github/stars/uber/NullAway) ![](https://img.shields.io/github/last-commit/uber/NullAway) ![](https://img.shields.io/github/issues/uber/NullAway) ![](https://img.shields.io/github/issues-pr/uber/NullAway) ![](https://img.shields.io/github/license/uber/NullAway) ![](https://img.shields.io/github/forks/uber/NullAway) ![](https://img.shields.io/github/contributors/uber/NullAway)

- [PMD](https://github.com/pmd/pmd) - Source code analysis for finding bad coding practices.

   ![](https://img.shields.io/github/stars/pmd/pmd) ![](https://img.shields.io/github/last-commit/pmd/pmd) ![](https://img.shields.io/github/issues/pmd/pmd) ![](https://img.shields.io/github/issues-pr/pmd/pmd) ![](https://img.shields.io/github/license/pmd/pmd) ![](https://img.shields.io/github/forks/pmd/pmd) ![](https://img.shields.io/github/contributors/pmd/pmd)

- [SonarJava](https://github.com/SonarSource/sonar-java) - Static analyzer for SonarQube & SonarLint. (LGPL-3.0-only)

   ![](https://img.shields.io/github/stars/SonarSource/sonar-java) ![](https://img.shields.io/github/last-commit/SonarSource/sonar-java) ![](https://img.shields.io/github/issues/SonarSource/sonar-java) ![](https://img.shields.io/github/issues-pr/SonarSource/sonar-java) ![](https://img.shields.io/github/license/SonarSource/sonar-java) ![](https://img.shields.io/github/forks/SonarSource/sonar-java) ![](https://img.shields.io/github/contributors/SonarSource/sonar-java)

- [Sourcetrail](https://www.sourcetrail.com) - Visual source code navigator.
- [Spoon](https://github.com/INRIA/spoon) - Library for analyzing and transforming Java source code.

   ![](https://img.shields.io/github/stars/INRIA/spoon) ![](https://img.shields.io/github/last-commit/INRIA/spoon) ![](https://img.shields.io/github/issues/INRIA/spoon) ![](https://img.shields.io/github/issues-pr/INRIA/spoon) ![](https://img.shields.io/github/license/INRIA/spoon) ![](https://img.shields.io/github/forks/INRIA/spoon) ![](https://img.shields.io/github/contributors/INRIA/spoon)

- [Spotbugs](https://github.com/spotbugs/spotbugs) - Static analysis of bytecode to find potential bugs. (LGPL-2.1-only)

   ![](https://img.shields.io/github/stars/spotbugs/spotbugs) ![](https://img.shields.io/github/last-commit/spotbugs/spotbugs) ![](https://img.shields.io/github/issues/spotbugs/spotbugs) ![](https://img.shields.io/github/issues-pr/spotbugs/spotbugs) ![](https://img.shields.io/github/license/spotbugs/spotbugs) ![](https://img.shields.io/github/forks/spotbugs/spotbugs) ![](https://img.shields.io/github/contributors/spotbugs/spotbugs)


### Code Coverage

_Frameworks and tools that enable code coverage metrics collection for test suites._

- [Clover](https://www.atlassian.com/software/clover) - Relies on source-code instrumentation instead of bytecode instrumentation.
- [Cobertura](https://cobertura.github.io/cobertura/) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics. (GPL-2.0-only)
- [JaCoCo](https://www.eclemma.org/jacoco/) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

_Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness._

- [ADT4J](https://github.com/sviperll/adt4j) - JSR-269 code generator for algebraic data types.

   ![](https://img.shields.io/github/stars/sviperll/adt4j) ![](https://img.shields.io/github/last-commit/sviperll/adt4j) ![](https://img.shields.io/github/issues/sviperll/adt4j) ![](https://img.shields.io/github/issues-pr/sviperll/adt4j) ![](https://img.shields.io/github/license/sviperll/adt4j) ![](https://img.shields.io/github/forks/sviperll/adt4j) ![](https://img.shields.io/github/contributors/sviperll/adt4j)

- [Auto](https://github.com/google/auto) - Generates factory, service, and value classes.

   ![](https://img.shields.io/github/stars/google/auto) ![](https://img.shields.io/github/last-commit/google/auto) ![](https://img.shields.io/github/issues/google/auto) ![](https://img.shields.io/github/issues-pr/google/auto) ![](https://img.shields.io/github/license/google/auto) ![](https://img.shields.io/github/forks/google/auto) ![](https://img.shields.io/github/contributors/google/auto)

- [Bootify ![c]](https://bootify.io) - Browser-based Spring Boot app generation with JPA model and REST API.
- [FreeBuilder](https://github.com/inferred/FreeBuilder) - Automatically generates the Builder pattern.

   ![](https://img.shields.io/github/stars/inferred/FreeBuilder) ![](https://img.shields.io/github/last-commit/inferred/FreeBuilder) ![](https://img.shields.io/github/issues/inferred/FreeBuilder) ![](https://img.shields.io/github/issues-pr/inferred/FreeBuilder) ![](https://img.shields.io/github/license/inferred/FreeBuilder) ![](https://img.shields.io/github/forks/inferred/FreeBuilder) ![](https://img.shields.io/github/contributors/inferred/FreeBuilder)

- [Geci](https://github.com/verhas/javageci) - Discovers files that need generated code, updates automatically and writes to the source with a convenient API.

   ![](https://img.shields.io/github/stars/verhas/javageci) ![](https://img.shields.io/github/last-commit/verhas/javageci) ![](https://img.shields.io/github/issues/verhas/javageci) ![](https://img.shields.io/github/issues-pr/verhas/javageci) ![](https://img.shields.io/github/license/verhas/javageci) ![](https://img.shields.io/github/forks/verhas/javageci) ![](https://img.shields.io/github/contributors/verhas/javageci)

- [Immutables](https://immutables.github.io) - Annotation processors to generate simple, safe and consistent value objects.
- [JavaPoet](https://github.com/square/javapoet) - API to generate source files.

   ![](https://img.shields.io/github/stars/square/javapoet) ![](https://img.shields.io/github/last-commit/square/javapoet) ![](https://img.shields.io/github/issues/square/javapoet) ![](https://img.shields.io/github/issues-pr/square/javapoet) ![](https://img.shields.io/github/license/square/javapoet) ![](https://img.shields.io/github/forks/square/javapoet) ![](https://img.shields.io/github/contributors/square/javapoet)

- [JHipster](https://github.com/jhipster/generator-jhipster) - Yeoman source code generator for Spring Boot and AngularJS.

   ![](https://img.shields.io/github/stars/jhipster/generator-jhipster) ![](https://img.shields.io/github/last-commit/jhipster/generator-jhipster) ![](https://img.shields.io/github/issues/jhipster/generator-jhipster) ![](https://img.shields.io/github/issues-pr/jhipster/generator-jhipster) ![](https://img.shields.io/github/license/jhipster/generator-jhipster) ![](https://img.shields.io/github/forks/jhipster/generator-jhipster) ![](https://img.shields.io/github/contributors/jhipster/generator-jhipster)

- [Joda-Beans](https://www.joda.org/joda-beans/) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
- [JPA Buddy ![c]](https://www.jpa-buddy.com) - Plugin for IntelliJ IDEA. Provides visual tools for generating JPA entities, Spring Data JPA repositories, Liquibase changelogs and SQL scripts. Offers automatic Liquibase/Flyway script generation by comparing model to DB, and reverse engineering JPA entities from DB tables.
- [Lombok](https://projectlombok.org) - Code generator that aims to reduce verbosity.
- [Record-Builder](https://github.com/Randgalt/record-builder) - Companion builder class, withers and templates for Java records.

   ![](https://img.shields.io/github/stars/Randgalt/record-builder) ![](https://img.shields.io/github/last-commit/Randgalt/record-builder) ![](https://img.shields.io/github/issues/Randgalt/record-builder) ![](https://img.shields.io/github/issues-pr/Randgalt/record-builder) ![](https://img.shields.io/github/license/Randgalt/record-builder) ![](https://img.shields.io/github/forks/Randgalt/record-builder) ![](https://img.shields.io/github/contributors/Randgalt/record-builder)

- [Telosys](https://www.telosys.org/) - Simple and light code generator available as an Eclipse Plugin and also as a CLI.

### Compiler-compiler

_Frameworks that help to create parsers, interpreters or compilers._

- [ANTLR](https://www.antlr.org) - Complex full-featured framework for top-down parsing.
- [JavaCC](https://javacc.github.io/javacc/) - Parser generator that generates top-down parsers. Allows lexical state switching and permits extended BNF specifications.
- [JFlex](https://jflex.de) - Lexical analyzer generator.

### Computer Vision

_Libraries which seek to gain high level information from images and videos._

- [BoofCV](https://boofcv.org) - Library for image processing, camera calibration, tracking, SFM, MVS, 3D vision, QR Code and much more.
- [ImageJ](https://imagej.net/ImageJ) - Medical image processing application with an API.
- [JavaCV](https://github.com/bytedeco/javacv) - Java interface to OpenCV, FFmpeg, and much more.

   ![](https://img.shields.io/github/stars/bytedeco/javacv) ![](https://img.shields.io/github/last-commit/bytedeco/javacv) ![](https://img.shields.io/github/issues/bytedeco/javacv) ![](https://img.shields.io/github/issues-pr/bytedeco/javacv) ![](https://img.shields.io/github/license/bytedeco/javacv) ![](https://img.shields.io/github/forks/bytedeco/javacv) ![](https://img.shields.io/github/contributors/bytedeco/javacv)


### Configuration

_Libraries that provide external configuration._

- [centraldogma](https://github.com/line/centraldogma) - Highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2.

   ![](https://img.shields.io/github/stars/line/centraldogma) ![](https://img.shields.io/github/last-commit/line/centraldogma) ![](https://img.shields.io/github/issues/line/centraldogma) ![](https://img.shields.io/github/issues-pr/line/centraldogma) ![](https://img.shields.io/github/license/line/centraldogma) ![](https://img.shields.io/github/forks/line/centraldogma) ![](https://img.shields.io/github/contributors/line/centraldogma)

- [cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps written in Java.

   ![](https://img.shields.io/github/stars/cfg4j/cfg4j) ![](https://img.shields.io/github/last-commit/cfg4j/cfg4j) ![](https://img.shields.io/github/issues/cfg4j/cfg4j) ![](https://img.shields.io/github/issues-pr/cfg4j/cfg4j) ![](https://img.shields.io/github/license/cfg4j/cfg4j) ![](https://img.shields.io/github/forks/cfg4j/cfg4j) ![](https://img.shields.io/github/contributors/cfg4j/cfg4j)

- [config](https://github.com/lightbend/config) - Configuration library supporting Java properties, JSON or its human optimized superset HOCON.

   ![](https://img.shields.io/github/stars/lightbend/config) ![](https://img.shields.io/github/last-commit/lightbend/config) ![](https://img.shields.io/github/issues/lightbend/config) ![](https://img.shields.io/github/issues-pr/lightbend/config) ![](https://img.shields.io/github/license/lightbend/config) ![](https://img.shields.io/github/forks/lightbend/config) ![](https://img.shields.io/github/contributors/lightbend/config)

- [Configurate](https://github.com/SpongePowered/Configurate) - Configuration library with support for various configuration formats and transformations.

   ![](https://img.shields.io/github/stars/SpongePowered/Configurate) ![](https://img.shields.io/github/last-commit/SpongePowered/Configurate) ![](https://img.shields.io/github/issues/SpongePowered/Configurate) ![](https://img.shields.io/github/issues-pr/SpongePowered/Configurate) ![](https://img.shields.io/github/license/SpongePowered/Configurate) ![](https://img.shields.io/github/forks/SpongePowered/Configurate) ![](https://img.shields.io/github/contributors/SpongePowered/Configurate)

- [dotenv](https://github.com/shyiko/dotenv) - Twelve-factor configuration library which uses environment-specific files.

   ![](https://img.shields.io/github/stars/shyiko/dotenv) ![](https://img.shields.io/github/last-commit/shyiko/dotenv) ![](https://img.shields.io/github/issues/shyiko/dotenv) ![](https://img.shields.io/github/issues-pr/shyiko/dotenv) ![](https://img.shields.io/github/license/shyiko/dotenv) ![](https://img.shields.io/github/forks/shyiko/dotenv) ![](https://img.shields.io/github/contributors/shyiko/dotenv)

- [ini4j](http://ini4j.sourceforge.net) - Provides an API for handling Windows' INI files.
- [KAConf](https://github.com/mariomac/kaconf) - Annotation-based configuration system for Java and Kotlin.

   ![](https://img.shields.io/github/stars/mariomac/kaconf) ![](https://img.shields.io/github/last-commit/mariomac/kaconf) ![](https://img.shields.io/github/issues/mariomac/kaconf) ![](https://img.shields.io/github/issues-pr/mariomac/kaconf) ![](https://img.shields.io/github/license/mariomac/kaconf) ![](https://img.shields.io/github/forks/mariomac/kaconf) ![](https://img.shields.io/github/contributors/mariomac/kaconf)

- [microconfig](https://microconfig.io) - Configuration system designed for microservices which helps to separate configuration from code. The configuration for different services can have common and specific parts and can be dynamically distributed.
- [owner](https://github.com/lviggiano/owner) - Reduces boilerplate of properties.

   ![](https://img.shields.io/github/stars/lviggiano/owner) ![](https://img.shields.io/github/last-commit/lviggiano/owner) ![](https://img.shields.io/github/issues/lviggiano/owner) ![](https://img.shields.io/github/issues-pr/lviggiano/owner) ![](https://img.shields.io/github/license/lviggiano/owner) ![](https://img.shields.io/github/forks/lviggiano/owner) ![](https://img.shields.io/github/contributors/lviggiano/owner)


### Constraint Satisfaction Problem Solver

_Libraries that help with implementing optimization and satisfiability problems._

- [Choco](https://choco-solver.org) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
- [JaCoP](https://github.com/radsz/jacop) - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models. (AGPL-3.0)

   ![](https://img.shields.io/github/stars/radsz/jacop) ![](https://img.shields.io/github/last-commit/radsz/jacop) ![](https://img.shields.io/github/issues/radsz/jacop) ![](https://img.shields.io/github/issues-pr/radsz/jacop) ![](https://img.shields.io/github/license/radsz/jacop) ![](https://img.shields.io/github/forks/radsz/jacop) ![](https://img.shields.io/github/contributors/radsz/jacop)

- [OptaPlanner](https://www.optaplanner.org) - Business planning and resource scheduling optimization solver.

### CSV

_Frameworks and libraries that simplify reading/writing CSV data._

- [FastCSV](https://github.com/osiegmar/FastCSV) - Performance-optimized, dependency-free and RFC 4180 compliant.

   ![](https://img.shields.io/github/stars/osiegmar/FastCSV) ![](https://img.shields.io/github/last-commit/osiegmar/FastCSV) ![](https://img.shields.io/github/issues/osiegmar/FastCSV) ![](https://img.shields.io/github/issues-pr/osiegmar/FastCSV) ![](https://img.shields.io/github/license/osiegmar/FastCSV) ![](https://img.shields.io/github/forks/osiegmar/FastCSV) ![](https://img.shields.io/github/contributors/osiegmar/FastCSV)

- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV.

   ![](https://img.shields.io/github/stars/FasterXML/jackson-dataformat-csv) ![](https://img.shields.io/github/last-commit/FasterXML/jackson-dataformat-csv) ![](https://img.shields.io/github/issues/FasterXML/jackson-dataformat-csv) ![](https://img.shields.io/github/issues-pr/FasterXML/jackson-dataformat-csv) ![](https://img.shields.io/github/license/FasterXML/jackson-dataformat-csv) ![](https://img.shields.io/github/forks/FasterXML/jackson-dataformat-csv) ![](https://img.shields.io/github/contributors/FasterXML/jackson-dataformat-csv)

- [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
- [Super CSV](https://super-csv.github.io/super-csv/) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records.

   ![](https://img.shields.io/github/stars/uniVocity/univocity-parsers) ![](https://img.shields.io/github/last-commit/uniVocity/univocity-parsers) ![](https://img.shields.io/github/issues/uniVocity/univocity-parsers) ![](https://img.shields.io/github/issues-pr/uniVocity/univocity-parsers) ![](https://img.shields.io/github/license/uniVocity/univocity-parsers) ![](https://img.shields.io/github/forks/uniVocity/univocity-parsers) ![](https://img.shields.io/github/contributors/uniVocity/univocity-parsers)


### Data Structures

_Efficient and specific data structures._

- [Apache Avro](https://avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
- [Apache Orc](https://orc.apache.org) - Fast and efficient columnar storage format for Hadoop-based workloads.
- [Apache Parquet](https://parquet.apache.org) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
- [Apache Thrift](https://thrift.apache.org) - Data interchange format that originated at Facebook.
- [Big Queue](https://github.com/bulldog2011/bigqueue) - Fast and persistent queue based on memory-mapped files.

   ![](https://img.shields.io/github/stars/bulldog2011/bigqueue) ![](https://img.shields.io/github/last-commit/bulldog2011/bigqueue) ![](https://img.shields.io/github/issues/bulldog2011/bigqueue) ![](https://img.shields.io/github/issues-pr/bulldog2011/bigqueue) ![](https://img.shields.io/github/license/bulldog2011/bigqueue) ![](https://img.shields.io/github/forks/bulldog2011/bigqueue) ![](https://img.shields.io/github/contributors/bulldog2011/bigqueue)

- [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java) - Probabilistic data structure for computing union, intersection, and set cardinality in loglog space.

   ![](https://img.shields.io/github/stars/LiveRamp/HyperMinHash-java) ![](https://img.shields.io/github/last-commit/LiveRamp/HyperMinHash-java) ![](https://img.shields.io/github/issues/LiveRamp/HyperMinHash-java) ![](https://img.shields.io/github/issues-pr/LiveRamp/HyperMinHash-java) ![](https://img.shields.io/github/license/LiveRamp/HyperMinHash-java) ![](https://img.shields.io/github/forks/LiveRamp/HyperMinHash-java) ![](https://img.shields.io/github/contributors/LiveRamp/HyperMinHash-java)

- [Persistent Collection](https://github.com/hrldcpr/pcollections) - Persistent and immutable analogue of the Java Collections Framework.

   ![](https://img.shields.io/github/stars/hrldcpr/pcollections) ![](https://img.shields.io/github/last-commit/hrldcpr/pcollections) ![](https://img.shields.io/github/issues/hrldcpr/pcollections) ![](https://img.shields.io/github/issues-pr/hrldcpr/pcollections) ![](https://img.shields.io/github/license/hrldcpr/pcollections) ![](https://img.shields.io/github/forks/hrldcpr/pcollections) ![](https://img.shields.io/github/contributors/hrldcpr/pcollections)

- [Protobuf](https://github.com/protocolbuffers/protobuf) - Google's data interchange format.

   ![](https://img.shields.io/github/stars/protocolbuffers/protobuf) ![](https://img.shields.io/github/last-commit/protocolbuffers/protobuf) ![](https://img.shields.io/github/issues/protocolbuffers/protobuf) ![](https://img.shields.io/github/issues-pr/protocolbuffers/protobuf) ![](https://img.shields.io/github/license/protocolbuffers/protobuf) ![](https://img.shields.io/github/forks/protocolbuffers/protobuf) ![](https://img.shields.io/github/contributors/protocolbuffers/protobuf)

- [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) - Fast and efficient compressed bitmap.

   ![](https://img.shields.io/github/stars/RoaringBitmap/RoaringBitmap) ![](https://img.shields.io/github/last-commit/RoaringBitmap/RoaringBitmap) ![](https://img.shields.io/github/issues/RoaringBitmap/RoaringBitmap) ![](https://img.shields.io/github/issues-pr/RoaringBitmap/RoaringBitmap) ![](https://img.shields.io/github/license/RoaringBitmap/RoaringBitmap) ![](https://img.shields.io/github/forks/RoaringBitmap/RoaringBitmap) ![](https://img.shields.io/github/contributors/RoaringBitmap/RoaringBitmap)

- [SBE](https://github.com/real-logic/simple-binary-encoding) - Simple Binary Encoding, one of the fastest message formats around.

   ![](https://img.shields.io/github/stars/real-logic/simple-binary-encoding) ![](https://img.shields.io/github/last-commit/real-logic/simple-binary-encoding) ![](https://img.shields.io/github/issues/real-logic/simple-binary-encoding) ![](https://img.shields.io/github/issues-pr/real-logic/simple-binary-encoding) ![](https://img.shields.io/github/license/real-logic/simple-binary-encoding) ![](https://img.shields.io/github/forks/real-logic/simple-binary-encoding) ![](https://img.shields.io/github/contributors/real-logic/simple-binary-encoding)

- [Tape](https://github.com/square/tape) - Lightning-fast, transactional, file-based FIFO.

   ![](https://img.shields.io/github/stars/square/tape) ![](https://img.shields.io/github/last-commit/square/tape) ![](https://img.shields.io/github/issues/square/tape) ![](https://img.shields.io/github/issues-pr/square/tape) ![](https://img.shields.io/github/license/square/tape) ![](https://img.shields.io/github/forks/square/tape) ![](https://img.shields.io/github/contributors/square/tape)

- [Wire](https://github.com/square/wire) - Clean, lightweight protocol buffers.

   ![](https://img.shields.io/github/stars/square/wire) ![](https://img.shields.io/github/last-commit/square/wire) ![](https://img.shields.io/github/issues/square/wire) ![](https://img.shields.io/github/issues-pr/square/wire) ![](https://img.shields.io/github/license/square/wire) ![](https://img.shields.io/github/forks/square/wire) ![](https://img.shields.io/github/contributors/square/wire)


### Database

_Everything that simplifies interactions with the database._

- [Apache Calcite](https://calcite.apache.org) - Dynamic data management framework. It contains many of the pieces that comprise a typical database management system.
- [Apache Drill](https://drill.apache.org) - Distributed, schema on-the-fly, ANSI SQL query engine for Big Data exploration.
- [Apache Phoenix](https://phoenix.apache.org) - High-performance relational database layer over HBase for low-latency applications.
- [ArangoDB](https://github.com/arangodb/arangodb-java-driver) - ArangoDB Java driver.

   ![](https://img.shields.io/github/stars/arangodb/arangodb-java-driver) ![](https://img.shields.io/github/last-commit/arangodb/arangodb-java-driver) ![](https://img.shields.io/github/issues/arangodb/arangodb-java-driver) ![](https://img.shields.io/github/issues-pr/arangodb/arangodb-java-driver) ![](https://img.shields.io/github/license/arangodb/arangodb-java-driver) ![](https://img.shields.io/github/forks/arangodb/arangodb-java-driver) ![](https://img.shields.io/github/contributors/arangodb/arangodb-java-driver)

- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store.

   ![](https://img.shields.io/github/stars/OpenHFT/Chronicle-Map) ![](https://img.shields.io/github/last-commit/OpenHFT/Chronicle-Map) ![](https://img.shields.io/github/issues/OpenHFT/Chronicle-Map) ![](https://img.shields.io/github/issues-pr/OpenHFT/Chronicle-Map) ![](https://img.shields.io/github/license/OpenHFT/Chronicle-Map) ![](https://img.shields.io/github/forks/OpenHFT/Chronicle-Map) ![](https://img.shields.io/github/contributors/OpenHFT/Chronicle-Map)

- [Debezium](https://debezium.io/) - Low latency data streaming platform for change data capture.
- [druid](https://druid.apache.org) - High-performance, column-oriented, distributed data store.
- [eXist](https://github.com/eXist-db/exist) - NoSQL document database and application platform. (LGPL-2.1-only)

   ![](https://img.shields.io/github/stars/eXist-db/exist) ![](https://img.shields.io/github/last-commit/eXist-db/exist) ![](https://img.shields.io/github/issues/eXist-db/exist) ![](https://img.shields.io/github/issues-pr/eXist-db/exist) ![](https://img.shields.io/github/license/eXist-db/exist) ![](https://img.shields.io/github/forks/eXist-db/exist) ![](https://img.shields.io/github/contributors/eXist-db/exist)

- [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - Brings metrics and failover strategies to the most common connection pooling solutions.

   ![](https://img.shields.io/github/stars/vladmihalcea/flexy-pool) ![](https://img.shields.io/github/last-commit/vladmihalcea/flexy-pool) ![](https://img.shields.io/github/issues/vladmihalcea/flexy-pool) ![](https://img.shields.io/github/issues-pr/vladmihalcea/flexy-pool) ![](https://img.shields.io/github/license/vladmihalcea/flexy-pool) ![](https://img.shields.io/github/forks/vladmihalcea/flexy-pool) ![](https://img.shields.io/github/contributors/vladmihalcea/flexy-pool)

- [Flyway](https://flywaydb.org) - Simple database migration tool.
- [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) - High-performance JDBC connection pool.

   ![](https://img.shields.io/github/stars/brettwooldridge/HikariCP) ![](https://img.shields.io/github/last-commit/brettwooldridge/HikariCP) ![](https://img.shields.io/github/issues/brettwooldridge/HikariCP) ![](https://img.shields.io/github/issues-pr/brettwooldridge/HikariCP) ![](https://img.shields.io/github/license/brettwooldridge/HikariCP) ![](https://img.shields.io/github/forks/brettwooldridge/HikariCP) ![](https://img.shields.io/github/contributors/brettwooldridge/HikariCP)

- [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
- [Jedis](https://github.com/xetorthio/jedis) - Small client for interaction with Redis, with methods for commands.

   ![](https://img.shields.io/github/stars/xetorthio/jedis) ![](https://img.shields.io/github/last-commit/xetorthio/jedis) ![](https://img.shields.io/github/issues/xetorthio/jedis) ![](https://img.shields.io/github/issues-pr/xetorthio/jedis) ![](https://img.shields.io/github/license/xetorthio/jedis) ![](https://img.shields.io/github/forks/xetorthio/jedis) ![](https://img.shields.io/github/contributors/xetorthio/jedis)

- [Jest](https://github.com/searchbox-io/Jest) - Client for the Elasticsearch REST API.

   ![](https://img.shields.io/github/stars/searchbox-io/Jest) ![](https://img.shields.io/github/last-commit/searchbox-io/Jest) ![](https://img.shields.io/github/issues/searchbox-io/Jest) ![](https://img.shields.io/github/issues-pr/searchbox-io/Jest) ![](https://img.shields.io/github/license/searchbox-io/Jest) ![](https://img.shields.io/github/forks/searchbox-io/Jest) ![](https://img.shields.io/github/contributors/searchbox-io/Jest)

- [jetcd](https://github.com/justinsb/jetcd) - Client library for etcd.

   ![](https://img.shields.io/github/stars/justinsb/jetcd) ![](https://img.shields.io/github/last-commit/justinsb/jetcd) ![](https://img.shields.io/github/issues/justinsb/jetcd) ![](https://img.shields.io/github/issues-pr/justinsb/jetcd) ![](https://img.shields.io/github/license/justinsb/jetcd) ![](https://img.shields.io/github/forks/justinsb/jetcd) ![](https://img.shields.io/github/contributors/justinsb/jetcd)

- [Jinq](https://github.com/my2iu/Jinq) - Typesafe database queries via symbolic execution of Java 8 Lambdas (on top of JPA or jOOQ).

   ![](https://img.shields.io/github/stars/my2iu/Jinq) ![](https://img.shields.io/github/last-commit/my2iu/Jinq) ![](https://img.shields.io/github/issues/my2iu/Jinq) ![](https://img.shields.io/github/issues-pr/my2iu/Jinq) ![](https://img.shields.io/github/license/my2iu/Jinq) ![](https://img.shields.io/github/forks/my2iu/Jinq) ![](https://img.shields.io/github/contributors/my2iu/Jinq)

- [jOOQ](https://www.jooq.org) - Generates typesafe code based on SQL schema.
- [Leaf](https://github.com/Meituan-Dianping/Leaf) - Distributed ID generate service.

   ![](https://img.shields.io/github/stars/Meituan-Dianping/Leaf) ![](https://img.shields.io/github/last-commit/Meituan-Dianping/Leaf) ![](https://img.shields.io/github/issues/Meituan-Dianping/Leaf) ![](https://img.shields.io/github/issues-pr/Meituan-Dianping/Leaf) ![](https://img.shields.io/github/license/Meituan-Dianping/Leaf) ![](https://img.shields.io/github/forks/Meituan-Dianping/Leaf) ![](https://img.shields.io/github/contributors/Meituan-Dianping/Leaf)

- [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
- [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
- [MariaDB4j](https://github.com/vorburger/MariaDB4j) - Launcher for MariaDB that requires no installation or external dependencies.

   ![](https://img.shields.io/github/stars/vorburger/MariaDB4j) ![](https://img.shields.io/github/last-commit/vorburger/MariaDB4j) ![](https://img.shields.io/github/issues/vorburger/MariaDB4j) ![](https://img.shields.io/github/issues-pr/vorburger/MariaDB4j) ![](https://img.shields.io/github/license/vorburger/MariaDB4j) ![](https://img.shields.io/github/forks/vorburger/MariaDB4j) ![](https://img.shields.io/github/contributors/vorburger/MariaDB4j)

- [Modality](https://github.com/arkanovicz/modality) - Lightweight ORM with database reverse engineering features.

   ![](https://img.shields.io/github/stars/arkanovicz/modality) ![](https://img.shields.io/github/last-commit/arkanovicz/modality) ![](https://img.shields.io/github/issues/arkanovicz/modality) ![](https://img.shields.io/github/issues-pr/arkanovicz/modality) ![](https://img.shields.io/github/license/arkanovicz/modality) ![](https://img.shields.io/github/forks/arkanovicz/modality) ![](https://img.shields.io/github/contributors/arkanovicz/modality)

- [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions) - Allows you to use MongoDB query language to query your relational database.

   ![](https://img.shields.io/github/stars/mhewedy/spring-data-jpa-mongodb-expressions) ![](https://img.shields.io/github/last-commit/mhewedy/spring-data-jpa-mongodb-expressions) ![](https://img.shields.io/github/issues/mhewedy/spring-data-jpa-mongodb-expressions) ![](https://img.shields.io/github/issues-pr/mhewedy/spring-data-jpa-mongodb-expressions) ![](https://img.shields.io/github/license/mhewedy/spring-data-jpa-mongodb-expressions) ![](https://img.shields.io/github/forks/mhewedy/spring-data-jpa-mongodb-expressions) ![](https://img.shields.io/github/contributors/mhewedy/spring-data-jpa-mongodb-expressions)

- [Trino](https://trino.io) - Distributed SQL query engine for big data.
- [QuestDB](https://github.com/questdb/questdb) - High-performance SQL database for time series. Supports InfluxDB line protocol, PostgreSQL wire protocol, and REST.

   ![](https://img.shields.io/github/stars/questdb/questdb) ![](https://img.shields.io/github/last-commit/questdb/questdb) ![](https://img.shields.io/github/issues/questdb/questdb) ![](https://img.shields.io/github/issues-pr/questdb/questdb) ![](https://img.shields.io/github/license/questdb/questdb) ![](https://img.shields.io/github/forks/questdb/questdb) ![](https://img.shields.io/github/contributors/questdb/questdb)

- [QueryStream](https://github.com/querystream/querystream) - Build JPA Criteria queries using a Stream-like API.

   ![](https://img.shields.io/github/stars/querystream/querystream) ![](https://img.shields.io/github/last-commit/querystream/querystream) ![](https://img.shields.io/github/issues/querystream/querystream) ![](https://img.shields.io/github/issues-pr/querystream/querystream) ![](https://img.shields.io/github/license/querystream/querystream) ![](https://img.shields.io/github/forks/querystream/querystream) ![](https://img.shields.io/github/contributors/querystream/querystream)

- [Querydsl](http://www.querydsl.com) - Typesafe unified queries.
- [Realm](https://github.com/realm/realm-java) - Mobile database to run directly inside phones, tablets or wearables.

   ![](https://img.shields.io/github/stars/realm/realm-java) ![](https://img.shields.io/github/last-commit/realm/realm-java) ![](https://img.shields.io/github/issues/realm/realm-java) ![](https://img.shields.io/github/issues-pr/realm/realm-java) ![](https://img.shields.io/github/license/realm/realm-java) ![](https://img.shields.io/github/forks/realm/realm-java) ![](https://img.shields.io/github/contributors/realm/realm-java)

- [Redisson](https://github.com/redisson/redisson) - Allows for distributed and scalable data structures on top of a Redis server.

   ![](https://img.shields.io/github/stars/redisson/redisson) ![](https://img.shields.io/github/last-commit/redisson/redisson) ![](https://img.shields.io/github/issues/redisson/redisson) ![](https://img.shields.io/github/issues-pr/redisson/redisson) ![](https://img.shields.io/github/license/redisson/redisson) ![](https://img.shields.io/github/forks/redisson/redisson) ![](https://img.shields.io/github/contributors/redisson/redisson)

- [requery](https://github.com/requery/requery) - Modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, or perform queries and updates from any Java-using platform.

   ![](https://img.shields.io/github/stars/requery/requery) ![](https://img.shields.io/github/last-commit/requery/requery) ![](https://img.shields.io/github/issues/requery/requery) ![](https://img.shields.io/github/issues-pr/requery/requery) ![](https://img.shields.io/github/license/requery/requery) ![](https://img.shields.io/github/forks/requery/requery) ![](https://img.shields.io/github/contributors/requery/requery)

- [Speedment](https://github.com/speedment/speedment) - Database access library that utilizes Java 8's Stream API for querying.

   ![](https://img.shields.io/github/stars/speedment/speedment) ![](https://img.shields.io/github/last-commit/speedment/speedment) ![](https://img.shields.io/github/issues/speedment/speedment) ![](https://img.shields.io/github/issues-pr/speedment/speedment) ![](https://img.shields.io/github/license/speedment/speedment) ![](https://img.shields.io/github/forks/speedment/speedment) ![](https://img.shields.io/github/contributors/speedment/speedment)

- [Vibur DBCP](https://www.vibur.org) - JDBC connection pool library with advanced performance monitoring capabilities.
- [Xodus](https://github.com/JetBrains/xodus) - Highly concurrent transactional schema-less and ACID-compliant embedded database.

   ![](https://img.shields.io/github/stars/JetBrains/xodus) ![](https://img.shields.io/github/last-commit/JetBrains/xodus) ![](https://img.shields.io/github/issues/JetBrains/xodus) ![](https://img.shields.io/github/issues-pr/JetBrains/xodus) ![](https://img.shields.io/github/license/JetBrains/xodus) ![](https://img.shields.io/github/forks/JetBrains/xodus) ![](https://img.shields.io/github/contributors/JetBrains/xodus)


### Date and Time

_Libraries related to handling date and time._

- [Almanac Converter](https://github.com/chrisengelsma/almanac-converter) - Simple conversion between different calendar systems.

   ![](https://img.shields.io/github/stars/chrisengelsma/almanac-converter) ![](https://img.shields.io/github/last-commit/chrisengelsma/almanac-converter) ![](https://img.shields.io/github/issues/chrisengelsma/almanac-converter) ![](https://img.shields.io/github/issues-pr/chrisengelsma/almanac-converter) ![](https://img.shields.io/github/license/chrisengelsma/almanac-converter) ![](https://img.shields.io/github/forks/chrisengelsma/almanac-converter) ![](https://img.shields.io/github/contributors/chrisengelsma/almanac-converter)

- [iCal4j](https://github.com/ical4j/ical4j) - Parse and build iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models.

   ![](https://img.shields.io/github/stars/ical4j/ical4j) ![](https://img.shields.io/github/last-commit/ical4j/ical4j) ![](https://img.shields.io/github/issues/ical4j/ical4j) ![](https://img.shields.io/github/issues-pr/ical4j/ical4j) ![](https://img.shields.io/github/license/ical4j/ical4j) ![](https://img.shields.io/github/forks/ical4j/ical4j) ![](https://img.shields.io/github/contributors/ical4j/ical4j)

- [Jollyday](http://jollyday.sourceforge.net) - Determines the holidays for a given year, country/name and eventually state/region.
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - Additional date-time classes that complement those in JDK 8.

   ![](https://img.shields.io/github/stars/ThreeTen/threeten-extra) ![](https://img.shields.io/github/last-commit/ThreeTen/threeten-extra) ![](https://img.shields.io/github/issues/ThreeTen/threeten-extra) ![](https://img.shields.io/github/issues-pr/ThreeTen/threeten-extra) ![](https://img.shields.io/github/license/ThreeTen/threeten-extra) ![](https://img.shields.io/github/forks/ThreeTen/threeten-extra) ![](https://img.shields.io/github/contributors/ThreeTen/threeten-extra)

- [Time4J](https://github.com/MenoData/Time4J) - Advanced date and time library. (LGPL-2.1-only)

   ![](https://img.shields.io/github/stars/MenoData/Time4J) ![](https://img.shields.io/github/last-commit/MenoData/Time4J) ![](https://img.shields.io/github/issues/MenoData/Time4J) ![](https://img.shields.io/github/issues-pr/MenoData/Time4J) ![](https://img.shields.io/github/license/MenoData/Time4J) ![](https://img.shields.io/github/forks/MenoData/Time4J) ![](https://img.shields.io/github/contributors/MenoData/Time4J)


### Dependency Injection

_Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm._

- [Apache DeltaSpike](https://deltaspike.apache.org) - CDI extension framework.
- [Dagger](https://dagger.dev/) - Compile-time injection framework without reflection.
- [Feather](https://github.com/zsoltherpai/feather) - Ultra-lightweight, JSR-330-compliant dependency injection library.

   ![](https://img.shields.io/github/stars/zsoltherpai/feather) ![](https://img.shields.io/github/last-commit/zsoltherpai/feather) ![](https://img.shields.io/github/issues/zsoltherpai/feather) ![](https://img.shields.io/github/issues-pr/zsoltherpai/feather) ![](https://img.shields.io/github/license/zsoltherpai/feather) ![](https://img.shields.io/github/forks/zsoltherpai/feather) ![](https://img.shields.io/github/contributors/zsoltherpai/feather)

- [Governator](https://github.com/Netflix/governator) - Extensions and utilities that enhance Google Guice.

   ![](https://img.shields.io/github/stars/Netflix/governator) ![](https://img.shields.io/github/last-commit/Netflix/governator) ![](https://img.shields.io/github/issues/Netflix/governator) ![](https://img.shields.io/github/issues-pr/Netflix/governator) ![](https://img.shields.io/github/license/Netflix/governator) ![](https://img.shields.io/github/forks/Netflix/governator) ![](https://img.shields.io/github/contributors/Netflix/governator)

- [Guice](https://github.com/google/guice) - Lightweight and opinionated framework that completes Dagger.

   ![](https://img.shields.io/github/stars/google/guice) ![](https://img.shields.io/github/last-commit/google/guice) ![](https://img.shields.io/github/issues/google/guice) ![](https://img.shields.io/github/issues-pr/google/guice) ![](https://img.shields.io/github/license/google/guice) ![](https://img.shields.io/github/forks/google/guice) ![](https://img.shields.io/github/contributors/google/guice)

- [HK2](https://javaee.github.io/hk2/) - Lightweight and dynamic dependency injection framework.
- [JayWire](https://github.com/vanillasource/jaywire) - Lightweight dependency injection framework. (LGPL-3.0-only)

   ![](https://img.shields.io/github/stars/vanillasource/jaywire) ![](https://img.shields.io/github/last-commit/vanillasource/jaywire) ![](https://img.shields.io/github/issues/vanillasource/jaywire) ![](https://img.shields.io/github/issues-pr/vanillasource/jaywire) ![](https://img.shields.io/github/license/vanillasource/jaywire) ![](https://img.shields.io/github/forks/vanillasource/jaywire) ![](https://img.shields.io/github/contributors/vanillasource/jaywire)


### Development

_Augmentation of the development process at a fundamental level._

- [AspectJ](https://www.eclipse.org/aspectj/) - Seamless aspect-oriented programming extension.
- [DCEVM](https://dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime. (GPL-2.0-only)
- [Faux Pas](https://github.com/zalando/faux-pas) - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions.

   ![](https://img.shields.io/github/stars/zalando/faux-pas) ![](https://img.shields.io/github/last-commit/zalando/faux-pas) ![](https://img.shields.io/github/issues/zalando/faux-pas) ![](https://img.shields.io/github/issues-pr/zalando/faux-pas) ![](https://img.shields.io/github/license/zalando/faux-pas) ![](https://img.shields.io/github/forks/zalando/faux-pas) ![](https://img.shields.io/github/contributors/zalando/faux-pas)

- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition. (GPL-2.0-only)

   ![](https://img.shields.io/github/stars/HotswapProjects/HotswapAgent) ![](https://img.shields.io/github/last-commit/HotswapProjects/HotswapAgent) ![](https://img.shields.io/github/issues/HotswapProjects/HotswapAgent) ![](https://img.shields.io/github/issues-pr/HotswapProjects/HotswapAgent) ![](https://img.shields.io/github/license/HotswapProjects/HotswapAgent) ![](https://img.shields.io/github/forks/HotswapProjects/HotswapAgent) ![](https://img.shields.io/github/contributors/HotswapProjects/HotswapAgent)

- [JavaParser](https://github.com/javaparser/javaparser) - Parse, modify and generate Java code.

   ![](https://img.shields.io/github/stars/javaparser/javaparser) ![](https://img.shields.io/github/last-commit/javaparser/javaparser) ![](https://img.shields.io/github/issues/javaparser/javaparser) ![](https://img.shields.io/github/issues-pr/javaparser/javaparser) ![](https://img.shields.io/github/license/javaparser/javaparser) ![](https://img.shields.io/github/forks/javaparser/javaparser) ![](https://img.shields.io/github/contributors/javaparser/javaparser)

- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) - Symbol solver.

   ![](https://img.shields.io/github/stars/javaparser/javasymbolsolver) ![](https://img.shields.io/github/last-commit/javaparser/javasymbolsolver) ![](https://img.shields.io/github/issues/javaparser/javasymbolsolver) ![](https://img.shields.io/github/issues-pr/javaparser/javasymbolsolver) ![](https://img.shields.io/github/license/javaparser/javasymbolsolver) ![](https://img.shields.io/github/forks/javaparser/javasymbolsolver) ![](https://img.shields.io/github/contributors/javaparser/javasymbolsolver)

- [Manifold](https://github.com/manifold-systems/manifold) - Re-energizes Java with powerful features like type-safe metaprogramming, structural typing and extension methods.

   ![](https://img.shields.io/github/stars/manifold-systems/manifold) ![](https://img.shields.io/github/last-commit/manifold-systems/manifold) ![](https://img.shields.io/github/issues/manifold-systems/manifold) ![](https://img.shields.io/github/issues-pr/manifold-systems/manifold) ![](https://img.shields.io/github/license/manifold-systems/manifold) ![](https://img.shields.io/github/forks/manifold-systems/manifold) ![](https://img.shields.io/github/contributors/manifold-systems/manifold)

- [NoException](https://noexception.machinezoo.com) - Allows checked exceptions in functional interfaces and converts exceptions to Optional return.
- [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow) - Ignores checked exceptions without bytecode manipulation. Can also be used inside Java 8 stream operations.

   ![](https://img.shields.io/github/stars/rainerhahnekamp/sneakythrow) ![](https://img.shields.io/github/last-commit/rainerhahnekamp/sneakythrow) ![](https://img.shields.io/github/issues/rainerhahnekamp/sneakythrow) ![](https://img.shields.io/github/issues-pr/rainerhahnekamp/sneakythrow) ![](https://img.shields.io/github/license/rainerhahnekamp/sneakythrow) ![](https://img.shields.io/github/forks/rainerhahnekamp/sneakythrow) ![](https://img.shields.io/github/contributors/rainerhahnekamp/sneakythrow)

- [Tail](https://kag0.github.io/tail) - Enable infinite recursion using tail call optimization.

### Distributed Applications

_Libraries and frameworks for writing distributed and fault-tolerant applications._

- [Apache Geode](https://geode.apache.org) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
- [Apache Storm](https://storm.apache.org) - Realtime computation system.
- [Apache ZooKeeper](https://zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
- [Atomix](https://atomix.io) - Fault-tolerant distributed coordination framework.
- [Axon](https://axoniq.io) - Framework for creating CQRS applications.
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker) - Circuit breaker design pattern for Dropwizard. (GPL-2.0-only)

   ![](https://img.shields.io/github/stars/mtakaki/dropwizard-circuitbreaker) ![](https://img.shields.io/github/last-commit/mtakaki/dropwizard-circuitbreaker) ![](https://img.shields.io/github/issues/mtakaki/dropwizard-circuitbreaker) ![](https://img.shields.io/github/issues-pr/mtakaki/dropwizard-circuitbreaker) ![](https://img.shields.io/github/license/mtakaki/dropwizard-circuitbreaker) ![](https://img.shields.io/github/forks/mtakaki/dropwizard-circuitbreaker) ![](https://img.shields.io/github/contributors/mtakaki/dropwizard-circuitbreaker)

- [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers.

   ![](https://img.shields.io/github/stars/jhalterman/failsafe) ![](https://img.shields.io/github/last-commit/jhalterman/failsafe) ![](https://img.shields.io/github/issues/jhalterman/failsafe) ![](https://img.shields.io/github/issues-pr/jhalterman/failsafe) ![](https://img.shields.io/github/license/jhalterman/failsafe) ![](https://img.shields.io/github/forks/jhalterman/failsafe) ![](https://img.shields.io/github/contributors/jhalterman/failsafe)

- [Hazelcast](https://github.com/hazelcast/hazelcast) - Highly scalable in-memory datagrid with a free open-source version.

   ![](https://img.shields.io/github/stars/hazelcast/hazelcast) ![](https://img.shields.io/github/last-commit/hazelcast/hazelcast) ![](https://img.shields.io/github/issues/hazelcast/hazelcast) ![](https://img.shields.io/github/issues-pr/hazelcast/hazelcast) ![](https://img.shields.io/github/license/hazelcast/hazelcast) ![](https://img.shields.io/github/forks/hazelcast/hazelcast) ![](https://img.shields.io/github/contributors/hazelcast/hazelcast)

- [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
- [Quasar](http://docs.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
- [resilience4j](https://github.com/resilience4j/resilience4j) - Functional fault tolerance library.

   ![](https://img.shields.io/github/stars/resilience4j/resilience4j) ![](https://img.shields.io/github/last-commit/resilience4j/resilience4j) ![](https://img.shields.io/github/issues/resilience4j/resilience4j) ![](https://img.shields.io/github/issues-pr/resilience4j/resilience4j) ![](https://img.shields.io/github/license/resilience4j/resilience4j) ![](https://img.shields.io/github/forks/resilience4j/resilience4j) ![](https://img.shields.io/github/contributors/resilience4j/resilience4j)

- [ScaleCube Services](https://github.com/scalecube/scalecube-services) - Embeddable Cluster-Membership library based on SWIM and gossip protocol.

   ![](https://img.shields.io/github/stars/scalecube/scalecube-services) ![](https://img.shields.io/github/last-commit/scalecube/scalecube-services) ![](https://img.shields.io/github/issues/scalecube/scalecube-services) ![](https://img.shields.io/github/issues-pr/scalecube/scalecube-services) ![](https://img.shields.io/github/license/scalecube/scalecube-services) ![](https://img.shields.io/github/forks/scalecube/scalecube-services) ![](https://img.shields.io/github/contributors/scalecube/scalecube-services)

- [Zuul](https://github.com/Netflix/zuul) - Gateway service that provides dynamic routing, monitoring, resiliency, security, and more.

   ![](https://img.shields.io/github/stars/Netflix/zuul) ![](https://img.shields.io/github/last-commit/Netflix/zuul) ![](https://img.shields.io/github/issues/Netflix/zuul) ![](https://img.shields.io/github/issues-pr/Netflix/zuul) ![](https://img.shields.io/github/license/Netflix/zuul) ![](https://img.shields.io/github/forks/Netflix/zuul) ![](https://img.shields.io/github/contributors/Netflix/zuul)


### Distributed Transactions

_Distributed transactions provide a mechanism for ensuring consistency of data updates in the presence of concurrent access and partial failures._

- [Atomikos](https://www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
- [Bitronix](https://github.com/bitronix/btm) - Simple but complete implementation of the JTA 1.1 API.

   ![](https://img.shields.io/github/stars/bitronix/btm) ![](https://img.shields.io/github/last-commit/bitronix/btm) ![](https://img.shields.io/github/issues/bitronix/btm) ![](https://img.shields.io/github/issues-pr/bitronix/btm) ![](https://img.shields.io/github/license/bitronix/btm) ![](https://img.shields.io/github/forks/bitronix/btm) ![](https://img.shields.io/github/contributors/bitronix/btm)

- [Narayana](https://narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards. (LGPL-2.1-only)
- [Seata](https://github.com/seata/seata) - Delivers high performance and easy to use distributed transaction services under a microservices architecture.

   ![](https://img.shields.io/github/stars/seata/seata) ![](https://img.shields.io/github/last-commit/seata/seata) ![](https://img.shields.io/github/issues/seata/seata) ![](https://img.shields.io/github/issues-pr/seata/seata) ![](https://img.shields.io/github/license/seata/seata) ![](https://img.shields.io/github/forks/seata/seata) ![](https://img.shields.io/github/contributors/seata/seata)


### Distribution

_Tools that handle the distribution of applications in native formats._

- [Artipie](https://github.com/artipie/artipie) - Binary artifact management toolkit which hosts them on the file system or S3.

   ![](https://img.shields.io/github/stars/artipie/artipie) ![](https://img.shields.io/github/last-commit/artipie/artipie) ![](https://img.shields.io/github/issues/artipie/artipie) ![](https://img.shields.io/github/issues-pr/artipie/artipie) ![](https://img.shields.io/github/license/artipie/artipie) ![](https://img.shields.io/github/forks/artipie/artipie) ![](https://img.shields.io/github/contributors/artipie/artipie)

- [Boxfuse ![c]](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
- [Capsule](https://github.com/puniverse/capsule) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.

   ![](https://img.shields.io/github/stars/puniverse/capsule) ![](https://img.shields.io/github/last-commit/puniverse/capsule) ![](https://img.shields.io/github/issues/puniverse/capsule) ![](https://img.shields.io/github/issues-pr/puniverse/capsule) ![](https://img.shields.io/github/license/puniverse/capsule) ![](https://img.shields.io/github/forks/puniverse/capsule) ![](https://img.shields.io/github/contributors/puniverse/capsule)

- [Central Repository](https://search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
- [Cloudsmith ![c]](https://cloudsmith.io) - Fully managed package management SaaS with support for Maven/Gradle/SBT with a free tier.
- [Getdown](https://github.com/threerings/getdown) - A system for deploying Java applications to end-user computers and keeping them up to date. Developed as an alternative to Java Web Start.

   ![](https://img.shields.io/github/stars/threerings/getdown) ![](https://img.shields.io/github/last-commit/threerings/getdown) ![](https://img.shields.io/github/issues/threerings/getdown) ![](https://img.shields.io/github/issues-pr/threerings/getdown) ![](https://img.shields.io/github/license/threerings/getdown) ![](https://img.shields.io/github/forks/threerings/getdown) ![](https://img.shields.io/github/contributors/threerings/getdown)

- [IzPack](http://izpack.org) - Setup authoring tool for cross-platform deployments.
- [JavaPackager](https://github.com/fvarrui/JavaPackager) - Maven and Gradle plugin which provides an easy way to package Java applications in native Windows, Mac OS X or GNU/Linux executables, and generate installers for them.

   ![](https://img.shields.io/github/stars/fvarrui/JavaPackager) ![](https://img.shields.io/github/last-commit/fvarrui/JavaPackager) ![](https://img.shields.io/github/issues/fvarrui/JavaPackager) ![](https://img.shields.io/github/issues-pr/fvarrui/JavaPackager) ![](https://img.shields.io/github/license/fvarrui/JavaPackager) ![](https://img.shields.io/github/forks/fvarrui/JavaPackager) ![](https://img.shields.io/github/contributors/fvarrui/JavaPackager)

- [jlink.online](https://github.com/cilki/jlink.online) - Builds optimized runtimes over HTTP.

   ![](https://img.shields.io/github/stars/cilki/jlink.online) ![](https://img.shields.io/github/last-commit/cilki/jlink.online) ![](https://img.shields.io/github/issues/cilki/jlink.online) ![](https://img.shields.io/github/issues-pr/cilki/jlink.online) ![](https://img.shields.io/github/license/cilki/jlink.online) ![](https://img.shields.io/github/forks/cilki/jlink.online) ![](https://img.shields.io/github/contributors/cilki/jlink.online)

- [Nexus ![c]](https://www.sonatype.com) - Binary management with proxy and caching capabilities.
- [packr](https://github.com/libgdx/packr) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and macOS.

   ![](https://img.shields.io/github/stars/libgdx/packr) ![](https://img.shields.io/github/last-commit/libgdx/packr) ![](https://img.shields.io/github/issues/libgdx/packr) ![](https://img.shields.io/github/issues-pr/libgdx/packr) ![](https://img.shields.io/github/license/libgdx/packr) ![](https://img.shields.io/github/forks/libgdx/packr) ![](https://img.shields.io/github/contributors/libgdx/packr)

- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) - Maven plugin for making self-executing JARs.

   ![](https://img.shields.io/github/stars/brianm/really-executable-jars-maven-plugin) ![](https://img.shields.io/github/last-commit/brianm/really-executable-jars-maven-plugin) ![](https://img.shields.io/github/issues/brianm/really-executable-jars-maven-plugin) ![](https://img.shields.io/github/issues-pr/brianm/really-executable-jars-maven-plugin) ![](https://img.shields.io/github/license/brianm/really-executable-jars-maven-plugin) ![](https://img.shields.io/github/forks/brianm/really-executable-jars-maven-plugin) ![](https://img.shields.io/github/contributors/brianm/really-executable-jars-maven-plugin)


### Document Processing

_Libraries that assist with processing office document formats._

- [Apache POI](https://poi.apache.org) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
- [documents4j](https://documents4j.com/#/) - API for document format conversion using third-party converters such as MS Word.
- [docx4j](https://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.
- [fastexcel](https://github.com/dhatim/fastexcel) - High performance library to read and write large Excel (XLSX) worksheets.

   ![](https://img.shields.io/github/stars/dhatim/fastexcel) ![](https://img.shields.io/github/last-commit/dhatim/fastexcel) ![](https://img.shields.io/github/issues/dhatim/fastexcel) ![](https://img.shields.io/github/issues-pr/dhatim/fastexcel) ![](https://img.shields.io/github/license/dhatim/fastexcel) ![](https://img.shields.io/github/forks/dhatim/fastexcel) ![](https://img.shields.io/github/contributors/dhatim/fastexcel)

- [zerocell](https://github.com/creditdatamw/zerocell) - Annotation-based API for reading data from Excel sheets into POJOs with focus on reduced overhead.

   ![](https://img.shields.io/github/stars/creditdatamw/zerocell) ![](https://img.shields.io/github/last-commit/creditdatamw/zerocell) ![](https://img.shields.io/github/issues/creditdatamw/zerocell) ![](https://img.shields.io/github/issues-pr/creditdatamw/zerocell) ![](https://img.shields.io/github/license/creditdatamw/zerocell) ![](https://img.shields.io/github/forks/creditdatamw/zerocell) ![](https://img.shields.io/github/contributors/creditdatamw/zerocell)


### Financial

_Libraries related to the financial domain._

- [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot) - Trading bot framework.

   ![](https://img.shields.io/github/stars/cassandre-tech/cassandre-trading-bot) ![](https://img.shields.io/github/last-commit/cassandre-tech/cassandre-trading-bot) ![](https://img.shields.io/github/issues/cassandre-tech/cassandre-trading-bot) ![](https://img.shields.io/github/issues-pr/cassandre-tech/cassandre-trading-bot) ![](https://img.shields.io/github/license/cassandre-tech/cassandre-trading-bot) ![](https://img.shields.io/github/forks/cassandre-tech/cassandre-trading-bot) ![](https://img.shields.io/github/contributors/cassandre-tech/cassandre-trading-bot)

- [Parity](https://github.com/paritytrading/parity) - Platform for trading venues.

   ![](https://img.shields.io/github/stars/paritytrading/parity) ![](https://img.shields.io/github/last-commit/paritytrading/parity) ![](https://img.shields.io/github/issues/paritytrading/parity) ![](https://img.shields.io/github/issues-pr/paritytrading/parity) ![](https://img.shields.io/github/license/paritytrading/parity) ![](https://img.shields.io/github/forks/paritytrading/parity) ![](https://img.shields.io/github/contributors/paritytrading/parity)

- [Philadelphia](https://github.com/paritytrading/philadelphia) - Low-latency financial information exchange.

   ![](https://img.shields.io/github/stars/paritytrading/philadelphia) ![](https://img.shields.io/github/last-commit/paritytrading/philadelphia) ![](https://img.shields.io/github/issues/paritytrading/philadelphia) ![](https://img.shields.io/github/issues-pr/paritytrading/philadelphia) ![](https://img.shields.io/github/license/paritytrading/philadelphia) ![](https://img.shields.io/github/forks/paritytrading/philadelphia) ![](https://img.shields.io/github/contributors/paritytrading/philadelphia)

- [Square](https://github.com/square/connect-java-sdk) - Integration with the Square API.

   ![](https://img.shields.io/github/stars/square/connect-java-sdk) ![](https://img.shields.io/github/last-commit/square/connect-java-sdk) ![](https://img.shields.io/github/issues/square/connect-java-sdk) ![](https://img.shields.io/github/issues-pr/square/connect-java-sdk) ![](https://img.shields.io/github/license/square/connect-java-sdk) ![](https://img.shields.io/github/forks/square/connect-java-sdk) ![](https://img.shields.io/github/contributors/square/connect-java-sdk)

- [Stripe](https://github.com/stripe/stripe-java) - Integration with the Stripe API.

   ![](https://img.shields.io/github/stars/stripe/stripe-java) ![](https://img.shields.io/github/last-commit/stripe/stripe-java) ![](https://img.shields.io/github/issues/stripe/stripe-java) ![](https://img.shields.io/github/issues-pr/stripe/stripe-java) ![](https://img.shields.io/github/license/stripe/stripe-java) ![](https://img.shields.io/github/forks/stripe/stripe-java) ![](https://img.shields.io/github/contributors/stripe/stripe-java)

- [ta4j](https://github.com/ta4j/ta4j) - Library for technical analysis.

   ![](https://img.shields.io/github/stars/ta4j/ta4j) ![](https://img.shields.io/github/last-commit/ta4j/ta4j) ![](https://img.shields.io/github/issues/ta4j/ta4j) ![](https://img.shields.io/github/issues-pr/ta4j/ta4j) ![](https://img.shields.io/github/license/ta4j/ta4j) ![](https://img.shields.io/github/forks/ta4j/ta4j) ![](https://img.shields.io/github/contributors/ta4j/ta4j)


### Formal Verification

_Formal-methods tools: proof assistants, model checking, symbolic execution, etc._

- [CATG](https://github.com/ksen007/janala2) - Concolic unit testing engine. Automatically generates unit tests using formal methods.

   ![](https://img.shields.io/github/stars/ksen007/janala2) ![](https://img.shields.io/github/last-commit/ksen007/janala2) ![](https://img.shields.io/github/issues/ksen007/janala2) ![](https://img.shields.io/github/issues-pr/ksen007/janala2) ![](https://img.shields.io/github/license/ksen007/janala2) ![](https://img.shields.io/github/forks/ksen007/janala2) ![](https://img.shields.io/github/contributors/ksen007/janala2)

- [Checker Framework](https://checkerframework.org) - Pluggable type systems. Includes nullness types, physical units, immutability types and more. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Daikon](https://plse.cs.washington.edu/daikon/) - Detects likely program invariants and generates JML specs based on those invariants.
- [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core) - JVM formal verification tool containing a model checker and more. Created by NASA.

   ![](https://img.shields.io/github/stars/javapathfinder/jpf-core) ![](https://img.shields.io/github/last-commit/javapathfinder/jpf-core) ![](https://img.shields.io/github/issues/javapathfinder/jpf-core) ![](https://img.shields.io/github/issues-pr/javapathfinder/jpf-core) ![](https://img.shields.io/github/license/javapathfinder/jpf-core) ![](https://img.shields.io/github/forks/javapathfinder/jpf-core) ![](https://img.shields.io/github/contributors/javapathfinder/jpf-core)

- [JMLOK 2.0](https://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected. (GPL-3.0-only)
- [KeY](https://www.key-project.org) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification. (GPL-2.0-or-later)
- [OpenJML](http://www.openjml.org) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers. (GPL-2.0-only)

### Functional Programming

_Libraries that facilitate functional programming._

- [Cyclops](https://github.com/aol/cyclops) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.

   ![](https://img.shields.io/github/stars/aol/cyclops) ![](https://img.shields.io/github/last-commit/aol/cyclops) ![](https://img.shields.io/github/issues/aol/cyclops) ![](https://img.shields.io/github/issues-pr/aol/cyclops) ![](https://img.shields.io/github/license/aol/cyclops) ![](https://img.shields.io/github/forks/aol/cyclops) ![](https://img.shields.io/github/contributors/aol/cyclops)

- [derive4j](https://github.com/derive4j/derive4j) - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching and morphisms. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/derive4j/derive4j) ![](https://img.shields.io/github/last-commit/derive4j/derive4j) ![](https://img.shields.io/github/issues/derive4j/derive4j) ![](https://img.shields.io/github/issues-pr/derive4j/derive4j) ![](https://img.shields.io/github/license/derive4j/derive4j) ![](https://img.shields.io/github/forks/derive4j/derive4j) ![](https://img.shields.io/github/contributors/derive4j/derive4j)

- [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
- [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
- [jOOλ](https://github.com/jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.

   ![](https://img.shields.io/github/stars/jOOQ/jOOL) ![](https://img.shields.io/github/last-commit/jOOQ/jOOL) ![](https://img.shields.io/github/issues/jOOQ/jOOL) ![](https://img.shields.io/github/issues-pr/jOOQ/jOOL) ![](https://img.shields.io/github/license/jOOQ/jOOL) ![](https://img.shields.io/github/forks/jOOQ/jOOL) ![](https://img.shields.io/github/contributors/jOOQ/jOOL)

- [protonpack](https://github.com/poetix/protonpack) - Collection of stream utilities.

   ![](https://img.shields.io/github/stars/poetix/protonpack) ![](https://img.shields.io/github/last-commit/poetix/protonpack) ![](https://img.shields.io/github/issues/poetix/protonpack) ![](https://img.shields.io/github/issues-pr/poetix/protonpack) ![](https://img.shields.io/github/license/poetix/protonpack) ![](https://img.shields.io/github/forks/poetix/protonpack) ![](https://img.shields.io/github/contributors/poetix/protonpack)

- [StreamEx](https://github.com/amaembo/streamex) - Enhances Java 8 Streams.

   ![](https://img.shields.io/github/stars/amaembo/streamex) ![](https://img.shields.io/github/last-commit/amaembo/streamex) ![](https://img.shields.io/github/issues/amaembo/streamex) ![](https://img.shields.io/github/issues-pr/amaembo/streamex) ![](https://img.shields.io/github/license/amaembo/streamex) ![](https://img.shields.io/github/forks/amaembo/streamex) ![](https://img.shields.io/github/contributors/amaembo/streamex)

- [Vavr](https://www.vavr.io) - Functional component library that provides persistent data types and functional control structures.

### Game Development

_Frameworks that support the development of games._

- [FXGL](https://almasb.github.io/FXGL/) - JavaFX Game Development Framework.
- [JBox2D](http://www.jbox2d.org/) - Port of the renowned C++ 2D physics engine.
- [jMonkeyEngine](https://jmonkeyengine.org) - Game engine for modern 3D development.
- [libGDX](https://libgdx.com) - All-round cross-platform, high-level framework.
- [Litiengine](https://litiengine.com/) - AWT-based, lightweight 2D game engine.
- [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.
- [Mini2Dx](https://mini2dx.org) - Beginner-friendly, master-ready framework for rapidly prototyping and building 2D games.

### Geospatial

_Libraries for working with geospatial data and algorithms._

- [Apache SIS](https://sis.apache.org) - Library for developing geospatial applications.
- [Geo](https://github.com/davidmoten/geo) - GeoHash utilities in Java.

   ![](https://img.shields.io/github/stars/davidmoten/geo) ![](https://img.shields.io/github/last-commit/davidmoten/geo) ![](https://img.shields.io/github/issues/davidmoten/geo) ![](https://img.shields.io/github/issues-pr/davidmoten/geo) ![](https://img.shields.io/github/license/davidmoten/geo) ![](https://img.shields.io/github/forks/davidmoten/geo) ![](https://img.shields.io/github/contributors/davidmoten/geo)

- [GeoTools](https://geotools.org) - Library that provides tools for geospatial data. (LGPL-2.1-only)
- [GraphHopper](https://github.com/graphhopper/graphhopper) - Road-routing engine. Used as a Java library or standalone web service.

   ![](https://img.shields.io/github/stars/graphhopper/graphhopper) ![](https://img.shields.io/github/last-commit/graphhopper/graphhopper) ![](https://img.shields.io/github/issues/graphhopper/graphhopper) ![](https://img.shields.io/github/issues-pr/graphhopper/graphhopper) ![](https://img.shields.io/github/license/graphhopper/graphhopper) ![](https://img.shields.io/github/forks/graphhopper/graphhopper) ![](https://img.shields.io/github/contributors/graphhopper/graphhopper)

- [H2GIS](http://www.h2gis.org) - Spatial extension of the H2 database. (LGPL-3.0-only)
- [Jgeohash](https://astrapi69.github.io/jgeohash/) - Library for using the GeoHash algorithm.
- [Mapsforge](https://github.com/mapsforge/mapsforge) - Map rendering based on OpenStreetMap data. (LGPL-3.0-only)

   ![](https://img.shields.io/github/stars/mapsforge/mapsforge) ![](https://img.shields.io/github/last-commit/mapsforge/mapsforge) ![](https://img.shields.io/github/issues/mapsforge/mapsforge) ![](https://img.shields.io/github/issues-pr/mapsforge/mapsforge) ![](https://img.shields.io/github/license/mapsforge/mapsforge) ![](https://img.shields.io/github/forks/mapsforge/mapsforge) ![](https://img.shields.io/github/contributors/mapsforge/mapsforge)

- [Spatial4j](https://github.com/locationtech/spatial4j) - General-purpose spatial/geospatial library.

   ![](https://img.shields.io/github/stars/locationtech/spatial4j) ![](https://img.shields.io/github/last-commit/locationtech/spatial4j) ![](https://img.shields.io/github/issues/locationtech/spatial4j) ![](https://img.shields.io/github/issues-pr/locationtech/spatial4j) ![](https://img.shields.io/github/license/locationtech/spatial4j) ![](https://img.shields.io/github/forks/locationtech/spatial4j) ![](https://img.shields.io/github/contributors/locationtech/spatial4j)


### GUI

_Libraries to create modern graphical user interfaces._

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - Successor of Swing.
- [Scene Builder](https://gluonhq.com/products/scene-builder/) - Visual layout tool for JavaFX applications.
- [SWT](https://www.eclipse.org/swt/) - Graphical widget toolkit.

### High Performance

_Everything about high-performance computation, from collections to specific libraries._

- [Agrona](https://github.com/real-logic/Agrona) - Data structures and utility methods that are common in high-performance applications.

   ![](https://img.shields.io/github/stars/real-logic/Agrona) ![](https://img.shields.io/github/last-commit/real-logic/Agrona) ![](https://img.shields.io/github/issues/real-logic/Agrona) ![](https://img.shields.io/github/issues-pr/real-logic/Agrona) ![](https://img.shields.io/github/license/real-logic/Agrona) ![](https://img.shields.io/github/forks/real-logic/Agrona) ![](https://img.shields.io/github/contributors/real-logic/Agrona)

- [Disruptor](https://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - Collections framework inspired by Smalltalk.

   ![](https://img.shields.io/github/stars/eclipse/eclipse-collections) ![](https://img.shields.io/github/last-commit/eclipse/eclipse-collections) ![](https://img.shields.io/github/issues/eclipse/eclipse-collections) ![](https://img.shields.io/github/issues-pr/eclipse/eclipse-collections) ![](https://img.shields.io/github/license/eclipse/eclipse-collections) ![](https://img.shields.io/github/forks/eclipse/eclipse-collections) ![](https://img.shields.io/github/contributors/eclipse/eclipse-collections)

- [fastutil](http://fastutil.di.unimi.it) - Fast and compact type-specific collections.
- [HPPC](https://labs.carrotsearch.com/hppc.html) - Primitive collections.
- [JCTools](https://github.com/JCTools/JCTools) - Concurrency tools currently missing from the JDK.

   ![](https://img.shields.io/github/stars/JCTools/JCTools) ![](https://img.shields.io/github/last-commit/JCTools/JCTools) ![](https://img.shields.io/github/issues/JCTools/JCTools) ![](https://img.shields.io/github/issues-pr/JCTools/JCTools) ![](https://img.shields.io/github/license/JCTools/JCTools) ![](https://img.shields.io/github/forks/JCTools/JCTools) ![](https://img.shields.io/github/contributors/JCTools/JCTools)

- [Koloboke](https://github.com/leventov/Koloboke) - Carefully designed extension of the Java Collections Framework with primitive specializations and more.

   ![](https://img.shields.io/github/stars/leventov/Koloboke) ![](https://img.shields.io/github/last-commit/leventov/Koloboke) ![](https://img.shields.io/github/issues/leventov/Koloboke) ![](https://img.shields.io/github/issues-pr/leventov/Koloboke) ![](https://img.shields.io/github/license/leventov/Koloboke) ![](https://img.shields.io/github/forks/leventov/Koloboke) ![](https://img.shields.io/github/contributors/leventov/Koloboke)


### HTTP Clients

_Libraries that assist with creating HTTP requests and/or binding responses._

- [Apache HttpComponents](https://hc.apache.org/) - A toolset of low level Java components focused on HTTP and associated protocols.
- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - Asynchronous HTTP and WebSocket client library.

   ![](https://img.shields.io/github/stars/AsyncHttpClient/async-http-client) ![](https://img.shields.io/github/last-commit/AsyncHttpClient/async-http-client) ![](https://img.shields.io/github/issues/AsyncHttpClient/async-http-client) ![](https://img.shields.io/github/issues-pr/AsyncHttpClient/async-http-client) ![](https://img.shields.io/github/license/AsyncHttpClient/async-http-client) ![](https://img.shields.io/github/forks/AsyncHttpClient/async-http-client) ![](https://img.shields.io/github/contributors/AsyncHttpClient/async-http-client)

- [Feign](https://github.com/OpenFeign/feign) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.

   ![](https://img.shields.io/github/stars/OpenFeign/feign) ![](https://img.shields.io/github/last-commit/OpenFeign/feign) ![](https://img.shields.io/github/issues/OpenFeign/feign) ![](https://img.shields.io/github/issues-pr/OpenFeign/feign) ![](https://img.shields.io/github/license/OpenFeign/feign) ![](https://img.shields.io/github/forks/OpenFeign/feign) ![](https://img.shields.io/github/contributors/OpenFeign/feign)

- [Google HTTP Client](https://github.com/googleapis/google-http-java-client) - Pluggable HTTP transport abstraction with support for java.net.HttpURLConnection, Apache HTTP Client, Android, Google App Engine, XML, Gson, Jackson and Protobuf.

   ![](https://img.shields.io/github/stars/googleapis/google-http-java-client) ![](https://img.shields.io/github/last-commit/googleapis/google-http-java-client) ![](https://img.shields.io/github/issues/googleapis/google-http-java-client) ![](https://img.shields.io/github/issues-pr/googleapis/google-http-java-client) ![](https://img.shields.io/github/license/googleapis/google-http-java-client) ![](https://img.shields.io/github/forks/googleapis/google-http-java-client) ![](https://img.shields.io/github/contributors/googleapis/google-http-java-client)

- [methanol](https://github.com/mizosoft/methanol) - HTTP client extensions library.

   ![](https://img.shields.io/github/stars/mizosoft/methanol) ![](https://img.shields.io/github/last-commit/mizosoft/methanol) ![](https://img.shields.io/github/issues/mizosoft/methanol) ![](https://img.shields.io/github/issues-pr/mizosoft/methanol) ![](https://img.shields.io/github/license/mizosoft/methanol) ![](https://img.shields.io/github/forks/mizosoft/methanol) ![](https://img.shields.io/github/contributors/mizosoft/methanol)

- [restQL-java](https://github.com/b2wdigital/restQL-java) - Microservice query language that fetches information from multiple services.

   ![](https://img.shields.io/github/stars/b2wdigital/restQL-java) ![](https://img.shields.io/github/last-commit/b2wdigital/restQL-java) ![](https://img.shields.io/github/issues/b2wdigital/restQL-java) ![](https://img.shields.io/github/issues-pr/b2wdigital/restQL-java) ![](https://img.shields.io/github/license/b2wdigital/restQL-java) ![](https://img.shields.io/github/forks/b2wdigital/restQL-java) ![](https://img.shields.io/github/contributors/b2wdigital/restQL-java)

- [Retrofit](https://square.github.io/retrofit/) - Typesafe REST client.
- [Ribbon](https://github.com/Netflix/ribbon) - Client-side IPC library that is battle-tested in cloud.

   ![](https://img.shields.io/github/stars/Netflix/ribbon) ![](https://img.shields.io/github/last-commit/Netflix/ribbon) ![](https://img.shields.io/github/issues/Netflix/ribbon) ![](https://img.shields.io/github/issues-pr/Netflix/ribbon) ![](https://img.shields.io/github/license/Netflix/ribbon) ![](https://img.shields.io/github/forks/Netflix/ribbon) ![](https://img.shields.io/github/contributors/Netflix/ribbon)

- [Riptide](https://github.com/zalando/riptide) - Client-side response routing for Spring's RestTemplate.

   ![](https://img.shields.io/github/stars/zalando/riptide) ![](https://img.shields.io/github/last-commit/zalando/riptide) ![](https://img.shields.io/github/issues/zalando/riptide) ![](https://img.shields.io/github/issues-pr/zalando/riptide) ![](https://img.shields.io/github/license/zalando/riptide) ![](https://img.shields.io/github/forks/zalando/riptide) ![](https://img.shields.io/github/contributors/zalando/riptide)

- [unirest-java](https://github.com/Kong/unirest-java) - Simplified, lightweight HTTP client library.

   ![](https://img.shields.io/github/stars/Kong/unirest-java) ![](https://img.shields.io/github/last-commit/Kong/unirest-java) ![](https://img.shields.io/github/issues/Kong/unirest-java) ![](https://img.shields.io/github/issues-pr/Kong/unirest-java) ![](https://img.shields.io/github/license/Kong/unirest-java) ![](https://img.shields.io/github/forks/Kong/unirest-java) ![](https://img.shields.io/github/contributors/Kong/unirest-java)


### Hypermedia Types

_Libraries that handle serialization to hypermedia types._

- [hate](https://github.com/blackdoor/hate) - Builds hypermedia-friendly objects according to HAL specification.

   ![](https://img.shields.io/github/stars/blackdoor/hate) ![](https://img.shields.io/github/last-commit/blackdoor/hate) ![](https://img.shields.io/github/issues/blackdoor/hate) ![](https://img.shields.io/github/issues-pr/blackdoor/hate) ![](https://img.shields.io/github/license/blackdoor/hate) ![](https://img.shields.io/github/forks/blackdoor/hate) ![](https://img.shields.io/github/contributors/blackdoor/hate)

- [JSON-LD](https://github.com/jsonld-java/jsonld-java) - JSON-LD implementation.

   ![](https://img.shields.io/github/stars/jsonld-java/jsonld-java) ![](https://img.shields.io/github/last-commit/jsonld-java/jsonld-java) ![](https://img.shields.io/github/issues/jsonld-java/jsonld-java) ![](https://img.shields.io/github/issues-pr/jsonld-java/jsonld-java) ![](https://img.shields.io/github/license/jsonld-java/jsonld-java) ![](https://img.shields.io/github/forks/jsonld-java/jsonld-java) ![](https://img.shields.io/github/contributors/jsonld-java/jsonld-java)

- [Siren4J](https://github.com/eserating-chwy/siren4j) - Library for the Siren specification.

   ![](https://img.shields.io/github/stars/eserating-chwy/siren4j) ![](https://img.shields.io/github/last-commit/eserating-chwy/siren4j) ![](https://img.shields.io/github/issues/eserating-chwy/siren4j) ![](https://img.shields.io/github/issues-pr/eserating-chwy/siren4j) ![](https://img.shields.io/github/license/eserating-chwy/siren4j) ![](https://img.shields.io/github/forks/eserating-chwy/siren4j) ![](https://img.shields.io/github/contributors/eserating-chwy/siren4j)


### IDE

_Integrated development environments that try to simplify several aspects of development._

- [Eclipse](https://www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea/) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- [jGRASP](https://www.jgrasp.org) - Created to provide software visualizations that work in conjunction with the debugger such as Control Structure Diagrams, UML class diagrams and Object Viewer.
- [NetBeans](https://netbeans.apache.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
- [Recaf](https://www.coley.software/Recaf/) - Bytecode editor.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.

### Imagery

_Libraries that assist with the creation, evaluation or manipulation of graphical images._

- [Imgscalr](https://github.com/rkalla/imgscalr) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D.

   ![](https://img.shields.io/github/stars/rkalla/imgscalr) ![](https://img.shields.io/github/last-commit/rkalla/imgscalr) ![](https://img.shields.io/github/issues/rkalla/imgscalr) ![](https://img.shields.io/github/issues-pr/rkalla/imgscalr) ![](https://img.shields.io/github/license/rkalla/imgscalr) ![](https://img.shields.io/github/forks/rkalla/imgscalr) ![](https://img.shields.io/github/contributors/rkalla/imgscalr)

- [Tess4J](https://github.com/nguyenq/tess4j) - JNA wrapper for Tesseract OCR API.

   ![](https://img.shields.io/github/stars/nguyenq/tess4j) ![](https://img.shields.io/github/last-commit/nguyenq/tess4j) ![](https://img.shields.io/github/issues/nguyenq/tess4j) ![](https://img.shields.io/github/issues-pr/nguyenq/tess4j) ![](https://img.shields.io/github/license/nguyenq/tess4j) ![](https://img.shields.io/github/forks/nguyenq/tess4j) ![](https://img.shields.io/github/contributors/nguyenq/tess4j)

- [Thumbnailator](https://github.com/coobird/thumbnailator) - High-quality thumbnail generation library.

   ![](https://img.shields.io/github/stars/coobird/thumbnailator) ![](https://img.shields.io/github/last-commit/coobird/thumbnailator) ![](https://img.shields.io/github/issues/coobird/thumbnailator) ![](https://img.shields.io/github/issues-pr/coobird/thumbnailator) ![](https://img.shields.io/github/license/coobird/thumbnailator) ![](https://img.shields.io/github/forks/coobird/thumbnailator) ![](https://img.shields.io/github/contributors/coobird/thumbnailator)

- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - Collection of plugins that extend the number of supported image file formats.

   ![](https://img.shields.io/github/stars/haraldk/TwelveMonkeys) ![](https://img.shields.io/github/last-commit/haraldk/TwelveMonkeys) ![](https://img.shields.io/github/issues/haraldk/TwelveMonkeys) ![](https://img.shields.io/github/issues-pr/haraldk/TwelveMonkeys) ![](https://img.shields.io/github/license/haraldk/TwelveMonkeys) ![](https://img.shields.io/github/forks/haraldk/TwelveMonkeys) ![](https://img.shields.io/github/contributors/haraldk/TwelveMonkeys)

- [ZXing](https://github.com/zxing/zxing) - Multi-format 1D/2D barcode image processing library.

   ![](https://img.shields.io/github/stars/zxing/zxing) ![](https://img.shields.io/github/last-commit/zxing/zxing) ![](https://img.shields.io/github/issues/zxing/zxing) ![](https://img.shields.io/github/issues-pr/zxing/zxing) ![](https://img.shields.io/github/license/zxing/zxing) ![](https://img.shields.io/github/forks/zxing/zxing) ![](https://img.shields.io/github/contributors/zxing/zxing)

- [image-comparison](https://github.com/romankh3/image-comparison) - Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison. Can be used for automation qa tests.

   ![](https://img.shields.io/github/stars/romankh3/image-comparison) ![](https://img.shields.io/github/last-commit/romankh3/image-comparison) ![](https://img.shields.io/github/issues/romankh3/image-comparison) ![](https://img.shields.io/github/issues-pr/romankh3/image-comparison) ![](https://img.shields.io/github/license/romankh3/image-comparison) ![](https://img.shields.io/github/forks/romankh3/image-comparison) ![](https://img.shields.io/github/contributors/romankh3/image-comparison)


### Introspection

_Libraries that help make the Java introspection and reflection API easier and faster to use._

- [ClassGraph](https://github.com/classgraph/classgraph) - ClassGraph (formerly FastClasspathScanner) is an uber-fast, ultra-lightweight, parallelized classpath scanner and module scanner for Java, Scala, Kotlin and other JVM languages.

   ![](https://img.shields.io/github/stars/classgraph/classgraph) ![](https://img.shields.io/github/last-commit/classgraph/classgraph) ![](https://img.shields.io/github/issues/classgraph/classgraph) ![](https://img.shields.io/github/issues-pr/classgraph/classgraph) ![](https://img.shields.io/github/license/classgraph/classgraph) ![](https://img.shields.io/github/forks/classgraph/classgraph) ![](https://img.shields.io/github/contributors/classgraph/classgraph)

- [jOOR](https://github.com/jOOQ/jOOR) - jOOR stands for jOOR Object Oriented Reflection. It is a simple wrapper for the java.lang.reflect package.

   ![](https://img.shields.io/github/stars/jOOQ/jOOR) ![](https://img.shields.io/github/last-commit/jOOQ/jOOR) ![](https://img.shields.io/github/issues/jOOQ/jOOR) ![](https://img.shields.io/github/issues-pr/jOOQ/jOOR) ![](https://img.shields.io/github/license/jOOQ/jOOR) ![](https://img.shields.io/github/forks/jOOQ/jOOR) ![](https://img.shields.io/github/contributors/jOOQ/jOOR)

- [Mirror](http://projetos.vidageek.net/mirror/mirror/) - Mirror was created to bring light to a simple problem, usually named ReflectionUtil, which is on almost all projects that rely on reflection to do advanced tasks.
- [Objenesis](http://objenesis.org) - Allows dynamic instantiation without default constructor, e.g. constructors which have required arguments, side effects or throw exceptions.
- [ReflectASM](https://github.com/EsotericSoftware/reflectasm) - ReflectASM is a very small Java library that provides high performance reflection by using code generation.

   ![](https://img.shields.io/github/stars/EsotericSoftware/reflectasm) ![](https://img.shields.io/github/last-commit/EsotericSoftware/reflectasm) ![](https://img.shields.io/github/issues/EsotericSoftware/reflectasm) ![](https://img.shields.io/github/issues-pr/EsotericSoftware/reflectasm) ![](https://img.shields.io/github/license/EsotericSoftware/reflectasm) ![](https://img.shields.io/github/forks/EsotericSoftware/reflectasm) ![](https://img.shields.io/github/contributors/EsotericSoftware/reflectasm)

- [Reflections](https://github.com/ronmamo/reflections) - Reflections scans your classpath, indexes the metadata, allows you to query it on runtime and may save and collect that information for many modules within your project.

   ![](https://img.shields.io/github/stars/ronmamo/reflections) ![](https://img.shields.io/github/last-commit/ronmamo/reflections) ![](https://img.shields.io/github/issues/ronmamo/reflections) ![](https://img.shields.io/github/issues-pr/ronmamo/reflections) ![](https://img.shields.io/github/license/ronmamo/reflections) ![](https://img.shields.io/github/forks/ronmamo/reflections) ![](https://img.shields.io/github/contributors/ronmamo/reflections)


### Job Scheduling

_Libraries for scheduling background jobs._

- [JobRunr](https://github.com/jobrunr/jobrunr) - Job scheduling library which utilizes lambdas for fire-and-forget, delayed and recurring jobs. Guarantees execution by single scheduler instance using optimistic locking. Has features for persistence, minimal dependencies and is embeddable.

   ![](https://img.shields.io/github/stars/jobrunr/jobrunr) ![](https://img.shields.io/github/last-commit/jobrunr/jobrunr) ![](https://img.shields.io/github/issues/jobrunr/jobrunr) ![](https://img.shields.io/github/issues-pr/jobrunr/jobrunr) ![](https://img.shields.io/github/license/jobrunr/jobrunr) ![](https://img.shields.io/github/forks/jobrunr/jobrunr) ![](https://img.shields.io/github/contributors/jobrunr/jobrunr)

- [Quartz](https://github.com/quartz-scheduler/quartz) - Feature-rich, open source job scheduling library that can be integrated within virtually any Java application.

   ![](https://img.shields.io/github/stars/quartz-scheduler/quartz) ![](https://img.shields.io/github/last-commit/quartz-scheduler/quartz) ![](https://img.shields.io/github/issues/quartz-scheduler/quartz) ![](https://img.shields.io/github/issues-pr/quartz-scheduler/quartz) ![](https://img.shields.io/github/license/quartz-scheduler/quartz) ![](https://img.shields.io/github/forks/quartz-scheduler/quartz) ![](https://img.shields.io/github/contributors/quartz-scheduler/quartz)

- [Sundial](https://github.com/knowm/Sundial) - Lightweight framework to simply define jobs, define triggers and start the scheduler.

   ![](https://img.shields.io/github/stars/knowm/Sundial) ![](https://img.shields.io/github/last-commit/knowm/Sundial) ![](https://img.shields.io/github/issues/knowm/Sundial) ![](https://img.shields.io/github/issues-pr/knowm/Sundial) ![](https://img.shields.io/github/license/knowm/Sundial) ![](https://img.shields.io/github/forks/knowm/Sundial) ![](https://img.shields.io/github/contributors/knowm/Sundial)

- [Wisp](https://github.com/Coreoz/Wisp) - Simple library with minimal footprint and straightforward API.

   ![](https://img.shields.io/github/stars/Coreoz/Wisp) ![](https://img.shields.io/github/last-commit/Coreoz/Wisp) ![](https://img.shields.io/github/issues/Coreoz/Wisp) ![](https://img.shields.io/github/issues-pr/Coreoz/Wisp) ![](https://img.shields.io/github/license/Coreoz/Wisp) ![](https://img.shields.io/github/forks/Coreoz/Wisp) ![](https://img.shields.io/github/contributors/Coreoz/Wisp)

- [db-scheduler](https://github.com/kagkarlsson/db-scheduler) - Persistent and cluster-friendly scheduler.

   ![](https://img.shields.io/github/stars/kagkarlsson/db-scheduler) ![](https://img.shields.io/github/last-commit/kagkarlsson/db-scheduler) ![](https://img.shields.io/github/issues/kagkarlsson/db-scheduler) ![](https://img.shields.io/github/issues-pr/kagkarlsson/db-scheduler) ![](https://img.shields.io/github/license/kagkarlsson/db-scheduler) ![](https://img.shields.io/github/forks/kagkarlsson/db-scheduler) ![](https://img.shields.io/github/contributors/kagkarlsson/db-scheduler)

- [easy-batch](https://github.com/j-easy/easy-batch) - Set up batch jobs with simple processing pipelines. Records are read in sequence from a data source, processed in pipeline and written in batches to a data sink.

   ![](https://img.shields.io/github/stars/j-easy/easy-batch) ![](https://img.shields.io/github/last-commit/j-easy/easy-batch) ![](https://img.shields.io/github/issues/j-easy/easy-batch) ![](https://img.shields.io/github/issues-pr/j-easy/easy-batch) ![](https://img.shields.io/github/license/j-easy/easy-batch) ![](https://img.shields.io/github/forks/j-easy/easy-batch) ![](https://img.shields.io/github/contributors/j-easy/easy-batch)

- [shedlock](https://github.com/lukas-krecan/ShedLock) - Makes sure that your scheduled tasks are executed at most once at the same time. If a task is being executed on one node, it acquires a lock which prevents execution of the same task from another node or thread.

   ![](https://img.shields.io/github/stars/lukas-krecan/ShedLock) ![](https://img.shields.io/github/last-commit/lukas-krecan/ShedLock) ![](https://img.shields.io/github/issues/lukas-krecan/ShedLock) ![](https://img.shields.io/github/issues-pr/lukas-krecan/ShedLock) ![](https://img.shields.io/github/license/lukas-krecan/ShedLock) ![](https://img.shields.io/github/forks/lukas-krecan/ShedLock) ![](https://img.shields.io/github/contributors/lukas-krecan/ShedLock)


### JSON

_Libraries for serializing and deserializing JSON to and from Java objects._

- [DSL-JSON](https://github.com/ngs-doo/dsl-json) - JSON library with advanced compile time databinding.

   ![](https://img.shields.io/github/stars/ngs-doo/dsl-json) ![](https://img.shields.io/github/last-commit/ngs-doo/dsl-json) ![](https://img.shields.io/github/issues/ngs-doo/dsl-json) ![](https://img.shields.io/github/issues-pr/ngs-doo/dsl-json) ![](https://img.shields.io/github/license/ngs-doo/dsl-json) ![](https://img.shields.io/github/forks/ngs-doo/dsl-json) ![](https://img.shields.io/github/contributors/ngs-doo/dsl-json)

- [Genson](http://genson.io) - Powerful and easy-to-use Java-to-JSON conversion library.
- [Gson](https://github.com/google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.

   ![](https://img.shields.io/github/stars/google/gson) ![](https://img.shields.io/github/last-commit/google/gson) ![](https://img.shields.io/github/issues/google/gson) ![](https://img.shields.io/github/issues-pr/google/gson) ![](https://img.shields.io/github/license/google/gson) ![](https://img.shields.io/github/forks/google/gson) ![](https://img.shields.io/github/contributors/google/gson)

- [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - High-performance JSON parser, 2x faster than Jackson.

   ![](https://img.shields.io/github/stars/brettwooldridge/HikariJSON) ![](https://img.shields.io/github/last-commit/brettwooldridge/HikariJSON) ![](https://img.shields.io/github/issues/brettwooldridge/HikariJSON) ![](https://img.shields.io/github/issues-pr/brettwooldridge/HikariJSON) ![](https://img.shields.io/github/license/brettwooldridge/HikariJSON) ![](https://img.shields.io/github/forks/brettwooldridge/HikariJSON) ![](https://img.shields.io/github/contributors/brettwooldridge/HikariJSON)

- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - Set of Jackson modules for Java 8 datatypes and features.

   ![](https://img.shields.io/github/stars/FasterXML/jackson-modules-java8) ![](https://img.shields.io/github/last-commit/FasterXML/jackson-modules-java8) ![](https://img.shields.io/github/issues/FasterXML/jackson-modules-java8) ![](https://img.shields.io/github/issues-pr/FasterXML/jackson-modules-java8) ![](https://img.shields.io/github/license/FasterXML/jackson-modules-java8) ![](https://img.shields.io/github/forks/FasterXML/jackson-modules-java8) ![](https://img.shields.io/github/contributors/FasterXML/jackson-modules-java8)

- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types.

   ![](https://img.shields.io/github/stars/zalando/jackson-datatype-money) ![](https://img.shields.io/github/last-commit/zalando/jackson-datatype-money) ![](https://img.shields.io/github/issues/zalando/jackson-datatype-money) ![](https://img.shields.io/github/issues-pr/zalando/jackson-datatype-money) ![](https://img.shields.io/github/license/zalando/jackson-datatype-money) ![](https://img.shields.io/github/forks/zalando/jackson-datatype-money) ![](https://img.shields.io/github/contributors/zalando/jackson-datatype-money)

- [Jackson](https://github.com/FasterXML/jackson) - Similar to GSON, but offers performance gains if you need to instantiate the library more often.

   ![](https://img.shields.io/github/stars/FasterXML/jackson) ![](https://img.shields.io/github/last-commit/FasterXML/jackson) ![](https://img.shields.io/github/issues/FasterXML/jackson) ![](https://img.shields.io/github/issues-pr/FasterXML/jackson) ![](https://img.shields.io/github/license/FasterXML/jackson) ![](https://img.shields.io/github/forks/FasterXML/jackson) ![](https://img.shields.io/github/contributors/FasterXML/jackson)

- [JSON-io](https://github.com/jdereg/json-io) - Convert Java to JSON. Convert JSON to Java. Pretty print JSON. Java JSON serializer.

   ![](https://img.shields.io/github/stars/jdereg/json-io) ![](https://img.shields.io/github/last-commit/jdereg/json-io) ![](https://img.shields.io/github/issues/jdereg/json-io) ![](https://img.shields.io/github/issues-pr/jdereg/json-io) ![](https://img.shields.io/github/license/jdereg/json-io) ![](https://img.shields.io/github/forks/jdereg/json-io) ![](https://img.shields.io/github/contributors/jdereg/json-io)

- [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library.

   ![](https://img.shields.io/github/stars/bluelinelabs/LoganSquare) ![](https://img.shields.io/github/last-commit/bluelinelabs/LoganSquare) ![](https://img.shields.io/github/issues/bluelinelabs/LoganSquare) ![](https://img.shields.io/github/issues-pr/bluelinelabs/LoganSquare) ![](https://img.shields.io/github/license/bluelinelabs/LoganSquare) ![](https://img.shields.io/github/forks/bluelinelabs/LoganSquare) ![](https://img.shields.io/github/contributors/bluelinelabs/LoganSquare)

- [Moshi](https://github.com/square/moshi) - Modern JSON library, less opinionated and uses built-in types like List and Map.

   ![](https://img.shields.io/github/stars/square/moshi) ![](https://img.shields.io/github/last-commit/square/moshi) ![](https://img.shields.io/github/issues/square/moshi) ![](https://img.shields.io/github/issues-pr/square/moshi) ![](https://img.shields.io/github/license/square/moshi) ![](https://img.shields.io/github/forks/square/moshi) ![](https://img.shields.io/github/contributors/square/moshi)

- [Yasson](https://github.com/eclipse-ee4j/yasson) - Binding layer between classes and JSON documents similar to JAXB.

   ![](https://img.shields.io/github/stars/eclipse-ee4j/yasson) ![](https://img.shields.io/github/last-commit/eclipse-ee4j/yasson) ![](https://img.shields.io/github/issues/eclipse-ee4j/yasson) ![](https://img.shields.io/github/issues-pr/eclipse-ee4j/yasson) ![](https://img.shields.io/github/license/eclipse-ee4j/yasson) ![](https://img.shields.io/github/forks/eclipse-ee4j/yasson) ![](https://img.shields.io/github/contributors/eclipse-ee4j/yasson)

- [fastjson](https://github.com/alibaba/fastjson) - Very fast processor with no additional dependencies and full data binding.

   ![](https://img.shields.io/github/stars/alibaba/fastjson) ![](https://img.shields.io/github/last-commit/alibaba/fastjson) ![](https://img.shields.io/github/issues/alibaba/fastjson) ![](https://img.shields.io/github/issues-pr/alibaba/fastjson) ![](https://img.shields.io/github/license/alibaba/fastjson) ![](https://img.shields.io/github/forks/alibaba/fastjson) ![](https://img.shields.io/github/contributors/alibaba/fastjson)

- [Jolt](https://github.com/bazaarvoice/jolt) - JSON to JSON transformation tool.

   ![](https://img.shields.io/github/stars/bazaarvoice/jolt) ![](https://img.shields.io/github/last-commit/bazaarvoice/jolt) ![](https://img.shields.io/github/issues/bazaarvoice/jolt) ![](https://img.shields.io/github/issues-pr/bazaarvoice/jolt) ![](https://img.shields.io/github/license/bazaarvoice/jolt) ![](https://img.shields.io/github/forks/bazaarvoice/jolt) ![](https://img.shields.io/github/contributors/bazaarvoice/jolt)

- [JsonPath](https://github.com/json-path/JsonPath) - Extract data from JSON using XPATH-like syntax.

   ![](https://img.shields.io/github/stars/json-path/JsonPath) ![](https://img.shields.io/github/last-commit/json-path/JsonPath) ![](https://img.shields.io/github/issues/json-path/JsonPath) ![](https://img.shields.io/github/issues-pr/json-path/JsonPath) ![](https://img.shields.io/github/license/json-path/JsonPath) ![](https://img.shields.io/github/forks/json-path/JsonPath) ![](https://img.shields.io/github/contributors/json-path/JsonPath)

- [JsonSurfer](https://github.com/jsurfer/JsonSurfer) - Streaming JsonPath processor dedicated to processing big and complicated JSON data.

   ![](https://img.shields.io/github/stars/jsurfer/JsonSurfer) ![](https://img.shields.io/github/last-commit/jsurfer/JsonSurfer) ![](https://img.shields.io/github/issues/jsurfer/JsonSurfer) ![](https://img.shields.io/github/issues-pr/jsurfer/JsonSurfer) ![](https://img.shields.io/github/license/jsurfer/JsonSurfer) ![](https://img.shields.io/github/forks/jsurfer/JsonSurfer) ![](https://img.shields.io/github/contributors/jsurfer/JsonSurfer)


### JVM and JDK

_Current implementations of the JVM/JDK._

- [Adopt Open JDK](https://adoptopenjdk.net) - Community-driven OpenJDK builds, including both HotSpot and OpenJ9.
- [Avian](https://github.com/ReadyTalk/avian) - JVM with JIT, AOT modes and iOS port.

   ![](https://img.shields.io/github/stars/ReadyTalk/avian) ![](https://img.shields.io/github/last-commit/ReadyTalk/avian) ![](https://img.shields.io/github/issues/ReadyTalk/avian) ![](https://img.shields.io/github/issues-pr/ReadyTalk/avian) ![](https://img.shields.io/github/license/ReadyTalk/avian) ![](https://img.shields.io/github/forks/ReadyTalk/avian) ![](https://img.shields.io/github/contributors/ReadyTalk/avian)

- [Corretto](https://aws.amazon.com/corretto/) - No-cost, multiplatform, production-ready distribution of OpenJDK by Amazon. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Dragonwell8](https://github.com/alibaba/dragonwell8) - Downstream version of OpenJDK optimized for online e-commerce, financial, logistics applications.

   ![](https://img.shields.io/github/stars/alibaba/dragonwell8) ![](https://img.shields.io/github/last-commit/alibaba/dragonwell8) ![](https://img.shields.io/github/issues/alibaba/dragonwell8) ![](https://img.shields.io/github/issues-pr/alibaba/dragonwell8) ![](https://img.shields.io/github/license/alibaba/dragonwell8) ![](https://img.shields.io/github/forks/alibaba/dragonwell8) ![](https://img.shields.io/github/contributors/alibaba/dragonwell8)

- [Graal](https://github.com/oracle/graal) - Polyglot embeddable JVM. (GPL-2.0-only WITH Classpath-exception-2.0)

   ![](https://img.shields.io/github/stars/oracle/graal) ![](https://img.shields.io/github/last-commit/oracle/graal) ![](https://img.shields.io/github/issues/oracle/graal) ![](https://img.shields.io/github/issues-pr/oracle/graal) ![](https://img.shields.io/github/license/oracle/graal) ![](https://img.shields.io/github/forks/oracle/graal) ![](https://img.shields.io/github/contributors/oracle/graal)

- [Liberica JDK](https://bell-sw.com) - Built from OpenJDK, thoroughly tested and passed the JCK. (GPL-2.0-only WITH Classpath-exception-2.0)
- [OpenJ9](https://github.com/eclipse/openj9) - High performance, enterprise-calibre, flexibly licensed, openly-governed cross-platform JVM extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project.

   ![](https://img.shields.io/github/stars/eclipse/openj9) ![](https://img.shields.io/github/last-commit/eclipse/openj9) ![](https://img.shields.io/github/issues/eclipse/openj9) ![](https://img.shields.io/github/issues-pr/eclipse/openj9) ![](https://img.shields.io/github/license/eclipse/openj9) ![](https://img.shields.io/github/forks/eclipse/openj9) ![](https://img.shields.io/github/contributors/eclipse/openj9)

- [Open JDK](https://openjdk.java.net) - Open JDK community home. (GPL-2.0-only WITH Classpath-exception-2.0)
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - VM with non-blocking, concurrent GC for iOS. (GPL-2.0-only WITH Classpath-exception-2.0)

   ![](https://img.shields.io/github/stars/codenameone/CodenameOne/tree/master/vm) ![](https://img.shields.io/github/last-commit/codenameone/CodenameOne/tree/master/vm) ![](https://img.shields.io/github/issues/codenameone/CodenameOne/tree/master/vm) ![](https://img.shields.io/github/issues-pr/codenameone/CodenameOne/tree/master/vm) ![](https://img.shields.io/github/license/codenameone/CodenameOne/tree/master/vm) ![](https://img.shields.io/github/forks/codenameone/CodenameOne/tree/master/vm) ![](https://img.shields.io/github/contributors/codenameone/CodenameOne/tree/master/vm)

- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview) - RedHat's OpenJDK distribution. (GPL-2.0-only WITH Classpath-exception-2.0)
- [SAP Machine](https://sap.github.io/SapMachine/) - SAP's no-cost, rigorously tested and JCK-verified OpenJDK friendly fork. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Zulu](https://www.azul.com/products/zulu-community/) - OpenJDK builds for Windows, Linux, and macOS. (GPL-2.0-only WITH Classpath-exception-2.0)

### Logging

_Libraries that log the behavior of an application._

- [Apache Log4j 2](https://logging.apache.org/log4j/) - Complete rewrite with a powerful plugin and configuration architecture.
- [Echopraxia](https://github.com/tersesystems/echopraxia) - API designed around structured logging, rich context, and conditional logging. There are Logback and Log4J2 implementations, but Echopraxia's API is completely dependency-free, meaning it can be implemented with any logging API.

   ![](https://img.shields.io/github/stars/tersesystems/echopraxia) ![](https://img.shields.io/github/last-commit/tersesystems/echopraxia) ![](https://img.shields.io/github/issues/tersesystems/echopraxia) ![](https://img.shields.io/github/issues-pr/tersesystems/echopraxia) ![](https://img.shields.io/github/license/tersesystems/echopraxia) ![](https://img.shields.io/github/forks/tersesystems/echopraxia) ![](https://img.shields.io/github/contributors/tersesystems/echopraxia)

- [Graylog](https://www.graylog.org) - Open-source aggregator suited for extended role and permission management. (GPL-3.0-only)
- [Kibana](https://www.elastic.co/kibana) - Analyzes and visualizes log files. Some features require payment.
- [Logback](http://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
- [Logbook](https://github.com/zalando/logbook) - Extensible, open-source library for HTTP request and response logging.

   ![](https://img.shields.io/github/stars/zalando/logbook) ![](https://img.shields.io/github/last-commit/zalando/logbook) ![](https://img.shields.io/github/issues/zalando/logbook) ![](https://img.shields.io/github/issues-pr/zalando/logbook) ![](https://img.shields.io/github/license/zalando/logbook) ![](https://img.shields.io/github/forks/zalando/logbook) ![](https://img.shields.io/github/contributors/zalando/logbook)

- [Logstash](https://www.elastic.co/logstash) - Tool for managing log files.
- [p6spy](https://github.com/p6spy/p6spy) - Enables logging for all JDBC transactions without changes to the code.

   ![](https://img.shields.io/github/stars/p6spy/p6spy) ![](https://img.shields.io/github/last-commit/p6spy/p6spy) ![](https://img.shields.io/github/issues/p6spy/p6spy) ![](https://img.shields.io/github/issues-pr/p6spy/p6spy) ![](https://img.shields.io/github/license/p6spy/p6spy) ![](https://img.shields.io/github/forks/p6spy/p6spy) ![](https://img.shields.io/github/contributors/p6spy/p6spy)

- [SLF4J](http://www.slf4j.org) - Abstraction layer/simple logging facade.
- [tinylog](https://tinylog.org/v2/) - Lightweight logging framework with static logger class.
- [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox) - Collection of libraries that build on top of OpenTracing and provide extensions and plugins to existing instrumentations.

   ![](https://img.shields.io/github/stars/zalando/opentracing-toolbox) ![](https://img.shields.io/github/last-commit/zalando/opentracing-toolbox) ![](https://img.shields.io/github/issues/zalando/opentracing-toolbox) ![](https://img.shields.io/github/issues-pr/zalando/opentracing-toolbox) ![](https://img.shields.io/github/license/zalando/opentracing-toolbox) ![](https://img.shields.io/github/forks/zalando/opentracing-toolbox) ![](https://img.shields.io/github/contributors/zalando/opentracing-toolbox)


### Machine Learning

_Tools that provide specific statistical algorithms for learning from data._

- [Apache Flink](https://flink.apache.org) - Fast, reliable, large-scale data processing engine.
- [Apache Mahout](https://mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
- [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
- [Deeplearning4j](https://deeplearning4j.org) - Distributed and multi-threaded deep learning library.
- [DJL](https://djl.ai) - High-level and engine-agnostic framework for deep learning.
- [H2O ![c]](https://www.h2o.ai) - Analytics engine for statistics over big data.
- [JSAT](https://github.com/EdwardRaff/JSAT) - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/EdwardRaff/JSAT) ![](https://img.shields.io/github/last-commit/EdwardRaff/JSAT) ![](https://img.shields.io/github/issues/EdwardRaff/JSAT) ![](https://img.shields.io/github/issues-pr/EdwardRaff/JSAT) ![](https://img.shields.io/github/license/EdwardRaff/JSAT) ![](https://img.shields.io/github/forks/EdwardRaff/JSAT) ![](https://img.shields.io/github/contributors/EdwardRaff/JSAT)

- [m2cgen](https://github.com/BayesWitnesses/m2cgen) - CLI tool to transpile models into native code.

   ![](https://img.shields.io/github/stars/BayesWitnesses/m2cgen) ![](https://img.shields.io/github/last-commit/BayesWitnesses/m2cgen) ![](https://img.shields.io/github/issues/BayesWitnesses/m2cgen) ![](https://img.shields.io/github/issues-pr/BayesWitnesses/m2cgen) ![](https://img.shields.io/github/license/BayesWitnesses/m2cgen) ![](https://img.shields.io/github/forks/BayesWitnesses/m2cgen) ![](https://img.shields.io/github/contributors/BayesWitnesses/m2cgen)

- [oj! Algorithms](https://www.ojalgo.org/) - High-performance mathematics, linear algebra and optimisation needed for data science, machine learning and scientific computing.
- [Oryx 2](https://github.com/OryxProject/oryx) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering.

   ![](https://img.shields.io/github/stars/OryxProject/oryx) ![](https://img.shields.io/github/last-commit/OryxProject/oryx) ![](https://img.shields.io/github/issues/OryxProject/oryx) ![](https://img.shields.io/github/issues-pr/OryxProject/oryx) ![](https://img.shields.io/github/license/OryxProject/oryx) ![](https://img.shields.io/github/forks/OryxProject/oryx) ![](https://img.shields.io/github/contributors/OryxProject/oryx)

- [Siddhi](https://github.com/siddhi-io/siddhi) - Cloud native streaming and complex event processing engine.

   ![](https://img.shields.io/github/stars/siddhi-io/siddhi) ![](https://img.shields.io/github/last-commit/siddhi-io/siddhi) ![](https://img.shields.io/github/issues/siddhi-io/siddhi) ![](https://img.shields.io/github/issues-pr/siddhi-io/siddhi) ![](https://img.shields.io/github/license/siddhi-io/siddhi) ![](https://img.shields.io/github/forks/siddhi-io/siddhi) ![](https://img.shields.io/github/contributors/siddhi-io/siddhi)

- [Smile](https://github.com/haifengl/smile) - Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.

   ![](https://img.shields.io/github/stars/haifengl/smile) ![](https://img.shields.io/github/last-commit/haifengl/smile) ![](https://img.shields.io/github/issues/haifengl/smile) ![](https://img.shields.io/github/issues-pr/haifengl/smile) ![](https://img.shields.io/github/license/haifengl/smile) ![](https://img.shields.io/github/forks/haifengl/smile) ![](https://img.shields.io/github/contributors/haifengl/smile)

- [Tribuo](https://tribuo.org/) - Provides tools for classification, regression, clustering, model development and interfaces with other libraries such as scikit-learn, pytorch and TensorFlow.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization. (GPL-3.0-only)

### Messaging

_Tools that help send messages between clients to ensure protocol independency._

- [Aeron](https://github.com/real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport.

   ![](https://img.shields.io/github/stars/real-logic/Aeron) ![](https://img.shields.io/github/last-commit/real-logic/Aeron) ![](https://img.shields.io/github/issues/real-logic/Aeron) ![](https://img.shields.io/github/issues-pr/real-logic/Aeron) ![](https://img.shields.io/github/license/real-logic/Aeron) ![](https://img.shields.io/github/forks/real-logic/Aeron) ![](https://img.shields.io/github/contributors/real-logic/Aeron)

- [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
- [Apache Pulsar](https://pulsar.apache.org) - Distributed pub/sub-messaging system.
- [Apache RocketMQ](https://rocketmq.apache.org) - Fast, reliable, and scalable distributed messaging platform.
- [Apache Qpid](https://qpid.apache.org) - Apache Qpid makes messaging tools that speak AMQP and support many languages and platforms.
- [EventBus](https://github.com/greenrobot/EventBus) - Simple publish/subscribe event bus.

   ![](https://img.shields.io/github/stars/greenrobot/EventBus) ![](https://img.shields.io/github/last-commit/greenrobot/EventBus) ![](https://img.shields.io/github/issues/greenrobot/EventBus) ![](https://img.shields.io/github/issues-pr/greenrobot/EventBus) ![](https://img.shields.io/github/license/greenrobot/EventBus) ![](https://img.shields.io/github/forks/greenrobot/EventBus) ![](https://img.shields.io/github/contributors/greenrobot/EventBus)

- [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
- [JeroMQ](https://github.com/zeromq/jeromq) - Implementation of ZeroMQ.

   ![](https://img.shields.io/github/stars/zeromq/jeromq) ![](https://img.shields.io/github/last-commit/zeromq/jeromq) ![](https://img.shields.io/github/issues/zeromq/jeromq) ![](https://img.shields.io/github/issues-pr/zeromq/jeromq) ![](https://img.shields.io/github/license/zeromq/jeromq) ![](https://img.shields.io/github/forks/zeromq/jeromq) ![](https://img.shields.io/github/contributors/zeromq/jeromq)

- [Nakadi](https://github.com/zalando/nakadi) - Provides a RESTful API on top of Kafka.

   ![](https://img.shields.io/github/stars/zalando/nakadi) ![](https://img.shields.io/github/last-commit/zalando/nakadi) ![](https://img.shields.io/github/issues/zalando/nakadi) ![](https://img.shields.io/github/issues-pr/zalando/nakadi) ![](https://img.shields.io/github/license/zalando/nakadi) ![](https://img.shields.io/github/forks/zalando/nakadi) ![](https://img.shields.io/github/contributors/zalando/nakadi)

- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) - RabbitMQ client.

   ![](https://img.shields.io/github/stars/rabbitmq/rabbitmq-java-client) ![](https://img.shields.io/github/last-commit/rabbitmq/rabbitmq-java-client) ![](https://img.shields.io/github/issues/rabbitmq/rabbitmq-java-client) ![](https://img.shields.io/github/issues-pr/rabbitmq/rabbitmq-java-client) ![](https://img.shields.io/github/license/rabbitmq/rabbitmq-java-client) ![](https://img.shields.io/github/forks/rabbitmq/rabbitmq-java-client) ![](https://img.shields.io/github/contributors/rabbitmq/rabbitmq-java-client)

- [Smack](https://github.com/igniterealtime/Smack) - Cross-platform XMPP client library.

   ![](https://img.shields.io/github/stars/igniterealtime/Smack) ![](https://img.shields.io/github/last-commit/igniterealtime/Smack) ![](https://img.shields.io/github/issues/igniterealtime/Smack) ![](https://img.shields.io/github/issues-pr/igniterealtime/Smack) ![](https://img.shields.io/github/license/igniterealtime/Smack) ![](https://img.shields.io/github/forks/igniterealtime/Smack) ![](https://img.shields.io/github/contributors/igniterealtime/Smack)

- [NATS client](https://github.com/nats-io/nats.java) - NATS client.

   ![](https://img.shields.io/github/stars/nats-io/nats.java) ![](https://img.shields.io/github/last-commit/nats-io/nats.java) ![](https://img.shields.io/github/issues/nats-io/nats.java) ![](https://img.shields.io/github/issues-pr/nats-io/nats.java) ![](https://img.shields.io/github/license/nats-io/nats.java) ![](https://img.shields.io/github/forks/nats-io/nats.java) ![](https://img.shields.io/github/contributors/nats-io/nats.java)


### Microservice

_Tools for creating and managing microservices._

- [ActiveRPC](https://rpc.activej.io) - Lightweight and fast library for complex high-load distributed applications and Memcached-like solutions.
- [Apollo](https://spotify.github.io/apollo/) - Libraries for writing composable microservices.
- [Armeria](https://github.com/line/armeria) - Asynchronous RPC/REST client/server library built on top of Java 8, Netty, HTTP/2, Thrift and gRPC.

   ![](https://img.shields.io/github/stars/line/armeria) ![](https://img.shields.io/github/last-commit/line/armeria) ![](https://img.shields.io/github/issues/line/armeria) ![](https://img.shields.io/github/issues-pr/line/armeria) ![](https://img.shields.io/github/license/line/armeria) ![](https://img.shields.io/github/forks/line/armeria) ![](https://img.shields.io/github/contributors/line/armeria)

- [consul-api](https://github.com/Ecwid/consul-api) - Client for the Consul API: a distributed, highly available and datacenter-aware registry/discovery service.

   ![](https://img.shields.io/github/stars/Ecwid/consul-api) ![](https://img.shields.io/github/last-commit/Ecwid/consul-api) ![](https://img.shields.io/github/issues/Ecwid/consul-api) ![](https://img.shields.io/github/issues-pr/Ecwid/consul-api) ![](https://img.shields.io/github/license/Ecwid/consul-api) ![](https://img.shields.io/github/forks/Ecwid/consul-api) ![](https://img.shields.io/github/contributors/Ecwid/consul-api)

- [Eureka](https://github.com/Netflix/eureka) - REST-based service registry for resilient load balancing and failover.

   ![](https://img.shields.io/github/stars/Netflix/eureka) ![](https://img.shields.io/github/last-commit/Netflix/eureka) ![](https://img.shields.io/github/issues/Netflix/eureka) ![](https://img.shields.io/github/issues-pr/Netflix/eureka) ![](https://img.shields.io/github/license/Netflix/eureka) ![](https://img.shields.io/github/forks/Netflix/eureka) ![](https://img.shields.io/github/contributors/Netflix/eureka)

- [Helidon](https://helidon.io) - Two-style approach for writing microservices: Functional-reactive and as an implementation of MicroProfile.
- [Micronaut](https://micronaut.io) - Modern full-stack framework with focus on modularity, minimal memory footprint and startup time.
- [Nacos](https://nacos.io) - Dynamic service discovery, configuration and service management platform for building cloud native applications.
- [Quarkus](https://quarkus.io) - Kubernetes stack tailored for the HotSpot and Graal VM.
- [Sentinel](https://github.com/alibaba/Sentinel) - Flow control component enabling reliability, resilience and monitoring for microservices.

   ![](https://img.shields.io/github/stars/alibaba/Sentinel) ![](https://img.shields.io/github/last-commit/alibaba/Sentinel) ![](https://img.shields.io/github/issues/alibaba/Sentinel) ![](https://img.shields.io/github/issues-pr/alibaba/Sentinel) ![](https://img.shields.io/github/license/alibaba/Sentinel) ![](https://img.shields.io/github/forks/alibaba/Sentinel) ![](https://img.shields.io/github/contributors/alibaba/Sentinel)


### Miscellaneous

_Everything else._

- [CQEngine](https://github.com/npgall/cqengine) - Ultra-fast, SQL-like queries on Java collections.

   ![](https://img.shields.io/github/stars/npgall/cqengine) ![](https://img.shields.io/github/last-commit/npgall/cqengine) ![](https://img.shields.io/github/issues/npgall/cqengine) ![](https://img.shields.io/github/issues-pr/npgall/cqengine) ![](https://img.shields.io/github/license/npgall/cqengine) ![](https://img.shields.io/github/forks/npgall/cqengine) ![](https://img.shields.io/github/contributors/npgall/cqengine)

- [Design Patterns](https://github.com/iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns.

   ![](https://img.shields.io/github/stars/iluwatar/java-design-patterns) ![](https://img.shields.io/github/last-commit/iluwatar/java-design-patterns) ![](https://img.shields.io/github/issues/iluwatar/java-design-patterns) ![](https://img.shields.io/github/issues-pr/iluwatar/java-design-patterns) ![](https://img.shields.io/github/license/iluwatar/java-design-patterns) ![](https://img.shields.io/github/forks/iluwatar/java-design-patterns) ![](https://img.shields.io/github/contributors/iluwatar/java-design-patterns)

- [FF4J](https://github.com/ff4j/ff4j) - Feature Flags for Java.

   ![](https://img.shields.io/github/stars/ff4j/ff4j) ![](https://img.shields.io/github/last-commit/ff4j/ff4j) ![](https://img.shields.io/github/issues/ff4j/ff4j) ![](https://img.shields.io/github/issues-pr/ff4j/ff4j) ![](https://img.shields.io/github/license/ff4j/ff4j) ![](https://img.shields.io/github/forks/ff4j/ff4j) ![](https://img.shields.io/github/contributors/ff4j/ff4j)

- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - No-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes. (No explicit license)

   ![](https://img.shields.io/github/stars/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ![](https://img.shields.io/github/last-commit/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ![](https://img.shields.io/github/issues/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ![](https://img.shields.io/github/issues-pr/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ![](https://img.shields.io/github/license/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ![](https://img.shields.io/github/forks/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ![](https://img.shields.io/github/contributors/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition)

- [J2ObjC](https://github.com/google/j2objc) - Java-to-Objective-C translator for porting Android libraries to iOS.

   ![](https://img.shields.io/github/stars/google/j2objc) ![](https://img.shields.io/github/last-commit/google/j2objc) ![](https://img.shields.io/github/issues/google/j2objc) ![](https://img.shields.io/github/issues-pr/google/j2objc) ![](https://img.shields.io/github/license/google/j2objc) ![](https://img.shields.io/github/forks/google/j2objc) ![](https://img.shields.io/github/contributors/google/j2objc)

- [JBake](https://jbake.org) - Static website generator.
- [JBot](https://github.com/rampatra/jbot) - Framework for building chatbots. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/rampatra/jbot) ![](https://img.shields.io/github/last-commit/rampatra/jbot) ![](https://img.shields.io/github/issues/rampatra/jbot) ![](https://img.shields.io/github/issues-pr/rampatra/jbot) ![](https://img.shields.io/github/license/rampatra/jbot) ![](https://img.shields.io/github/forks/rampatra/jbot) ![](https://img.shields.io/github/contributors/rampatra/jbot)

- [JCuda](http://jcuda.org) - JCuda offers Java bindings for CUDA and CUDA-related libraries.
- [Jimfs](https://github.com/google/jimfs) - In-memory file system.

   ![](https://img.shields.io/github/stars/google/jimfs) ![](https://img.shields.io/github/last-commit/google/jimfs) ![](https://img.shields.io/github/issues/google/jimfs) ![](https://img.shields.io/github/issues-pr/google/jimfs) ![](https://img.shields.io/github/license/google/jimfs) ![](https://img.shields.io/github/forks/google/jimfs) ![](https://img.shields.io/github/contributors/google/jimfs)

- [JObfuscator![c]](https://www.pelock.com/products/jobfuscator) - Source code obfuscator.
- [Joda-Money](https://www.joda.org/joda-money/) - Basic currency and money classes and algorithms not provided by the JDK.
- [JPad](http://jpad.io) - Snippet runner.
- [jsweet](https://github.com/cincheo/jsweet) - Source transpiler to TypeScript/JavaScript.

   ![](https://img.shields.io/github/stars/cincheo/jsweet) ![](https://img.shields.io/github/last-commit/cincheo/jsweet) ![](https://img.shields.io/github/issues/cincheo/jsweet) ![](https://img.shields.io/github/issues-pr/cincheo/jsweet) ![](https://img.shields.io/github/license/cincheo/jsweet) ![](https://img.shields.io/github/forks/cincheo/jsweet) ![](https://img.shields.io/github/contributors/cincheo/jsweet)

- [Maven Wrapper](https://github.com/takari/maven-wrapper) - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven.

   ![](https://img.shields.io/github/stars/takari/maven-wrapper) ![](https://img.shields.io/github/last-commit/takari/maven-wrapper) ![](https://img.shields.io/github/issues/takari/maven-wrapper) ![](https://img.shields.io/github/issues-pr/takari/maven-wrapper) ![](https://img.shields.io/github/license/takari/maven-wrapper) ![](https://img.shields.io/github/forks/takari/maven-wrapper) ![](https://img.shields.io/github/contributors/takari/maven-wrapper)

- [Membrane Service Proxy](https://github.com/membrane/service-proxy) - Open-source, reverse-proxy framework.

   ![](https://img.shields.io/github/stars/membrane/service-proxy) ![](https://img.shields.io/github/last-commit/membrane/service-proxy) ![](https://img.shields.io/github/issues/membrane/service-proxy) ![](https://img.shields.io/github/issues-pr/membrane/service-proxy) ![](https://img.shields.io/github/license/membrane/service-proxy) ![](https://img.shields.io/github/forks/membrane/service-proxy) ![](https://img.shields.io/github/contributors/membrane/service-proxy)

- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) - Lightweight, small and customizable FTP server.

   ![](https://img.shields.io/github/stars/Guichaguri/MinimalFTP) ![](https://img.shields.io/github/last-commit/Guichaguri/MinimalFTP) ![](https://img.shields.io/github/issues/Guichaguri/MinimalFTP) ![](https://img.shields.io/github/issues-pr/Guichaguri/MinimalFTP) ![](https://img.shields.io/github/license/Guichaguri/MinimalFTP) ![](https://img.shields.io/github/forks/Guichaguri/MinimalFTP) ![](https://img.shields.io/github/contributors/Guichaguri/MinimalFTP)

- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - Popular Java 8 guide.

   ![](https://img.shields.io/github/stars/winterbe/java8-tutorial) ![](https://img.shields.io/github/last-commit/winterbe/java8-tutorial) ![](https://img.shields.io/github/issues/winterbe/java8-tutorial) ![](https://img.shields.io/github/issues-pr/winterbe/java8-tutorial) ![](https://img.shields.io/github/license/winterbe/java8-tutorial) ![](https://img.shields.io/github/forks/winterbe/java8-tutorial) ![](https://img.shields.io/github/contributors/winterbe/java8-tutorial)

- [Modernizer](https://github.com/gaul/modernizer-maven-plugin) - Detect uses of legacy Java APIs.

   ![](https://img.shields.io/github/stars/gaul/modernizer-maven-plugin) ![](https://img.shields.io/github/last-commit/gaul/modernizer-maven-plugin) ![](https://img.shields.io/github/issues/gaul/modernizer-maven-plugin) ![](https://img.shields.io/github/issues-pr/gaul/modernizer-maven-plugin) ![](https://img.shields.io/github/license/gaul/modernizer-maven-plugin) ![](https://img.shields.io/github/forks/gaul/modernizer-maven-plugin) ![](https://img.shields.io/github/contributors/gaul/modernizer-maven-plugin)

- [OctoLinker](https://github.com/OctoLinker/OctoLinker) - Browser extension which allows to navigate through code on GitHub more efficiently.

   ![](https://img.shields.io/github/stars/OctoLinker/OctoLinker) ![](https://img.shields.io/github/last-commit/OctoLinker/OctoLinker) ![](https://img.shields.io/github/issues/OctoLinker/OctoLinker) ![](https://img.shields.io/github/issues-pr/OctoLinker/OctoLinker) ![](https://img.shields.io/github/license/OctoLinker/OctoLinker) ![](https://img.shields.io/github/forks/OctoLinker/OctoLinker) ![](https://img.shields.io/github/contributors/OctoLinker/OctoLinker)

- [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
- [PipelinR](https://github.com/sizovs/pipelinr) - Small utility library for using handlers and commands with pipelines.

   ![](https://img.shields.io/github/stars/sizovs/pipelinr) ![](https://img.shields.io/github/last-commit/sizovs/pipelinr) ![](https://img.shields.io/github/issues/sizovs/pipelinr) ![](https://img.shields.io/github/issues-pr/sizovs/pipelinr) ![](https://img.shields.io/github/license/sizovs/pipelinr) ![](https://img.shields.io/github/forks/sizovs/pipelinr) ![](https://img.shields.io/github/contributors/sizovs/pipelinr)

- [Polyglot for Maven](https://github.com/takari/polyglot-maven) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML.

   ![](https://img.shields.io/github/stars/takari/polyglot-maven) ![](https://img.shields.io/github/last-commit/takari/polyglot-maven) ![](https://img.shields.io/github/issues/takari/polyglot-maven) ![](https://img.shields.io/github/issues-pr/takari/polyglot-maven) ![](https://img.shields.io/github/license/takari/polyglot-maven) ![](https://img.shields.io/github/forks/takari/polyglot-maven) ![](https://img.shields.io/github/contributors/takari/polyglot-maven)

- [RR4J](https://github.com/Kartikvk1996/RR4J) - RR4J is a tool that records java bytecode execution and later allows developers to replay locally.

   ![](https://img.shields.io/github/stars/Kartikvk1996/RR4J) ![](https://img.shields.io/github/last-commit/Kartikvk1996/RR4J) ![](https://img.shields.io/github/issues/Kartikvk1996/RR4J) ![](https://img.shields.io/github/issues-pr/Kartikvk1996/RR4J) ![](https://img.shields.io/github/license/Kartikvk1996/RR4J) ![](https://img.shields.io/github/forks/Kartikvk1996/RR4J) ![](https://img.shields.io/github/contributors/Kartikvk1996/RR4J)

- [Simple Java Mail](https://github.com/bbottema/simple-java-mail) - Mailing with a clean and fluent API.

   ![](https://img.shields.io/github/stars/bbottema/simple-java-mail) ![](https://img.shields.io/github/last-commit/bbottema/simple-java-mail) ![](https://img.shields.io/github/issues/bbottema/simple-java-mail) ![](https://img.shields.io/github/issues-pr/bbottema/simple-java-mail) ![](https://img.shields.io/github/license/bbottema/simple-java-mail) ![](https://img.shields.io/github/forks/bbottema/simple-java-mail) ![](https://img.shields.io/github/contributors/bbottema/simple-java-mail)

- [Smooks](https://github.com/smooks/smooks) - Framework for fragment-based message processing. (Apache-2.0 OR LGPL-3.0-or-later)

   ![](https://img.shields.io/github/stars/smooks/smooks) ![](https://img.shields.io/github/last-commit/smooks/smooks) ![](https://img.shields.io/github/issues/smooks/smooks) ![](https://img.shields.io/github/issues-pr/smooks/smooks) ![](https://img.shields.io/github/license/smooks/smooks) ![](https://img.shields.io/github/forks/smooks/smooks) ![](https://img.shields.io/github/contributors/smooks/smooks)

- [Togglz](https://www.togglz.org) - Implementation of the Feature Toggles pattern.
- [TypeTools](https://github.com/jhalterman/typetools) - Tools for resolving generic types.

   ![](https://img.shields.io/github/stars/jhalterman/typetools) ![](https://img.shields.io/github/last-commit/jhalterman/typetools) ![](https://img.shields.io/github/issues/jhalterman/typetools) ![](https://img.shields.io/github/issues-pr/jhalterman/typetools) ![](https://img.shields.io/github/license/jhalterman/typetools) ![](https://img.shields.io/github/forks/jhalterman/typetools) ![](https://img.shields.io/github/contributors/jhalterman/typetools)

- [XMLBeam](https://github.com/SvenEwald/xmlbeam) - Processes XML by using annotations or XPath within code.

   ![](https://img.shields.io/github/stars/SvenEwald/xmlbeam) ![](https://img.shields.io/github/last-commit/SvenEwald/xmlbeam) ![](https://img.shields.io/github/issues/SvenEwald/xmlbeam) ![](https://img.shields.io/github/issues-pr/SvenEwald/xmlbeam) ![](https://img.shields.io/github/license/SvenEwald/xmlbeam) ![](https://img.shields.io/github/forks/SvenEwald/xmlbeam) ![](https://img.shields.io/github/contributors/SvenEwald/xmlbeam)

- [yGuard](https://github.com/yWorks/yGuard) - Obfuscation via renaming and shrinking.

   ![](https://img.shields.io/github/stars/yWorks/yGuard) ![](https://img.shields.io/github/last-commit/yWorks/yGuard) ![](https://img.shields.io/github/issues/yWorks/yGuard) ![](https://img.shields.io/github/issues-pr/yWorks/yGuard) ![](https://img.shields.io/github/license/yWorks/yGuard) ![](https://img.shields.io/github/forks/yWorks/yGuard) ![](https://img.shields.io/github/contributors/yWorks/yGuard)


### Mobile Development

_Tools for creating or managing mobile applications._

- [Codename One](https://www.codenameone.com) - Cross-platform solution for writing native mobile apps. (GPL-2.0-only WITH Classpath-exception-2.0)
- [MobileUI](https://mobileui.dev) - Cross-platform framework for developing mobile apps with native UI in Java and Kotlin.
- [Multi-OS Engine](https://multi-os-engine.org) - Open-source, cross-platform engine to develop native mobile (iOS, Android, etc.) apps.

### Monitoring

_Tools that monitor applications in production._

- [Automon](https://github.com/stevensouza/automon) - Combines the power of AOP with monitoring and/or logging tools.

   ![](https://img.shields.io/github/stars/stevensouza/automon) ![](https://img.shields.io/github/last-commit/stevensouza/automon) ![](https://img.shields.io/github/issues/stevensouza/automon) ![](https://img.shields.io/github/issues-pr/stevensouza/automon) ![](https://img.shields.io/github/license/stevensouza/automon) ![](https://img.shields.io/github/forks/stevensouza/automon) ![](https://img.shields.io/github/contributors/stevensouza/automon)

- [Failsafe Actuator](https://github.com/zalando/failsafe-actuator) - Out of the box monitoring of Failsafe Circuit Breaker in Spring-Boot environment.

   ![](https://img.shields.io/github/stars/zalando/failsafe-actuator) ![](https://img.shields.io/github/last-commit/zalando/failsafe-actuator) ![](https://img.shields.io/github/issues/zalando/failsafe-actuator) ![](https://img.shields.io/github/issues-pr/zalando/failsafe-actuator) ![](https://img.shields.io/github/license/zalando/failsafe-actuator) ![](https://img.shields.io/github/forks/zalando/failsafe-actuator) ![](https://img.shields.io/github/contributors/zalando/failsafe-actuator)

- [Glowroot](https://glowroot.org) - Open-source Java APM.
- [inspectIT](https://www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
- [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
- [JavaMelody](https://github.com/javamelody/javamelody) - Performance monitoring and profiling.

   ![](https://img.shields.io/github/stars/javamelody/javamelody) ![](https://img.shields.io/github/last-commit/javamelody/javamelody) ![](https://img.shields.io/github/issues/javamelody/javamelody) ![](https://img.shields.io/github/issues-pr/javamelody/javamelody) ![](https://img.shields.io/github/license/javamelody/javamelody) ![](https://img.shields.io/github/forks/javamelody/javamelody) ![](https://img.shields.io/github/contributors/javamelody/javamelody)

- [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) - Jaeger client.

   ![](https://img.shields.io/github/stars/jaegertracing/jaeger-client-java) ![](https://img.shields.io/github/last-commit/jaegertracing/jaeger-client-java) ![](https://img.shields.io/github/issues/jaegertracing/jaeger-client-java) ![](https://img.shields.io/github/issues-pr/jaegertracing/jaeger-client-java) ![](https://img.shields.io/github/license/jaegertracing/jaeger-client-java) ![](https://img.shields.io/github/forks/jaegertracing/jaeger-client-java) ![](https://img.shields.io/github/contributors/jaegertracing/jaeger-client-java)

- [jmxtrans](https://github.com/jmxtrans/jmxtrans) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD.

   ![](https://img.shields.io/github/stars/jmxtrans/jmxtrans) ![](https://img.shields.io/github/last-commit/jmxtrans/jmxtrans) ![](https://img.shields.io/github/issues/jmxtrans/jmxtrans) ![](https://img.shields.io/github/issues-pr/jmxtrans/jmxtrans) ![](https://img.shields.io/github/license/jmxtrans/jmxtrans) ![](https://img.shields.io/github/forks/jmxtrans/jmxtrans) ![](https://img.shields.io/github/contributors/jmxtrans/jmxtrans)

- [Jolokia](https://jolokia.org) - JMX over REST.
- [Metrics](https://github.com/dropwizard/metrics) - Expose metrics via JMX or HTTP and send them to a database.

   ![](https://img.shields.io/github/stars/dropwizard/metrics) ![](https://img.shields.io/github/last-commit/dropwizard/metrics) ![](https://img.shields.io/github/issues/dropwizard/metrics) ![](https://img.shields.io/github/issues-pr/dropwizard/metrics) ![](https://img.shields.io/github/license/dropwizard/metrics) ![](https://img.shields.io/github/forks/dropwizard/metrics) ![](https://img.shields.io/github/contributors/dropwizard/metrics)

- [Datadog ![c]](https://github.com/DataDog/dd-trace-java) - Modern monitoring & analytics.
- [nudge4j](https://github.com/lorenzoongithub/nudge4j) - Remote developer console from the browser for Java 8 via bytecode injection.

   ![](https://img.shields.io/github/stars/lorenzoongithub/nudge4j) ![](https://img.shields.io/github/last-commit/lorenzoongithub/nudge4j) ![](https://img.shields.io/github/issues/lorenzoongithub/nudge4j) ![](https://img.shields.io/github/issues-pr/lorenzoongithub/nudge4j) ![](https://img.shields.io/github/license/lorenzoongithub/nudge4j) ![](https://img.shields.io/github/forks/lorenzoongithub/nudge4j) ![](https://img.shields.io/github/contributors/lorenzoongithub/nudge4j)

- [Pinpoint](https://github.com/naver/pinpoint) - Open-source APM tool.

   ![](https://img.shields.io/github/stars/naver/pinpoint) ![](https://img.shields.io/github/last-commit/naver/pinpoint) ![](https://img.shields.io/github/issues/naver/pinpoint) ![](https://img.shields.io/github/issues-pr/naver/pinpoint) ![](https://img.shields.io/github/license/naver/pinpoint) ![](https://img.shields.io/github/forks/naver/pinpoint) ![](https://img.shields.io/github/contributors/naver/pinpoint)

- [Prometheus](https://github.com/prometheus/client_java) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.

   ![](https://img.shields.io/github/stars/prometheus/client_java) ![](https://img.shields.io/github/last-commit/prometheus/client_java) ![](https://img.shields.io/github/issues/prometheus/client_java) ![](https://img.shields.io/github/issues-pr/prometheus/client_java) ![](https://img.shields.io/github/license/prometheus/client_java) ![](https://img.shields.io/github/forks/prometheus/client_java) ![](https://img.shields.io/github/contributors/prometheus/client_java)

- [Sentry ![c]](https://github.com/getsentry/sentry-java) - Integration with [Sentry](https://github.com/getsentry/sentry), an application error tracking and performance analysis platform.
- [SPM ![c]](https://github.com/sematext/sematext-agent-java) - Performance monitor with distributing transaction tracing for JVM apps.
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor) - Open-source performance monitoring and transaction tracing for JVM apps.

   ![](https://img.shields.io/github/stars/stagemonitor/stagemonitor) ![](https://img.shields.io/github/last-commit/stagemonitor/stagemonitor) ![](https://img.shields.io/github/issues/stagemonitor/stagemonitor) ![](https://img.shields.io/github/issues-pr/stagemonitor/stagemonitor) ![](https://img.shields.io/github/license/stagemonitor/stagemonitor) ![](https://img.shields.io/github/forks/stagemonitor/stagemonitor) ![](https://img.shields.io/github/contributors/stagemonitor/stagemonitor)

- [Sysmon](https://github.com/palantir/Sysmon) - Lightweight platform monitoring tool for Java VMs.

   ![](https://img.shields.io/github/stars/palantir/Sysmon) ![](https://img.shields.io/github/last-commit/palantir/Sysmon) ![](https://img.shields.io/github/issues/palantir/Sysmon) ![](https://img.shields.io/github/issues-pr/palantir/Sysmon) ![](https://img.shields.io/github/license/palantir/Sysmon) ![](https://img.shields.io/github/forks/palantir/Sysmon) ![](https://img.shields.io/github/contributors/palantir/Sysmon)

- [zipkin](https://zipkin.io) - Distributed tracing system which gathers timing data needed to troubleshoot latency problems in microservice architectures.

### Native

_For working with platform-specific native libraries._

- [Aparapi](https://github.com/Syncleus/aparapi) - Converts bytecode to OpenCL which allows execution on GPUs.

   ![](https://img.shields.io/github/stars/Syncleus/aparapi) ![](https://img.shields.io/github/last-commit/Syncleus/aparapi) ![](https://img.shields.io/github/issues/Syncleus/aparapi) ![](https://img.shields.io/github/issues-pr/Syncleus/aparapi) ![](https://img.shields.io/github/license/Syncleus/aparapi) ![](https://img.shields.io/github/forks/Syncleus/aparapi) ![](https://img.shields.io/github/contributors/Syncleus/aparapi)

- [JavaCPP](https://github.com/bytedeco/javacpp) - Provides efficient and easy access to native C++.

   ![](https://img.shields.io/github/stars/bytedeco/javacpp) ![](https://img.shields.io/github/last-commit/bytedeco/javacpp) ![](https://img.shields.io/github/issues/bytedeco/javacpp) ![](https://img.shields.io/github/issues-pr/bytedeco/javacpp) ![](https://img.shields.io/github/license/bytedeco/javacpp) ![](https://img.shields.io/github/forks/bytedeco/javacpp) ![](https://img.shields.io/github/contributors/bytedeco/javacpp)

- [JNA](https://github.com/java-native-access/jna) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries.

   ![](https://img.shields.io/github/stars/java-native-access/jna) ![](https://img.shields.io/github/last-commit/java-native-access/jna) ![](https://img.shields.io/github/issues/java-native-access/jna) ![](https://img.shields.io/github/issues-pr/java-native-access/jna) ![](https://img.shields.io/github/license/java-native-access/jna) ![](https://img.shields.io/github/forks/java-native-access/jna) ![](https://img.shields.io/github/contributors/java-native-access/jna)

- [JNR](https://github.com/jnr/jnr-ffi) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama).

   ![](https://img.shields.io/github/stars/jnr/jnr-ffi) ![](https://img.shields.io/github/last-commit/jnr/jnr-ffi) ![](https://img.shields.io/github/issues/jnr/jnr-ffi) ![](https://img.shields.io/github/issues-pr/jnr/jnr-ffi) ![](https://img.shields.io/github/license/jnr/jnr-ffi) ![](https://img.shields.io/github/forks/jnr/jnr-ffi) ![](https://img.shields.io/github/contributors/jnr/jnr-ffi)


### Natural Language Processing

_Libraries that specialize in processing text._

- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp) - Provides common annotators for plain text input. (Research and Academic Use License)

   ![](https://img.shields.io/github/stars/CogComp/cogcomp-nlp) ![](https://img.shields.io/github/last-commit/CogComp/cogcomp-nlp) ![](https://img.shields.io/github/issues/CogComp/cogcomp-nlp) ![](https://img.shields.io/github/issues-pr/CogComp/cogcomp-nlp) ![](https://img.shields.io/github/license/CogComp/cogcomp-nlp) ![](https://img.shields.io/github/forks/CogComp/cogcomp-nlp) ![](https://img.shields.io/github/contributors/CogComp/cogcomp-nlp)

- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis. (GPL-3.0-or-later)
- [DKPro](https://dkpro.github.io) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
- [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

### Networking

_Libraries for building network servers._

- [Commons-networking](https://github.com/CiscoSE/commons-networking) - Client for server-sent events (SSE).

   ![](https://img.shields.io/github/stars/CiscoSE/commons-networking) ![](https://img.shields.io/github/last-commit/CiscoSE/commons-networking) ![](https://img.shields.io/github/issues/CiscoSE/commons-networking) ![](https://img.shields.io/github/issues-pr/CiscoSE/commons-networking) ![](https://img.shields.io/github/license/CiscoSE/commons-networking) ![](https://img.shields.io/github/forks/CiscoSE/commons-networking) ![](https://img.shields.io/github/contributors/CiscoSE/commons-networking)

- [Comsat](https://github.com/puniverse/comsat) - Integrates standard Java web-related APIs with Quasar fibers and actors.

   ![](https://img.shields.io/github/stars/puniverse/comsat) ![](https://img.shields.io/github/last-commit/puniverse/comsat) ![](https://img.shields.io/github/issues/puniverse/comsat) ![](https://img.shields.io/github/issues-pr/puniverse/comsat) ![](https://img.shields.io/github/license/puniverse/comsat) ![](https://img.shields.io/github/forks/puniverse/comsat) ![](https://img.shields.io/github/contributors/puniverse/comsat)

- [Dubbo](https://github.com/apache/dubbo) - High-performance RPC framework.

   ![](https://img.shields.io/github/stars/apache/dubbo) ![](https://img.shields.io/github/last-commit/apache/dubbo) ![](https://img.shields.io/github/issues/apache/dubbo) ![](https://img.shields.io/github/issues-pr/apache/dubbo) ![](https://img.shields.io/github/license/apache/dubbo) ![](https://img.shields.io/github/forks/apache/dubbo) ![](https://img.shields.io/github/contributors/apache/dubbo)

- [Grizzly](https://javaee.github.io/grizzly/) - NIO framework. Used as a network layer in Glassfish.
- [gRPC](https://github.com/grpc/grpc-java) - RPC framework based on protobuf and HTTP/2.

   ![](https://img.shields.io/github/stars/grpc/grpc-java) ![](https://img.shields.io/github/last-commit/grpc/grpc-java) ![](https://img.shields.io/github/issues/grpc/grpc-java) ![](https://img.shields.io/github/issues-pr/grpc/grpc-java) ![](https://img.shields.io/github/license/grpc/grpc-java) ![](https://img.shields.io/github/forks/grpc/grpc-java) ![](https://img.shields.io/github/contributors/grpc/grpc-java)

- [KryoNet](https://github.com/EsotericSoftware/kryonet) - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo.

   ![](https://img.shields.io/github/stars/EsotericSoftware/kryonet) ![](https://img.shields.io/github/last-commit/EsotericSoftware/kryonet) ![](https://img.shields.io/github/issues/EsotericSoftware/kryonet) ![](https://img.shields.io/github/issues-pr/EsotericSoftware/kryonet) ![](https://img.shields.io/github/license/EsotericSoftware/kryonet) ![](https://img.shields.io/github/forks/EsotericSoftware/kryonet) ![](https://img.shields.io/github/contributors/EsotericSoftware/kryonet)

- [MINA](https://mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
- [Netty](https://netty.io) - Framework for building high-performance network applications.
- [Drift](https://github.com/airlift/drift) - Easy-to-use, annotation-based library for creating Thrift clients and serializable types.

   ![](https://img.shields.io/github/stars/airlift/drift) ![](https://img.shields.io/github/last-commit/airlift/drift) ![](https://img.shields.io/github/issues/airlift/drift) ![](https://img.shields.io/github/issues-pr/airlift/drift) ![](https://img.shields.io/github/license/airlift/drift) ![](https://img.shields.io/github/forks/airlift/drift) ![](https://img.shields.io/github/contributors/airlift/drift)

- [ServiceTalk](https://github.com/apple/servicetalk) - Framework built on Netty with APIs tailored to specific protocols and support for multiple programming paradigms.

   ![](https://img.shields.io/github/stars/apple/servicetalk) ![](https://img.shields.io/github/last-commit/apple/servicetalk) ![](https://img.shields.io/github/issues/apple/servicetalk) ![](https://img.shields.io/github/issues-pr/apple/servicetalk) ![](https://img.shields.io/github/license/apple/servicetalk) ![](https://img.shields.io/github/forks/apple/servicetalk) ![](https://img.shields.io/github/contributors/apple/servicetalk)

- [sshj](https://github.com/hierynomus/sshj) - Programmatically use SSH, SCP or SFTP.

   ![](https://img.shields.io/github/stars/hierynomus/sshj) ![](https://img.shields.io/github/last-commit/hierynomus/sshj) ![](https://img.shields.io/github/issues/hierynomus/sshj) ![](https://img.shields.io/github/issues-pr/hierynomus/sshj) ![](https://img.shields.io/github/license/hierynomus/sshj) ![](https://img.shields.io/github/forks/hierynomus/sshj) ![](https://img.shields.io/github/contributors/hierynomus/sshj)

- [TLS Channel](https://github.com/marianobarrios/tls-channel) - Implements a ByteChannel interface over SSLEngine, enabling easy-to-use (socket-like) TLS.

   ![](https://img.shields.io/github/stars/marianobarrios/tls-channel) ![](https://img.shields.io/github/last-commit/marianobarrios/tls-channel) ![](https://img.shields.io/github/issues/marianobarrios/tls-channel) ![](https://img.shields.io/github/issues-pr/marianobarrios/tls-channel) ![](https://img.shields.io/github/license/marianobarrios/tls-channel) ![](https://img.shields.io/github/forks/marianobarrios/tls-channel) ![](https://img.shields.io/github/contributors/marianobarrios/tls-channel)

- [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly. (LGPL-2.1-only)
- [urnlib](https://github.com/slub/urnlib) - Represent, parse and encode URNs, as in RFC 2141. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/slub/urnlib) ![](https://img.shields.io/github/last-commit/slub/urnlib) ![](https://img.shields.io/github/issues/slub/urnlib) ![](https://img.shields.io/github/issues-pr/slub/urnlib) ![](https://img.shields.io/github/license/slub/urnlib) ![](https://img.shields.io/github/forks/slub/urnlib) ![](https://img.shields.io/github/contributors/slub/urnlib)


### ORM

_APIs that handle the persistence of objects._

- [Apache Cayenne](https://cayenne.apache.org) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
- [Doma](https://github.com/domaframework/doma) - Database access framework that verifies and generates source code at compile time using annotation processing as well as native SQL templates called two-way SQL.

   ![](https://img.shields.io/github/stars/domaframework/doma) ![](https://img.shields.io/github/last-commit/domaframework/doma) ![](https://img.shields.io/github/issues/domaframework/doma) ![](https://img.shields.io/github/issues-pr/domaframework/doma) ![](https://img.shields.io/github/license/domaframework/doma) ![](https://img.shields.io/github/forks/domaframework/doma) ![](https://img.shields.io/github/contributors/domaframework/doma)

- [Ebean](https://ebean.io) - Provides simple and fast data access.
- [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
- [Hibernate](http://hibernate.org/orm/) - Robust and widely used, with an active community. (LGPL-2.1-only)
- [MyBatis](https://github.com/mybatis/mybatis-3) - Couples objects with stored procedures or SQL statements.

   ![](https://img.shields.io/github/stars/mybatis/mybatis-3) ![](https://img.shields.io/github/last-commit/mybatis/mybatis-3) ![](https://img.shields.io/github/issues/mybatis/mybatis-3) ![](https://img.shields.io/github/issues-pr/mybatis/mybatis-3) ![](https://img.shields.io/github/license/mybatis/mybatis-3) ![](https://img.shields.io/github/forks/mybatis/mybatis-3) ![](https://img.shields.io/github/contributors/mybatis/mybatis-3)

- [ObjectiveSql](https://github.com/braisdom/ObjectiveSql) - ActiveRecord ORM for rapid development and convention over configuration.

   ![](https://img.shields.io/github/stars/braisdom/ObjectiveSql) ![](https://img.shields.io/github/last-commit/braisdom/ObjectiveSql) ![](https://img.shields.io/github/issues/braisdom/ObjectiveSql) ![](https://img.shields.io/github/issues-pr/braisdom/ObjectiveSql) ![](https://img.shields.io/github/license/braisdom/ObjectiveSql) ![](https://img.shields.io/github/forks/braisdom/ObjectiveSql) ![](https://img.shields.io/github/contributors/braisdom/ObjectiveSql)

- [Permazen](https://github.com/permazen/permazen) - Language-natural persistence layer.

   ![](https://img.shields.io/github/stars/permazen/permazen) ![](https://img.shields.io/github/last-commit/permazen/permazen) ![](https://img.shields.io/github/issues/permazen/permazen) ![](https://img.shields.io/github/issues-pr/permazen/permazen) ![](https://img.shields.io/github/license/permazen/permazen) ![](https://img.shields.io/github/forks/permazen/permazen) ![](https://img.shields.io/github/contributors/permazen/permazen)

- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - Simple database and CSV mapper.

   ![](https://img.shields.io/github/stars/arnaudroger/SimpleFlatMapper) ![](https://img.shields.io/github/last-commit/arnaudroger/SimpleFlatMapper) ![](https://img.shields.io/github/issues/arnaudroger/SimpleFlatMapper) ![](https://img.shields.io/github/issues-pr/arnaudroger/SimpleFlatMapper) ![](https://img.shields.io/github/license/arnaudroger/SimpleFlatMapper) ![](https://img.shields.io/github/forks/arnaudroger/SimpleFlatMapper) ![](https://img.shields.io/github/contributors/arnaudroger/SimpleFlatMapper)


### PaaS

_Java platform as a service._

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/) - AWS-based, with support for Tomcat and Jetty.
- [AWS Lambda ![c]](https://aws.amazon.com/lambda/) - Serverless computation.
- [Google Cloud ![c]](https://cloud.google.com) - Google's cloud infrastructure.
- [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
- [Microsoft Azure ![c]](https://azure.microsoft.com/en-us/) - Microsoft's cloud infrastructure.
- [OpenShift ![c]](https://www.openshift.com) - Provides additionally an on-premise solution.

### PDF

_Tools to help with PDF files._

- [Apache FOP](https://xmlgraphics.apache.org/fop/) - Creates PDFs from XSL-FO.
- [Apache PDFBox](https://pdfbox.apache.org) - Toolbox for creating and manipulating PDFs.
- [Dynamic Jasper](http://dynamicjasper.com) - Abstraction layer to JasperReports. (LGPL-3.0-only)
- [DynamicReports](https://github.com/dynamicreports/dynamicreports) - Simplifies JasperReports. (LGPL-3.0-only)

   ![](https://img.shields.io/github/stars/dynamicreports/dynamicreports) ![](https://img.shields.io/github/last-commit/dynamicreports/dynamicreports) ![](https://img.shields.io/github/issues/dynamicreports/dynamicreports) ![](https://img.shields.io/github/issues-pr/dynamicreports/dynamicreports) ![](https://img.shields.io/github/license/dynamicreports/dynamicreports) ![](https://img.shields.io/github/forks/dynamicreports/dynamicreports) ![](https://img.shields.io/github/contributors/dynamicreports/dynamicreports)

- [Eclipse BIRT](https://www.eclipse.org/birt) - Report engine for creating PDF and other formats (DOCX, XLSX, HTML, etc) using Eclipse-based visual editor.
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer. (LGPL-2.1-or-later)

   ![](https://img.shields.io/github/stars/flyingsaucerproject/flyingsaucer) ![](https://img.shields.io/github/last-commit/flyingsaucerproject/flyingsaucer) ![](https://img.shields.io/github/issues/flyingsaucerproject/flyingsaucer) ![](https://img.shields.io/github/issues-pr/flyingsaucerproject/flyingsaucer) ![](https://img.shields.io/github/license/flyingsaucerproject/flyingsaucer) ![](https://img.shields.io/github/forks/flyingsaucerproject/flyingsaucer) ![](https://img.shields.io/github/contributors/flyingsaucerproject/flyingsaucer)

- [iText ![c]](https://itextpdf.com/en) - Creates PDF files programmatically.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine. (LGPL-3.0-only)
- [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf) - Properly supports modern PDF standards based on flyingsaucer and Apache PDFBox.

   ![](https://img.shields.io/github/stars/danfickle/openhtmltopdf) ![](https://img.shields.io/github/last-commit/danfickle/openhtmltopdf) ![](https://img.shields.io/github/issues/danfickle/openhtmltopdf) ![](https://img.shields.io/github/issues-pr/danfickle/openhtmltopdf) ![](https://img.shields.io/github/license/danfickle/openhtmltopdf) ![](https://img.shields.io/github/forks/danfickle/openhtmltopdf) ![](https://img.shields.io/github/contributors/danfickle/openhtmltopdf)

- [OpenPDF](https://github.com/LibrePDF/OpenPDF) - Open-source iText fork. (LGPL-3.0-only & MPL-2.0)

   ![](https://img.shields.io/github/stars/LibrePDF/OpenPDF) ![](https://img.shields.io/github/last-commit/LibrePDF/OpenPDF) ![](https://img.shields.io/github/issues/LibrePDF/OpenPDF) ![](https://img.shields.io/github/issues-pr/LibrePDF/OpenPDF) ![](https://img.shields.io/github/license/LibrePDF/OpenPDF) ![](https://img.shields.io/github/forks/LibrePDF/OpenPDF) ![](https://img.shields.io/github/contributors/LibrePDF/OpenPDF)

- [Tabula](https://github.com/tabulapdf/tabula-java) - Extracts tables from PDF files.

   ![](https://img.shields.io/github/stars/tabulapdf/tabula-java) ![](https://img.shields.io/github/last-commit/tabulapdf/tabula-java) ![](https://img.shields.io/github/issues/tabulapdf/tabula-java) ![](https://img.shields.io/github/issues-pr/tabulapdf/tabula-java) ![](https://img.shields.io/github/license/tabulapdf/tabula-java) ![](https://img.shields.io/github/forks/tabulapdf/tabula-java) ![](https://img.shields.io/github/contributors/tabulapdf/tabula-java)


### Performance analysis

_Tools for performance analysis, profiling and benchmarking._

- [fastThread ![c]](https://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
- [GCeasy ![c]](https://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
- [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler) - Low-overhead, bias-free sampling profiler.

   ![](https://img.shields.io/github/stars/jvm-profiling-tools/honest-profiler) ![](https://img.shields.io/github/last-commit/jvm-profiling-tools/honest-profiler) ![](https://img.shields.io/github/issues/jvm-profiling-tools/honest-profiler) ![](https://img.shields.io/github/issues-pr/jvm-profiling-tools/honest-profiler) ![](https://img.shields.io/github/license/jvm-profiling-tools/honest-profiler) ![](https://img.shields.io/github/forks/jvm-profiling-tools/honest-profiler) ![](https://img.shields.io/github/contributors/jvm-profiling-tools/honest-profiler)

- [jHiccup](https://github.com/giltene/jHiccup) - Logs and records platform JVM stalls.

   ![](https://img.shields.io/github/stars/giltene/jHiccup) ![](https://img.shields.io/github/last-commit/giltene/jHiccup) ![](https://img.shields.io/github/issues/giltene/jHiccup) ![](https://img.shields.io/github/issues-pr/giltene/jHiccup) ![](https://img.shields.io/github/license/giltene/jHiccup) ![](https://img.shields.io/github/forks/giltene/jHiccup) ![](https://img.shields.io/github/contributors/giltene/jHiccup)

- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) - Analyze the JIT compiler optimisations made by the HotSpot JVM.

   ![](https://img.shields.io/github/stars/AdoptOpenJDK/jitwatch) ![](https://img.shields.io/github/last-commit/AdoptOpenJDK/jitwatch) ![](https://img.shields.io/github/issues/AdoptOpenJDK/jitwatch) ![](https://img.shields.io/github/issues-pr/AdoptOpenJDK/jitwatch) ![](https://img.shields.io/github/license/AdoptOpenJDK/jitwatch) ![](https://img.shields.io/github/forks/AdoptOpenJDK/jitwatch) ![](https://img.shields.io/github/contributors/AdoptOpenJDK/jitwatch)

- [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - Harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM. (GPL-2.0 only WITH Classpath-exception-2.0)
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) - Utilities for latency measurement and reporting.

   ![](https://img.shields.io/github/stars/LatencyUtils/LatencyUtils) ![](https://img.shields.io/github/last-commit/LatencyUtils/LatencyUtils) ![](https://img.shields.io/github/issues/LatencyUtils/LatencyUtils) ![](https://img.shields.io/github/issues-pr/LatencyUtils/LatencyUtils) ![](https://img.shields.io/github/license/LatencyUtils/LatencyUtils) ![](https://img.shields.io/github/forks/LatencyUtils/LatencyUtils) ![](https://img.shields.io/github/contributors/LatencyUtils/LatencyUtils)


### Platform

_Frameworks that are suites of multiple libraries encompassing several categories._

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel/) - Byte Code Engineering Library - analyze, create, and manipulate Java class files.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils/) - Easy-to-use wrappers around the Java reflection and introspection APIs.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2/) - Redesign of Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf/) - Bean Scripting Framework - interface to scripting languages, including JSR-223.
- [Chain](http://commons.apache.org/proper/commons-chain/) - Chain of Responsibility pattern implementation.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan/) - Find Class interfaces, methods, fields, and annotations without loading.
- [CLI](http://commons.apache.org/proper/commons-cli/) - Command-line arguments parser.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2/) - Redesign of Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec/) - General encoding/decoding algorithms, e.g. phonetic, base64 or URL.
- [Collections](http://commons.apache.org/proper/commons-collections/) - Extends or augments the Java Collections Framework.
- [Compress](http://commons.apache.org/proper/commons-compress/) - Defines an API for working with tar, zip and bzip2 files.
- [Configuration](http://commons.apache.org/proper/commons-configuration/) - Reading of configuration/preferences files in various formats.
- [Convert](http://commons.apache.org/sandbox/commons-convert/) - Commons-Convert aims to provide a single library dedicated to the task of converting an object of one type to another.
- [CSV](http://commons.apache.org/proper/commons-csv/) - Component for reading and writing comma separated value files.
- [Daemon](http://commons.apache.org/proper/commons-daemon/) - Alternative invocation mechanism for unix-daemon-like java code.
- [DBCP](http://commons.apache.org/proper/commons-dbcp/) - Database connection pooling services.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils/) - JDBC helper library.
- [Digester](http://commons.apache.org/proper/commons-digester/) - XML-to-Java-object mapping utility.
- [Email](http://commons.apache.org/proper/commons-email/) - Library for sending e-mail from Java.
- [Exec](http://commons.apache.org/proper/commons-exec/) - API for dealing with external process execution and environment management in Java.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload/) - File upload capability for your servlets and web applications.
- [Finder](http://commons.apache.org/sandbox/commons-finder/) - Java library inspired by the UNIX find command.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile/) - Java library for working with flat data structures.
- [Functor](http://commons.apache.org/proper/commons-functor/) - Function that can be manipulated as an object, or an object representing a single, generic function.
- [Graph](http://commons.apache.org/sandbox/commons-graph/) - General purpose graph APIs and algorithms.
- [I18n](http://commons.apache.org/sandbox/commons-i18n/) - Adds the feature of localized message bundles that consist of one or many localized texts that belong together.
- [Id](http://commons.apache.org/sandbox/commons-id/) - Id is a component used to generate identifiers.
- [Imaging](http://commons.apache.org/proper/commons-imaging/) - Image library.
- [IO](http://commons.apache.org/proper/commons-io/) - Collection of I/O utilities.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow/) - Continuation implementation to capture the state of the application.
- [JCI](http://commons.apache.org/proper/commons-jci/) - Java Compiler Interface.
- [JCS](http://commons.apache.org/proper/commons-jcs/) - Java Caching System.
- [Jelly](http://commons.apache.org/proper/commons-jelly/) - XML based scripting and processing engine.
- [Jexl](http://commons.apache.org/proper/commons-jexl/) - Expression language which extends the Expression Language of the JSTL.
- [JNet](http://commons.apache.org/sandbox/commons-jnet/) - JNet allows to use dynamically register url stream handlers through the java.net API.
- [JXPath](http://commons.apache.org/proper/commons-jxpath/) - Utilities for manipulating Java Beans using the XPath syntax.
- [Lang](http://commons.apache.org/proper/commons-lang/) - Provides extra functionality for classes in java.lang.
- [Logging](https://commons.apache.org/proper/commons-logging/) - Wrapper around a variety of logging API implementations.
- [Math](http://commons.apache.org/proper/commons-math/) - Lightweight, self-contained mathematics and statistics components.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring/) - Monitoring aims to provide a simple but extensible monitoring solution for Java applications.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla/) - Nabla provides automatic differentiation classes that can generate derivative of any function implemented in the Java language.
- [Net](http://commons.apache.org/proper/commons-net/) - Collection of network utilities and protocol implementations.
- [OGNL](http://commons.apache.org/proper/commons-ognl/) - Object-graph navigation language.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp/) - Interface to signing and verifying data using OpenPGP.
- [Performance](http://commons.apache.org/sandbox/commons-performance/) - Small framework for microbenchmark clients, with implementations for Commons DBCP and Pool.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline/) - Provides a set of pipeline utilities designed around work queues that run in parallel to sequentially process data objects.
- [Pool](http://commons.apache.org/proper/commons-pool/) - Generic object pooling component.
- [Proxy](http://commons.apache.org/proper/commons-proxy/) - Library for creating dynamic proxies.
- [RDF](https://commons.apache.org/proper/commons-rdf/) - Common implementation of RDF 1.1 that could be implemented by systems on the JVM.
- [RNG](https://commons.apache.org/proper/commons-rng/) - Commons Rng provides implementations of pseudo-random numbers generators.
- [SCXML](http://commons.apache.org/proper/commons-scxml/) - Implementation of the State Chart XML specification aimed at creating and maintaining a Java SCXML engine.
- [Validator](http://commons.apache.org/proper/commons-validator/) - Framework to define validators and validation rules in an xml file.
- [VFS](http://commons.apache.org/proper/commons-vfs/) - Virtual File System component for treating files, FTP, SMB, ZIP and such like as a single logical file system.
- [Weaver](http://commons.apache.org/proper/commons-weaver/) - Provides an easy way to enhance (weave) compiled bytecode.

#### Other

- [CUBA Platform](https://www.cuba-platform.com/) - High-level framework for developing enterprise applications with a rich web interface, based on Spring, EclipseLink and Vaadin.
- [Light-4J](https://github.com/networknt/light-4j/) - Fast, lightweight and productive microservices framework with built-in [security](https://github.com/networknt/light-oauth2/).

   ![](https://img.shields.io/github/stars/networknt/light-4j/) ![](https://img.shields.io/github/last-commit/networknt/light-4j/) ![](https://img.shields.io/github/issues/networknt/light-4j/) ![](https://img.shields.io/github/issues-pr/networknt/light-4j/) ![](https://img.shields.io/github/license/networknt/light-4j/) ![](https://img.shields.io/github/forks/networknt/light-4j/) ![](https://img.shields.io/github/contributors/networknt/light-4j/)

- [Orienteer](https://github.com/OrienteerBAP/Orienteer/) - Open-source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications.

   ![](https://img.shields.io/github/stars/OrienteerBAP/Orienteer/) ![](https://img.shields.io/github/last-commit/OrienteerBAP/Orienteer/) ![](https://img.shields.io/github/issues/OrienteerBAP/Orienteer/) ![](https://img.shields.io/github/issues-pr/OrienteerBAP/Orienteer/) ![](https://img.shields.io/github/license/OrienteerBAP/Orienteer/) ![](https://img.shields.io/github/forks/OrienteerBAP/Orienteer/) ![](https://img.shields.io/github/contributors/OrienteerBAP/Orienteer/)

- [Spring](https://spring.io/projects/) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Processes

_Libraries that help the management of operating system processes._

- [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) - Convenient API around Apache Commons Exec.

   ![](https://img.shields.io/github/stars/vorburger/ch.vorburger.exec) ![](https://img.shields.io/github/last-commit/vorburger/ch.vorburger.exec) ![](https://img.shields.io/github/issues/vorburger/ch.vorburger.exec) ![](https://img.shields.io/github/issues-pr/vorburger/ch.vorburger.exec) ![](https://img.shields.io/github/license/vorburger/ch.vorburger.exec) ![](https://img.shields.io/github/forks/vorburger/ch.vorburger.exec) ![](https://img.shields.io/github/contributors/vorburger/ch.vorburger.exec)

- [zt-exec](https://github.com/zeroturnaround/zt-exec) - Provides a unified API to Apache Commons Exec and ProcessBuilder.

   ![](https://img.shields.io/github/stars/zeroturnaround/zt-exec) ![](https://img.shields.io/github/last-commit/zeroturnaround/zt-exec) ![](https://img.shields.io/github/issues/zeroturnaround/zt-exec) ![](https://img.shields.io/github/issues-pr/zeroturnaround/zt-exec) ![](https://img.shields.io/github/license/zeroturnaround/zt-exec) ![](https://img.shields.io/github/forks/zeroturnaround/zt-exec) ![](https://img.shields.io/github/contributors/zeroturnaround/zt-exec)

- [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) - Stops processes started from Java or the system processes via PID.

   ![](https://img.shields.io/github/stars/zeroturnaround/zt-process-killer) ![](https://img.shields.io/github/last-commit/zeroturnaround/zt-process-killer) ![](https://img.shields.io/github/issues/zeroturnaround/zt-process-killer) ![](https://img.shields.io/github/issues-pr/zeroturnaround/zt-process-killer) ![](https://img.shields.io/github/license/zeroturnaround/zt-process-killer) ![](https://img.shields.io/github/forks/zeroturnaround/zt-process-killer) ![](https://img.shields.io/github/contributors/zeroturnaround/zt-process-killer)


### Reactive libraries

_Libraries for developing reactive applications._

- [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) - Provides a standard for asynchronous stream processing with non-blocking backpressure.

   ![](https://img.shields.io/github/stars/reactive-streams/reactive-streams-jvm) ![](https://img.shields.io/github/last-commit/reactive-streams/reactive-streams-jvm) ![](https://img.shields.io/github/issues/reactive-streams/reactive-streams-jvm) ![](https://img.shields.io/github/issues-pr/reactive-streams/reactive-streams-jvm) ![](https://img.shields.io/github/license/reactive-streams/reactive-streams-jvm) ![](https://img.shields.io/github/forks/reactive-streams/reactive-streams-jvm) ![](https://img.shields.io/github/contributors/reactive-streams/reactive-streams-jvm)

- [Reactor](https://github.com/reactor/reactor-core) - Library for building reactive fast-data applications.

   ![](https://img.shields.io/github/stars/reactor/reactor-core) ![](https://img.shields.io/github/last-commit/reactor/reactor-core) ![](https://img.shields.io/github/issues/reactor/reactor-core) ![](https://img.shields.io/github/issues-pr/reactor/reactor-core) ![](https://img.shields.io/github/license/reactor/reactor-core) ![](https://img.shields.io/github/forks/reactor/reactor-core) ![](https://img.shields.io/github/contributors/reactor/reactor-core)

- [RxJava](https://github.com/ReactiveX/RxJava) - Allows for composing asynchronous and event-based programs using observable sequences.

   ![](https://img.shields.io/github/stars/ReactiveX/RxJava) ![](https://img.shields.io/github/last-commit/ReactiveX/RxJava) ![](https://img.shields.io/github/issues/ReactiveX/RxJava) ![](https://img.shields.io/github/issues-pr/ReactiveX/RxJava) ![](https://img.shields.io/github/license/ReactiveX/RxJava) ![](https://img.shields.io/github/forks/ReactiveX/RxJava) ![](https://img.shields.io/github/contributors/ReactiveX/RxJava)

- [vert.x](https://vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

_Frameworks specifically for creating RESTful services._

- [Dropwizard](https://github.com/dropwizard/dropwizard) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.

   ![](https://img.shields.io/github/stars/dropwizard/dropwizard) ![](https://img.shields.io/github/last-commit/dropwizard/dropwizard) ![](https://img.shields.io/github/issues/dropwizard/dropwizard) ![](https://img.shields.io/github/issues-pr/dropwizard/dropwizard) ![](https://img.shields.io/github/license/dropwizard/dropwizard) ![](https://img.shields.io/github/forks/dropwizard/dropwizard) ![](https://img.shields.io/github/contributors/dropwizard/dropwizard)

- [Elide](https://elide.io) - Opinionated framework for JSON- or GraphQL-APIs based on a JPA data model.
- [Jersey](https://jersey.github.io) - JAX-RS reference implementation.
- [Microserver](https://github.com/aol/micro-server) - Convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.

   ![](https://img.shields.io/github/stars/aol/micro-server) ![](https://img.shields.io/github/last-commit/aol/micro-server) ![](https://img.shields.io/github/issues/aol/micro-server) ![](https://img.shields.io/github/issues-pr/aol/micro-server) ![](https://img.shields.io/github/license/aol/micro-server) ![](https://img.shields.io/github/forks/aol/micro-server) ![](https://img.shields.io/github/contributors/aol/micro-server)

- [Rapidoid](https://www.rapidoid.org) - Simple, secure and extremely fast framework consisting of an embedded HTTP server, GUI components and dependency injection.
- [rest.li](https://github.com/linkedin/rest.li) - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling.

   ![](https://img.shields.io/github/stars/linkedin/rest.li) ![](https://img.shields.io/github/last-commit/linkedin/rest.li) ![](https://img.shields.io/github/issues/linkedin/rest.li) ![](https://img.shields.io/github/issues-pr/linkedin/rest.li) ![](https://img.shields.io/github/license/linkedin/rest.li) ![](https://img.shields.io/github/forks/linkedin/rest.li) ![](https://img.shields.io/github/contributors/linkedin/rest.li)

- [RESTEasy](https://resteasy.github.io) - Fully certified and portable implementation of the JAX-RS specification.
- [RestExpress](https://github.com/RestExpress/RestExpress) - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance.

   ![](https://img.shields.io/github/stars/RestExpress/RestExpress) ![](https://img.shields.io/github/last-commit/RestExpress/RestExpress) ![](https://img.shields.io/github/issues/RestExpress/RestExpress) ![](https://img.shields.io/github/issues-pr/RestExpress/RestExpress) ![](https://img.shields.io/github/license/RestExpress/RestExpress) ![](https://img.shields.io/github/forks/RestExpress/RestExpress) ![](https://img.shields.io/github/contributors/RestExpress/RestExpress)

- [Restlet Framework](https://github.com/restlet/restlet-framework-java) - Pioneering framework with powerful routing and filtering capabilities, and a unified client and server API.

   ![](https://img.shields.io/github/stars/restlet/restlet-framework-java) ![](https://img.shields.io/github/last-commit/restlet/restlet-framework-java) ![](https://img.shields.io/github/issues/restlet/restlet-framework-java) ![](https://img.shields.io/github/issues-pr/restlet/restlet-framework-java) ![](https://img.shields.io/github/license/restlet/restlet-framework-java) ![](https://img.shields.io/github/forks/restlet/restlet-framework-java) ![](https://img.shields.io/github/contributors/restlet/restlet-framework-java)

- [Spark](http://sparkjava.com) - Sinatra inspired framework.
- [Crnk](http://www.crnk.io) - Implementation of the JSON API specification to build resource-oriented REST endpoints with sorting, filtering, paging, linking, object graphs, type-safety, bulk updates, integrations and more.
- [springdoc-openapi](https://github.com/springdoc/springdoc-openapi) - Automates the generation of API documentation using Spring Boot projects.

   ![](https://img.shields.io/github/stars/springdoc/springdoc-openapi) ![](https://img.shields.io/github/last-commit/springdoc/springdoc-openapi) ![](https://img.shields.io/github/issues/springdoc/springdoc-openapi) ![](https://img.shields.io/github/issues-pr/springdoc/springdoc-openapi) ![](https://img.shields.io/github/license/springdoc/springdoc-openapi) ![](https://img.shields.io/github/forks/springdoc/springdoc-openapi) ![](https://img.shields.io/github/contributors/springdoc/springdoc-openapi)

- [Swagger](https://swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

_Libraries for scientific computing, analysis and visualization._

- [BioJava](https://biojava.org/) - Facilitates processing biological data by providing algorithms, file format parsers, sequencing and 3D visualization commonly used in bioinformatics.
- [Chart-FX](https://github.com/GSI-CS-CO/chart-fx) - Scientific charting library with focus on performance optimised real-time data visualisation at 25 Hz update rates for large data sets.

   ![](https://img.shields.io/github/stars/GSI-CS-CO/chart-fx) ![](https://img.shields.io/github/last-commit/GSI-CS-CO/chart-fx) ![](https://img.shields.io/github/issues/GSI-CS-CO/chart-fx) ![](https://img.shields.io/github/issues-pr/GSI-CS-CO/chart-fx) ![](https://img.shields.io/github/license/GSI-CS-CO/chart-fx) ![](https://img.shields.io/github/forks/GSI-CS-CO/chart-fx) ![](https://img.shields.io/github/contributors/GSI-CS-CO/chart-fx)

- [DataMelt](https://jwork.org/dmelt/) - Environment for scientific computation, data analysis and data visualization. (GPL-3.0-or-later)
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) - Modular, light and easy graph framework for theoretic algorithms.

   ![](https://img.shields.io/github/stars/Erdos-Graph-Framework/Erdos) ![](https://img.shields.io/github/last-commit/Erdos-Graph-Framework/Erdos) ![](https://img.shields.io/github/issues/Erdos-Graph-Framework/Erdos) ![](https://img.shields.io/github/issues-pr/Erdos-Graph-Framework/Erdos) ![](https://img.shields.io/github/license/Erdos-Graph-Framework/Erdos) ![](https://img.shields.io/github/forks/Erdos-Graph-Framework/Erdos) ![](https://img.shields.io/github/contributors/Erdos-Graph-Framework/Erdos)

- [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
- [JFreeChart](http://www.jfree.org/jfreechart/) - 2D chart library for Swing, JavaFX and server-side applications. (LGPL-2.1-only)
- [JGraphT](https://github.com/jgrapht/jgrapht) - Graph library that provides mathematical graph-theory objects and algorithms.

   ![](https://img.shields.io/github/stars/jgrapht/jgrapht) ![](https://img.shields.io/github/last-commit/jgrapht/jgrapht) ![](https://img.shields.io/github/issues/jgrapht/jgrapht) ![](https://img.shields.io/github/issues-pr/jgrapht/jgrapht) ![](https://img.shields.io/github/license/jgrapht/jgrapht) ![](https://img.shields.io/github/forks/jgrapht/jgrapht) ![](https://img.shields.io/github/contributors/jgrapht/jgrapht)

- [JGraphX](https://github.com/jgraph/jgraphx) - Library for visualizing (mainly Swing) and interacting with node-edge graphs.

   ![](https://img.shields.io/github/stars/jgraph/jgraphx) ![](https://img.shields.io/github/last-commit/jgraph/jgraphx) ![](https://img.shields.io/github/issues/jgraph/jgraphx) ![](https://img.shields.io/github/issues-pr/jgraph/jgraphx) ![](https://img.shields.io/github/license/jgraph/jgraphx) ![](https://img.shields.io/github/forks/jgraph/jgraphx) ![](https://img.shields.io/github/contributors/jgraph/jgraphx)

- [LogicNG](https://github.com/logic-ng/LogicNG) - Library for creating, manipulating and solving Boolean and Pseudo-Boolean formulas.

   ![](https://img.shields.io/github/stars/logic-ng/LogicNG) ![](https://img.shields.io/github/last-commit/logic-ng/LogicNG) ![](https://img.shields.io/github/issues/logic-ng/LogicNG) ![](https://img.shields.io/github/issues-pr/logic-ng/LogicNG) ![](https://img.shields.io/github/license/logic-ng/LogicNG) ![](https://img.shields.io/github/forks/logic-ng/LogicNG) ![](https://img.shields.io/github/contributors/logic-ng/LogicNG)

- [Mines Java Toolkit](https://github.com/MinesJTK/jtk) - Library for geophysical scientific computation, visualization and digital signal analysis.

   ![](https://img.shields.io/github/stars/MinesJTK/jtk) ![](https://img.shields.io/github/last-commit/MinesJTK/jtk) ![](https://img.shields.io/github/issues/MinesJTK/jtk) ![](https://img.shields.io/github/issues-pr/MinesJTK/jtk) ![](https://img.shields.io/github/license/MinesJTK/jtk) ![](https://img.shields.io/github/forks/MinesJTK/jtk) ![](https://img.shields.io/github/contributors/MinesJTK/jtk)

- [Morpheus](https://github.com/zavtech/morpheus-core) - Provides a versatile two-dimensional memory efficient tabular data structure called a DataFrame to enable efficient in-memory analytics for scientific computing on the JVM.

   ![](https://img.shields.io/github/stars/zavtech/morpheus-core) ![](https://img.shields.io/github/last-commit/zavtech/morpheus-core) ![](https://img.shields.io/github/issues/zavtech/morpheus-core) ![](https://img.shields.io/github/issues-pr/zavtech/morpheus-core) ![](https://img.shields.io/github/license/zavtech/morpheus-core) ![](https://img.shields.io/github/forks/zavtech/morpheus-core) ![](https://img.shields.io/github/contributors/zavtech/morpheus-core)

- [Orson-Charts](https://github.com/jfree/orson-charts) - Generates a wide variety of 3D charts that can be displayed with Swing and JavaFX or exported to PDF, SVG, PNG and JPEG. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/jfree/orson-charts) ![](https://img.shields.io/github/last-commit/jfree/orson-charts) ![](https://img.shields.io/github/issues/jfree/orson-charts) ![](https://img.shields.io/github/issues-pr/jfree/orson-charts) ![](https://img.shields.io/github/license/jfree/orson-charts) ![](https://img.shields.io/github/forks/jfree/orson-charts) ![](https://img.shields.io/github/contributors/jfree/orson-charts)

- [Tablesaw](https://github.com/jtablesaw/tablesaw) - Includes a data-frame, an embedded column store, and hundreds of methods to transform, summarize, or filter data.

   ![](https://img.shields.io/github/stars/jtablesaw/tablesaw) ![](https://img.shields.io/github/last-commit/jtablesaw/tablesaw) ![](https://img.shields.io/github/issues/jtablesaw/tablesaw) ![](https://img.shields.io/github/issues-pr/jtablesaw/tablesaw) ![](https://img.shields.io/github/license/jtablesaw/tablesaw) ![](https://img.shields.io/github/forks/jtablesaw/tablesaw) ![](https://img.shields.io/github/contributors/jtablesaw/tablesaw)

- [XChart](https://github.com/knowm/XChart) - Light-weight library for plotting data. Many customizable chart types are available.

   ![](https://img.shields.io/github/stars/knowm/XChart) ![](https://img.shields.io/github/last-commit/knowm/XChart) ![](https://img.shields.io/github/issues/knowm/XChart) ![](https://img.shields.io/github/issues-pr/knowm/XChart) ![](https://img.shields.io/github/license/knowm/XChart) ![](https://img.shields.io/github/forks/knowm/XChart) ![](https://img.shields.io/github/contributors/knowm/XChart)


### Search

_Engines that index documents for search and analysis._

- [Apache Lucene](https://lucene.apache.org) - High-performance, full-featured, cross-platform, text search engine library.
- [Apache Solr](https://lucene.apache.org/solr/) - Enterprise search engine optimized for high-volume traffic.
- [Elasticsearch](https://www.elastic.co) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.
- [Indexer4j](https://github.com/haeungun/indexer4j) - Simple and light full text indexing and searching library.

   ![](https://img.shields.io/github/stars/haeungun/indexer4j) ![](https://img.shields.io/github/last-commit/haeungun/indexer4j) ![](https://img.shields.io/github/issues/haeungun/indexer4j) ![](https://img.shields.io/github/issues-pr/haeungun/indexer4j) ![](https://img.shields.io/github/license/haeungun/indexer4j) ![](https://img.shields.io/github/forks/haeungun/indexer4j) ![](https://img.shields.io/github/contributors/haeungun/indexer4j)


### Security

_Libraries that handle security, authentication, authorization or session management._

- [Apache Shiro](https://shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.
- [Cryptomator](https://cryptomator.org) - Multiplatform, transparent, client-side encryption of files in the cloud. (GPL-3.0-only)
- [Hdiv](https://github.com/hdiv/hdiv) - Runtime application that repels application security risks included in the OWASP Top 10, including SQL injection, cross-site scripting, cross-site request forgery, data tampering, and brute force attacks.

   ![](https://img.shields.io/github/stars/hdiv/hdiv) ![](https://img.shields.io/github/last-commit/hdiv/hdiv) ![](https://img.shields.io/github/issues/hdiv/hdiv) ![](https://img.shields.io/github/issues-pr/hdiv/hdiv) ![](https://img.shields.io/github/license/hdiv/hdiv) ![](https://img.shields.io/github/forks/hdiv/hdiv) ![](https://img.shields.io/github/contributors/hdiv/hdiv)

- [jjwt](https://github.com/jwtk/jjwt) - JSON web token for Java and Android.

   ![](https://img.shields.io/github/stars/jwtk/jjwt) ![](https://img.shields.io/github/last-commit/jwtk/jjwt) ![](https://img.shields.io/github/issues/jwtk/jjwt) ![](https://img.shields.io/github/issues-pr/jwtk/jjwt) ![](https://img.shields.io/github/license/jwtk/jjwt) ![](https://img.shields.io/github/forks/jwtk/jjwt) ![](https://img.shields.io/github/contributors/jwtk/jjwt)

- [jwt-java](https://github.com/BastiaanJansen/jwt-java) - Easily create and parse JSON Web Tokens and create customized JWT validators using a fluent API.

   ![](https://img.shields.io/github/stars/BastiaanJansen/jwt-java) ![](https://img.shields.io/github/last-commit/BastiaanJansen/jwt-java) ![](https://img.shields.io/github/issues/BastiaanJansen/jwt-java) ![](https://img.shields.io/github/issues-pr/BastiaanJansen/jwt-java) ![](https://img.shields.io/github/license/BastiaanJansen/jwt-java) ![](https://img.shields.io/github/forks/BastiaanJansen/jwt-java) ![](https://img.shields.io/github/contributors/BastiaanJansen/jwt-java)

- [Jwks RSA](https://github.com/auth0/jwks-rsa-java) - JSON Web Key Set parser.

   ![](https://img.shields.io/github/stars/auth0/jwks-rsa-java) ![](https://img.shields.io/github/last-commit/auth0/jwks-rsa-java) ![](https://img.shields.io/github/issues/auth0/jwks-rsa-java) ![](https://img.shields.io/github/issues-pr/auth0/jwks-rsa-java) ![](https://img.shields.io/github/license/auth0/jwks-rsa-java) ![](https://img.shields.io/github/forks/auth0/jwks-rsa-java) ![](https://img.shields.io/github/contributors/auth0/jwks-rsa-java)

- [Kalium](https://github.com/abstractj/kalium) - Binding for the Networking and Cryptography (NaCl) library.

   ![](https://img.shields.io/github/stars/abstractj/kalium) ![](https://img.shields.io/github/last-commit/abstractj/kalium) ![](https://img.shields.io/github/issues/abstractj/kalium) ![](https://img.shields.io/github/issues-pr/abstractj/kalium) ![](https://img.shields.io/github/license/abstractj/kalium) ![](https://img.shields.io/github/forks/abstractj/kalium) ![](https://img.shields.io/github/contributors/abstractj/kalium)

- [Keycloak](https://www.keycloak.org) - Integrated SSO and IDM for browser apps and RESTful web services.
- [Keywhiz](https://github.com/square/keywhiz) - System for distributing and managing secrets.

   ![](https://img.shields.io/github/stars/square/keywhiz) ![](https://img.shields.io/github/last-commit/square/keywhiz) ![](https://img.shields.io/github/issues/square/keywhiz) ![](https://img.shields.io/github/issues-pr/square/keywhiz) ![](https://img.shields.io/github/license/square/keywhiz) ![](https://img.shields.io/github/forks/square/keywhiz) ![](https://img.shields.io/github/contributors/square/keywhiz)

- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) - Advanced password strength estimation.

   ![](https://img.shields.io/github/stars/GoSimpleLLC/nbvcxz) ![](https://img.shields.io/github/last-commit/GoSimpleLLC/nbvcxz) ![](https://img.shields.io/github/issues/GoSimpleLLC/nbvcxz) ![](https://img.shields.io/github/issues-pr/GoSimpleLLC/nbvcxz) ![](https://img.shields.io/github/license/GoSimpleLLC/nbvcxz) ![](https://img.shields.io/github/forks/GoSimpleLLC/nbvcxz) ![](https://img.shields.io/github/contributors/GoSimpleLLC/nbvcxz)

- [OACC](http://oaccframework.org) - Provides permission-based authorization services.
- [OTP-Java](https://github.com/BastiaanJansen/OTP-Java) - One-time password generator library according to RFC 4226 (HOTP) and RFC 6238 (TOTP).

   ![](https://img.shields.io/github/stars/BastiaanJansen/OTP-Java) ![](https://img.shields.io/github/last-commit/BastiaanJansen/OTP-Java) ![](https://img.shields.io/github/issues/BastiaanJansen/OTP-Java) ![](https://img.shields.io/github/issues-pr/BastiaanJansen/OTP-Java) ![](https://img.shields.io/github/license/BastiaanJansen/OTP-Java) ![](https://img.shields.io/github/forks/BastiaanJansen/OTP-Java) ![](https://img.shields.io/github/contributors/BastiaanJansen/OTP-Java)

- [pac4j](https://github.com/pac4j/pac4j) - Security engine.

   ![](https://img.shields.io/github/stars/pac4j/pac4j) ![](https://img.shields.io/github/last-commit/pac4j/pac4j) ![](https://img.shields.io/github/issues/pac4j/pac4j) ![](https://img.shields.io/github/issues-pr/pac4j/pac4j) ![](https://img.shields.io/github/license/pac4j/pac4j) ![](https://img.shields.io/github/forks/pac4j/pac4j) ![](https://img.shields.io/github/contributors/pac4j/pac4j)

- [Password4j](https://github.com/Password4j/password4j) - User-friendly cryptographic library that supports Argon2, Bcrypt, Scrypt, PBKDF2 and various other cryptographic hash functions.

   ![](https://img.shields.io/github/stars/Password4j/password4j) ![](https://img.shields.io/github/last-commit/Password4j/password4j) ![](https://img.shields.io/github/issues/Password4j/password4j) ![](https://img.shields.io/github/issues-pr/Password4j/password4j) ![](https://img.shields.io/github/license/Password4j/password4j) ![](https://img.shields.io/github/forks/Password4j/password4j) ![](https://img.shields.io/github/contributors/Password4j/password4j)

- [SecurityBuilder](https://github.com/tersesystems/securitybuilder) - Fluent Builder API for JCA and JSSE classes and especially X.509 certificates.

   ![](https://img.shields.io/github/stars/tersesystems/securitybuilder) ![](https://img.shields.io/github/last-commit/tersesystems/securitybuilder) ![](https://img.shields.io/github/issues/tersesystems/securitybuilder) ![](https://img.shields.io/github/issues-pr/tersesystems/securitybuilder) ![](https://img.shields.io/github/license/tersesystems/securitybuilder) ![](https://img.shields.io/github/forks/tersesystems/securitybuilder) ![](https://img.shields.io/github/contributors/tersesystems/securitybuilder)

- [SSLContext-Kickstart](https://github.com/Hakky54/sslcontext-kickstart) - High-level SSL context builder for configuring HTTP clients with SSL/TLS.

   ![](https://img.shields.io/github/stars/Hakky54/sslcontext-kickstart) ![](https://img.shields.io/github/last-commit/Hakky54/sslcontext-kickstart) ![](https://img.shields.io/github/issues/Hakky54/sslcontext-kickstart) ![](https://img.shields.io/github/issues-pr/Hakky54/sslcontext-kickstart) ![](https://img.shields.io/github/license/Hakky54/sslcontext-kickstart) ![](https://img.shields.io/github/forks/Hakky54/sslcontext-kickstart) ![](https://img.shields.io/github/contributors/Hakky54/sslcontext-kickstart)

- [Themis](https://github.com/cossacklabs/themis) - Multi-platform high-level cryptographic library provides easy-to-use encryption for protecting sensitive data: secure messaging with forward secrecy, secure data storage (AES256GCM); suits for building end-to-end encrypted applications.

   ![](https://img.shields.io/github/stars/cossacklabs/themis) ![](https://img.shields.io/github/last-commit/cossacklabs/themis) ![](https://img.shields.io/github/issues/cossacklabs/themis) ![](https://img.shields.io/github/issues-pr/cossacklabs/themis) ![](https://img.shields.io/github/license/cossacklabs/themis) ![](https://img.shields.io/github/forks/cossacklabs/themis) ![](https://img.shields.io/github/contributors/cossacklabs/themis)

- [Tink](https://github.com/google/tink) - Provides a simple and misuse-proof API for common cryptographic tasks.

   ![](https://img.shields.io/github/stars/google/tink) ![](https://img.shields.io/github/last-commit/google/tink) ![](https://img.shields.io/github/issues/google/tink) ![](https://img.shields.io/github/issues-pr/google/tink) ![](https://img.shields.io/github/license/google/tink) ![](https://img.shields.io/github/forks/google/tink) ![](https://img.shields.io/github/contributors/google/tink)


### Serialization

_Libraries that handle serialization with high efficiency._

- [FlatBuffers](https://github.com/google/flatbuffers) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it.

   ![](https://img.shields.io/github/stars/google/flatbuffers) ![](https://img.shields.io/github/last-commit/google/flatbuffers) ![](https://img.shields.io/github/issues/google/flatbuffers) ![](https://img.shields.io/github/issues-pr/google/flatbuffers) ![](https://img.shields.io/github/license/google/flatbuffers) ![](https://img.shields.io/github/forks/google/flatbuffers) ![](https://img.shields.io/github/contributors/google/flatbuffers)

- [FST](https://github.com/RuedigerMoeller/fast-serialization) - JDK-compatible, high-performance object graph serialization.

   ![](https://img.shields.io/github/stars/RuedigerMoeller/fast-serialization) ![](https://img.shields.io/github/last-commit/RuedigerMoeller/fast-serialization) ![](https://img.shields.io/github/issues/RuedigerMoeller/fast-serialization) ![](https://img.shields.io/github/issues-pr/RuedigerMoeller/fast-serialization) ![](https://img.shields.io/github/license/RuedigerMoeller/fast-serialization) ![](https://img.shields.io/github/forks/RuedigerMoeller/fast-serialization) ![](https://img.shields.io/github/contributors/RuedigerMoeller/fast-serialization)

- [Kryo](https://github.com/EsotericSoftware/kryo) - Fast and efficient object graph serialization framework.

   ![](https://img.shields.io/github/stars/EsotericSoftware/kryo) ![](https://img.shields.io/github/last-commit/EsotericSoftware/kryo) ![](https://img.shields.io/github/issues/EsotericSoftware/kryo) ![](https://img.shields.io/github/issues-pr/EsotericSoftware/kryo) ![](https://img.shields.io/github/license/EsotericSoftware/kryo) ![](https://img.shields.io/github/forks/EsotericSoftware/kryo) ![](https://img.shields.io/github/contributors/EsotericSoftware/kryo)

- [MessagePack](https://github.com/msgpack/msgpack-java) - Efficient binary serialization format.

   ![](https://img.shields.io/github/stars/msgpack/msgpack-java) ![](https://img.shields.io/github/last-commit/msgpack/msgpack-java) ![](https://img.shields.io/github/issues/msgpack/msgpack-java) ![](https://img.shields.io/github/issues-pr/msgpack/msgpack-java) ![](https://img.shields.io/github/license/msgpack/msgpack-java) ![](https://img.shields.io/github/forks/msgpack/msgpack-java) ![](https://img.shields.io/github/contributors/msgpack/msgpack-java)

- [PHP Serializer](https://github.com/marcospassos/java-php-serializer) - Serializing objects in the PHP serialization format.

   ![](https://img.shields.io/github/stars/marcospassos/java-php-serializer) ![](https://img.shields.io/github/last-commit/marcospassos/java-php-serializer) ![](https://img.shields.io/github/issues/marcospassos/java-php-serializer) ![](https://img.shields.io/github/issues-pr/marcospassos/java-php-serializer) ![](https://img.shields.io/github/license/marcospassos/java-php-serializer) ![](https://img.shields.io/github/forks/marcospassos/java-php-serializer) ![](https://img.shields.io/github/contributors/marcospassos/java-php-serializer)


### Server

_Servers specifically used to deploy applications._

- [Apache Tomcat](https://tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
- [Apache TomEE](https://tomee.apache.org) - Tomcat plus Java EE.
- [Jetty](https://www.eclipse.org/jetty/) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server.

   ![](https://img.shields.io/github/stars/NanoHttpd/nanohttpd) ![](https://img.shields.io/github/last-commit/NanoHttpd/nanohttpd) ![](https://img.shields.io/github/issues/NanoHttpd/nanohttpd) ![](https://img.shields.io/github/issues-pr/NanoHttpd/nanohttpd) ![](https://img.shields.io/github/license/NanoHttpd/nanohttpd) ![](https://img.shields.io/github/forks/NanoHttpd/nanohttpd) ![](https://img.shields.io/github/contributors/NanoHttpd/nanohttpd)

- [WildFly](https://www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support. (LGPL-2.1-only)

### Template Engine

_Tools that substitute expressions in a template._

- [Freemarker](https://freemarker.apache.org) - Library to generate text output (HTML web pages, e-mails, configuration files, source code, etc.) based on templates and changing data.
- [Handlebars.java](https://jknack.github.io/handlebars.java/) - Logicless and semantic Mustache templates.
- [Jade4J](https://github.com/neuland/jade4j) - Implementation of Pug (formerly known as Jade).

   ![](https://img.shields.io/github/stars/neuland/jade4j) ![](https://img.shields.io/github/last-commit/neuland/jade4j) ![](https://img.shields.io/github/issues/neuland/jade4j) ![](https://img.shields.io/github/issues-pr/neuland/jade4j) ![](https://img.shields.io/github/license/neuland/jade4j) ![](https://img.shields.io/github/forks/neuland/jade4j) ![](https://img.shields.io/github/contributors/neuland/jade4j)

- [Jamal](https://github.com/verhas/jamal) - Extendable template engine embedded into Maven/JavaDoc, supporting multiple extensions (Groovy, Ruby, JavaScript, JShell, PlantUml) with support for snippet handling.

   ![](https://img.shields.io/github/stars/verhas/jamal) ![](https://img.shields.io/github/last-commit/verhas/jamal) ![](https://img.shields.io/github/issues/verhas/jamal) ![](https://img.shields.io/github/issues-pr/verhas/jamal) ![](https://img.shields.io/github/license/verhas/jamal) ![](https://img.shields.io/github/forks/verhas/jamal) ![](https://img.shields.io/github/contributors/verhas/jamal)

- [jte](https://github.com/casid/jte) - Compiles to classes, and uses an easy syntax, several features to make development easier and provides fast execution and a small footprint.

   ![](https://img.shields.io/github/stars/casid/jte) ![](https://img.shields.io/github/last-commit/casid/jte) ![](https://img.shields.io/github/issues/casid/jte) ![](https://img.shields.io/github/issues-pr/casid/jte) ![](https://img.shields.io/github/license/casid/jte) ![](https://img.shields.io/github/forks/casid/jte) ![](https://img.shields.io/github/contributors/casid/jte)

- [Jtwig](https://github.com/jtwig/jtwig) - Modular, configurable and fully tested template engine.

   ![](https://img.shields.io/github/stars/jtwig/jtwig) ![](https://img.shields.io/github/last-commit/jtwig/jtwig) ![](https://img.shields.io/github/issues/jtwig/jtwig) ![](https://img.shields.io/github/issues-pr/jtwig/jtwig) ![](https://img.shields.io/github/license/jtwig/jtwig) ![](https://img.shields.io/github/forks/jtwig/jtwig) ![](https://img.shields.io/github/contributors/jtwig/jtwig)

- [Pebble](https://pebbletemplates.io) - Inspired by Twig and separates itself with its inheritance feature and its easy-to-read syntax. It ships with built-in autoescaping for security and it includes integrated support for internationalization.
- [Rocker](https://github.com/fizzed/rocker) - Optimized, memory efficient and speedy template engine producing statically typed, plain objects.

   ![](https://img.shields.io/github/stars/fizzed/rocker) ![](https://img.shields.io/github/last-commit/fizzed/rocker) ![](https://img.shields.io/github/issues/fizzed/rocker) ![](https://img.shields.io/github/issues-pr/fizzed/rocker) ![](https://img.shields.io/github/license/fizzed/rocker) ![](https://img.shields.io/github/forks/fizzed/rocker) ![](https://img.shields.io/github/contributors/fizzed/rocker)

- [StringTemplate](https://github.com/antlr/stringtemplate4) - Template engine for generating source code, web pages, emails, or any other formatted text output.

   ![](https://img.shields.io/github/stars/antlr/stringtemplate4) ![](https://img.shields.io/github/last-commit/antlr/stringtemplate4) ![](https://img.shields.io/github/issues/antlr/stringtemplate4) ![](https://img.shields.io/github/issues-pr/antlr/stringtemplate4) ![](https://img.shields.io/github/license/antlr/stringtemplate4) ![](https://img.shields.io/github/forks/antlr/stringtemplate4) ![](https://img.shields.io/github/contributors/antlr/stringtemplate4)

- [Thymeleaf](https://www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

_Tools that test from model to the view._

#### Asynchronous

_Tools that simplify testing asynchronous services._

- [Awaitility](https://github.com/awaitility/awaitility) - DSL for synchronizing asynchronous operations.

   ![](https://img.shields.io/github/stars/awaitility/awaitility) ![](https://img.shields.io/github/last-commit/awaitility/awaitility) ![](https://img.shields.io/github/issues/awaitility/awaitility) ![](https://img.shields.io/github/issues-pr/awaitility/awaitility) ![](https://img.shields.io/github/license/awaitility/awaitility) ![](https://img.shields.io/github/forks/awaitility/awaitility) ![](https://img.shields.io/github/contributors/awaitility/awaitility)

- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) - Toolkit for testing multi-threaded and asynchronous applications.

   ![](https://img.shields.io/github/stars/jhalterman/concurrentunit) ![](https://img.shields.io/github/last-commit/jhalterman/concurrentunit) ![](https://img.shields.io/github/issues/jhalterman/concurrentunit) ![](https://img.shields.io/github/issues-pr/jhalterman/concurrentunit) ![](https://img.shields.io/github/license/jhalterman/concurrentunit) ![](https://img.shields.io/github/forks/jhalterman/concurrentunit) ![](https://img.shields.io/github/contributors/jhalterman/concurrentunit)

- [GreenMail](http://www.icegreen.com/greenmail/) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL. (GPL-2.0-only)
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Native bindings for Hoverfly, a proxy which allows you to simulate HTTP services.

   ![](https://img.shields.io/github/stars/SpectoLabs/hoverfly-java) ![](https://img.shields.io/github/last-commit/SpectoLabs/hoverfly-java) ![](https://img.shields.io/github/issues/SpectoLabs/hoverfly-java) ![](https://img.shields.io/github/issues-pr/SpectoLabs/hoverfly-java) ![](https://img.shields.io/github/license/SpectoLabs/hoverfly-java) ![](https://img.shields.io/github/forks/SpectoLabs/hoverfly-java) ![](https://img.shields.io/github/contributors/SpectoLabs/hoverfly-java)

- [Karate](https://github.com/intuit/karate) - DSL that combines API test-automation, mocks and performance-testing making testing REST/HTTP services easy.

   ![](https://img.shields.io/github/stars/intuit/karate) ![](https://img.shields.io/github/last-commit/intuit/karate) ![](https://img.shields.io/github/issues/intuit/karate) ![](https://img.shields.io/github/issues-pr/intuit/karate) ![](https://img.shields.io/github/license/intuit/karate) ![](https://img.shields.io/github/forks/intuit/karate) ![](https://img.shields.io/github/contributors/intuit/karate)

- [REST Assured](https://github.com/rest-assured/rest-assured) - DSL for easy testing of REST/HTTP services.

   ![](https://img.shields.io/github/stars/rest-assured/rest-assured) ![](https://img.shields.io/github/last-commit/rest-assured/rest-assured) ![](https://img.shields.io/github/issues/rest-assured/rest-assured) ![](https://img.shields.io/github/issues-pr/rest-assured/rest-assured) ![](https://img.shields.io/github/license/rest-assured/rest-assured) ![](https://img.shields.io/github/forks/rest-assured/rest-assured) ![](https://img.shields.io/github/contributors/rest-assured/rest-assured)


#### BDD

_Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD._

- [Cucumber](https://github.com/cucumber/cucumber-jvm) - Provides a way to describe features in a plain language which customers can understand.

   ![](https://img.shields.io/github/stars/cucumber/cucumber-jvm) ![](https://img.shields.io/github/last-commit/cucumber/cucumber-jvm) ![](https://img.shields.io/github/issues/cucumber/cucumber-jvm) ![](https://img.shields.io/github/issues-pr/cucumber/cucumber-jvm) ![](https://img.shields.io/github/license/cucumber/cucumber-jvm) ![](https://img.shields.io/github/forks/cucumber/cucumber-jvm) ![](https://img.shields.io/github/contributors/cucumber/cucumber-jvm)

- [Cukes-REST](https://github.com/ctco/cukes) - Collection of Gherkin steps for REST-service testing using Cucumber.

   ![](https://img.shields.io/github/stars/ctco/cukes) ![](https://img.shields.io/github/last-commit/ctco/cukes) ![](https://img.shields.io/github/issues/ctco/cukes) ![](https://img.shields.io/github/issues-pr/ctco/cukes) ![](https://img.shields.io/github/license/ctco/cukes) ![](https://img.shields.io/github/forks/ctco/cukes) ![](https://img.shields.io/github/contributors/ctco/cukes)

- [J8Spec](https://github.com/j8spec/j8spec) - Follows a Jasmine-like syntax.

   ![](https://img.shields.io/github/stars/j8spec/j8spec) ![](https://img.shields.io/github/last-commit/j8spec/j8spec) ![](https://img.shields.io/github/issues/j8spec/j8spec) ![](https://img.shields.io/github/issues-pr/j8spec/j8spec) ![](https://img.shields.io/github/license/j8spec/j8spec) ![](https://img.shields.io/github/forks/j8spec/j8spec) ![](https://img.shields.io/github/contributors/j8spec/j8spec)

- [JBehave](https://jbehave.org) - Extensively configurable framework that describes stories.
- [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English.

   ![](https://img.shields.io/github/stars/RichardWarburton/lambda-behave) ![](https://img.shields.io/github/last-commit/RichardWarburton/lambda-behave) ![](https://img.shields.io/github/issues/RichardWarburton/lambda-behave) ![](https://img.shields.io/github/issues-pr/RichardWarburton/lambda-behave) ![](https://img.shields.io/github/license/RichardWarburton/lambda-behave) ![](https://img.shields.io/github/forks/RichardWarburton/lambda-behave) ![](https://img.shields.io/github/contributors/RichardWarburton/lambda-behave)

- [Serenity BDD](https://github.com/serenity-bdd/serenity-core) - Automated Acceptance testing and reporting library that works with Cucumber, JBehave and JUnit to make it easier to write high quality executable specifications.

   ![](https://img.shields.io/github/stars/serenity-bdd/serenity-core) ![](https://img.shields.io/github/last-commit/serenity-bdd/serenity-core) ![](https://img.shields.io/github/issues/serenity-bdd/serenity-core) ![](https://img.shields.io/github/issues-pr/serenity-bdd/serenity-core) ![](https://img.shields.io/github/license/serenity-bdd/serenity-core) ![](https://img.shields.io/github/forks/serenity-bdd/serenity-core) ![](https://img.shields.io/github/contributors/serenity-bdd/serenity-core)


#### Fixtures

_Everything related to the creation and handling of random data._

- [Beanmother](https://github.com/keepcosmos/beanmother) - Sets up beans from YAML fixtures.

   ![](https://img.shields.io/github/stars/keepcosmos/beanmother) ![](https://img.shields.io/github/last-commit/keepcosmos/beanmother) ![](https://img.shields.io/github/issues/keepcosmos/beanmother) ![](https://img.shields.io/github/issues-pr/keepcosmos/beanmother) ![](https://img.shields.io/github/license/keepcosmos/beanmother) ![](https://img.shields.io/github/forks/keepcosmos/beanmother) ![](https://img.shields.io/github/contributors/keepcosmos/beanmother)

- [Fixture Factory](https://github.com/six2six/fixture-factory) - Generates fake objects from a template.

   ![](https://img.shields.io/github/stars/six2six/fixture-factory) ![](https://img.shields.io/github/last-commit/six2six/fixture-factory) ![](https://img.shields.io/github/issues/six2six/fixture-factory) ![](https://img.shields.io/github/issues-pr/six2six/fixture-factory) ![](https://img.shields.io/github/license/six2six/fixture-factory) ![](https://img.shields.io/github/forks/six2six/fixture-factory) ![](https://img.shields.io/github/contributors/six2six/fixture-factory)

- [jFairy](https://github.com/Devskiller/jfairy) - Fake data generator.

   ![](https://img.shields.io/github/stars/Devskiller/jfairy) ![](https://img.shields.io/github/last-commit/Devskiller/jfairy) ![](https://img.shields.io/github/issues/Devskiller/jfairy) ![](https://img.shields.io/github/issues-pr/Devskiller/jfairy) ![](https://img.shields.io/github/license/Devskiller/jfairy) ![](https://img.shields.io/github/forks/Devskiller/jfairy) ![](https://img.shields.io/github/contributors/Devskiller/jfairy)

- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.

   ![](https://img.shields.io/github/stars/randomizedtesting/randomizedtesting) ![](https://img.shields.io/github/last-commit/randomizedtesting/randomizedtesting) ![](https://img.shields.io/github/issues/randomizedtesting/randomizedtesting) ![](https://img.shields.io/github/issues-pr/randomizedtesting/randomizedtesting) ![](https://img.shields.io/github/license/randomizedtesting/randomizedtesting) ![](https://img.shields.io/github/forks/randomizedtesting/randomizedtesting) ![](https://img.shields.io/github/contributors/randomizedtesting/randomizedtesting)

- [Java Faker](https://github.com/DiUS/java-faker) - Port of Ruby's fake data generator.

   ![](https://img.shields.io/github/stars/DiUS/java-faker) ![](https://img.shields.io/github/last-commit/DiUS/java-faker) ![](https://img.shields.io/github/issues/DiUS/java-faker) ![](https://img.shields.io/github/issues-pr/DiUS/java-faker) ![](https://img.shields.io/github/license/DiUS/java-faker) ![](https://img.shields.io/github/forks/DiUS/java-faker) ![](https://img.shields.io/github/contributors/DiUS/java-faker)


#### Frameworks

_Provide environments to run tests for a specific use case._

- [ArchUnit](https://github.com/TNG/ArchUnit) - Test library for specifying and asserting architecture rules.

   ![](https://img.shields.io/github/stars/TNG/ArchUnit) ![](https://img.shields.io/github/last-commit/TNG/ArchUnit) ![](https://img.shields.io/github/issues/TNG/ArchUnit) ![](https://img.shields.io/github/issues-pr/TNG/ArchUnit) ![](https://img.shields.io/github/license/TNG/ArchUnit) ![](https://img.shields.io/github/forks/TNG/ArchUnit) ![](https://img.shields.io/github/contributors/TNG/ArchUnit)

- [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
- [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
- [Citrus](https://citrusframework.org) - Integration testing framework that focuses on both client- and server-side messaging.
- [Gatling](https://gatling.io) - Load testing tool designed for ease of use, maintainability and high performance.
- [JUnit](https://junit.org/junit5/) - Common testing framework.
- [jqwik](https://jqwik.net) - Engine for property-based testing built on JUnit 5.
- [Pact JVM](https://github.com/DiUS/pact-jvm) - Consumer-driven contract testing.

   ![](https://img.shields.io/github/stars/DiUS/pact-jvm) ![](https://img.shields.io/github/last-commit/DiUS/pact-jvm) ![](https://img.shields.io/github/issues/DiUS/pact-jvm) ![](https://img.shields.io/github/issues-pr/DiUS/pact-jvm) ![](https://img.shields.io/github/license/DiUS/pact-jvm) ![](https://img.shields.io/github/forks/DiUS/pact-jvm) ![](https://img.shields.io/github/contributors/DiUS/pact-jvm)

- [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

#### Matchers

_Libraries that provide custom matchers._

- [AssertJ](https://joel-costigliola.github.io/assertj/) - Fluent assertions that improve readability.
- [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Matchers that can be combined to create flexible expressions of intent.
- [JSONAssert](http://jsonassert.skyscreamer.org) - Simplifies testing JSON strings.
- [Truth](https://truth.dev) - Google's fluent assertion and proposition framework.
- [XMLUnit](https://github.com/xmlunit/xmlunit) - Simplifies testing for XML output.

   ![](https://img.shields.io/github/stars/xmlunit/xmlunit) ![](https://img.shields.io/github/last-commit/xmlunit/xmlunit) ![](https://img.shields.io/github/issues/xmlunit/xmlunit) ![](https://img.shields.io/github/issues-pr/xmlunit/xmlunit) ![](https://img.shields.io/github/license/xmlunit/xmlunit) ![](https://img.shields.io/github/forks/xmlunit/xmlunit) ![](https://img.shields.io/github/contributors/xmlunit/xmlunit)


#### Miscellaneous

_Other stuff related to testing._

- [ConsoleCaptor](https://github.com/Hakky54/console-captor) - Captures console output for unit testing purposes.

   ![](https://img.shields.io/github/stars/Hakky54/console-captor) ![](https://img.shields.io/github/last-commit/Hakky54/console-captor) ![](https://img.shields.io/github/issues/Hakky54/console-captor) ![](https://img.shields.io/github/issues-pr/Hakky54/console-captor) ![](https://img.shields.io/github/license/Hakky54/console-captor) ![](https://img.shields.io/github/forks/Hakky54/console-captor) ![](https://img.shields.io/github/contributors/Hakky54/console-captor)

- [junit-dataprovider](https://github.com/TNG/junit-dataprovider) - TestNG-like data provider/runner for JUnit.

   ![](https://img.shields.io/github/stars/TNG/junit-dataprovider) ![](https://img.shields.io/github/last-commit/TNG/junit-dataprovider) ![](https://img.shields.io/github/issues/TNG/junit-dataprovider) ![](https://img.shields.io/github/issues-pr/TNG/junit-dataprovider) ![](https://img.shields.io/github/license/TNG/junit-dataprovider) ![](https://img.shields.io/github/forks/TNG/junit-dataprovider) ![](https://img.shields.io/github/contributors/TNG/junit-dataprovider)

- [LogCaptor](https://github.com/Hakky54/log-captor) - Captures log entries for unit testing purposes.

   ![](https://img.shields.io/github/stars/Hakky54/log-captor) ![](https://img.shields.io/github/last-commit/Hakky54/log-captor) ![](https://img.shields.io/github/issues/Hakky54/log-captor) ![](https://img.shields.io/github/issues-pr/Hakky54/log-captor) ![](https://img.shields.io/github/license/Hakky54/log-captor) ![](https://img.shields.io/github/forks/Hakky54/log-captor) ![](https://img.shields.io/github/contributors/Hakky54/log-captor)

- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) - Reports whether instances of a given class are immutable.

   ![](https://img.shields.io/github/stars/MutabilityDetector/MutabilityDetector) ![](https://img.shields.io/github/last-commit/MutabilityDetector/MutabilityDetector) ![](https://img.shields.io/github/issues/MutabilityDetector/MutabilityDetector) ![](https://img.shields.io/github/issues-pr/MutabilityDetector/MutabilityDetector) ![](https://img.shields.io/github/license/MutabilityDetector/MutabilityDetector) ![](https://img.shields.io/github/forks/MutabilityDetector/MutabilityDetector) ![](https://img.shields.io/github/contributors/MutabilityDetector/MutabilityDetector)

- [raml-tester](https://github.com/nidi3/raml-tester) - Tests if a request/response matches a given RAML definition.

   ![](https://img.shields.io/github/stars/nidi3/raml-tester) ![](https://img.shields.io/github/last-commit/nidi3/raml-tester) ![](https://img.shields.io/github/issues/nidi3/raml-tester) ![](https://img.shields.io/github/issues-pr/nidi3/raml-tester) ![](https://img.shields.io/github/license/nidi3/raml-tester) ![](https://img.shields.io/github/forks/nidi3/raml-tester) ![](https://img.shields.io/github/contributors/nidi3/raml-tester)

- [TestContainers](https://github.com/testcontainers/testcontainers-java) - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.

   ![](https://img.shields.io/github/stars/testcontainers/testcontainers-java) ![](https://img.shields.io/github/last-commit/testcontainers/testcontainers-java) ![](https://img.shields.io/github/issues/testcontainers/testcontainers-java) ![](https://img.shields.io/github/issues-pr/testcontainers/testcontainers-java) ![](https://img.shields.io/github/license/testcontainers/testcontainers-java) ![](https://img.shields.io/github/forks/testcontainers/testcontainers-java) ![](https://img.shields.io/github/contributors/testcontainers/testcontainers-java)

- [pojo-tester](https://www.pojo.pl) - Automatically performs tests on basic POJO methods. (LGPL-3.0-only)

#### Mocking

_Tools which mock collaborators to help testing single, isolated units._

- [JMockit](http://jmockit.github.io) - Integration testing, API mocking and faking, and code coverage.
- [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API.

   ![](https://img.shields.io/github/stars/mockito/mockito) ![](https://img.shields.io/github/last-commit/mockito/mockito) ![](https://img.shields.io/github/issues/mockito/mockito) ![](https://img.shields.io/github/issues-pr/mockito/mockito) ![](https://img.shields.io/github/license/mockito/mockito) ![](https://img.shields.io/github/forks/mockito/mockito) ![](https://img.shields.io/github/contributors/mockito/mockito)

- [MockServer](https://www.mock-server.com) - Allows mocking of systems integrated with HTTPS.
- [Moco](https://github.com/dreamhead/moco) - Concise web services for stubs and mocks.

   ![](https://img.shields.io/github/stars/dreamhead/moco) ![](https://img.shields.io/github/last-commit/dreamhead/moco) ![](https://img.shields.io/github/issues/dreamhead/moco) ![](https://img.shields.io/github/issues-pr/dreamhead/moco) ![](https://img.shields.io/github/license/dreamhead/moco) ![](https://img.shields.io/github/forks/dreamhead/moco) ![](https://img.shields.io/github/contributors/dreamhead/moco)

- [PowerMock](https://github.com/powermock/powermock) - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers.

   ![](https://img.shields.io/github/stars/powermock/powermock) ![](https://img.shields.io/github/last-commit/powermock/powermock) ![](https://img.shields.io/github/issues/powermock/powermock) ![](https://img.shields.io/github/issues-pr/powermock/powermock) ![](https://img.shields.io/github/license/powermock/powermock) ![](https://img.shields.io/github/forks/powermock/powermock) ![](https://img.shields.io/github/contributors/powermock/powermock)

- [WireMock](http://wiremock.org) - Stubs and mocks web services.

### Utility

_Libraries which provide general utility functions._

- [Arthas](https://github.com/alibaba/arthas) - Allows to troubleshoot production issues for applications without modifying code or restarting servers.

   ![](https://img.shields.io/github/stars/alibaba/arthas) ![](https://img.shields.io/github/last-commit/alibaba/arthas) ![](https://img.shields.io/github/issues/alibaba/arthas) ![](https://img.shields.io/github/issues-pr/alibaba/arthas) ![](https://img.shields.io/github/license/alibaba/arthas) ![](https://img.shields.io/github/forks/alibaba/arthas) ![](https://img.shields.io/github/contributors/alibaba/arthas)

- [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) - Rate limiting library based on token-bucket algorithm.

   ![](https://img.shields.io/github/stars/vladimir-bukhtoyarov/bucket4j) ![](https://img.shields.io/github/last-commit/vladimir-bukhtoyarov/bucket4j) ![](https://img.shields.io/github/issues/vladimir-bukhtoyarov/bucket4j) ![](https://img.shields.io/github/issues-pr/vladimir-bukhtoyarov/bucket4j) ![](https://img.shields.io/github/license/vladimir-bukhtoyarov/bucket4j) ![](https://img.shields.io/github/forks/vladimir-bukhtoyarov/bucket4j) ![](https://img.shields.io/github/contributors/vladimir-bukhtoyarov/bucket4j)

- [cactoos](https://github.com/yegor256/cactoos) - Collection of object-oriented primitives.

   ![](https://img.shields.io/github/stars/yegor256/cactoos) ![](https://img.shields.io/github/last-commit/yegor256/cactoos) ![](https://img.shields.io/github/issues/yegor256/cactoos) ![](https://img.shields.io/github/issues-pr/yegor256/cactoos) ![](https://img.shields.io/github/license/yegor256/cactoos) ![](https://img.shields.io/github/forks/yegor256/cactoos) ![](https://img.shields.io/github/contributors/yegor256/cactoos)

- [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others. (LGPL-2.1-or-later)
- [Dex](https://github.com/PatMartin/Dex) - Java/JavaFX tool capable of powerful ETL and data visualization.

   ![](https://img.shields.io/github/stars/PatMartin/Dex) ![](https://img.shields.io/github/last-commit/PatMartin/Dex) ![](https://img.shields.io/github/issues/PatMartin/Dex) ![](https://img.shields.io/github/issues-pr/PatMartin/Dex) ![](https://img.shields.io/github/license/PatMartin/Dex) ![](https://img.shields.io/github/forks/PatMartin/Dex) ![](https://img.shields.io/github/contributors/PatMartin/Dex)

- [Embulk](https://github.com/embulk/embulk) - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.

   ![](https://img.shields.io/github/stars/embulk/embulk) ![](https://img.shields.io/github/last-commit/embulk/embulk) ![](https://img.shields.io/github/issues/embulk/embulk) ![](https://img.shields.io/github/issues-pr/embulk/embulk) ![](https://img.shields.io/github/license/embulk/embulk) ![](https://img.shields.io/github/forks/embulk/embulk) ![](https://img.shields.io/github/contributors/embulk/embulk)

- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService.

   ![](https://img.shields.io/github/stars/vorburger/ch.vorburger.fswatch) ![](https://img.shields.io/github/last-commit/vorburger/ch.vorburger.fswatch) ![](https://img.shields.io/github/issues/vorburger/ch.vorburger.fswatch) ![](https://img.shields.io/github/issues-pr/vorburger/ch.vorburger.fswatch) ![](https://img.shields.io/github/license/vorburger/ch.vorburger.fswatch) ![](https://img.shields.io/github/forks/vorburger/ch.vorburger.fswatch) ![](https://img.shields.io/github/contributors/vorburger/ch.vorburger.fswatch)

- [Gephi](https://github.com/gephi/gephi) - Cross-platform for visualizing and manipulating large graph networks. (GPL-3.0-only)

   ![](https://img.shields.io/github/stars/gephi/gephi) ![](https://img.shields.io/github/last-commit/gephi/gephi) ![](https://img.shields.io/github/issues/gephi/gephi) ![](https://img.shields.io/github/issues-pr/gephi/gephi) ![](https://img.shields.io/github/license/gephi/gephi) ![](https://img.shields.io/github/forks/gephi/gephi) ![](https://img.shields.io/github/contributors/gephi/gephi)

- [Guava](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more.

   ![](https://img.shields.io/github/stars/google/guava) ![](https://img.shields.io/github/last-commit/google/guava) ![](https://img.shields.io/github/issues/google/guava) ![](https://img.shields.io/github/issues-pr/google/guava) ![](https://img.shields.io/github/license/google/guava) ![](https://img.shields.io/github/forks/google/guava) ![](https://img.shields.io/github/contributors/google/guava)

- [JADE](http://jade.tilab.com) - Framework and environment for building and debugging multi-agent systems. (LGPL-2.0-only)
- [Java Diff Utils](https://java-diff-utils.github.io/java-diff-utils/) - Utilities for text or data comparison and patching.
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - Library that helps with constructing difficult regular expressions.

   ![](https://img.shields.io/github/stars/VerbalExpressions/JavaVerbalExpressions) ![](https://img.shields.io/github/last-commit/VerbalExpressions/JavaVerbalExpressions) ![](https://img.shields.io/github/issues/VerbalExpressions/JavaVerbalExpressions) ![](https://img.shields.io/github/issues-pr/VerbalExpressions/JavaVerbalExpressions) ![](https://img.shields.io/github/license/VerbalExpressions/JavaVerbalExpressions) ![](https://img.shields.io/github/forks/VerbalExpressions/JavaVerbalExpressions) ![](https://img.shields.io/github/contributors/VerbalExpressions/JavaVerbalExpressions)

- [JGit](https://www.eclipse.org/jgit/) - Lightweight, pure Java library implementing the Git version control system.
- [minio-java](https://github.com/minio/minio-java) - Provides simple APIs to access any Amazon S3-compatible object storage server.

   ![](https://img.shields.io/github/stars/minio/minio-java) ![](https://img.shields.io/github/last-commit/minio/minio-java) ![](https://img.shields.io/github/issues/minio/minio-java) ![](https://img.shields.io/github/issues-pr/minio/minio-java) ![](https://img.shields.io/github/license/minio/minio-java) ![](https://img.shields.io/github/forks/minio/minio-java) ![](https://img.shields.io/github/contributors/minio/minio-java)

- [Protégé](https://protege.stanford.edu) - Provides an ontology editor and a framework to build knowledge-based systems.
- [Underscore-java](https://github.com/javadev/underscore-java) - Port of Underscore.js functions.

   ![](https://img.shields.io/github/stars/javadev/underscore-java) ![](https://img.shields.io/github/last-commit/javadev/underscore-java) ![](https://img.shields.io/github/issues/javadev/underscore-java) ![](https://img.shields.io/github/issues-pr/javadev/underscore-java) ![](https://img.shields.io/github/license/javadev/underscore-java) ![](https://img.shields.io/github/forks/javadev/underscore-java) ![](https://img.shields.io/github/contributors/javadev/underscore-java)


### Version Managers

_Utilities that help create the development shell environment and switch between different Java versions._

- [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports macOS, Linux and Windows.

   ![](https://img.shields.io/github/stars/shyiko/jabba) ![](https://img.shields.io/github/last-commit/shyiko/jabba) ![](https://img.shields.io/github/issues/shyiko/jabba) ![](https://img.shields.io/github/issues-pr/shyiko/jabba) ![](https://img.shields.io/github/license/shyiko/jabba) ![](https://img.shields.io/github/forks/shyiko/jabba) ![](https://img.shields.io/github/contributors/shyiko/jabba)

- [jenv](https://github.com/jenv/jenv) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and macOS.

   ![](https://img.shields.io/github/stars/jenv/jenv) ![](https://img.shields.io/github/last-commit/jenv/jenv) ![](https://img.shields.io/github/issues/jenv/jenv) ![](https://img.shields.io/github/issues-pr/jenv/jenv) ![](https://img.shields.io/github/license/jenv/jenv) ![](https://img.shields.io/github/forks/jenv/jenv) ![](https://img.shields.io/github/contributors/jenv/jenv)

- [SDKMan](https://github.com/sdkman/sdkman-cli) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows.

   ![](https://img.shields.io/github/stars/sdkman/sdkman-cli) ![](https://img.shields.io/github/last-commit/sdkman/sdkman-cli) ![](https://img.shields.io/github/issues/sdkman/sdkman-cli) ![](https://img.shields.io/github/issues-pr/sdkman/sdkman-cli) ![](https://img.shields.io/github/license/sdkman/sdkman-cli) ![](https://img.shields.io/github/forks/sdkman/sdkman-cli) ![](https://img.shields.io/github/contributors/sdkman/sdkman-cli)


### Web Crawling

_Libraries that analyze the content of websites._

- [Apache Nutch](https://nutch.apache.org) - Highly extensible, highly scalable web crawler for production environments.
- [Crawler4j](https://github.com/yasserg/crawler4j) - Simple and lightweight web crawler.

   ![](https://img.shields.io/github/stars/yasserg/crawler4j) ![](https://img.shields.io/github/last-commit/yasserg/crawler4j) ![](https://img.shields.io/github/issues/yasserg/crawler4j) ![](https://img.shields.io/github/issues-pr/yasserg/crawler4j) ![](https://img.shields.io/github/license/yasserg/crawler4j) ![](https://img.shields.io/github/forks/yasserg/crawler4j) ![](https://img.shields.io/github/contributors/yasserg/crawler4j)

- [jsoup](https://jsoup.org) - Scrapes, parses, manipulates and cleans HTML.
- [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.
- [webmagic](https://github.com/code4craft/webmagic) - Scalable crawler with downloading, url management, content extraction and persistent.

   ![](https://img.shields.io/github/stars/code4craft/webmagic) ![](https://img.shields.io/github/last-commit/code4craft/webmagic) ![](https://img.shields.io/github/issues/code4craft/webmagic) ![](https://img.shields.io/github/issues-pr/code4craft/webmagic) ![](https://img.shields.io/github/license/code4craft/webmagic) ![](https://img.shields.io/github/forks/code4craft/webmagic) ![](https://img.shields.io/github/contributors/code4craft/webmagic)


### Web Frameworks

_Frameworks that handle the communication between the layers of a web application._

- [ActiveJ](https://activej.io) - Lightweight asynchronous framework built from the ground up for developing high-performance web applications.
- [Apache Tapestry](https://tapestry.apache.org) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
- [Apache Wicket](https://wicket.apache.org) - Component-based web application framework similar to Tapestry, with a stateful GUI.
- [Blade](https://github.com/lets-blade/blade) - Lightweight, modular framework that aims to be elegant and simple.

   ![](https://img.shields.io/github/stars/lets-blade/blade) ![](https://img.shields.io/github/last-commit/lets-blade/blade) ![](https://img.shields.io/github/issues/lets-blade/blade) ![](https://img.shields.io/github/issues-pr/lets-blade/blade) ![](https://img.shields.io/github/license/lets-blade/blade) ![](https://img.shields.io/github/forks/lets-blade/blade) ![](https://img.shields.io/github/contributors/lets-blade/blade)

- [Bootique](https://bootique.io) - Minimally opinionated framework for runnable apps.
- [Firefly](http://www.fireflysource.com) - Asynchronous framework for rapid development of high-performance web application.
- [Jooby](http://www.jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
- [Ninja](http://www.ninjaframework.org) - Full-stack web framework.
- [Pippo](http://www.pippo.ro) - Small, highly modularized, Sinatra-like framework.
- [Play](https://www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
- [PrimeFaces](https://www.primefaces.org) - JSF framework with both free and commercial/support versions and frontend components.
- [Ratpack](https://ratpack.io) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
- [Takes](https://github.com/yegor256/takes) - Opinionated web framework which is built around the concepts of True Object-Oriented Programming and immutability.

   ![](https://img.shields.io/github/stars/yegor256/takes) ![](https://img.shields.io/github/last-commit/yegor256/takes) ![](https://img.shields.io/github/issues/yegor256/takes) ![](https://img.shields.io/github/issues-pr/yegor256/takes) ![](https://img.shields.io/github/license/yegor256/takes) ![](https://img.shields.io/github/forks/yegor256/takes) ![](https://img.shields.io/github/contributors/yegor256/takes)

- [Vaadin](https://vaadin.com) - Event-driven framework that uses standard web components. Server-side architecture with Ajax on the client side.

### Workflow Orchestration Engines

- [Cadence](https://cadenceworkflow.io) - Stateful code platform from Uber.
- [flowable](https://github.com/flowable/flowable-engine) - Compact and efficient workflow and business process management platform.

   ![](https://img.shields.io/github/stars/flowable/flowable-engine) ![](https://img.shields.io/github/last-commit/flowable/flowable-engine) ![](https://img.shields.io/github/issues/flowable/flowable-engine) ![](https://img.shields.io/github/issues-pr/flowable/flowable-engine) ![](https://img.shields.io/github/license/flowable/flowable-engine) ![](https://img.shields.io/github/forks/flowable/flowable-engine) ![](https://img.shields.io/github/contributors/flowable/flowable-engine)

- [Temporal](https://temporal.io) - Microservice orchestration platform, forked from Cadence but gRPC based.

## Resources

### Related Awesome Lists

_Awesome Lists related to the Java & JVM ecosystem._

- [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing)

   ![](https://img.shields.io/github/stars/gunnarmorling/awesome-annotation-processing) ![](https://img.shields.io/github/last-commit/gunnarmorling/awesome-annotation-processing) ![](https://img.shields.io/github/issues/gunnarmorling/awesome-annotation-processing) ![](https://img.shields.io/github/issues-pr/gunnarmorling/awesome-annotation-processing) ![](https://img.shields.io/github/license/gunnarmorling/awesome-annotation-processing) ![](https://img.shields.io/github/forks/gunnarmorling/awesome-annotation-processing) ![](https://img.shields.io/github/contributors/gunnarmorling/awesome-annotation-processing)

- [Awesome Graal](https://github.com/neomatrix369/awesome-graal)

   ![](https://img.shields.io/github/stars/neomatrix369/awesome-graal) ![](https://img.shields.io/github/last-commit/neomatrix369/awesome-graal) ![](https://img.shields.io/github/issues/neomatrix369/awesome-graal) ![](https://img.shields.io/github/issues-pr/neomatrix369/awesome-graal) ![](https://img.shields.io/github/license/neomatrix369/awesome-graal) ![](https://img.shields.io/github/forks/neomatrix369/awesome-graal) ![](https://img.shields.io/github/contributors/neomatrix369/awesome-graal)

- [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle)

   ![](https://img.shields.io/github/stars/ksoichiro/awesome-gradle) ![](https://img.shields.io/github/last-commit/ksoichiro/awesome-gradle) ![](https://img.shields.io/github/issues/ksoichiro/awesome-gradle) ![](https://img.shields.io/github/issues-pr/ksoichiro/awesome-gradle) ![](https://img.shields.io/github/license/ksoichiro/awesome-gradle) ![](https://img.shields.io/github/forks/ksoichiro/awesome-gradle) ![](https://img.shields.io/github/contributors/ksoichiro/awesome-gradle)

- [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX)

   ![](https://img.shields.io/github/stars/mhrimaz/AwesomeJavaFX) ![](https://img.shields.io/github/last-commit/mhrimaz/AwesomeJavaFX) ![](https://img.shields.io/github/issues/mhrimaz/AwesomeJavaFX) ![](https://img.shields.io/github/issues-pr/mhrimaz/AwesomeJavaFX) ![](https://img.shields.io/github/license/mhrimaz/AwesomeJavaFX) ![](https://img.shields.io/github/forks/mhrimaz/AwesomeJavaFX) ![](https://img.shields.io/github/contributors/mhrimaz/AwesomeJavaFX)

- [Awesome JVM](https://github.com/deephacks/awesome-jvm)

   ![](https://img.shields.io/github/stars/deephacks/awesome-jvm) ![](https://img.shields.io/github/last-commit/deephacks/awesome-jvm) ![](https://img.shields.io/github/issues/deephacks/awesome-jvm) ![](https://img.shields.io/github/issues-pr/deephacks/awesome-jvm) ![](https://img.shields.io/github/license/deephacks/awesome-jvm) ![](https://img.shields.io/github/forks/deephacks/awesome-jvm) ![](https://img.shields.io/github/contributors/deephacks/awesome-jvm)

- [Awesome Microservices](https://github.com/mfornos/awesome-microservices)

   ![](https://img.shields.io/github/stars/mfornos/awesome-microservices) ![](https://img.shields.io/github/last-commit/mfornos/awesome-microservices) ![](https://img.shields.io/github/issues/mfornos/awesome-microservices) ![](https://img.shields.io/github/issues-pr/mfornos/awesome-microservices) ![](https://img.shields.io/github/license/mfornos/awesome-microservices) ![](https://img.shields.io/github/forks/mfornos/awesome-microservices) ![](https://img.shields.io/github/contributors/mfornos/awesome-microservices)

- [Awesome REST](https://github.com/marmelab/awesome-rest)

   ![](https://img.shields.io/github/stars/marmelab/awesome-rest) ![](https://img.shields.io/github/last-commit/marmelab/awesome-rest) ![](https://img.shields.io/github/issues/marmelab/awesome-rest) ![](https://img.shields.io/github/issues-pr/marmelab/awesome-rest) ![](https://img.shields.io/github/license/marmelab/awesome-rest) ![](https://img.shields.io/github/forks/marmelab/awesome-rest) ![](https://img.shields.io/github/contributors/marmelab/awesome-rest)

- [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium)

   ![](https://img.shields.io/github/stars/christian-bromann/awesome-selenium) ![](https://img.shields.io/github/last-commit/christian-bromann/awesome-selenium) ![](https://img.shields.io/github/issues/christian-bromann/awesome-selenium) ![](https://img.shields.io/github/issues-pr/christian-bromann/awesome-selenium) ![](https://img.shields.io/github/license/christian-bromann/awesome-selenium) ![](https://img.shields.io/github/forks/christian-bromann/awesome-selenium) ![](https://img.shields.io/github/contributors/christian-bromann/awesome-selenium)

- [ciandcd](https://github.com/ciandcd/awesome-ciandcd)

   ![](https://img.shields.io/github/stars/ciandcd/awesome-ciandcd) ![](https://img.shields.io/github/last-commit/ciandcd/awesome-ciandcd) ![](https://img.shields.io/github/issues/ciandcd/awesome-ciandcd) ![](https://img.shields.io/github/issues-pr/ciandcd/awesome-ciandcd) ![](https://img.shields.io/github/license/ciandcd/awesome-ciandcd) ![](https://img.shields.io/github/forks/ciandcd/awesome-ciandcd) ![](https://img.shields.io/github/contributors/ciandcd/awesome-ciandcd)

- [Useful Java Links](https://github.com/Vedenin/useful-java-links)

   ![](https://img.shields.io/github/stars/Vedenin/useful-java-links) ![](https://img.shields.io/github/last-commit/Vedenin/useful-java-links) ![](https://img.shields.io/github/issues/Vedenin/useful-java-links) ![](https://img.shields.io/github/issues-pr/Vedenin/useful-java-links) ![](https://img.shields.io/github/license/Vedenin/useful-java-links) ![](https://img.shields.io/github/forks/Vedenin/useful-java-links) ![](https://img.shields.io/github/contributors/Vedenin/useful-java-links)

- [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency)

   ![](https://img.shields.io/github/stars/code-review-checklists/java-concurrency) ![](https://img.shields.io/github/last-commit/code-review-checklists/java-concurrency) ![](https://img.shields.io/github/issues/code-review-checklists/java-concurrency) ![](https://img.shields.io/github/issues-pr/code-review-checklists/java-concurrency) ![](https://img.shields.io/github/license/code-review-checklists/java-concurrency) ![](https://img.shields.io/github/forks/code-review-checklists/java-concurrency) ![](https://img.shields.io/github/contributors/code-review-checklists/java-concurrency)

- [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap)

   ![](https://img.shields.io/github/stars/s4kibs4mi/java-developer-roadmap) ![](https://img.shields.io/github/last-commit/s4kibs4mi/java-developer-roadmap) ![](https://img.shields.io/github/issues/s4kibs4mi/java-developer-roadmap) ![](https://img.shields.io/github/issues-pr/s4kibs4mi/java-developer-roadmap) ![](https://img.shields.io/github/license/s4kibs4mi/java-developer-roadmap) ![](https://img.shields.io/github/forks/s4kibs4mi/java-developer-roadmap) ![](https://img.shields.io/github/contributors/s4kibs4mi/java-developer-roadmap)


### Communities

_Active discussions._

- [r/java](https://www.reddit.com/r/java/) - Subreddit for the Java community.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.
- [VirtualJUG](https://virtualjug.com) - Virtual Java User Group.

### Frontends

_Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one._

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

_Books that made a big impact and are still worth reading._

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

_Something to look at or listen to while programming._

- [A Bootiful Podcast](https://bootifulpodcast.fm)
- [Inside Java](https://inside.java/podcast) (Official)
- [Java Off Heap](http://www.javaoffheap.com)
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### People

#### Twitter

_Active accounts to follow. Descriptions from Twitter._

- [Adam Bien](https://twitter.com/AdamBien) - Freelance author, JavaOne Rockstar speaker, consultant, Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) - Performance geek, benchmarking czar, concurrency bug hunter.
- [Antonio Goncalves](https://twitter.com/agoncal) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
- [Arun Gupta](https://twitter.com/arungupta) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
- [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
- [Bruno Borges](https://twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
- [Chris Richardson](https://twitter.com/crichardson) - Software architect, consultant, and serial entrepreneur, Java Champion, JavaOne Rock Star, \*POJOs in Action- author.
- [Ed Burns](https://twitter.com/edburns) - Consulting Member of the Technical Staff at Oracle.
- [Eugen Paraschiv](https://twitter.com/baeldung) - Author of the Spring Security Course.
- [Heinz Kabutz](https://twitter.com/heinzkabutz) - Java Champion, speaker, author of The Java Specialists' Newsletter, concurrency performance expert.
- [Holly Cummins](https://twitter.com/holly_cummins) - Technical Lead of IBM London's Bluemix Garage, Java Champion, developer, author, JavaOne rockstar.
- [James Weaver](https://twitter.com/JavaFXpert) - Java/JavaFX/IoT developer, author and speaker.
- [Java EE](https://twitter.com/Java_EE) - Official Java EE Twitter account.
- [Java Magazine](https://twitter.com/Oraclejavamag) - Official Java Magazine account.
- [Java](https://twitter.com/java) - Official Java Twitter account.
- [Javin Paul](https://twitter.com/javinpaul) - Well-known Java blogger.
- [Josh Long](https://twitter.com/starbuxman) - Spring Advocate at Pivotal, author of O'Reilly's Cloud Native Java- and Building Microservices with Spring Boot, JavaOne Rock Star.
- [Lukas Eder](https://twitter.com/lukaseder) - Java Champion, speaker, Founder and CEO Data Geekery (jOOQ).
- [Mani Sarkar](https://twitter.com/theNeomatrix369) - Java champion, Polyglot, Software Crafter involved with @graalvm, AI/ML/DL, Data Science, Developer communities, speaker & blogger. Creator of couple of awesome lists like this one.
- [Mario Fusco](https://twitter.com/mariofusco) - RedHatter, JUG coordinator, frequent speaker and author.
- [Mark Heckler](https://twitter.com/MkHeck) - Pivotal Principal Technologist and Developer Advocate, conference speaker, published author, and Java Champion, focusing on Internet of Things and the cloud.
- [Mark Reinhold](https://twitter.com/mreinhold) - Chief Architect, Java Platform Group, Oracle.
- [Markus Eisele](https://twitter.com/myfear) - Java EE evangelist, Red Hat.
- [Martijn Verburg](https://twitter.com/karianna) - London JUG co-leader, speaker, author, Java Champion and much more.
- [Martin Thompson](https://twitter.com/mjpt777) - Pasty faced performance gangster.
- [Monica Beckwith](https://twitter.com/mon_beck) - Performance consultant, JavaOne Rock Star.
- [OpenJDK](https://twitter.com/OpenJDK) - Official OpenJDK account.
- [Peter Lawrey](https://twitter.com/PeterLawrey) - Peter Lawrey, Java performance expert.
- [Randy Shoup](https://twitter.com/randyshoup) - Stitch Fix VP Engineering, speaker, JavaOne Rock Star.
- [Reza Rahman](https://twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic evangelist, author, speaker, open source hacker.
- [Sander Mak](https://twitter.com/Sander_Mak) - Java Champion, author.
- [Simon Maple](https://twitter.com/sjmaple) - Java Champion, VirtualJUG founder, LJC leader, RebelLabs author.
- [Spencer Gibb](https://twitter.com/spencerbgibb) - Software Engineer, Dad, Geek, Co-founder and Lead of Spring Cloud Core @pivotal.
- [Stephen Colebourne](https://twitter.com/jodastephen) - Java Champion, speaker.
- [Trisha Gee](https://twitter.com/trisha_gee) - Java Champion and speaker.
- [Venkat Subramaniam](https://twitter.com/venkat_s) - Author, University of Houston professor, MicroSoft MVP award recipient, JavaOne Rock Star, Java Champion.
- [Vlad Mihalcea](https://twitter.com/vlad_mihalcea) - Java Champion working on Hypersistence Optimizer, database aficionado, author of High-Performance Java Persistence book.

#### Other

- [Groundbreakers](https://apexapps.oracle.com/pls/apex/f?p=119297:3::::::) - Oracle ACEs, Groundbreaker Ambassadors and Java Champions.

### Websites

_Sites to read._

- [Baeldung](https://www.baeldung.com)
- [Dzone](https://dzone.com)
- [foojay.io](https://foojay.io)
- [Google Java Style](https://google.github.io/styleguide/javaguide.html)
- [InfoQ](https://www.infoq.com)
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
- [Java, SQL, and jOOQ](https://blog.jooq.org)
- [Java.net](https://community.oracle.com/community/java)
- [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
- [JavaWorld](https://www.javaworld.com)
- [JAXenter](https://jaxenter.com)
- [RebelLabs](https://zeroturnaround.com/rebellabs)
- [OverOps Blog](https://blog.overops.com)
- [TheServerSide.com](http://www.theserverside.com)
- [Vanilla Java](https://vanilla-java.github.io)
- [Voxxed](https://www.voxxed.com)

## Contributing

Contributions are very welcome!

Please have a look at the [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) guidelines and [the validation tools](https://github.com/akullpp/awesome-java-lint).

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
