# Merkle tree


(数据结构)



定义:
一种树(通常是二叉树)，其中每个内部节点都有其下叶节点中所有信息的散列。具体来说，每个内部节点都有其子节点中信息的散列。每个叶子都有它所代表的信息块的哈希值。所有叶节点都在相同的深度。所有节点都尽可能地向左。

要将块(叶子)添加到完整的树中，将创建一个新的根，并将旧根作为其左子根。它的右子树是一棵简并树(只有左子树)，一直到叶级。



也称为哈希树。



概括(我是一种……)
树。



聚合子(…)是我的一部分或在我身上使用。)
哈希函数。



另请参阅
Merkle_tree(维基百科)。



注意:
通常是两个分支，这是一个二叉树，但它也可以是k叉树。

Merkle的论文描述了一个概念上无限的(二叉)树，每个内部节点上都有块(文档)。要添加新块，请在水平顺序遍历中使用下一个节点。(水平顺序遍历与从根开始的宽度优先搜索的顺序相同。)

给定由Merkle树表示的可能相同的信息的两个副本，可以通过比较根的哈希值来检查副本是否相同。通过比较通往不同叶子的路径上的内部节点上的哈希值，就可以发现副本之间的一个差异。这是叶节点数量的对数。

一棵完整的树也有尽可能多的节点，但每一层都是满的。


作者:钢


搜索、遍历、插入、删除和同步所需的平均空间和复杂度。



Ralph C. Merkle，提供数字签名的方法，美国专利4309569,1979年9月5日提交。PDF图像可从http://pdfpiw.uspto.gov/.piw?Docid=04309569获得。文本版本可在http://patft.uspto.gov/netahtml/PTO/srchnum.htm找到，输入4309569，单击搜索。刘志强，基于传统加密函数的数字签名，《计算机科学》(ei)， 2007。计算机科学，1993(3):369-378。doi: 10.1007 / 3 - 540 - 48184 - 2 - _32








条目于2019年2月19日修改。
HTML页面格式化星期三三月13 12:42:46 2019。



引用如下:
保罗·e·布莱克，《默克尔树》，in
算法与数据结构词典[在线]，Paul E. Black主编，2019年2月19日。(今天访问)
可从:https://www.nist.gov/dads/HTML/MerkleTree.html获得