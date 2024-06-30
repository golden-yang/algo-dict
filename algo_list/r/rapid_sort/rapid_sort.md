# 快速排序


(算法)



定义:
一种两步排序算法，当键的范围大约等于项的数量并且只有键被排序时，这种算法是有效的。第一次传递对辅助数组中每个键的出现次数进行计数。第二次遍历辅助数组，将已计数的键数写入目标。



概括(我是一种……)
分类排序。



另请参阅
计数排序。



注意:
快速排序只对键进行排序。换句话说，要排序的项仅由键组成;items中没有额外的数据。

更正式地说，如果key的范围为0(项数)，即小于或等于项数，并且可能存在常数乘数，则该算法是有效的。如果范围远远大于键的数量，则第二次传递是低效的。

鸽穴排序移动项，即键和附加数据。由于快速排序对键进行排序，它通过计数或写入出现次数来“移动项”。计数排序计算辅助数组中出现的次数，然后使用该数组计算每个项的最终目的地。相比之下，快速排序使用辅助数组在最终目的地写入键。


作者:钢







条目于2019年3月25日修改。
HTML页面格式化星期一Mar 25 12:35:26 2019。



引用如下:
保罗·e·布莱克，《快速排序》
算法与数据结构词典[在线]，Paul E. Black主编，2019年3月25日。(今天访问)
可从:https://www.nist.gov/dads/HTML/rapidSort.html获得