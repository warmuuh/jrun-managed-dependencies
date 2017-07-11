resolved dependencies of project

```
[INFO] --- maven-dependency-plugin:2.10:resolve (default-cli) @ demo ---
[INFO]
[INFO] The following files have been resolved:
[INFO]    org.springframework.boot:spring-boot-starter:jar:2.0.0.M2:compile
[INFO]    org.skyscreamer:jsonassert:jar:1.5.0:test
[INFO]    org.springframework.boot:spring-boot-starter-logging:jar:2.0.0.M2:compile
[INFO]    net.bytebuddy:byte-buddy:jar:1.6.14:test
[INFO]    org.eclipse.jetty:jetty-webapp:jar:9.4.6.v20170531:compile
[INFO]    org.hamcrest:hamcrest-library:jar:1.3:test
[INFO]    org.eclipse.jetty:jetty-continuation:jar:9.4.6.v20170531:compile
[INFO]    org.springframework:spring-aop:jar:5.0.0.RC2:compile
[INFO]    org.eclipse.jetty:jetty-servlets:jar:9.4.6.v20170531:compile
[INFO]    org.assertj:assertj-core:jar:3.8.0:test
[INFO]    net.bytebuddy:byte-buddy-agent:jar:1.6.14:test
[INFO]    ch.qos.logback:logback-classic:jar:1.2.3:compile
[INFO]    com.github.jknack:handlebars:jar:4.0.6:compile
[INFO]    org.springframework.boot:spring-boot-starter-test:jar:2.0.0.M2:test
[INFO]    org.apache.httpcomponents:httpcore:jar:4.4.6:compile
[INFO]    org.hamcrest:hamcrest-core:jar:1.3:test
[INFO]    org.springframework:spring-expression:jar:5.0.0.RC2:compile
[INFO]    org.eclipse.jetty:jetty-util:jar:9.4.6.v20170531:compile
[INFO]    com.jayway.jsonpath:json-path:jar:2.2.0:compile
[INFO]    org.apache.commons:commons-lang3:jar:3.5:compile
[INFO]    org.springframework.boot:spring-boot-test-autoconfigure:jar:2.0.0.M2:test
[INFO]    org.springframework:spring-context:jar:5.0.0.RC2:compile
[INFO]    org.xmlunit:xmlunit-core:jar:2.3.0:compile
[INFO]    org.yaml:snakeyaml:jar:1.18:runtime
[INFO]    org.antlr:antlr4-runtime:jar:4.5.1-1:compile
[INFO]    org.eclipse.jetty:jetty-servlet:jar:9.4.6.v20170531:compile
[INFO]    com.github.tomakehurst:wiremock:jar:2.6.0:compile
[INFO]    org.springframework:spring-jcl:jar:5.0.0.RC2:compile
[INFO]    com.fasterxml.jackson.core:jackson-core:jar:2.9.0.pr3:compile
[INFO]    org.eclipse.jetty:jetty-http:jar:9.4.6.v20170531:compile
[INFO]    org.apache.httpcomponents:httpclient:jar:4.5.3:compile
[INFO]    org.ow2.asm:asm:jar:5.0.3:compile
[INFO]    com.flipkart.zjsonpatch:zjsonpatch:jar:0.3.0:compile
[INFO]    org.springframework.boot:spring-boot-test:jar:2.0.0.M2:test
[INFO]    org.slf4j:log4j-over-slf4j:jar:1.7.25:compile
[INFO]    org.eclipse.jetty:jetty-io:jar:9.4.6.v20170531:compile
[INFO]    org.springframework.boot:spring-boot:jar:2.0.0.M2:compile
[INFO]    org.eclipse.jetty:jetty-security:jar:9.4.6.v20170531:compile
[INFO]    ch.qos.logback:logback-core:jar:1.2.3:compile
[INFO]    org.xmlunit:xmlunit-legacy:jar:2.3.0:compile
[INFO]    org.apache.commons:commons-collections4:jar:4.1:compile
[INFO]    commons-codec:commons-codec:jar:1.10:compile
[INFO]    com.fasterxml.jackson.core:jackson-annotations:jar:2.9.0.pr3:compile
[INFO]    org.springframework:spring-beans:jar:5.0.0.RC2:compile
[INFO]    org.objenesis:objenesis:jar:2.5:test
[INFO]    com.fasterxml.jackson.core:jackson-databind:jar:2.9.0.pr3:compile
[INFO]    org.springframework.boot:spring-boot-autoconfigure:jar:2.0.0.M2:compile
[INFO]    javax.servlet:javax.servlet-api:jar:3.1.0:compile
[INFO]    org.springframework:spring-core:jar:5.0.0.RC2:compile
[INFO]    org.mockito:mockito-core:jar:2.8.9:test
[INFO]    junit:junit:jar:4.12:compile
[INFO]    net.sf.jopt-simple:jopt-simple:jar:4.9:compile
[INFO]    com.google.guava:guava:jar:18.0:compile
[INFO]    org.slf4j:slf4j-api:jar:1.7.25:compile
[INFO]    org.eclipse.jetty:jetty-server:jar:9.4.6.v20170531:compile
[INFO]    net.minidev:json-smart:jar:2.2.1:compile
[INFO]    net.minidev:accessors-smart:jar:1.1:compile
[INFO]    com.vaadin.external.google:android-json:jar:0.0.20131108.vaadin1:test
[INFO]    org.springframework:spring-test:jar:5.0.0.RC2:test
[INFO]    org.slf4j:jul-to-slf4j:jar:1.7.25:compile
[INFO]    org.eclipse.jetty:jetty-xml:jar:9.4.6.v20170531:compile
```


usign jitpack. in .jrunrc:
```
[repositories]
jit = https://jitpack.io
```

run with 
``` 
jrun com.github.warmuuh:jrun-managed-dependencies:0.0.1
```

resolved dependencies:
```
pmucha@mock-6457:~/.jrun/com.github.warmuuh/jrun-managed-dependencies/0.0.1$ ls
accessors-smart-1.1.jar        jackson-databind-2.6.1.jar               jrun-managed-dependencies-0.0.1.jar  spring-beans-5.0.0.RC2.jar
antlr4-runtime-4.5.1-1.jar     javax.servlet-api-3.1.0.jar              json-path-2.2.0.jar                  spring-boot-2.0.0.M2.jar
asm-5.0.3.jar                  jetty-continuation-9.2.13.v20150730.jar  json-smart-2.2.1.jar                 spring-boot-autoconfigure-2.0.0.M2.jar
commons-codec-1.9.jar          jetty-http-9.2.13.v20150730.jar          jul-to-slf4j-1.7.25.jar              spring-boot-starter-2.0.0.M2.jar
commons-collections4-4.1.jar   jetty-io-9.2.13.v20150730.jar            junit-4.12.jar                       spring-boot-starter-logging-2.0.0.M2.jar
commons-lang3-3.4.jar          jetty-security-9.2.13.v20150730.jar      log4j-over-slf4j-1.7.25.jar          spring-context-5.0.0.RC2.jar
commons-logging-1.2.jar        jetty-server-9.2.13.v20150730.jar        logback-classic-1.2.3.jar            spring-core-5.0.0.RC2.jar
guava-18.0.jar                 jetty-servlet-9.2.13.v20150730.jar       logback-core-1.2.3.jar               spring-expression-5.0.0.RC2.jar
handlebars-4.0.6.jar           jetty-servlets-9.2.13.v20150730.jar      mainClass                            spring-jcl-5.0.0.RC2.jar
httpclient-4.5.1.jar           jetty-util-9.2.13.v20150730.jar          pom.xml                              wiremock-2.6.0.jar
httpcore-4.4.3.jar             jetty-webapp-9.2.13.v20150730.jar        slf4j-api-1.7.12.jar                 xmlunit-core-2.3.0.jar
jackson-annotations-2.6.1.jar  jetty-xml-9.2.13.v20150730.jar           snakeyaml-1.18.jar                   xmlunit-legacy-2.3.0.jar
jackson-core-2.6.1.jar         jopt-simple-4.9.jar                      spring-aop-5.0.0.RC2.jar             zjsonpatch-0.3.0.jar
```

=> for example different jackson version
