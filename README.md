# jenkins2-with-docker

#### Pull the docker image from docker hub.
```
docker run -p 8090:8080 -p 50000:50000 jenkins:2.7.1
```
#### Install maven
```
brew install maven
mvn -v
```
#### Compile the java source codes into java class
```
<Dir-of-src-code>$mvn compile
```
#### To test
```
mvn test
```
