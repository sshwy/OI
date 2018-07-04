OI(信息学竞赛)
======

|Author|杜博识Dubos|
|---|---|
|E-mail|dubos@foxmail.com|

------  

OI (Olympiads in Informatics)，国内译作`信息学竞赛`（或`信息学奥林匹克`、`程序设计竞赛`、`算法竞赛`）。本文按知识大纲，点击知识点即可进入对应讲义。学习顺序与大纲并不完全相同，学习顺序请参考本文件夹中的讲义编号。信息学竞赛参赛过程、升学政策与各年级学习安排具体见：《[NOIP 00 信息学竞赛与升学](/NOIP%2000%20信息学竞赛与升学.md)》

* **NOIP普及组**  
	* C++入门
		1. [入门：基本数据类型，常量与变量，赋值，算术表达式，整除与求余，模运算，数制转化，输入输出][NOIP 01 1]，文件操作
		3. [程序的控制结构，逻辑表达式，逻辑运算，关系表达式，复合语句，条件语句，循环语句，条件嵌套，循环嵌套][NOIP 02]
		4. [一维数组][NOIP 03 1]，[二维数组][NOIP 03 2]，[字符数组][NOIP 03 3]，[字符串string][NOIP 03 4]，字符串cstring，[高精度计算][NOIP 03 6]
		5. [指针，引用][NOIP 04]
		5. [函数，常用数学函数（幂函数、指数函数、对数函数、三角函数、随机函数）][NOIP 05 1]
		6. 结构体，自定义数据类型

	* 数据结构
		1. 一般线性表，队列，堆，栈，链表，STL容器
		2. 树，二叉树的存储与遍历
		
	* 算法基础：
		1. 时间复杂度，空间复杂度
		2. 位运算
		3. 模拟，枚举，回溯，简单查找
		4. 简单排序，快速排序
		5. 贪心
		6. 递归
		7. 分治，二分
	
	* 数学：
		1. 数论：素数与合数，最大公约数，最小公倍数，互质数，整数的质因数分解，筛法，欧几里得算法
		2. 排列组合与集合：加法原理，乘法原理，圆排列，可重集排列，鸽笼原理，容斥原理，二项式定理与杨辉三角形
	
	* 动态规划：递推，最长上升子序列LIS，最长公共子序列LCS，数字三角形，背包，记忆化搜索
		
	* 图论：深度优先搜索DFS，广度优先搜索BFS，拓扑排序，欧拉回路

* **NOIP提高组**  
 
	* 数学：
		1. 数论：拓展欧几里得算法，中国剩余定理，剩余类，费马小定理，欧拉定理，母函数
		2. 概率，数学期望
		3. 矩阵，线性方程组
		4. 解析几何
		5. 函数的连续性、单调性和极值，数列与级数
		
	* 动态规划：有向无环图DAG上的动态规划，树形动态规划，环形动态规划，后效性处理，状态压缩，倍增优化
	
	* 数据结构：
		1. 二叉堆， 并查集，线段树，二叉索引树/树状数组，哈夫曼Huffman树  
		2. 字典树Trie，哈希表Hash与字符串，KMP算法，AC自动机，后缀数组，后缀树  
	
	* 图论：
		1. 生成树：最小生成树MST，Kruskal算法，Prim算法，最近公共祖先LCA，最小有向生成树/最小树形图  
		2. 最短路：单源最短路SSSP，Dijkstra算法，Bellman-Ford算法及其SPFA优化，Floyd-Warshall算法，负环/负圈，差分约束   
		3. 连通性：强连通分量SCC，Trajan算法，Kosaraju算法，2SAT问题

* **省选与NOI**

	* 数学：
		1. 博弈论SG函数，Nim
		2. 群，置换群，Burnside定理，Polya原理
		3. 快速傅里叶变换FFT
		4. 莫比乌斯反演
		5. 模拟退火算法
		6. 线性规划
		
	* 动态规划：数据结构优化DP，单调队列优化DP，斜率优化，四边形不等式，计数类DP，数位统计DP，双重动态规划，基于连通性的动态规划
		
	* 计算几何
		1. 基本运算，点积，叉积，点和直线，多边形
		2. 圆和球
		3. 二维几何：点在多边形内的判定，凸包，半平面，平面区域
		4. 三维几何
		5. 多边形的布尔计算 
		
	* 数据结构：1. 二叉查找树BST，平衡树Treap，伸展树Splay，动态树LCT（Link-Cut Trees），树套树，树链剖分，分块/块状链表，可持久化数据结构
		
	* 图论（还有NOIP图论中括号内有加号的内容）：   
		1. 二分图：二分图的构造，二分图的匹配，匈牙利算法，KM算法（Kuhn-Munkres算法)，Hopcroft-Karp算法，一般图的匹配
		2. 网络流：最大流问题，Ford-Fulkerson增广路径算法与Edmonds-Karp算法，Dinic算法，ISAP算法，最大流最小割定理，最小费用最大流问题  
		3. 启发式搜索：A* 算法，IDA* 算法  

信息学竞赛跟数理化生竞赛不同的是，做题可以用在线测评系统（Online Judge）评分:100:。除了公平、高效之外，还有一个好处是让用户看到许多其他用户的水平，这样就可以了解到其他学校、城市、省份乃至国家的选手:raising_hand:。当然OJ平台也有很多，有的主要用于学习阶段刷题，有的是学成之后去与高手切磋的，不同学习阶段用不同的平台。关于Online Judge的更多内容见[《OJ简介》](/NOIP%2000%20OJ简介.md)

[NOIP 01 1]:https://github.com/Duboshi/OI/blob/master/NOIP%2001%201%20C++%E5%85%A5%E9%97%A8.cpp
[NOIP 02]:https://github.com/Duboshi/OI/blob/master/NOIP%2002%20%E7%A8%8B%E5%BA%8F%E7%9A%84%E6%8E%A7%E5%88%B6%E7%BB%93%E6%9E%84.cpp
[NOIP 03 1]:https://github.com/Duboshi/OI/blob/master/NOIP%2003%201%20%E4%B8%80%E7%BB%B4%E6%95%B0%E7%BB%84.cpp
[NOIP 03 2]:https://github.com/Duboshi/OI/blob/master/NOIP%2003%202%20%E4%BA%8C%E7%BB%B4%E6%95%B0%E7%BB%84.cpp
[NOIP 03 3]:https://github.com/Duboshi/OI/blob/master/NOIP%2003%203%20%E5%AD%97%E7%AC%A6%E6%95%B0%E7%BB%84.cpp
[NOIP 03 4]:https://github.com/Duboshi/OI/blob/master/NOIP%2003%204%20string%E5%AD%97%E7%AC%A6%E4%B8%B2.cpp
[NOIP 03 6]:https://github.com/Duboshi/OI/blob/master/NOIP%2003%206%20%E9%AB%98%E7%B2%BE%E5%BA%A6%E8%AE%A1%E7%AE%97.cpp
[NOIP 04]:https://github.com/Duboshi/OI/blob/master/NOIP%2004%20%E6%8C%87%E9%92%88.cpp
[NOIP 05 1]:https://github.com/Duboshi/OI/blob/master/NOIP%2005%201%20%E5%87%BD%E6%95%B0.cpp
