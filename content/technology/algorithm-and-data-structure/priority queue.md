---
title: 优先队列
date: 2024-07-28
---
## 基础概念

定义：一种特殊的队列，元素按优先级排序，优先级高的元素先被取出

例子：  想象一个紧急任务处理系统，紧急任务优先处理，非紧急任务等待

特点：

- 按优先级排序:  元素按优先级排序，优先级高的元素先被取出
- FIFO:  在同一优先级下，元素按照先进先出原则排序
- 优先级比较:  需要一个优先级比较函数，用于比较元素的优先级

基本操作

- 入队 (Enqueue):  将元素插入队列，并根据优先级找到合适的位置
- 出队 (Dequeue):  取出优先级最高的元素
- 查找 (Peek):  查看优先级最高的元素

应用场景

- 任务调度系统:  根据任务优先级调度任务执行
- 操作系统:  处理中断和信号，优先处理紧急事件
- 贪婪算法:  选择最优解，例如 Dijkstra 算法
