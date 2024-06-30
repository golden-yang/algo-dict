# 扭曲表哈希


(算法)



定义:
类似于制表散列，不同之处在于最后一个表是通过最后一个字符的xor和字符串其余部分的扭转值进行索引的。



形式定义:(t, hr(c)) =⊕ni=2 t *i[ci] h(c) = hr(c)⊕T1[c1⊕t]其中⊕为xor运算，t *i为第i个表，ci为第i个字符。



聚合子(…)是我的一部分或在我身上使用。)
制表散列。



注意:
扭转值和中间哈希值可以累加到同一个整数中，因为组合操作是异或。

与表列散列中使用的表相比，这些表具有额外的扭曲值。

不管是第一个字符还是最后一个字符都不需要特别处理。


作者:钢


Mihai pictraucu和Mikkel Thorup，扭曲表哈希，Proc.第24届ACM-SIAM离散算法研讨会(SODA '13)，页209-228,2013。








条目于2018年6月7日修改。
HTML页面格式化星期三三月13 12:42:46 2019。



引用如下:
Paul E. Black，“扭曲的表列散列”，in
算法与数据结构词典[在线]，Paul E. Black主编，2018年6月7日。(今天访问)
可从:https://www.nist.gov/dads/HTML/twistedTabulationHashing.html获得