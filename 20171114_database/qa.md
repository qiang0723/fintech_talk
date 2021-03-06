## 答疑解惑

**问：大数据区块链等新概念的出现是否意味着数据库技术的发展现在碰到了瓶颈？**

答：我觉得区块链技术是从另外一个方面补充了传统数据库。正如stonebrake所说，one size does not fit all。在一些新的应用场景之下，特别是在许多参与方没有建立信任关系的前提之下，目前很多数据库管理技术（基于集中式架构）确实无法使用。区块链恰巧能够适应这样的应用场景。将区块链技术与数据库技术相融合，能够解决更多的领域问题。


**问：数据库领域的相关背景给研究区块链技术带来哪些优势？**

答：我觉得有很强的促进意义。因为区块链技术从发展到现在为止，真正在数据管理方面的着眼点还不太多。我们通常说的数据管理，往往是指查询语言，存储与索引，数据库模式，数据库范式，事务管理等概念。但是从目前来看，很多区块链技术并没有达到这个要求。将现有的数据库技术融入到区块链系统中去，我认为至少在便捷性和高效性方面会有很大意义。

**问：加密盲抽选取共识节点和刚才金老师说的可信随机集合工程实现有哪些突破？**

答：我不是特别理解“加密盲抽选取共识节点”所指。不知道是否就是我前面提到的那个。我前面所说的就是随机采样。一个通俗的解释就是说：假设一个袋子中有1000个球，其中有100个是红球，其余是黑球。那么，任意随机取少数球（比如说取50个球），则平均下来有5个是红球。同时，从概率意义上来讲，红球的数量非常偏离均值的概率也不会太高。例如，具有超过10个红球的概率也不会太高。这是由大数定理决定的。那么，假设红球是不诚实节点，黑球是诚实节点。一般意义上可以认为即使取一个小的样本集合，也是能够保证诚实节点的数量占多数的。这样的话，就能够达到sharding的效果。
