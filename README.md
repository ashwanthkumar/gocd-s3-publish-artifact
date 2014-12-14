# S3 Artifact Publish (Task Plugin)

Task Plugin that allows to push artifacts from pipeline to S3.

TODO: More details

## Compiling
In order to compile the project, you need to download the go-plugin-api-current.jar from the Go-Server. The best way is to install the 14.3.0 version of plugin in the `sdk/` folder using the below command.
```
mvn install:install-file -Dfile=sdk/go-plugin-api-current.jar -DgroupId=com.thoughtworks.go -DartifactId=go-plugin-api -Dversion=14.3.0 -Dpackaging=jar
```
