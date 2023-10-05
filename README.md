## Steps to create
Followed guide: https://guides.micronaut.io/latest/creating-your-first-micronaut-app-gradle-java.html
```
mn create-app example.micronaut.micronautguide --build=gradle --lang=java
```

### Gradle Dependencies
```
./gradlew -q dependencies > ref/gradle-dependencies.txt
```

### Grype

```
grype directory --file build/libs/micronautguide-0.1-all.jar
```


### Creating Docker Image
```
./gradlew dockerBuild
```
