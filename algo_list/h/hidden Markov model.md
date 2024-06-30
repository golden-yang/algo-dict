# hidden Markov model


(数据结构)



定义:
有限状态机的一种变体，具有一组状态，Q，一个输出字母，O，转移概率，A，输出概率，B和初始状态概率，Π。当前状态是不可观察的。相反，每个状态产生一个具有一定概率(B)的输出。通常状态Q和输出O是可以理解的，因此HMM被称为三元组(a, B， Π)。



正式定义:在Michael Cohen的讲座之后，花费760美元。




也被称为HMM。



概括(我是一种……)
有限状态机。



聚合父级(我是…的一部分或在…中使用)
Baum Welch算法，Viterbi算法。



另请参阅
马尔可夫链。



注意:
计算给定一组观察输出序列的模型是非常困难的，因为状态不是直接可观察到的，而且转换是概率性的。一种方法是鲍姆·韦尔奇算法。

虽然根据定义，状态不能被直接观察到，但是对于给定的观察输出序列，最可能的集合序列可以用O(nt)来计算，其中n是状态数，t是序列的长度。一种方法是维特比算法。

感谢Arvind <uk_arvind@mail.utexas.edu> 2002年5月。

以安德烈·安德烈耶维奇·马尔科夫(1856 - 1922)的名字命名，他把诗歌和其他文本作为随机的字符序列来研究。


作者:钢


李立民，马可夫过程概率函数统计估计中的不等式和相关的最大化技术，不等式，(3):1-8,1972。








条目于2020年12月21日修改。
12月21日星期一09:49:05 2020。



引用如下:
Paul E. Black，“隐马尔可夫模型”，in
算法与数据结构词典[在线]，Paul E. Black主编，2020年12月21日。(今天访问)
可从:https://www.nist.gov/dads/HTML/hiddenMarkovModel.html获得