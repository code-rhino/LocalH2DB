Run H2 Server Locally

For screen shots and more detailed instructions please look at instructions.pdf

In the project folder , build the project using MVN

```
mvn install -DskipTests
```

Once the Project is built to start in terminal or gitbash

```
java -jar target/local-h2-server-0.0.1-SNAPSHOT.jar
```