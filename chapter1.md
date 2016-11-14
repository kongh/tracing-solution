# zipkin搭建

1.下载zipkin
<pre>
> wget -O zipkin.jar 'https://search.maven.org/remote_content?g=io.zipkin.java&a=zipkin-server&v=LATEST&c=exec' 
> java -jar zipkin.jar
</pre>

2.访问http://localhost:9411/

3.zipkin的存储策略

|存储策略|存储实现|备注|
| :-------- | --------:| :--: |
|内存存储策略|InMemoryStorage|默认,测试使用|
|MySQL存储策略|MySQLStorage|大量数据时，存在查询耗时问题|
|Cassandra存储策略|CassandraStorage||
|Elasticsearch存储策略|ElasticsearchStorage||


