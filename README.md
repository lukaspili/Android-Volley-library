Android Volley gradle library
=============================

Include volley as jar dependency in your pom.xml or build.gradle.

1. Clone the repo
2. `mvn clean install`

It pushes the volley jar in your local maven repository.
Next, you can include the dependency in your projects using maven or gradle.


Dependency for `pom.xml`:

```xml
<dependency>
  <groupId>com.google.volley</groupId>
  <artifactId>volley</artifactId>
  <version>1.0.0-SNAPSHOT</version>
  <packaging>jar</packaging>
</dependency>
```

Dependency for `build.gradle`:

```groovy
repositories {
    mavenCentral()
    mavenLocal()
}

dependencies {
  compile 'com.google.volley:volley:1.0.0-SNAPSHOT'
}
```

