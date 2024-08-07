---
title: 动态规划
date: 2024-07-28
---
动态规划的核心思想：**“倒着分析问题”**

- 定位到问题的终点
- 站在终点这个视角，思考后退的可能性
- 记忆化搜索：在递归的过程中，不断保存已经计算出的结果，从而避免重复计算的手法

树形思维和动态规划的区别

- 树形思维模型
    - 站在一个比较大的未知数量级（也就是最终的那个`n`），不断进行拆分，最终拆回较小的已知数量级（`f(1)`、`f(2)`）
    - **自顶向下**过程
- 动态规划
    - 站在**已知**的角度，通过定位已知和未知之间的关系，一步一步向前推导，进而求解出未知的值
    - **自底向上**过程

动态规划应用场景

- **最优子结构**：问题的最优解包含着子问题的最优解
    - 不管前面的决策如何，此后的状态必须是基于当前状态（由上次决策产生）的最优决策
    - `f(n)`和`f(n-1)`、`f(n-2)`之间的关系印证了这一点（状态转移方程）
- **重叠子问题**：在递归的过程中，出现了反复计算的情况
- **最值问题

动态规划的实现步骤

1. **定义子问题：** 明确子问题的含义
2. **写出状态转移方程：** 找出子问题之间的关系
3. **确定初始条件和边界情况：** 确定子问题的初始值
4. **计算结果：** 根据状态转移方程计算出最终结果

动态规划实践问题

- [[fibonacci-sequence|斐波那契数列]]
- [[knapsack-problem|背包问题]]
- [[longest-common-subsequence|最长公共子序列]]
