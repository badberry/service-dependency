# dependency

### 说明
定义用strawberry开发微服务时所需要的依赖.pom继承自spring-boot-starter-parent.

### 添加的依赖
1. swagger support: 自动化的接口文档支持
2. etcd4j: 服务启动后自动注册到服务注册中心支持
3. rest-assured: 服务测试支持
4. commons-lang3: apache基础封装

### 使用说明
在需要用到的pom.xml中添加:
``` xml
<parent>
	<groupId>cn.cloudtop.strawberry</groupId>
	<artifactId>dependency-parent</artifactId>
	<version>1.0</version>
</parent>
```
