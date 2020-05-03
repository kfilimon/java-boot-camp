# Java Boot Camp

Boot Camp for developers interested to learn Java.

## Plan

### [Primer](01%20-%20Primer.md)

1. [Setup Environment (SDKMAN)](01%20-%20Primer.md#setup-environment-sdkman)
1. [Gradle and Maven](01%20-%20Primer.md#gradle-and-maven)
    1. [Advantages of Gradle over Maven](01%20-%20Primer.md#advantages-of-gradle-over-maven)
    1. [Install Gradle](01%20-%20Primer.md#install-gradle)
1. [IDE (IntelliJ IDEA and VS Code)](01%20-%20Primer.md#ide-intellij-idea-and-vs-code)
1. [Create a project using Gradle](01%20-%20Primer.md#create-a-project-using-gradle)
    1. [Create Project](01%20-%20Primer.md#create-project)
    1. [Explore Project](01%20-%20Primer.md#explore-project)
1. [Hello World Application (packaged as an executable application)](01%20-%20Primer.md#hello-world-application-packaged-as-an-executable-application)
    1. [Gradle Task Dependency Tree](01%20-%20Primer.md#gradle-task-dependency-tree)
    1. [Project Dependencies](01%20-%20Primer.md#project-dependencies)
    1. [Package Project](01%20-%20Primer.md#package-project)
1. [Docker](01%20-%20Primer.md#docker)
    1. [Setup Docker](01%20-%20Primer.md#setup-docker)
    1. [Dockerize the Application](01%20-%20Primer.md#dockerize-the-application)
    1. [Multi-Stage Docker Build](01%20-%20Primer.md#multi-stage-docker-build)
1. [Java Language Specification](01%20-%20Primer.md#java-language-specification)

### [Data Types](02%20-%20Data%20Types.md)

1. [JShell](02%20-%20Data%20Types.md#jshell)
1. [Numbers and Strings (Variables)](02%20-%20Data%20Types.md#numbers-and-strings-variables)
1. [Operators](02%20-%20Data%20Types.md#operators)
1. [Autoboxing](02%20-%20Data%20Types.md#autoboxing)
1. [Imports and Packages](02%20-%20Data%20Types.md#imports-and-packages)
1. [Date Time API](02%20-%20Data%20Types.md#date-time-api)
1. [Internationalization](02%20-%20Data%20Types.md#internationalization)

### [Classes, Methods and Control Flow](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md)

1. [Classes and methods (static no OOP)](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#classes-and-methods-static-no-oop)
1. [Properties (static no OOP)](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#properties-static-no-oop)
1. [Mutable and Immutable](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#mutable-and-immutable)
1. [Access Control](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#access-control)
1. [Control Flow and Loops](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#control-flow-and-loops)
    1. [Switch](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#switch)
1. [Exceptions](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#exceptions)
1. [Java Single File Execution](03%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#java-single-file-execution)

### [Testing](04%20-%20Testing.md)

1. [Testing with JUnit 5 (Hamcrest and AssertJ)](04%20-%20Testing.md#testing-with-junit-5-hamcrest-and-assertj)
    1. [Add JUnit 5](04%20-%20Testing.md#add-junit-5)
    1. [Parameterized Test](04%20-%20Testing.md#parameterized-test)
    1. [Custom Converters](04%20-%20Testing.md#custom-converters)
    1. [Tests Tagging](04%20-%20Testing.md#tests-tagging)
    1. [Nested Tests](04%20-%20Testing.md#nested-tests)
    1. [Hamcrest](04%20-%20Testing.md#hamcrest)
    1. [AssertJ](04%20-%20Testing.md#assertj)
    1. [JUnit 5, Hamcrest and AssertJ](04%20-%20Testing.md#junit-5-hamcrest-and-assertj)
    1. [Test Lifecycle](04%20-%20Testing.md#test-lifecycle)
1. [Mocking (Mockito and EasyMock)](04%20-%20Testing.md#mocking-mockito-and-easymock)
    1. [What is Mocking (Test Doubles) and Why do we need it?](04%20-%20Testing.md#what-is-mocking-test-doubles-and-why-do-we-need-it)
    1. [Test Doubles](04%20-%20Testing.md#test-doubles)
    1. [Mockito](04%20-%20Testing.md#mockito)
    1. [EasyMock](04%20-%20Testing.md#easymock)
    1. [Which Mocking Framework](04%20-%20Testing.md#which-mocking-framework)
1. [Mutation Testing (PIT)](04%20-%20Testing.md#mutation-testing-pit)
1. [Google Guava (Preconditions)](04%20-%20Testing.md#google-guava-preconditions)

### [Objects](05%20-%20Objects.md)

1. [Simple Objects](05%20-%20Objects.md#simple-objects)
    1. [Basic Object](05%20-%20Objects.md#basic-object)
    1. [Add State](05%20-%20Objects.md#add-state)
    1. [More State](05%20-%20Objects.md#more-state)
    1. [Multiple Instances](05%20-%20Objects.md#multiple-instances)
    1. [Mutable and Immutable](05%20-%20Objects.md#mutable-and-immutable)
1. [Inheritance](05%20-%20Objects.md#inheritance)
    1. [Light Box Example](05%20-%20Objects.md#light-box-example)
    1. [Heavy Box Example](05%20-%20Objects.md#heavy-box-example)
    1. [The `super` keyword](05%20-%20Objects.md#the-super-keyword)
    1. [The `final` keyword](05%20-%20Objects.md#the-final-keyword)
    1. [Private Constructor](05%20-%20Objects.md#private-constructor)
1. [Abstraction](05%20-%20Objects.md#abstraction)
    1. [When a class must be abstract?](05%20-%20Objects.md#when-a-class-must-be-abstract)
    1. [Final Classes](05%20-%20Objects.md#final-classes)
1. [The Object Class](05%20-%20Objects.md#the-object-class)
1. [Interfaces](05%20-%20Objects.md#interfaces)
1. [instanceof and cast operators](05%20-%20Objects.md#instanceof-and-cast-operators)
1. [Inheritance and Composition](05%20-%20Objects.md#inheritance-and-composition)
1. [Overloading and Overriding](05%20-%20Objects.md#overloading-and-overriding)
1. [Outer, Inner and Anonymous Classes](05%20-%20Objects.md#outer-inner-and-anonymous-classes)
1. [Enumerations](05%20-%20Objects.md#enumerations)
1. [Annotations](05%20-%20Objects.md#annotations)
1. [Generics](05%20-%20Objects.md#generics)

### [SOLID](06%20-%20SOLID.md)

1. [Single-responsibility principle](06%20-%20SOLID.md#single-responsibility-principle)
1. [Open–closed principle](06%20-%20SOLID.md#open-closed-principle)
1. [Liskov substitution principle](06%20-%20SOLID.md#liskov-substitution-principle)
1. [Interface segregation principle](06%20-%20SOLID.md#interface-segregation-principle)
1. [Dependency inversion principle](06%20-%20SOLID.md#dependency-inversion-principle)

### [Collections](07%20-%20Collections.md)

1. [Arrays](07%20-%20Collections.md#arrays)
    1. [Create Arrays](07%20-%20Collections.md#create-arrays)
    1. [Working with Arrays](07%20-%20Collections.md#working-with-arrays)
    1. [Multidimensional Arrays](07%20-%20Collections.md#multidimensional-arrays)
    1. [Arrays are always Mutable](07%20-%20Collections.md#arrays-are-always-mutable)
    1. [Defensive Copying](07%20-%20Collections.md#defensive-copying)
    1. [Arrays of Objects](07%20-%20Collections.md#arrays-of-objects)
    1. [Sorting and Searching](07%20-%20Collections.md#sorting-and-searching)
1. [Lists (ArrayList and Vector)](07%20-%20Collections.md#lists-arraylist-and-vector)
    1. [Create Lists](07%20-%20Collections.md#create-lists)
    1. [Types of Lists](07%20-%20Collections.md#types-of-lists)
    1. [Mutable and Immutable Lists](07%20-%20Collections.md#mutable-and-immutable-lists)
1. [Set (HashSet, linkedHashSet and TreeSet)](07%20-%20Collections.md#set-hashset-linkedhashset-and-treeset)
1. [Map (HashMap, LinkedHashMap and TreeMap)](07%20-%20Collections.md#map-hashmap-linkedhashmap-and-treemap)
1. [Queue and Stack](07%20-%20Collections.md#queue-and-stack)
1. [Java Collections Framework](07%20-%20Collections.md#java-collections-framework)
1. [Google Guava (Collections)](07%20-%20Collections.md#google-guava-collections)

### [Lambda](08%20-%20Lambda.md)

1. [Lambda Expressions](08%20-%20Lambda.md#lambda-expressions)
1. [Multiple Parameters](08%20-%20Lambda.md#multiple-parameters)
1. [Dealing with Exceptions](08%20-%20Lambda.md#dealing-with-exceptions)
1. [Foreach Loops](08%20-%20Lambda.md#foreach-loops)
1. [Streams (Lambda)](08%20-%20Lambda.md#streams-lambda)
1. [Mapping and Filtering](08%20-%20Lambda.md#mapping-and-filtering)
1. [Collectors](08%20-%20Lambda.md#collectors)

### [IO & Streams](09%20-%20IO%20&%20Streams.md)

1. [Files](09%20-%20IO%20&%20Streams.md#files)
1. [Java Streams](09%20-%20IO%20&%20Streams.md#java-streams)
1. [Java Non-Blocking IO](09%20-%20IO%20&%20Streams.md#java-non-blocking-io)
1. [HTTP Client (Java)](09%20-%20IO%20&%20Streams.md#http-client-java)

### [Databases](10%20-%20Databases.md)

1. [Data Sources (Hikari Connection Pool)](10%20-%20Databases.md#data-sources-hikari-connection-pool)
1. [H2, MySQL and PostgreSQL](10%20-%20Databases.md#h2-mysql-and-postgresql)
1. [Flyway (Database Migration)](10%20-%20Databases.md#flyway-database-migration)
1. [Statements, Prepared Statements, Result Sets](10%20-%20Databases.md#statements-prepared-statements-result-sets)
1. [Transactions](10%20-%20Databases.md#transactions)
1. [JOOQ](10%20-%20Databases.md#jooq)
1. [Query DSL](10%20-%20Databases.md#query-dsl)
1. [JPA and Hibernate](10%20-%20Databases.md#jpa-and-hibernate)

### [Concurrency](11%20-%20Concurrency.md)

1. [Threads](11%20-%20Concurrency.md#threads)
1. [Synchronized](11%20-%20Concurrency.md#synchronized)
1. [Deadlocks](11%20-%20Concurrency.md#deadlocks)
1. [Race Conditions](11%20-%20Concurrency.md#race-conditions)
1. [Executors and Schedulers](11%20-%20Concurrency.md#executors-and-schedulers)
1. [New Concurrent Primitives](11%20-%20Concurrency.md#new-concurrent-primitives)
1. [Fork Join Framework](11%20-%20Concurrency.md#fork-join-framework)

### [Common Design Patterns](12%20-%20Common%20Design%20Patterns.md)

1. [Creational Design Pattern](12%20-%20Common%20Design%20Patterns.md#creational-design-pattern)
    1. [Factory Pattern](12%20-%20Common%20Design%20Patterns.md#factory-pattern)
    1. [Abstract Factory Pattern](12%20-%20Common%20Design%20Patterns.md#abstract-factory-pattern)
    1. [Singleton Pattern](12%20-%20Common%20Design%20Patterns.md#singleton-pattern)
    1. [Prototype Pattern](12%20-%20Common%20Design%20Patterns.md#prototype-pattern)
    1. [Builder Pattern.](12%20-%20Common%20Design%20Patterns.md#builder-pattern)
1. [Structural Design Pattern](12%20-%20Common%20Design%20Patterns.md#structural-design-pattern)
    1. [Adapter Pattern](12%20-%20Common%20Design%20Patterns.md#adapter-pattern)
    1. [Bridge Pattern](12%20-%20Common%20Design%20Patterns.md#bridge-pattern)
    1. [Composite Pattern](12%20-%20Common%20Design%20Patterns.md#composite-pattern)
    1. [Decorator Pattern](12%20-%20Common%20Design%20Patterns.md#decorator-pattern)
    1. [Facade Pattern](12%20-%20Common%20Design%20Patterns.md#facade-pattern)
    1. [Flyweight Pattern](12%20-%20Common%20Design%20Patterns.md#flyweight-pattern)
    1. [Proxy Pattern](12%20-%20Common%20Design%20Patterns.md#proxy-pattern)
1. [Behavioral Design Pattern](12%20-%20Common%20Design%20Patterns.md#behavioral-design-pattern)
    1. [Chain Of Responsibility Pattern](12%20-%20Common%20Design%20Patterns.md#chain-of-responsibility-pattern)
    1. [Command Pattern](12%20-%20Common%20Design%20Patterns.md#command-pattern)
    1. [Interpreter Pattern](12%20-%20Common%20Design%20Patterns.md#interpreter-pattern)
    1. [Iterator Pattern](12%20-%20Common%20Design%20Patterns.md#iterator-pattern)
    1. [Mediator Pattern](12%20-%20Common%20Design%20Patterns.md#mediator-pattern)
    1. [Memento Pattern](12%20-%20Common%20Design%20Patterns.md#memento-pattern)
    1. [Observer Pattern](12%20-%20Common%20Design%20Patterns.md#observer-pattern)
    1. [State Pattern](12%20-%20Common%20Design%20Patterns.md#state-pattern)
    1. [Strategy Pattern](12%20-%20Common%20Design%20Patterns.md#strategy-pattern)
    1. [Template Pattern](12%20-%20Common%20Design%20Patterns.md#template-pattern)
    1. [Visitor Pattern](12%20-%20Common%20Design%20Patterns.md#visitor-pattern)
