## 巧妙AA

题目描述
> 一群程序员小伙伴出去旅行, 他们决定用程序来管理旅行中的账目, 首先输入所有小伙伴的名字, 以列表方式, 比如: A B C D. 然后每当在旅行途中有一次消费, 就会把出钱的人和金额记录下来, 类似这样的结构:  A 100. 当旅行结束后, 所有的小伙伴要AA旅行总费用, 请你编写程序来帮助他们计算最后AA付款清单, 比如:B A 50, 且满足条件: 结算的转账总次数最少和转账总金额的乘积最低. 金额都以整数类型表示，当AA不能整除时，取floor


输入
> 大于等于1行字符串， 第一行表示有旅行成员列表， 剩下的所有行，每一行表示一个成员的一次付钱

输出
> 按照输入成员的顺序， 每行一次列出谁结算付给谁多少钱。

样例输入
>A　B　C　D  
A　100  
B　50  
C　50  
D　40


样例输出
>B　A　10  
C　A　10  
D　A　20  

Hint
>抓紧时间， 使用简单粗暴有效的办法解决
