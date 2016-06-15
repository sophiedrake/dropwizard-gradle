# Dropwizard Gradle

Skeleton project for Dropwizard and Gradle, based on the [Dropwizard
getting started guide](http://www.dropwizard.io/0.9.2/docs/getting-started.html)

## Endpoints 

```
 GET     /hello-world (com.example.resources.HelloWorldResource)
 
```

## Run Service

To run:

```
./gradlew run
```

To compile:

```
./gradlew oneJar
```

To run the jar:

```
java -jar build/libs/basic-dropwizard-standalone.jar server config.yml
```

To test:

```
./gradlew test
```
