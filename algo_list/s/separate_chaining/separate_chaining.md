# 分离链


(数据结构)



定义:
一种方案，其中哈希表中的每个位置都有一个列表来处理冲突。每个位置可能只是到列表的一个链接(直接链接)，也可能是一个项和一个链接，本质上是列表的头部。在后者中，一个项目在表中，其他冲突项目在列表中。



也称为外链。



概括(我是一种……)
链接，冲突解决方案。



专业化(…是一种我。)
直接链接。



聚合父级(我是…的一部分或在…中使用)
哈希表。



聚合子(…)是我的一部分或在我身上使用。)
链表。



另请参阅
合并链接。



注意:
可以使用任何列表搜索算法搜索和维护列表中的项。任何可搜索的数据结构都可以用来代替列表。

源自[GBY91，第74-77页]


作者:钢


Francis A. Williams，作为语言处理器内部符号的标识符处理，计算机工程，2(6):21-24,1959年6月。Williams表中的每个位置都是一个项和一个列表头。








条目于2019年2月12日修改。
HTML页面格式化星期三三月13 12:42:46 2019。



引用如下:
保罗·e·布莱克，《分开的锁链》，见
算法与数据结构词典[在线]，Paul E. Black主编，2019年2月12日。(今天访问)
可从:https://www.nist.gov/dads/HTML/separateChaining.html获得