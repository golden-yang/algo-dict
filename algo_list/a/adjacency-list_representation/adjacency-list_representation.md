# 邻接列表表示


（数据结构）



释义
使用n个顶点列表的数组表示具有n个顶点的有向图。如果存在从顶点i到顶点j的边，则列表i包含顶点j。加权图可以用顶点/权重对的列表来表示。无向图可以通过使顶点j在顶点i的列表中并且使顶点i在顶点j的列表中来表示。



另请参阅
邻接矩阵表示、稀疏图。



笔记
假设我们有一个有向图，它有四个顶点。这里是邻接矩阵和邻接列表的表示。箭头（->）表示列表中的链接。












一种变体是有一个列数组，而不是行数组，列表是“向下”的。对于稀疏矩阵，邻接列表表示更紧凑。


作者：BB，PEB







条目于2021年10月15日修改。
HTML页面格式为2021年10月15日星期五16:48:46。



引用如下：
Bob Bockholt和Paul E.Black，“邻接列表表示”，在
《算法和数据结构词典》[在线]，Paul E.Black，2021年10月15日版。（今天访问）
可从以下位置获得：https://www.nist.gov/dads/HTML/adjacencyListRep.html