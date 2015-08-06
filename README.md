# 大数据方案(扯)


### 专有名词

##### docker 		<https://www.docker.com/>
大规模快速部署工具, 方便的持续集成工具,环境和开发部署工具.
使用镜像和版本控制存储系统.
也是云计算时代运维的关键工具.

假想使用环境:

1. 本地进入docker镜像开发,提交git, docer保存,git触发持续集成,测试服务器拉下最新docker镜像 自动部署 代码. (参见 daocloud, oschina云雀网  ), 可缩短部署流程步骤.
2. 快速的装上大数据 hadoop hive storm 等云环境,也可以快速进行水平扩展,例如买了一台云服务器,只需几条简单命令, 即可快速部署一台大数据分析节点.
2. 可将开发环境和部署环境一致化,因为docker镜像是版本控制式的.
3. 快速安装tomcat mongodb redis等环境  ,直接啦别人做好的镜像

##### hadoop 		 大数据基石

##### hive 		
hadoop 组件里的 数据查询组件,同样支持多种数据源, mysql,xml.

##### hbase 		
hadoop 组件里的 数据存储
hbase使用 php需要加载thrift库,
java和hadoop的结合最精密.

##### hdfs
hadoop 组件里的  文件存储系统,属于分布式文件存储.

##### mongodb 		<http://www.infoq.com/articles/mongodb-java-orm-bcd>
java上有完整的 访问库,包括了简单的mongodb库官方和
官方的orm库 ,php的开源库也很多.

##### cansandra
? 也是java流的nosql kv数据库...有待商榷

##### spark 	定位实时分析	<http://spark.apache.com>
与strom在实时分析的选择还有待考量.基于hadoop的大数据分析器,可以算作是hive+hadoop的强化版,因为在单机上全部使用内存访问,肯定要比hadoop用硬盘快.,支持mysql数据源
mysql,mongodb数据源,xml 等各种数据源.   但使用jvm的scala编写,需要简单学习下scala 语法.
视频教程:

1.	<http://boolan.com/course/29>
2.	<http://www.jikexueyuan.com/search/s/q_spark>

##### scala 		<http://www.typesafe.com/>
有差不多4年历史的jvm语言, 比另一个很流行的jvm groove差不多,
但语法更类似 ios的swift. 

##### R语言 		
老牌数据统计分析语言.

##### storm 	定位实时分析	
另一个twitter开源的 " 实时 "分析,具体和spark的差别有待讨论.

视频教程:

1. <http://www.jikexueyuan.com/search/s/q_storm>
2. <http://www.imooc.com/course/list?c=%E5%A4%A7%E6%95%B0%E6%8D%AE>








##关于需要查询到电子书下载
待续
