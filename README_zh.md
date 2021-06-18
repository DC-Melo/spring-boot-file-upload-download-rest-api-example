# spring-boot-file-upload-download-rest-api-example

#### 项目背景
使用gradle,spring-boot 上传和现在文件

#### 软件架构
编译运行环境
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

#### 编译安装

1. 克隆仓库
```
git clone https://gitee.com/dc-melo/spring-boot-file-upload-download-rest-api-example.git

```
2. 修改上传文件地址
```
cd spring-boot-file-upload-download-rest-api-example
```
Open src/main/resources/application.properties file and change the property file.upload-dir to the path where you want the uploaded files to be stored.
file.upload-dir=uploads

3. 编译生成jar包
```
./gradlew build
```

#### 使用说明

1. 运行jar包

```
java -jar build/libs/file-demo-0.0.1-SNAPSHOT.jar 
```

2. 打开对应网站

在浏览器中打开：http://localhost:8080.

#### 项目负责人

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

#### 相关项目

#### 开源协议
