## 题目出现频率

LeetCode中的题目按真实面试中的出现频率降序排列。

| Col 1 | Col 2 |  Col 3 | Col 4 |
| :-------------: | :-------------: | :-------------: | :-------------: |
| [栈](https://github.com/pwstrick/daily/blob/master/article/leetcode/stack.md) | [堆](https://github.com/pwstrick/daily/blob/master/article/leetcode/heap.md) | [贪心算法](https://github.com/pwstrick/daily/blob/master/article/leetcode/greedy.md) | [排序](https://github.com/pwstrick/daily/blob/master/article/leetcode/sort.md) |
| [位运算](https://github.com/pwstrick/daily/blob/master/article/leetcode/bit-manipulation.md) | [树](https://github.com/pwstrick/daily/blob/master/article/leetcode/tree.md) | [深度优先搜索](https://github.com/pwstrick/daily/blob/master/article/leetcode/depth-first-search.md) | [广度优先搜索](https://github.com/pwstrick/daily/blob/master/article/leetcode/breadth-first-search.md) |
| [并查集](https://github.com/pwstrick/daily/blob/master/article/leetcode/union-find.md) | [图](https://github.com/pwstrick/daily/blob/master/article/leetcode/graph.md) | [设计](https://github.com/pwstrick/daily/blob/master/article/leetcode/design.md) | [拓扑排序](https://github.com/pwstrick/daily/blob/master/article/leetcode/topological-sort.md) |
| [字典树](https://github.com/pwstrick/daily/blob/master/article/leetcode/trie.md) | [树状数组](https://github.com/pwstrick/daily/blob/master/article/leetcode/binary-indexed-tree.md) | [线段树](https://github.com/pwstrick/daily/blob/master/article/leetcode/segment-tree.md) | [二叉搜索树](https://github.com/pwstrick/daily/blob/master/article/leetcode/binary-search-tree.md) |
| [递归](https://github.com/pwstrick/daily/blob/master/article/leetcode/recursion.md) | [脑筋急转弯](https://github.com/pwstrick/daily/blob/master/article/leetcode/brainteaser.md) | [记忆化](https://github.com/pwstrick/daily/blob/master/article/leetcode/memoization.md) | [队列](https://github.com/pwstrick/daily/blob/master/article/leetcode/queue.md) |
| [极小化极大](https://github.com/pwstrick/daily/blob/master/article/leetcode/minimax.md) | [蓄水池抽样](https://github.com/pwstrick/daily/blob/master/article/leetcode/reservoir-sampling.md) | [几何](https://github.com/pwstrick/daily/blob/master/article/leetcode/geometry.md) | [数组](https://github.com/pwstrick/daily/blob/master/article/leetcode/array.md) |
| [哈希表](https://github.com/pwstrick/daily/blob/master/article/leetcode/hash-table.md) | [链表](https://github.com/pwstrick/daily/blob/master/article/leetcode/linked-list.md) | [数学](https://github.com/pwstrick/daily/blob/master/article/leetcode/math.md) | [双指针](https://github.com/pwstrick/daily/blob/master/article/leetcode/two-pointers.md) |
| [字符串](https://github.com/pwstrick/daily/blob/master/article/leetcode/string.md) | [二分查找](https://github.com/pwstrick/daily/blob/master/article/leetcode/binary-search.md) | [分治算法](https://github.com/pwstrick/daily/blob/master/article/leetcode/divide-and-conquer.md) | [动态规划](https://github.com/pwstrick/daily/blob/master/article/leetcode/dynamic-programming.md) |
| [回溯算法](https://github.com/pwstrick/daily/blob/master/article/leetcode/backtracking.md) | [Random](https://github.com/pwstrick/daily/blob/master/article/leetcode/random.md) | [Rejection Sampling](https://github.com/pwstrick/daily/blob/master/article/leetcode/rejection-sampling.md) | [Sliding Window](https://github.com/pwstrick/daily/blob/master/article/leetcode/sliding-window.md) |
| [Ordered Map](https://github.com/pwstrick/daily/blob/master/article/leetcode/ordered-map.md) | [Line Sweep](https://github.com/pwstrick/daily/blob/master/article/leetcode/line-sweep.md) | &nbsp; | &nbsp; |

## GitHub刷题库
* [LeetCode算法模版](https://github.com/greyireland/algorithm-pattern)
* [LeetCode顺序刷题](https://github.com/wind-liang/leetcode)
* [LeetCode动画思路](https://github.com/MisterBooo/LeetCodeAnimation)
* [算法小抄](https://github.com/labuladong/fucking-algorithm)
* [LeetCode题解](https://github.com/azl397985856/leetcode)
* [LeetCode Cookbook](https://github.com/halfrost/LeetCode-Go)

## 刷题记录
从简单题开始刷，给自己点信心，题目太长和超过5分钟不能理解题目含义的直接跳过。
再根据题解数量，先刷题解多的算法题。

### 栈
用栈做中转，当满足某个条件时，进栈或出栈，很多时候结果就存放在栈中。
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
[20. 有效的括号](https://leetcode-cn.com/problems/valid-parentheses/) | [辅助栈](https://leetcode-cn.com/problems/valid-parentheses/solution/zhu-bu-fen-xi-tu-jie-zhan-zhan-shi-zui-biao-zhun-d/) | [查看](https://github.com/pwstrick/daily/issues/1012) |
| [496. 下一个更大元素 I](https://leetcode-cn.com/problems/next-greater-element-i/) | [单调栈](https://leetcode-cn.com/problems/next-greater-element-i/solution/xia-yi-ge-geng-da-yuan-su-i-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1013) |
| [682. 棒球比赛](https://leetcode-cn.com/problems/baseball-game/) | [辅助栈](https://leetcode-cn.com/problems/baseball-game/solution/bang-qiu-bi-sai-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1014) |
| [844. 比较含退格的字符串](https://leetcode-cn.com/problems/backspace-string-compare/) | [辅助栈](https://leetcode-cn.com/problems/backspace-string-compare/solution/bi-jiao-han-tui-ge-de-zi-fu-chuan-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1015) |
| [1047. 删除字符串中的所有相邻重复项](https://leetcode-cn.com/problems/remove-all-adjacent-duplicates-in-string/) | [辅助栈](https://leetcode-cn.com/problems/remove-all-adjacent-duplicates-in-string/solution/shan-chu-zi-fu-chuan-zhong-de-suo-you-xiang-lin-zh/) | [查看](https://github.com/pwstrick/daily/issues/1016) |

### 队列
和栈类似，也是做中转，当满足某个条件时，进队或出队，很多时候结果就存放在队列中。
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [剑指 Offer 59 - I. 滑动窗口的最大值](https://leetcode-cn.com/problems/hua-dong-chuang-kou-de-zui-da-zhi-lcof/) | [单调队列](https://leetcode-cn.com/problems/hua-dong-chuang-kou-de-zui-da-zhi-lcof/solution/mian-shi-ti-59-i-hua-dong-chuang-kou-de-zui-da-1-6/) | [查看](https://github.com/pwstrick/daily/issues/1017) |

### 排序
排序好后再做比对或计算。
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [242. 有效的字母异位词](https://leetcode-cn.com/problems/valid-anagram/) | [字母排序](https://leetcode-cn.com/problems/valid-anagram/solution/you-xiao-de-zi-mu-yi-wei-ci-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1018) |
| [349. 两个数组的交集](https://leetcode-cn.com/problems/intersection-of-two-arrays/) |  | [查看](https://github.com/pwstrick/daily/issues/1019) |
| [350. 两个数组的交集 II](https://leetcode-cn.com/problems/intersection-of-two-arrays-ii/) | [数字排序](https://leetcode-cn.com/problems/intersection-of-two-arrays-ii/solution/liang-ge-shu-zu-de-jiao-ji-ii-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1020) |
| [922. 按奇偶排序数组 II](https://leetcode-cn.com/problems/sort-array-by-parity-ii/) | [双指针](https://leetcode-cn.com/problems/sort-array-by-parity-ii/solution/an-qi-ou-pai-xu-shu-zu-ii-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1021) |
| [976. 三角形的最大周长](https://leetcode-cn.com/problems/largest-perimeter-triangle/) | [数字排序](https://leetcode-cn.com/problems/largest-perimeter-triangle/solution/san-jiao-xing-de-zui-da-zhou-chang-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1022) |
| [1122. 数组的相对排序](https://leetcode-cn.com/problems/relative-sort-array/) | [计数排序](https://leetcode-cn.com/problems/relative-sort-array/solution/ming-que-bi-jiao-fang-shi-hou-xiang-zen-yao-pai-ji/) | [查看](https://github.com/pwstrick/daily/issues/1023) |
| [1356. 根据数字二进制下 1 的数目排序](https://leetcode-cn.com/problems/sort-integers-by-the-number-of-1-bits/) | 自定义排序规则 | [查看](https://github.com/pwstrick/daily/issues/1024) |
| [1491. 去掉最低工资和最高工资后的工资平均值](https://leetcode-cn.com/problems/average-salary-excluding-the-minimum-and-maximum-salary/) |  | [查看](https://github.com/pwstrick/daily/issues/1025) |
| [1502. 判断能否形成等差数列](https://leetcode-cn.com/problems/can-make-arithmetic-progression-from-sequence/) |  | [查看](https://github.com/pwstrick/daily/issues/1026) |

### 位运算
使用异或、与、非等位运算符解决各类计算。
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [136. 只出现一次的数字](https://leetcode-cn.com/problems/single-number/) | 异或 | [查看](https://github.com/pwstrick/daily/issues/1027) |
| [169. 多数元素](https://leetcode-cn.com/problems/majority-element/) |  | [查看](https://github.com/pwstrick/daily/issues/1028) |
| [191. 位1的个数](https://leetcode-cn.com/problems/number-of-1-bits/submissions/) | 二进制 | [查看](https://github.com/pwstrick/daily/issues/1029) |
| [231. 2的幂](https://leetcode-cn.com/problems/power-of-two/) |  | [查看](https://github.com/pwstrick/daily/issues/1030) |
| [268. 缺失数字](https://leetcode-cn.com/problems/missing-number/) | 减法 | [查看](https://github.com/pwstrick/daily/issues/1031) |
| [371. 两整数之和](https://leetcode-cn.com/problems/sum-of-two-integers/) | [异或+移位+与](https://leetcode-cn.com/problems/sum-of-two-integers/solution/wei-yun-suan-xiang-jie-yi-ji-zai-python-zhong-xu-y/) | [查看](https://github.com/pwstrick/daily/issues/1032) |
| [389. 找不同](https://leetcode-cn.com/problems/find-the-difference/) | 异或 | [查看](https://github.com/pwstrick/daily/issues/1033) |
| [461. 汉明距离](https://leetcode-cn.com/problems/hamming-distance/) | [异或](https://leetcode-cn.com/problems/hamming-distance/solution/yi-ming-ju-chi-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1034) |

### 树
可以用递归遍历二叉树，添加各种边界条件。
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [100. 相同的树](https://leetcode-cn.com/problems/same-tree/) | [递归](https://leetcode-cn.com/problems/same-tree/solution/hua-jie-suan-fa-100-xiang-tong-de-shu-by-guanpengc/) | [查看](https://github.com/pwstrick/daily/issues/1035) |
| [101. 对称二叉树](https://leetcode-cn.com/problems/symmetric-tree/) | [递归](https://leetcode-cn.com/problems/symmetric-tree/solution/dong-hua-yan-shi-101-dui-cheng-er-cha-shu-by-user7/) | [查看](https://github.com/pwstrick/daily/issues/1036) |
| [104. 二叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/) | [递归](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/solution/er-cha-shu-de-zui-da-shen-du-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1037) |
| [107. 二叉树的层次遍历 II](https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/) | [BFS+辅助栈](https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/solution/shi-yong-zhan-jin-xing-zhong-zhuan-by-liu-lang-xi-/) | [查看](https://github.com/pwstrick/daily/issues/1038) |
| [110. 平衡二叉树](https://leetcode-cn.com/problems/balanced-binary-tree/) | [两次递归](https://leetcode-cn.com/problems/balanced-binary-tree/solution/ping-heng-er-cha-shu-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1039) |
| [112. 路径总和](https://leetcode-cn.com/problems/path-sum/) | [减法递归](https://leetcode-cn.com/problems/path-sum/solution/lu-jing-zong-he-by-leetcode-solution/) | [查看](https://github.com/pwstrick/daily/issues/1040) |
| [102. 二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/) | 辅助队列 | [查看](https://github.com/pwstrick/daily/issues/1063) |
| [98. 验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree/) | 中序遍历 | [查看](https://github.com/pwstrick/daily/issues/1064) |
| [199. 二叉树的右视图](https://leetcode-cn.com/problems/binary-tree-right-side-view/) | BFS+取最后一个结点 | [查看](https://github.com/pwstrick/daily/issues/1065) |
| [103. 二叉树的锯齿形层次遍历](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/) | BFS | [查看](https://github.com/pwstrick/daily/issues/1066) |
| [113. 路径总和 II](https://leetcode-cn.com/problems/path-sum-ii/) | DFS+回溯 | [查看](https://github.com/pwstrick/daily/issues/1067) |
| [105. 从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | 前序+中序 | [查看](https://github.com/pwstrick/daily/issues/1068) |
| [226. 翻转二叉树](https://leetcode-cn.com/problems/invert-binary-tree/) | 递归+左右结点互换 | [查看](https://github.com/pwstrick/daily/issues/1069) |
| [96. 不同的二叉搜索树](https://leetcode-cn.com/problems/unique-binary-search-trees/) | [卡塔兰数](https://leetcode-cn.com/problems/unique-binary-search-trees/solution/bu-tong-de-er-cha-sou-suo-shu-by-leetcode-solution/) | [查看](https://github.com/pwstrick/daily/issues/1071) |
| [236. 二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/) | 递归 | [查看](https://github.com/pwstrick/daily/issues/1072) |

### 递归
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [783. 二叉搜索树节点最小距离](https://leetcode-cn.com/problems/minimum-distance-between-bst-nodes/) | [中序遍历](https://leetcode-cn.com/problems/minimum-distance-between-bst-nodes/solution/er-cha-sou-suo-shu-jie-dian-zui-xiao-ju-chi-by-lee/) | [查看](https://github.com/pwstrick/daily/issues/1041) |
| [938. 二叉搜索树的范围和](https://leetcode-cn.com/problems/range-sum-of-bst/) | [DFS](https://leetcode-cn.com/problems/range-sum-of-bst/solution/hua-jie-suan-fa-938-er-cha-sou-suo-shu-de-fan-wei-/) | [查看](https://github.com/pwstrick/daily/issues/1042) |
| [1137. 第 N 个泰波那契数](https://leetcode-cn.com/problems/n-th-tribonacci-number/) | 递归+缓存 | [查看](https://github.com/pwstrick/daily/issues/1043) |
| [剑指 Offer 10- II. 青蛙跳台阶问题](https://leetcode-cn.com/problems/qing-wa-tiao-tai-jie-wen-ti-lcof/) | 递归 | [查看](https://github.com/pwstrick/daily/issues/1044) |

### 链表
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [141. 环形链表](https://leetcode-cn.com/problems/linked-list-cycle/) | [双指针](https://leetcode-cn.com/problems/linked-list-cycle/solution/huan-xing-lian-biao-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1045) |
| [160. 相交链表](https://leetcode-cn.com/problems/intersection-of-two-linked-lists/) | [双指针](https://leetcode-cn.com/problems/intersection-of-two-linked-lists/solution/xiang-jiao-lian-biao-by-leetcode/) | [查看](https://github.com/pwstrick/daily/issues/1046) |
| [876. 链表的中间结点](https://leetcode-cn.com/problems/middle-of-the-linked-list/) | [双指针](https://leetcode-cn.com/problems/middle-of-the-linked-list/solution/lian-biao-de-zhong-jian-jie-dian-by-leetcode-solut/) | [查看](https://github.com/pwstrick/daily/issues/1047) |

### 字符串
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [14. 最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix/) | 遍历 | [查看](https://github.com/pwstrick/daily/issues/1048) |
| [680. 验证回文字符串 Ⅱ](https://leetcode-cn.com/problems/valid-palindrome-ii/) | [双指针](https://leetcode-cn.com/problems/valid-palindrome-ii/solution/shan-chu-zuo-zhi-huo-you-zhi-zhen-zi-fu-pan-duan-s/) | [查看](https://github.com/pwstrick/daily/issues/1049) |
| [647. 回文子串](https://leetcode-cn.com/problems/palindromic-substrings/) | 递归 | [查看](https://github.com/pwstrick/daily/issues/1073) |

### 数组
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [53. 最大子序和](https://leetcode-cn.com/problems/maximum-subarray/) | 双重循环或[动态规划](https://leetcode-cn.com/problems/maximum-subarray/solution/zui-da-zi-xu-he-by-leetcode-solution/) | [查看](https://github.com/pwstrick/daily/issues/1050) |

### 回溯
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [17. 电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number/) | [回溯模板](https://www.cnblogs.com/strick/p/13384038.html) | [查看](https://github.com/pwstrick/daily/issues/1059) |
| [22. 括号生成](https://leetcode-cn.com/problems/generate-parentheses/) | [递归加左括号或加右括号](https://leetcode-cn.com/problems/generate-parentheses/solution/gua-hao-sheng-cheng-by-leetcode-solution/) | [查看](https://github.com/pwstrick/daily/issues/1060) |

### 贪心算法
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [435. 无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/) | 按终点排序 | [查看](https://github.com/pwstrick/daily/issues/1053) |
| [455. 分发饼干](https://leetcode-cn.com/problems/assign-cookies/) | 将饼干大小和孩子需求升序 | [查看](https://github.com/pwstrick/daily/issues/1054) |
| [860. 柠檬水找零](https://leetcode-cn.com/problems/lemonade-change/) | 用最大面值找零 | [查看](https://github.com/pwstrick/daily/issues/1055) |
| [55. 跳跃游戏](https://leetcode-cn.com/problems/jump-game/) | 计算各个位置的最远距离 | [查看](https://github.com/pwstrick/daily/issues/1061) |
| [122. 买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/) | [今天的股价 - 昨天的股价](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/solution/tan-xin-suan-fa-by-liweiwei1419-2/) | [查看](https://github.com/pwstrick/daily/issues/1062) |

### 动态规划
| 题目 | 思路 | 实现  |
| :------------- | :-------------: | :-------------: |
| [198. 打家劫舍](https://leetcode-cn.com/problems/house-robber/) | [dp[n] = max(dp[n-1], dp[n-2] + nums[n])](https://leetcode-cn.com/problems/house-robber/solution/hua-jie-suan-fa-198-da-jia-jie-she-by-guanpengchn/) | [查看](https://github.com/pwstrick/daily/issues/1051) |
| [746. 使用最小花费爬楼梯](https://leetcode-cn.com/problems/min-cost-climbing-stairs/) | [dp[n] = min(dp[n-2], dp[n-1]) + cost[n]](https://leetcode-cn.com/problems/min-cost-climbing-stairs/solution/yi-bu-yi-bu-tui-dao-dong-tai-gui-hua-de-duo-chong-/) | [查看](https://github.com/pwstrick/daily/issues/1052) |
| [1143. 最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence/) | dp[i][j] = (dp[i-1][j-1] + 1) \| max(dp[i-1][j], dp[i][j-1]) | [查看](https://github.com/pwstrick/daily/issues/1056) |
| [300. 最长上升子序列](https://leetcode-cn.com/problems/longest-increasing-subsequence/) | dp[i][i] = 1 \| max(dp[i][j]) + 1 | [查看](https://github.com/pwstrick/daily/issues/1057) |
| [322. 零钱兑换](https://leetcode-cn.com/problems/coin-change/) | dp[i][j] = min(dp[i-1][j], dp[i][j - coins[i]] + 1) | [查看](https://github.com/pwstrick/daily/issues/1058) |
| [120. 三角形最小路径和](https://leetcode-cn.com/problems/triangle/) | dp[i][j] = min(dp[i-1][j], dp[i-1][j-1]) + triangle[i][j] | [查看](https://github.com/pwstrick/daily/issues/1070) |

