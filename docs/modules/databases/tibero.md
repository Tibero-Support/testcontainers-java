# QuestDB Module

Testcontainers module for [Tibero](https://www.tibero.com/). 

See [Database containers](./index.md) for documentation and usage that is common to all relational database container
types.

## Adding this module to your project dependencies

Add the following dependency to your `pom.xml`/`build.gradle` file:

=== "Gradle"

```groovy
testImplementation "org.testcontainers:tibero:{{latest_version}}"
```

=== "Maven"

```xml

<dependency>
    <groupId>org.testcontainers</groupId>
    <artifactId>tibero</artifactId>
    <version>{{latest_version}}</version>
    <scope>test</scope>
</dependency>
```
