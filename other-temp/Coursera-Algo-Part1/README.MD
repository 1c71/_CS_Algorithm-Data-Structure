
### Coursera, Algorithem Part 1 的代码和笔记

课程用的是 Java
所以这里也是用 Java
下面是一些精简的总结笔记


#### Week 1
有一堆点, 怎么求两个点是否连接在一起? (间接连接也算)


#### Week 2
栈: 链表实现, 数组实现. 会有什么问题, 怎么改进.

Dijkstra's two-stack algorithem
用于计算数学式子
有两个栈, 一个存数字. 一个存操作符, 比如加减乘除.

碰到数字: push 到"数字栈"里
碰到操作符: push 到"操作符栈"里
碰到左括号: 忽略
碰到右括号: 从"数字栈"里拿出2个数字, 然后用"操作符栈"里的操作符进行运算

排序

#### Week 3

