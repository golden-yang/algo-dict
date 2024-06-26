# Shell排序


(算法)



定义:
第一个递减增量排序。在每次传递中，对n/i个元素的i个集合进行排序，通常使用插入排序。在接下来的每一次传递中，i被减小，直到最后一次传递为1。一个好的i值系列对效率很重要。



概括(我是一种……)
递减增量排序。



聚合子(…)是我的一部分或在我身上使用。)
插入排序。



注意:
梳子排序对每个间隔或增量对每个集合进行一次“冒泡”传递(即冒泡排序)，而Shell排序对每个集合进行完全排序。

Donald E. Knuth在[knuth98,3:84]中广泛分析了该算法为5.2 d。一个好的增量集合是2k+1，…，9,5,3,1，第一个增量不超过N/3。


作者:钢,问


Shell排序演示之后是Shell排序和插入排序之间的竞争(Shell排序带有针对10个项目优化的间隙序列)。通过匈牙利民间舞蹈说明Shellsort: Csángó。由Sapientia大学创建。



张建军，张建军，张建军，等。一种高速分选方法，中国机械工程，2(7):30-32,1959年7月。



历史上的注意
这个算法被John P. Grillo不恰当地称为Shell-Metzner排序，排序的比较，创造性计算，2:76-80,1976年11 / 12月。

Grillo引用Fredric Stuart, FORTRAN Programming, John Wiley and Sons，纽约，1969年，第294页。斯图尔特在脚注中称赞“最快”的分类程序之一，“由马琳·梅茨纳出版，普拉特&惠特尼飞机公司。根据d.l. Shell描述的方法。”

2003年4月3日，马琳·梅茨纳·诺顿写道

我和这种事毫无关系，我的名字也不应该跟它扯上关系。

下面是独家新闻。

1956年，我大学毕业，获得了数学学位。1956年我为获得大学学位所修的数学，现在几乎都是高中的课程。我申请了通用电气在辛辛那提埃文代尔的一份工作。(那是我在高中教的。)他们让我用一种叫做CAGE的汇编语言给IBM 704编程。我不记得它代表什么了，但GE就是通用电气。可能是通用电气的“计算机组装工”。唐·谢尔在同一栋楼工作，但他是系统分析部的经理。我和许多人一样，有好几页方程，把它们变成可以通过打孔卡运行的代码。这是在Basic和Fortran出现之前。系统分析员编写汇编程序、创建缓冲区以加快打印速度的方法等。我怀疑唐·谢尔甚至不知道我是谁。大约在1959年，我们开始使用Fortran——只是一点点。

我想Don Shell在计算机系的时事通讯上写过他的分类方法的理论。我觉得这本书很有趣，就留下了一本。

1960年，我买了一辆敞篷车，搬到了佛罗里达。为什么?我年轻，单身，前途无量，佛罗里达听起来很有趣。接受了西棕榈滩普惠公司的工作。做同样的编程，但普拉特有一台全新的IBM 7090。他们用SAP编程，类似于CAGE。逻辑是一样的，但是指令名称的不同足以让人困惑。

大约在1961年左右，普拉特买了一台IBM 1620。这是一种更小的计算机，使用打孔纸带代替卡片。大学用它来教计算机。普拉特在工程部使用它，这样工程师们就可以自己处理小问题，而不是把问题带到计算机实验室。我负责协调1620工程与计算机部门。IBM成立了一个1620用户组。我被派去参加第一次会议。作为那里唯一的女性，我自然被选为财务部长。在第一年里，一家德国公司买了一个，所以现在它是IBM 1620国际用户组。

用户组发布了一份通讯。人们来信提出问题、建议、想法等等。为了帮助填充一个早期版本，我取出了Don Shell的排序方法并用Fortran对其进行了编码。用了大约10行代码，上下相差5行，用了同样多的时间。给了Don Shell完全的信任。

1963年我结婚了。1964年，我离开宝洁公司组建家庭。在棕榈滩初级学院(现在的棕榈滩社区学院)教1620和IBM 1401几年，但没有接触过宝洁或用户组。

现在我发现有人读了它，开始叫它Shell-Metzner。唐·谢尔没有把我抓起来告我，真是个奇迹!

玛琳

顺带一提，我把你的网站发给了我的孩子们。人们对妈妈曾经“聪明”这一想法的反应值得可能的法律诉讼。








2023年4月6日修改。
HTML页面格式Thu Apr 6 14:16:28 2023。



引用如下:
保罗·e·布莱克和阿特·s·卡格尔，《贝壳分类》，页
算法与数据结构词典[在线]，Paul E. Black主编，2023年4月6日。(今天访问)
可从:https://www.nist.gov/dads/HTML/shellsort.html获得

