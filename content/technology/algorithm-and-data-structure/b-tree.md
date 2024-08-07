---
title: B 树
date: 2024-07-28
---

## 基础概念

定义：一种自平衡的多路树，它用于存储和检索大量数据，特别适用于磁盘存储

例子：想象一个文件系统，每个节点代表一个磁盘块，每个节点包含多个键值对，B 树帮助快速查找目标文件

特点：

- 多路：每个节点可以包含多个子节点，提高磁盘访问效率
- 自平衡：通过调整节点数量和键值对来保持平衡
- 查找、插入和删除操作的时间复杂度为 O(log n)

基本操作

- 插入 (Insert):  将新键值对插入到 B 树中，并调整节点数量和键值对来保持平衡
- 删除 (Delete):  删除键值对，并调整节点数量和键值对来保持平衡
- 查找 (Search):  查找目标键值对，时间复杂度为 O(log n)

应用场景

- 数据库索引:  B 树可以用于快速查找数据库记录，提高查询效率
- 文件系统:  B 树可以用于组织文件和目录，提高文件访问效率
- 操作系统:  B 树可以用于内存管理和页面替换算法
