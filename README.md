## archetype-jdk8

* JDK8
* Slf4j
* Log4j2
* Junit5
* Source Encoding : UTF8

### Install
+ Build and install to local repository
```
mvn install
```
+ Update catalog
```
mvn archetype:update-local-catalog
```
   
### Generate Project
```
mvn archetype:generate 
  -DgroupId=.. 
  -DartifactId=.. 
  -DarchetypeVersion=1.0-SNAPSHOT 
  -DarchetypeArtifactId=archetype-jdk8 
  -DarchetypeGroupId=me.yorick
```

### Import to Eclipse
+ Windows -> Preferences -> Maven -> Archetypes -> Add Local Catalog -> Browse
+ Select ~/.m2/repository/archetype-catalog.xml
