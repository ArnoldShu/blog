# 关于我

java工程师，有一位我很爱同时也很爱我的傻乎乎的未婚妻。



# 热爱
java技术栈的所有相关技术(虽然可能技术并不是每项技术都很厉害)
家事国事天下事,事事关心的微胖少年,有趣且逐渐懂事的痞气Boy
看书音乐都还蛮喜欢



# 关于本站
本站有一些文章可成系列，多为平时工作总结和看书所得,摘记以供回味学习,其余文章则随心所致。
## 一、开发环境
## 二、知识总结
 - [Maven学习浅记-常用命令及相关概念](https://blog.csdn.net/qq_20340547/article/details/103547879)
 - [Java注解以及自定义注解总结](https://blog.csdn.net/qq_20340547/article/details/103549373)
 - [docker摘记-docker相关知识点总结摘要](https://blog.csdn.net/qq_20340547/article/details/103848953)
 - [Zookeeper学习记录及简单上手代码展示](https://blog.csdn.net/qq_20340547/article/details/104585659)
 - [Kafka学习记录及简单上手代码](https://blog.csdn.net/qq_20340547/article/details/104736172)
 - [ELK日志管理解决方案浅探(Elasticsearch、Logstash、Kibana)](https://blog.csdn.net/qq_20340547/article/details/105273918)
 - [centos7虚拟机(VMware 12 Pro)静态IP配置](https://blog.csdn.net/qq_20340547/article/details/108737639)
 - [Netty知识点摘记](https://blog.csdn.net/qq_20340547/article/details/107994197)
 - [Hexo个人blog搭建(Centos7)](https://blog.csdn.net/qq_20340547/article/details/109731776)
 - [Nginx上手记录](https://blog.csdn.net/qq_20340547/article/details/109330412)
 - [Docker运用过程问题记载(持续更新累加)](https://blog.csdn.net/qq_20340547/article/details/109616486)
 - [Git常用命令记载(持续记录更新...)](https://blog.csdn.net/qq_20340547/article/details/111611061)


## 三、常用工具

 - [Hutool工具包](https://www.hutool.cn/)

## 四、代码工具包
## 五、代码规范

 - 所有入数据库数据都要校验合法性,其他的过滤和标志字段**都要有默认值且不能为null**
 - 代码交互中的所有数据都要做**合法性校验**,不能导致代码运行时异常的出现
 - 代码中如果有**递归操作**,一定要做**递归跳出逻辑处理**
 - 给前端的数据字段信息尽量保持数据字段与参数字段一致,如果出现不一致情况注释应标明并且口头告知对接人相关信息
 - Java实体以及返回的视图类都加上数据类型的**默认值**,对象类型赋**null**
 - 严格按照**高内聚低耦合**设计代码,最好做到一个方法完成特定的一项功能,注意方法拆分,杜绝一个方法多个功能
 - 最底层的**通用方法参数以基本数据类型为主**,增强方法通用性

## 六、Bug排查步骤

 - 确定用户操作步骤是否无误
 - 确定用户填写数据是否合法有效且录入数据库无误
 - 确定用户数据时间查询范围是否与展现预期一致
 - 确定程序逻辑是否存在错误

## 七、工作流程规范

 - 开工之前,获取最新代码,下班之前,提交工作完成代码(不影响项目整体稳定)
 - 操作Linux文件,先备份在操作

## 八、数据库设计

 - 表名一般以【**模块名称_具体表名**】来实现，同一个模块的前缀是一样的
 - 一些作为多对多连接的表，可以使用两个表的前缀作为表名：如：用户登录表User_Login，用户分组表User_GroupInfo，这两个表建立多对多关系的表名为：User_Group_Relation（关系统一用Relation）且表之间的关联字段一致
 - 数据库中应建立这样一个表，就是**数据库本身的字段信息，表的说明**，也就是数据库设计文档的一个表，方便查询使用，有什么不明的可以直接从数据库查询，数据库文档丢失，注释丢失，都可以重新起作用

## 九、每日学习计划安排

 - 白天短时间可观看学习视频,晚上可敲实践代码,搭建框架





# 版权与协议
若无特殊说明，本站所有文章均为原创文章，并遵循 CC BY-SA 4.0 协议发布。

你可以自由地对博客中内容进行分享、创作演绎直至商业性的使用，但必须在文章末尾或参考文献处注明文章的出处（文章链接）。完整的[协议](https://creativecommons.org/licenses/by-nc-sa/4.0/)可以参看这里。