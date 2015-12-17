# 玩转Spring Data Repositories
抽象出Spring Data repository是因为在开发过程中，常常会为了实现不同持久化存储的数据访问层而写大量的大同小异的代码。Spring Data repository的目的就是要大幅减少这些重复的代码。

>本章阐述了Spring Data repository的核心概念及接口。本章的内容来自Spring data的公共模块，配置和样例代码来自Java Persistence Api(JPA)模块。如有需要，可以将XML文件的命名空间调整到你所使用特定模块。[命名空间参考文档](../6/6.1.md)涵盖了所有支持Repository API的Spring Data模块的XML配置。[Repository查询关键字说明文档](../6/6.3.md)内列出了repository支持的查询方法的关键字。如果想要了解其他特定模块的详细信息，可以查询指定模块的参考文档。