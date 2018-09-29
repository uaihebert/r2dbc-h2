# Reactive Relational Database Connectivity H2 Implementation

This project contains the [H2][h] implementation of the [R2DBC SPI][r].  This implementation is not inteded to be used directly, but rather to be used as the backing implementation for a humane client library to delegate to

[h]: https://www.h2database.com/html/main.html
[r]: https://github.com/r2dbc/r2dbc-spi

**THIS IS ONLY AN EXPERIMENT AND NOT SUPPORTED SOFTWARE**

## Maven
Both milestone and snapshot artifacts (library, source, and javadoc) can be found in Maven repositories.

```xml
<dependency>
  <groupId>io.r2dbc</groupId>
  <artifactId>r2dbc-h2</artifactId>
  <version>1.0.0.M5</version>
</dependency>
```

Artifacts can bound found at the following repositories.

### Repositories
```xml
<repository>
    <id>spring-snapshots</id>
    <name>Spring Snapshots</name>
    <url>https://repo.spring.io/snapshot</url>
    <snapshots>
        <enabled>true</enabled>
    </snapshots>
</repository>
```

```xml
<repository>
    <id>spring-milestones</id>
    <name>Spring Milestones</name>
    <url>https://repo.spring.io/milestone</url>
    <snapshots>
        <enabled>false</enabled>
    </snapshots>
</repository>
```

## License
This project is released under version 2.0 of the [Apache License][l].

[l]: https://www.apache.org/licenses/LICENSE-2.0
