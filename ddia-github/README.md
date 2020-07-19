# 设计数据密集型应用 - 中文翻译 

- 作者： [Martin Kleppmann](https://martin.kleppmann.com)
- 原书名称：[《Designing Data-Intensive Application》](http://shop.oreilly.com/product/0636920032175.do)
- 译者：[冯若航]( http://vonng.com/about) （fengruohang@outlook.com ）
- Gitbook地址：[ddia-cn](https://www.gitbook.com/book/vonng/ddia-cn)
- 使用[Typora](https://www.typora.io)或Gitbook以获取最佳阅读体验。




## 译序

> 不懂数据库的全栈工程师不是好架构师
>
> —— Vonng

​	现今，尤其是在互联网领域，大多数应用都属于数据密集型应用。本书从底层数据结构到顶层架构设计，将数据系统设计中的精髓娓娓道来。其中的宝贵经验无论是对架构师，DBA、还是后端工程师、甚至产品经理都会有帮助。

​	这是一本理论结合实践的书，书中很多问题，译者在实际场景中都曾遇到过，读来让人击节扼腕。如果能早点读到这本书，该少走多少弯路啊！

​	这也是一本深入浅出的书，讲述概念的来龙去脉而不是卖弄定义，介绍事物发展演化历程而不是事实堆砌，将复杂的概念讲述的浅显易懂，但又直击本质不失深度。每章最后的引用质量非常好，是深入学习各个主题的绝佳索引。

​	本书为数据系统的设计、实现、与评价提供了很好的概念框架。读完并理解本书内容后，读者可以轻松看破大多数的技术忽悠，与技术砖家撕起来虎虎生风🤣。

​	这是2017年译者读过最好的一本技术类书籍，这么好的书没有中文翻译，实在是遗憾。某不才，愿为先进技术文化的传播贡献一分力量。既可以深入学习有趣的技术主题，又可以锻炼中英文语言文字功底，何乐而不为？



## 前言

> 在我们的社会中，技术是一种强大的力量。数据、软件、通信可以用于坏的方面：不公平的阶级固化，损害公民权利，保护既得利益集团。但也可以用于好的方面：让底层人民发出自己的声音，让每个人都拥有机会，避免灾难。本书献给所有将技术用于善途的人们。

---------

> 计算是一种流行文化，流行文化鄙视历史。 流行文化关乎个体身份和参与感，但与合作无关。流行文化活在当下，也与过去和未来无关。 我认为大部分（为了钱）编写代码的人就是这样的， 他们不知道自己的文化来自哪里。                         
>
>  ——阿兰·凯接受Dobb博士的杂志采访时（2012年）



## 目录

### [序言](preface.md)

### [第一部分：数据系统的基石](part-i.md)

* [第一章：可靠性、可扩展性、可维护性](ch1.md) 
* [第二章：数据模型与查询语言](ch2.md)
* [第三章：存储与检索](ch3.md) 
* [第四章：编码与演化](ch4.md)

### [第二部分：分布式数据](part-ii.md)

* [第五章：复制](ch5.md) 
* [第六章：分区](ch6.md) 
* [第七章：事务](ch7.md) 
* [第八章：分布式系统的麻烦](ch8.md) 
* [第九章：一致性与共识](ch9.md) 

### [第三部分：衍生数据](part-iii.md)

* [第十章：批处理](ch10.md) 
* [第十一章：流处理](ch11.md) 
* [第十二章：数据系统的未来](ch12.md) 

### [术语表](glossary.md)

### [后记](colophon.md)



## 法律声明

从原作者处得知，已经有简体中文的翻译计划，将于2018年末完成。

译者纯粹出于**学习目的**与**个人兴趣**翻译本书，不追求任何经济利益。

译者保留对此版本译文的署名权，其他权利以原作者和出版社的主张为准。

本译文只供学习研究参考之用，不得公开传播发行或用于商业用途。有能力阅读英文书籍者请购买正版支持。



## CONTRIBUTION

1. [序言初翻修正](https://github.com/Vonng/ddia/commit/afb5edab55c62ed23474149f229677e3b42dfc2c) by [@seagullbird](https://github.com/Vonng/ddia/commits?author=seagullbird)
2. [第一章语法标点校正](https://github.com/Vonng/ddia/commit/973b12cd8f8fcdf4852f1eb1649ddd9d187e3644) by [@nevertiree](https://github.com/Vonng/ddia/commits?author=nevertiree)
3. [第六章部分校正](https://github.com/Vonng/ddia/commit/d4eb0852c0ec1e93c8aacc496c80b915bb1e6d48) 与[第10章的初翻](https://github.com/Vonng/ddia/commit/9de8dbd1bfe6fbb03b3bf6c1a1aa2291aed2490e) by @[MuAlex](https://github.com/Vonng/ddia/commits?author=MuAlex) 
4. 第一部分前言，ch2校正 by @jiajiadebug
5. 词汇表、后记关于野猪的部分 by @[Chowss](https://github.com/Vonng/ddia/commits?author=Chowss)

https://github.com/Vonng/ddia/pulls)

感谢所有作出贡献，提出意见的朋友们：[Issues](https://github.com/Vonng/ddia/issues)，[Pull Requests](https://github.com/Vonng/ddia/pulls)



## LICENSE

CC-BY 4.0