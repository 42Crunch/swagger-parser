# Swagger Parser

[![Build Status](https://travis-ci.org/swagger-api/swagger-parser.png)](https://travis-ci.org/swagger-api/swagger-parser)

## Overview
This is the swagger parser project, which reads and converts legacy swagger specifications into valid 2.0 versions.

## What's Swagger?

The goal of Swagger™ is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection. When properly defined via Swagger, a consumer can understand and interact with the remote service with a minimal amount of implementation logic. Similar to what interfaces have done for lower-level programming, Swagger removes the guesswork in calling the service.


Check out [Swagger-Spec](https://github.com/swagger-api/swagger-spec) for additional information about the Swagger project, including additional libraries with support for other languages and more. 


### Prerequisites
You need the following installed and available in your $PATH:

* [Java 1.7](http://java.oracle.com)

Note!  Some folks have had issues with OOM errors with java version "1.6.0_51".  It's strongly suggested that you upgrade to 1.7!

* [Apache maven 3.0.3 or greater](http://maven.apache.org/)

After cloning the project, you can build it from source with this command:

```
mvn package
```

### Usage in your project
You can include this library from Sonatype OSS for SNAPSHOTS, or Maven central for releases.  In your dependencies:

```xml
<dependency>
  <groupId>com.wordnik</groupId>
  <artifactId>swagger-parser</artifactId>
  <version>1.0.0-SNAPSHOT</version>
  <scope>compile</scope>
</dependency>

```
And add a repository reference to sonatype snapshots:

```xml
<repositories>
  <repository>
    <id>sonatype-snapshots</id>
    <url>https://oss.sonatype.org/content/repositories/snapshots</url>
    <snapshots>
      <enabled>true</enabled>
    </snapshots>
  </repository>
</repositories>
```

License
-------

Copyright 2014 Reverb Technologies, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
