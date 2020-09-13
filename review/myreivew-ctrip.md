## 2020.8.31 阿里飞猪（搜索方向）

### 一面

1. 问了项目，如何重构结果页的，怎么把时间缩短到200ms？
2. Spring Boot与Spring MVC区别？
3. 有A和B两个有序数组，A的长度是l，A的元素和B的元素的个数分别是m和n，已知l > m+n，如何将A和B合并一个有序数组？
4. 有笔试题，单独约了笔试时间，题目不难，两道题在leecode上都有原题。(详细参考：data/20200904-alifeizhu.txt)
   - 给定两个二叉树，编写一个函数来检验它们是否相同
   - 给定字符串（合法字符只包括0，1，？），替换字符串中的通配符？为0或者1，生成所有可能的字符串。比如输入的字符串为"1??0?101"

## 2020.9.1 途虎养车网（搜索方向）

### 一面

1. 你们刷新数据有几种方式？

   答：途虎是每天新建索引，将Alias指向新的索引，个人觉得数据量较小可以这么做，也可以解决脏数据的问题

2. 你们是怎么做ES分词的？

   答：途虎是事先分词后，再索引到es，然后用空格分词

3. 你们是如何解决es脏数据的问题？

4. java锁如何实现，比如sycnizered

   答：原理的是JDK的动态代理

5. hashmap是如何实现的

6. 你们是如何使用jdk8实现异步的

7. Java注解的实现原理

## 2020.9.11 喜马拉雅（搜索方向）

一面

1. 你知道es和solr的区别吗？
   - 为什么solr查询是比es快的？
   - 为什么es写入比solr稳定？
2. lucene底层的update和add是如何实现的？
3. es常用的聚合操作有哪些？district和group，底层原理是怎么做的？
4. es如何实现深分页？
5. 平衡二叉树和跳跃表是如何实现的？