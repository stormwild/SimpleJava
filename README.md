# Maven By Example

[Maven by Example - 3.1. Introduction](https://books.sonatype.com/mvnex-book/reference/simple-project-sect-intro.html)

> When you run archetype:generate as shown below, the default maven-archetype-quickstart will be selected by default.

```sh
mvn archetype:generate \
-DgroupId=org.sonatype.mavenbook \
-DartifactId=simple \
-Dpackage=org.sonatype.mavenbook \
-Dversion=1.0-SNAPSHOT
```

Build the project

```sh
mvn install
```

Run the project

```sh
java -cp target/simple-1.0-SNAPSHOT.jar org.sonatype.mavenbook.App
```
