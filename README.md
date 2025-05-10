# Build instructions

Requirements:

- JDK 17
- Maven 3.9.x+

Build:

```bash
mvn clean install
```

Debian artifacts can be found in:

```bash
ls -l distrib/target/deb
```

`jdeb` configuration can be found in `distrib/pom.xml`.
