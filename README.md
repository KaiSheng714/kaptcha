# kaptcha - A kaptcha generation engine.

This repo is the fork of https://github.com/penggle/kaptcha.

I change it form gradle to maven and 2.3.3 version, and 

<artifactId>javax.servlet-api</artifactId>
<version>4.0.0</version>


This project has not been published to Maven Central, so you need to build and install the jar file locally.

```
mvn clean package

mvn install:install-file -Dfile=lib/kaptcha-2.3.3.jar -DgroupId=com.github.penggle -DartifactId=kaptcha -Dversion=2.3.3 -Dpackaging=jar
```

```
<dependency>
  <groupId>com.github.penggle</groupId>
  <artifactId>kaptcha</artifactId>
  <version>2.3.3</version>
</dependency>
```