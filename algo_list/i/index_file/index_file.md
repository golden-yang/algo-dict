# index file


(数据结构)



定义:
将键和索引存储到另一个文件中的文件。索引文件可以有额外的结构，例如，是一个b树。



另请参阅
倒排索引，正排索引。



注意:
如果记录很大，索引文件是有用的:键和索引可以被提取、排序，并且访问原始文件的速度比将原始文件重新排列成有序的速度快。此外，如果文件需要同时被不同的键访问，则不能按所有键进行排序。因此，为每个不同的键维护一个索引文件。


作者:PEB







2004年12月17日修改。
HTML页面格式化星期三三月13 12:42:46 2019。



引用如下:
Paul E. Black，“索引文件”，in
算法与数据结构词典[在线]，Paul E. Black主编，2004年12月17日。(今天访问)
可从:https://www.nist.gov/dads/HTML/indexfile.html获得