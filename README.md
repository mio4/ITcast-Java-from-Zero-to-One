# SSM-Mall

SSM框架搭建一个简易商城

### 说明

- JDK 1.7
- tomcat 7
- mysql 5.7

### 项目进度

- [x] 配置Maven本地仓库【修改Eclipse默认仓库】
- [x] 搭建Maven工程框架【War包 + Jar包 + POM包】
- [x] 整合：Spring  + Spring MVC + MyBatis xml配置文件



---

## Learn

- [ ] quartz框架
- [ ] druid连接池
- [ ] solr
- [ ] dubbo
- [ ] zookeeper

---

## 项目架构

- mall-parent

  - mall-common

  - mall-manager [ service dao interface pojo]
  - mall-manager-web

### MySQL

- Windows环境：`net stop mysql` `net start mysql`
- [Mysql导入大容量SQL文件数据问题](https://www.2cto.com/database/201206/134420.html) 
  - 首先修改my.ini文件中character为utf8，同时修改max_allowed_packet
  - 在MySQL中set names 'utf8';
  - source 文件路径

### Maven

> 在Eclipse环境下使用maven管理项目

- `run as maven install` 将项目安装到本地仓库
- `clean tomcat7:run` 使用apache tomcat7运行项目

### MyBatis逆向

> 逆向工程：通过数据库表结构生成对应的接口和POJO类

- `generatorConfig.xml` 配置数据库信息
- `run as application` 运行main方法

### xml配置文件

so much to learn...

### dubbo









































