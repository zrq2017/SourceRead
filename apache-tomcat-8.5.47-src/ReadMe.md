# Tomcat8源码阅读

1.启动类：org.apache.catalina.startup.Bootstrap

2.IDEA配置参数：

```shell
VM Options：
-Dcatalina.home=tomcat源码根目录/ 
-Dcatalina.base=tomcat源码根目录/   
-Djava.endorsed.dirs=tomcat源码根目录/endorsed 
-Djava.io.tmpdir=tomcat源码根目录/temp   
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager   
-Djava.util.logging.config.file=tomcat源码根目录/conf/logging.properties
```

3.官方下载源码使用localhost:8080出现JSP解析错误，参见Bootstrap中的静态初始化部分解决问题