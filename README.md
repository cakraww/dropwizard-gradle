A minimal Dropwizard getting started project using Gradle. Use [shadowJar plugin](https://github.com/johnrengelman/shadow) to create fat jars. 

To create a fat jar:
```
./gradlew shadowJar
```

To run your application:
```
java -jar build/libs/dropwizard-gradle-1.0-SNAPSHOT-all.jar server hello-world.yml
```

To build and run your application:
```
./gradlew runServer
```
This command runs both first two commands above. There will be gradle output stuck at the bottom of the output and it is normal.