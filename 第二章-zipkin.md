# 第二章 zipkin集成与实现

1.zipkin体系结构

![zipkin体系结构图](http://zipkin.io/public/img/architecture-1.png)
更多的说明:http://zipkin.io/pages/architecture.html

2.应用关键技术

|项目名称|项目地址|关键应用|备注|
| :-------- | --------:| :--: | :--: |
|brave|https://github.com/openzipkin/brave|zipkin java实现 | http、mysql等|
|zipkin-reporter-java|https://github.com/openzipkin/zipkin-reporter-java| http、kafka传输实现 |
|zipkin-ui|https://github.com/openzipkin/zipkin-ui|提供另外一种ui形式|暂未应用|

