# 洗牌排序

(算法)



定义:
一种分布排序算法，首先删除n项中的前1/8，对它们进行排序(递归地)，然后将它们放入数组中。这将创建n/8个桶，剩余的7/8项将分配到这些桶中。然后对每个桶进行排序，并将桶连接起来。



概括(我是一种……)
分布。



聚合父级(我是…的一部分或在…中使用)
J。



另请参阅
美国国旗排序，分配分区排序，b树。



注意:
Shuffle排序可以被认为是形成非常宽的树，比如m=n/8的b树，以便在许多情况下高效排序。

随机排序通过检查前n/8个项目来估计要排序的项目的分布。分配划分排序通过逼近中位数和从最小值到中位数以及从中位数到最大值的线性插值来估计分布。


作者:钢


在1997年发布的一条关于J排序的信息中解释了这一点。








条目于2020年12月21日修改。
12月21日星期一09:49:05 2020。



引用如下:
保罗·e·布莱克，《洗牌排序》，入
算法与数据结构词典[在线]，Paul E. Black主编，2020年12月21日。(今天访问)
可从:https://www.nist.gov/dads/HTML/shuffleSort.html获得