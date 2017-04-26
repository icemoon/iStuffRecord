# 分布式(Distributed)资料

--------

* [Spanner: Google's Globally-Distributed Database](https://research.google.com/archive/spanner.html)([中文](http://dblab.xmu.edu.cn/wp-content/uploads/2012/09/20120925_094508_876.pdf))
google的全球分布式系统介绍

* [Windows Azure Storage: A Highly Available Cloud Storage Service with Strong Consistency](http://www-bcf.usc.edu/~minlanyu/teach/csci599-fall12/papers/11-calder.pdf)
微软的分布式存储平台, 主要技术特点：采用Stream/Partition两层设计（类似BigTable）;写错（写满）就封存Extent,使得副本字节一致, 简化了选主和恢复操作; 将S3对象存储、表格、队列、块设备等融入到统一的底层存储架构中

* [Erasure Coding in Windows Azure Storage](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/LRC12-cheng20webpage.pdf)
微软云计算的EC策略，6+2+2的分析，主要降低one failover的重建代价，在one failover的情况下可降低一半

--------

* [VLDB 2016 Paper](http://www.vldb.org/pvldb/vol9.html)
记录VLDB 2016的发表论文

* [SIGMOD 2016 Paper](http://sigmod2016.org/pods_list.shtml)
记录SIGMOD 2016的发表论文

* [ICDE 2016 Paper](http://icde2016.fi/papers.php)
记录ICDE 2016的发表论文

