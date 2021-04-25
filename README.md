
<p align="center">
  <h1 align="center">AlgorithmDiary 算法日记📕</h1>
</p>

---


<div align="center">

![visitors](https://visitor-badge.glitch.me/badge?page_id=ExcaliburEX.AlgorithmDiary)[![Build Status](https://www.travis-ci.org/ExcaliburEX/AlgorithmDiary.svg?branch=master)](https://www.travis-ci.org/ExcaliburEX/AlgorithmDiary)
[![GitHub Issues](https://img.shields.io/github/issues/ExcaliburEX/AlgorithmDiary.svg)](https://github.com/ExcaliburEX/AlgorithmDiary)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/ExcaliburEX/AlgorithmDiary.svg)](https://github.com/ExcaliburEX/AlgorithmDiary/pulls)
![forks](https://img.shields.io/github/forks/ExcaliburEX/AlgorithmDiary)
![stars](	https://img.shields.io/github/stars/ExcaliburEX/AlgorithmDiary)
![repo size](https://img.shields.io/github/repo-size/ExcaliburEX/AlgorithmDiary)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)
<a href=""><img src="https://img.shields.io/github/commit-activity/m/ExcaliburEX/AlgorithmDiary.svg?color=blue&style=for-the-badge" alt="img"  width="260px"></a><a href=""><img src="https://img.shields.io/github/last-commit/ExcaliburEX/AlgorithmDiary.svg?color=blue&style=for-the-badge" alt="img" width="200px"></a><a href=""><img src="http://ForTheBadge.com/images/badges/makes-people-smile.svg" alt="img" width="190px"></a>

[![Travis](https://img.shields.io/badge/language-Python-red.svg)]()
</div>

---

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [柯摩的刷题日记](#%E6%9F%AF%E6%91%A9%E7%9A%84%E5%88%B7%E9%A2%98%E6%97%A5%E8%AE%B0)
  - [2021.2.4 ~ $\infty$](#202124--%5Cinfty)
- [1️⃣ 数据结构篇](#%E2%83%A3-%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E7%AF%87)
  - [📚 1️⃣.1️⃣ 二叉树](#-%E2%83%A3%E2%83%A3-%E4%BA%8C%E5%8F%89%E6%A0%91)
    - [1️⃣.1️⃣.1️⃣ 二叉树遍历](#%E2%83%A3%E2%83%A3%E2%83%A3-%E4%BA%8C%E5%8F%89%E6%A0%91%E9%81%8D%E5%8E%86)
      - [前序递归](#%E5%89%8D%E5%BA%8F%E9%80%92%E5%BD%92)
      - [前序非递归](#%E5%89%8D%E5%BA%8F%E9%9D%9E%E9%80%92%E5%BD%92)
      - [中序非递归](#%E4%B8%AD%E5%BA%8F%E9%9D%9E%E9%80%92%E5%BD%92)
      - [后序非递归](#%E5%90%8E%E5%BA%8F%E9%9D%9E%E9%80%92%E5%BD%92)
      - [DFS 深度搜索-从上到下](#dfs-%E6%B7%B1%E5%BA%A6%E6%90%9C%E7%B4%A2-%E4%BB%8E%E4%B8%8A%E5%88%B0%E4%B8%8B)
      - [DFS 深度搜索-从下向上（分治法）](#dfs-%E6%B7%B1%E5%BA%A6%E6%90%9C%E7%B4%A2-%E4%BB%8E%E4%B8%8B%E5%90%91%E4%B8%8A%E5%88%86%E6%B2%BB%E6%B3%95)
      - [BFS 层次遍历](#bfs-%E5%B1%82%E6%AC%A1%E9%81%8D%E5%8E%86)
    - [1️⃣.1️⃣.2️⃣ 分治法应用](#%E2%83%A3%E2%83%A3%E2%83%A3-%E5%88%86%E6%B2%BB%E6%B3%95%E5%BA%94%E7%94%A8)
      - [典型示例](#%E5%85%B8%E5%9E%8B%E7%A4%BA%E4%BE%8B)
      - [归并排序](#%E5%BD%92%E5%B9%B6%E6%8E%92%E5%BA%8F)
      - [快速排序](#%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F)
      - [2021-02-04](#2021-02-04)
        - [1️⃣ 104. Maximum Depth of Binary Tree](#%E2%83%A3-104-maximum-depth-of-binary-tree)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF)
          - [解法一](#%E8%A7%A3%E6%B3%95%E4%B8%80)
      - [2021-04-08](#2021-04-08)
        - [1️⃣ 105. 平衡二叉树](#%E2%83%A3-105-%E5%B9%B3%E8%A1%A1%E4%BA%8C%E5%8F%89%E6%A0%91)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-1)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-1)
          - [解法一](#%E8%A7%A3%E6%B3%95%E4%B8%80-1)
      - [2021-04-15](#2021-04-15)
        - [1️⃣ 124.  二叉树中的最大路径和](#%E2%83%A3-124--%E4%BA%8C%E5%8F%89%E6%A0%91%E4%B8%AD%E7%9A%84%E6%9C%80%E5%A4%A7%E8%B7%AF%E5%BE%84%E5%92%8C)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-2)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-2)
          - [解法](#%E8%A7%A3%E6%B3%95)
      - [2021-04-24](#2021-04-24)
        - [1️⃣ 236. 二叉树的最近公共祖先](#%E2%83%A3-236-%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-3)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-3)
          - [解法](#%E8%A7%A3%E6%B3%95-1)
    - [1️⃣.1️⃣.3️⃣ BFS 层次应用](#%E2%83%A3%E2%83%A3%E2%83%A3-bfs-%E5%B1%82%E6%AC%A1%E5%BA%94%E7%94%A8)
      - [2021-04-25](#2021-04-25)
        - [1️⃣ 103. 二叉树的锯齿形层序遍历](#%E2%83%A3-103-%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E9%94%AF%E9%BD%BF%E5%BD%A2%E5%B1%82%E5%BA%8F%E9%81%8D%E5%8E%86)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-4)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-4)
          - [解法](#%E8%A7%A3%E6%B3%95-2)
    - [1️⃣.1️⃣.4️⃣ 二叉搜索树应用](#%E2%83%A3%E2%83%A3%E2%83%A3-%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E5%BA%94%E7%94%A8)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 柯摩的刷题日记


## 2021.2.4 ~ $\infty$

0️⃣1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣🔟🔢*️⃣🆕🆒🆗🆙

刷题路径：

[`algorithm-pattern 练习题`](https://greyireland.gitbook.io/algorithm-pattern/) —> [`LeetCode 精选 TOP 面试题`](https://leetcode-cn.com/problemset/all/?listId=2ckc81c)(一个半月) —> [`剑指 offer`](https://leetcode-cn.com/problemset/lcof/)(半个月)

# 1️⃣ 数据结构篇
- 掌握二叉树递归与非递归遍历
- 理解 DFS 前序遍历与分治法
- 理解 BFS 层次遍历

## 📚 1️⃣.1️⃣ 二叉树
### 1️⃣.1️⃣.1️⃣ 二叉树遍历
前序遍历：先访问根节点，再前序遍历左子树，再前序遍历右子树 中序遍历：先中序遍历左子树，再访问根节点，再中序遍历右子树 后序遍历：先后序遍历左子树，再后序遍历右子树，再访问根节点。
- 注意点
	- 以根访问顺序决定是什么遍历
	- 左子树都是优先右子树
#### 前序递归
```python
def preorder_rec(root):
    if root is None:
        return
    visit(root)
    preorder_rec(root.left)
    preorder_rec(root.right)
    return

def inorder_rec(root):
    if root is None:
        return
    inorder_rec(root.left)
    visit(root)
    inorder_rec(root.right)
    return

def postorder_rec(root):
    if root is None:
        return
    postorder_rec(root.left)
    postorder_rec(root.right)
    visit(root)
    return
```
#### 前序非递归
```python
class Solution:
    def preorderTraversal(self, root: TreeNode) -> List[int]:
        
        preorder = []
        if root is None:
            return preorder
        
        s = [root]
        while len(s) > 0:
            node = s.pop()
            preorder.append(node.val)
            if node.right is not None:
                s.append(node.right)
            if node.left is not None:
                s.append(node.left)
        
        return preorder
```
#### 中序非递归
```python
class Solution:
    def inorderTraversal(self, root: TreeNode) -> List[int]:
        s, inorder = [], []
        node = root
        while len(s) > 0 or node is not None:
            if node is not None:
                s.append(node)
                node = node.left
            else:
                node = s.pop()
                inorder.append(node.val)
                node = node.right
        return inorder
```
#### 后序非递归
```python
class Solution:
    def postorderTraversal(self, root: TreeNode) -> List[int]:

        s, postorder = [], []
        node, last_visit = root, None
        
        while len(s) > 0 or node is not None:
            if node is not None:
                s.append(node)
                node = node.left
            else:
                peek = s[-1]
                if peek.right is not None and last_visit != peek.right:
                    node = peek.right
                else:
                    last_visit = s.pop()
                    postorder.append(last_visit.val)
        
        
        return postorder
```
- 注意点
	- 核心就是：根节点必须在右节点弹出之后，再弹出

#### DFS 深度搜索-从上到下
```go
type TreeNode struct {
    Val   int
    Left  *TreeNode
    Right *TreeNode
}

func preorderTraversal(root *TreeNode) []int {
    result := make([]int, 0)
    dfs(root, &result)
    return result
}

// V1：深度遍历，结果指针作为参数传入到函数内部
func dfs(root *TreeNode, result *[]int) {
    if root == nil {
        return
    }
    *result = append(*result, root.Val)
    dfs(root.Left, result)
    dfs(root.Right, result)
}
```
#### DFS 深度搜索-从下向上（分治法）
```python
// V2：通过分治法遍历
class Solution:
    def preorderTraversal(self, root: TreeNode) -> List[int]:
        
        if root is None:
            return []
        
        left_result = self.preorderTraversal(root.left)
        right_result = self.preorderTraversal(root.right)
        
        return [root.val] + left_result + right_result
```

- 注意点：
	- DFS 深度搜索（从上到下） 和分治法区别：前者一般将最终结果通过指针参数传入，后者一般递归返回结果最后合并

#### BFS 层次遍历
```python
class Solution:
    def levelOrder(self, root: TreeNode) -> List[List[int]]:
        
        levels = []
        if root is None:
            return levels
        
        bfs = collections.deque([root])
        
        while len(bfs) > 0:
            levels.append([])
            
            level_size = len(bfs)
            for _ in range(level_size):
                node = bfs.popleft()
                levels[-1].append(node.val)
                
                if node.left is not None:
                    bfs.append(node.left)
                if node.right is not None:
                    bfs.append(node.right)
        
        return levels
```





### 1️⃣.1️⃣.2️⃣ 分治法应用
先分别处理局部，再合并结果。

**适用场景**

- 快速排序

- 归并排序

- 二叉树相关问题

**分治法模板**

- 递归返回条件

- 分段处理

- 合并结果

```go
func traversal(root *TreeNode) ResultType  {
    // nil or leaf
    if root == nil {
        // do something and return
    }

    // Divide
    ResultType left = traversal(root.Left)
    ResultType right = traversal(root.Right)

    // Conquer
    ResultType result = Merge from left and right

    return result
}
```

#### 典型示例

```go
// V2：通过分治法遍历二叉树
func preorderTraversal(root *TreeNode) []int {
    result := divideAndConquer(root)
    return result
}
func divideAndConquer(root *TreeNode) []int {
    result := make([]int, 0)
    // 返回条件(null & leaf)
    if root == nil {
        return result
    }
    // 分治(Divide)
    left := divideAndConquer(root.Left)
    right := divideAndConquer(root.Right)
    // 合并结果(Conquer)
    result = append(result, root.Val)
    result = append(result, left...)
    result = append(result, right...)
    return result
}
```

#### 归并排序
```go
func MergeSort(nums []int) []int {
    return mergeSort(nums)
}
func mergeSort(nums []int) []int {
    if len(nums) <= 1 {
        return nums
    }
    // 分治法：divide 分为两段
    mid := len(nums) / 2
    left := mergeSort(nums[:mid])
    right := mergeSort(nums[mid:])
    // 合并两段数据
    result := merge(left, right)
    return result
}
func merge(left, right []int) (result []int) {
    // 两边数组合并游标
    l := 0
    r := 0
    // 注意不能越界
    for l < len(left) && r < len(right) {
        // 谁小合并谁
        if left[l] > right[r] {
            result = append(result, right[r])
            r++
        } else {
            result = append(result, left[l])
            l++
        }
    }
    // 剩余部分合并
    result = append(result, left[l:]...)
    result = append(result, right[r:]...)
    return
}
```
- **注意点**
	- 递归需要返回结果用于合并

#### 快速排序

```go
func QuickSort(nums []int) []int {
    // 思路：把一个数组分为左右两段，左段小于右段，类似分治法没有合并过程
    quickSort(nums, 0, len(nums)-1)
    return nums

}
// 原地交换，所以传入交换索引
func quickSort(nums []int, start, end int) {
    if start < end {
        // 分治法：divide
        pivot := partition(nums, start, end)
        quickSort(nums, 0, pivot-1)
        quickSort(nums, pivot+1, end)
    }
}
// 分区
func partition(nums []int, start, end int) int {
    p := nums[end]
    i := start
    for j := start; j < end; j++ {
        if nums[j] < p {
            swap(nums, i, j)
            i++
        }
    }
    // 把中间的值换为用于比较的基准值
    swap(nums, i, end)
    return i
}
func swap(nums []int, i, j int) {
    t := nums[i]
    nums[i] = nums[j]
    nums[j] = t
}
```

- **注意点**
	- 快排由于是原地交换所以没有合并过程 传入的索引是存在的索引（如：0、length-1 等），越界可能导致崩溃。

#### 2021-02-04

##### 1️⃣ 104. [Maximum Depth of Binary Tree](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/)
###### **题目描述**
> 给定一个二叉树，找出其最大深度。二叉树的深度为根节点到最远叶子节点的最长路径上的节点数。说明: 叶子节点是指没有子节点的节点。

###### 解题思路
简单题，常规思路，分治法

###### 解法一
```python
class Solution:
    def maxDepth(self, root: TreeNode) -> int:
        
        if root is None:
            return 0
        
        return 1 + max(self.maxDepth(root.left), self.maxDepth(root.right))
```
#### 2021-04-08
#####  1️⃣ 105. [平衡二叉树](https://leetcode-cn.com/problems/balanced-binary-tree/)

###### **题目描述**
> 给定一个二叉树，判断它是否是高度平衡的二叉树。

###### 解题思路
分治法，左边平衡 && 右边平衡 && 左右两边高度 <= 1

###### 解法一

```python
class Solution(object):
    def isBalanced(self, root):
        """
        :type root: TreeNode
        :rtype: bool
        """
        def depth(root):
            if root == None:
                return 0, True
            
            dl, bl = depth(root.left)
            dr, br = depth(root.right)
            
            return max(dl, dr) + 1, bl and br and abs(dl- dr) <2
        _, out = depth(root)
        return out
```

#### 2021-04-15
#####  1️⃣ 124. [ 二叉树中的最大路径和](https://leetcode-cn.com/problems/binary-tree-maximum-path-sum/)

###### **题目描述**
> 给定一个非空二叉树，返回其最大路径和。

###### 解题思路
思路：分治法。最大路径的可能情况：左子树的最大路径，右子树的最大路径，或通过根结点的最大路径。其中通过根结点的最大路径值等于以左子树根结点为端点的最大路径值加以右子树根结点为端点的最大路径值再加上根结点值，这里还要考虑有负值的情况即负值路径需要丢弃不取。

###### 解法
```python
class Solution(object):
    def maxPathSum(self, root):
        """
        :type root: TreeNode
        :rtype: int
        """
        self.maxPath = float('-inf')

        def largest_path_ends_at(node):
            if node is None:
                return float('-inf')
            e_l = largest_path_ends_at(node.left)
            e_r = largest_path_ends_at(node.right)

            self.maxPath = max(self.maxPath, node.val +
                               max(0, e_l)+max(0, e_r), e_l, e_r)

            return node.val + max(e_l, e_r, 0)

        largest_path_ends_at(root)
        return self.maxPath
```


#### 2021-04-24
#####  1️⃣ 236. [二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/)

###### **题目描述**
> 给定一个二叉树, 找到该树中两个指定节点的最近公共祖先。

###### 解题思路
思路：分治法，有左子树的公共祖先或者有右子树的公共祖先，就返回子树的祖先，否则返回根节点

###### 解法
```python
class Solution:
    def lowestCommonAncestor(self, root: 'TreeNode', p: 'TreeNode', q: 'TreeNode') -> 'TreeNode':
        if root is None:
            return None

        if root == p or root == q:
            return root

        left  = self.lowestCommonAncestor(root.left, p, q)
        right = self.lowestCommonAncestor(root.right, p, q)

        if left is not None and right is not None:
            return root
        elif left is not None:
            return left
        elif right is not None:
            return right
        else:
            return None
```


### 1️⃣.1️⃣.3️⃣ BFS 层次应用

#### 2021-04-25
#####  1️⃣ 103. [二叉树的锯齿形层序遍历](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/)

###### **题目描述**
> 给定一个二叉树，返回其节点值的锯齿形层序遍历。（即先从左往右，再从右往左进行下一层遍历，以此类推，层与层之间交替进行）。

###### 解题思路
思路：在BFS迭代模板上改用双端队列控制输出顺序

###### 解法
```python
class Solution:
    def zigzagLevelOrder(self, root: TreeNode) -> List[List[int]]:
        levels = []
        if root is None:
            return levels
        s = collections.deque([root])
        start_from_left = True
        while len(s) > 0:
            levels.append([])
            level_size = len(s)

            if start_from_left:
                for _ in range(level_size):
                    node = s.popleft()
                    levels[-1].append(node.val)
                    if node.left is not None:
                        s.append(node.left)
                    if node.right is not None:
                        s.append(node.right)
            else:
                for _ in range(level_size):
                    node = s.pop()
                    levels[-1].append(node.val)
                    if node.right is not None:
                        s.appendleft(node.right)
                    if node.left is not None:
                        s.appendleft(node.left)
            start_from_left = not start_from_left

        return levels
```


### 1️⃣.1️⃣.4️⃣ 二叉搜索树应用
