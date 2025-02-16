# TNetwork

[![Maven Central Version](https://img.shields.io/maven-central/v/one.tranic/t-network)](https://central.sonatype.com/artifact/one.tranic/t-network)
[![javadoc](https://javadoc.io/badge2/one.tranic/t-network/javadoc.svg)](https://javadoc.io/doc/one.tranic/t-network)

No need to install TLIB Base, need Java 17.

## Install
Please use shadow to remap TNetwork to your own path to avoid conflicts with other libraries/plugins using TProxy.

`maven`

```xml
<dependency>
    <groupId>one.tranic</groupId>
    <artifactId>t-network</artifactId>
    <version>[VERSION]</version>
</dependency>
```

`Gradle (Groovy)`
```groovy
repositories {
    mavenCentral()
}

dependencies {
    implementation 'one.tranic:t-network:[VERSION]'
}
```

`Gradle (Kotlin DSL)`
```kotlin
repositories {
    mavenCentral()
}

dependencies {
    implementation("one.tranic:t-network:[VERSION]")
}
```