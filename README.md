
# spring-boot-file-upload-download-rest-api-example

# Background
Uploading an Downloading files with Spring Boot

# Enviroment
```
$ uname -a
Linux wtdcserver 5.4.0-73-generic #82~18.04.1-Ubuntu SMP Fri Apr 16 15:10:02 UTC 2021 x86_64 x86_64 x86_64 GNU/Linux
$ java -version
java version "13.0.1" 2019-10-15
Java(TM) SE Runtime Environment (build 13.0.1+9)
Java HotSpot(TM) 64-Bit Server VM (build 13.0.1+9, mixed mode, sharing)
$ gradle -version
------------------------------------------------------------
Gradle 7.0.2
------------------------------------------------------------
```

#### Build and Install
1. Clone the repository
```
git clone https://gitee.com/dc-melo/spring-boot-file-upload-download-rest-api-example.git

```
2. Specify the file uploads directory
```
cd spring-boot-file-upload-download-rest-api-example
```
Open src/main/resources/application.properties file and change the property file.upload-dir to the path where you want the uploaded files to be stored.
file.upload-dir=uploads

3. build the application 
```
./gradlew build
```
![spring_web_build](readme_files/spring_web_build.png)

#### Usage
1. run the jar application

```
java -jar target/file-demo-0.0.1-SNAPSHOT.jar
```
![spring_web_run](readme_files/spring_web_run.png)

2. open the web 

That's it! The application can be accessed at http://localhost:8080.
![spring_web_result](readme_files/spring_web_result.png)

#### Badge

#### Maintainers

#### Related Efforts

#### Related Project

#### License
