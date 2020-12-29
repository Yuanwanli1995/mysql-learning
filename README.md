# mysql-learning
这里是关系型数据mysql学习资料的整理。 包括学习书籍，教程，文章，博客等汇总  

### 书籍
- 《mysql必知必会》

    书中从介绍简单的数据检索开始，逐步深入一些复杂的内容，包括联结的使用、子查询、正则表达式和基于全文本的搜索、存储过程、游标、触发器、表约束，等等。通过重点突出的章节，条理清晰、系统而扼要地讲述了读者应该掌握的知识，使他们不经意间立刻功力大增。非常适合入门的一本书，跟着书中走慢慢掌握基础实践。作者Ben Forta是世界知名的技术作家，也是Adobe技术界最为知名的专家之一，目前担任Adobe公司的高级技术推广专家。
- 《高性能MySQL》

   MySQL 领域的经典之作，拥有广泛的影响力。第3 版更新了大量的内容，不但涵盖了最新mysql 5.5版本的新特性，也讲述了关于固态盘、高可扩展性设计和云计算环境下的数据库相关的新内容，原有的基准测试和性能优化部分也做了大量的扩展和补充
- 《MySQL技术内幕:InnoDB存储引擎》 

  本书宏观地介绍了MySQL的体系结构和各种常见的存储引擎以及它们之间的比较；接着以InnoDB的内部实现为切入点，逐一详细讲解了InnoDB存储引擎内部的各个功能模块的实现原理，包括InnoDB存储引擎的体系结构、内存中的数据结构、基于InnoDB存储引擎的表和页的物理存储、索引与算法、文件、锁、事务、备份与恢复，以及InnoDB的性能调优等重要的知识；最后对InnoDB存储引擎源代码的编译和调试做了介绍，对大家阅读和理解InnoDB的源代码有重要的指导意义。
- 《深入理解MySQL核心技术》
MysQL开发团队的前成员Sasha Pachev通过《深入理解MySQL核心技术》给出了MySQL 5的全面指南，揭示了这一强大数据库的内部运作。您将直奔MySQL核心技术，了解各种数据结构和各种方便的功能的运作情况，了解如何添加新的存储引擎和配置选项等。

###  教程
- MySQL数据库 —— 网易云课堂 
https://study.163.com/course/introduction/247003.htm#/courseDetail

- 一天学会数据库 —— B站火热课程
https://www.bilibili.com/video/BV1Vt411z7wy?from=search&seid=12048993812767280690 

- MySQL数据库设计与应用 ——mooc慕课
https://www.icourse163.org/course/KMUST-1206687836

###  文章
#####  sql知识点
一、[安装与入门](https://blog.csdn.net/qq_43715354/article/details/109354222?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160920434716780274016026%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=160920434716780274016026&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_click~default-1-109354222.first_rank_v2_pc_rank_v29&utm_term=mysql%E5%AE%89%E8%A3%85)

二、[数据类型与操作数据表](https://blog.csdn.net/ithomer/article/details/4470253?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921017916780274027503%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=160921017916780274027503&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-4470253.first_rank_v2_pc_rank_v29&utm_term=mysql%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B)

三、[约束以及修改数据表](https://blog.csdn.net/weixin_43705953/article/details/107067161?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921024116780277843853%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fblog.%252522%25257D&request_id=160921024116780277843853&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v1~rank_blog_v1-1-107067161.pc_v1_rank_blog_v1&utm_term=%E7%BA%A6%E6%9D%9F)

四、[操作数据表中的记录](https://blog.csdn.net/erlian1992/article/details/51407275?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921028316780261974937%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=160921028316780261974937&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-51407275.first_rank_v2_pc_rank_v29&utm_term=mysql%E6%93%8D%E4%BD%9C%E6%95%B0%E6%8D%AE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%AE%B0%E5%BD%95)

五、[子查询与连接](https://blog.csdn.net/weixin_43705953/article/details/107103971?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921033016780265384807%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fblog.%252522%25257D&request_id=160921033016780265384807&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v1~rank_blog_v1-1-107103971.pc_v1_rank_blog_v1&utm_term=%E5%AD%90%E6%9F%A5%E8%AF%A2)

六、[运算符和函数](https://blog.csdn.net/j_better/article/details/82469957?ops_request_misc=&request_id=&biz_id=102&utm_term=mysql%25E8%25BF%2590%25E7%25AE%2597%25E7%25AC%25A6%25E5%2592%258C%25E5%2587%25BD%25E6%2595%25B0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-1-82469957.first_rank_v2_pc_rank_v29)

七、[自定义函数](https://blog.csdn.net/weixin_43705953/article/details/107598611?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921038516780308341801%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fblog.%252522%25257D&request_id=160921038516780308341801&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v1~rank_blog_v1-5-107598611.pc_v1_rank_blog_v1&utm_term=sql)

八、[MySQL存储过程](https://blog.csdn.net/weixin_43705953/article/details/107550164?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921046616780288742582%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fblog.%252522%25257D&request_id=160921046616780288742582&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v1~rank_blog_v1-4-107550164.pc_v1_rank_blog_v1&utm_term=mysql)

九、[MYSQL事务与隔离级别](https://blog.csdn.net/weixin_43705953/article/details/107203188?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921046616780288742582%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fblog.%252522%25257D&request_id=160921046616780288742582&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v1~rank_blog_v1-6-107203188.pc_v1_rank_blog_v1&utm_term=mysql)

十、[MySQL图形化管理工具](https://blog.csdn.net/slowlifes/article/details/53692238?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921052316780257458250%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=160921052316780257458250&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-53692238.first_rank_v2_pc_rank_v29&utm_term=MySQL%E5%9B%BE%E5%BD%A2%E5%8C%96%E7%AE%A1%E7%90%86%E5%B7%A5%E5%85%B7)
#####  sql面试 
1.[全面面试经验](https://zhuanlan.zhihu.com/p/78982303) 

2.[面试题库](https://blog.csdn.net/ThinkWon/article/details/104778621?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921064616780265347636%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=160921064616780265347636&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_click~default-1-104778621.first_rank_v2_pc_rank_v29&utm_term=mysql%E9%9D%A2%E8%AF%95)

3.[面试题汇总](https://blog.csdn.net/u014209205/article/details/83051001?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921064616780265347636%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=160921064616780265347636&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-3-83051001.first_rank_v2_pc_rank_v29&utm_term=mysql%E9%9D%A2%E8%AF%95)

4.[Mysql面试必备知识点](https://blog.csdn.net/twt936457991/article/details/89458134?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921064616780288224021%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fall.%252522%25257D&request_id=160921064616780288224021&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_v2~rank_v29-11-89458134.first_rank_v2_pc_rank_v29&utm_term=mysql%E9%9D%A2%E8%AF%95)

5.[面试解答](https://blog.csdn.net/qq1353424111/article/details/108643297?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522160921064616780288224021%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fall.%252522%25257D&request_id=160921064616780288224021&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_v2~rank_v29-14-108643297.first_rank_v2_pc_rank_v29&utm_term=mysql%E9%9D%A2%E8%AF%95)
