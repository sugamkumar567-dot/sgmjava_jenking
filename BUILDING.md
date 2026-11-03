# Building

The Java source is built with Apache Maven and requires JDK 17 or newer.

```powershell
mvn clean package
java -cp target/classes Main
```

`Main.java` remains in the project root; the Maven compiler configuration includes that source file.
