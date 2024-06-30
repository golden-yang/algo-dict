# 弱堆


(数据结构)



定义:
满足以下三个条件的松弛堆:(1)节点右子树中的每个键都大于存储在节点本身中的键，(2)根没有左子节点，(3)叶子只在树的最后两层找到。



另请参阅
weak-heap排序。



注意:
弱堆可以有效地用一个包含项的数组A和一个包含反向位的数组r来实现。索引i的左子结点的索引是2i+1-ri，右子结点的索引是2i+ri。

这是最小弱堆。最大弱堆具有小于节点键的子树键。


作者:SE







2011年5月26日修改。
HTML页面格式化星期三三月13 12:42:46 2019。



引用如下:
Stefan Edelkamp，“弱堆”，in
算法与数据结构词典[在线]，Paul E. Black主编，2011年5月26日。(今天访问)
可从:https://www.nist.gov/dads/HTML/weakheap.html获得