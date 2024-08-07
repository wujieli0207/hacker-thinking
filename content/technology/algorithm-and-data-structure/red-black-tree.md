---
title: 红黑树
date: 2024-07-28
---
## 基础概念

定义：一种自平衡二叉搜索树，它通过维护节点的颜色（红或黑）来保证查找、插入和删除操作的时间复杂度始终为 O(log n)。

例子：  想象一颗树，每个节点都有颜色，红色节点表示不平衡，黑色节点表示平衡，树通过调整节点颜色来保持平衡。

特点：

- 节点颜色:  每个节点都有颜色，红或黑
- 自平衡:  通过调整节点颜色来保持平衡
- 查找:  O(log n) 时间复杂度
- 插入:  O(log n) 时间复杂度
- 删除:  O(log n) 时间复杂度

基本操作

- 插入 (Insert):  将新节点插入到红黑树中，并调整节点颜色来保持平衡
- 删除 (Delete):  删除节点，并调整节点颜色来保持平衡
- 查找 (Search):  查找目标节点，时间复杂度为 O(log n)

应用场景

- 数据库索引:  红黑树可以用于快速查找数据库记录
- 操作系统:  红黑树可以用于实现内存管理
- 算法:  许多算法，例如路径查找和最短路径算法，依赖于红黑树结
