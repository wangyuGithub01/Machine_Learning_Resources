### 常考概率题

- [蓄水池抽样（数据流中随机采样）](https://www.cnblogs.com/snowInPluto/p/5996269.html)
- [等概率无重复的从n个数中选取m个数](https://blog.csdn.net/yusiguyuan/article/details/42607681)
- [两个小孩，已知其中一个为女，求另一个也是女的概率？](https://www.zhihu.com/question/31140434)
- [rand(5)生成rand(7)](https://blog.csdn.net/u010025211/article/details/49668017)
- [一个骰子，每个面至少被投出一次需要投多少次？](https://www.zhihu.com/question/40320381)
- [13个人生日都不是同一天的概率]()
- [甲乙轮流抛硬币，正面胜，先抛的人优势多大？](https://www.zhihu.com/question/290055193)
- 抛2k+1次硬币，问正面次数比背面多的概率是多大

假设正反面概率是1/2,那么抛2k+1次硬币就是一个伯努利分布(2k+1,1/2)
求正面比反面次数多的概率为P.
P=(1/2)^n*{C(2k+1,2k+1)+C(2k+1,2k)+C(2k+1,2k-1)+...C(2k+1,k+1)}=(1/2)^n*{C(2k+1,0)+C(2k+1,1)+..C(2k+1,k)}=(1/2)^n*(1/2)*{C(2k+1,0)+.....C(2k+1,2k+1)}
其中组合公式求和为2^n,所以上式为:
P=(1/2)^n*(1/2)*(2^n)=1/2


