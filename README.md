spring-boot-dubbox
=====

```
$ git clone https://github.com/dangdangdotcom/dubbox.git
$ mvn install -Dmaven.test.skip=true
```

```xml
<dependency>
    <groupId>com.alibaba</groupId>
    <artifactId>dubbo</artifactId>
    <version>2.8.4</version>
    <exclusions>
        <exclusion>
            <groupId>org.springframework</groupId>
            <artifactId>spring</artifactId>
        </exclusion>
    </exclusions>
</dependency>

<dependency>
    <groupId>cn.stackbox.boot</groupId>
    <artifactId>spring-boot-starter-dubbo</artifactId>
    <version>1.0.0-SNAPSHOT</version>
</dependency>
```
