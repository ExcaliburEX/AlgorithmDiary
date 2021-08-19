
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
      - [2021-05-03](#2021-05-03)
        - [1️⃣ 98. 验证二叉搜索树](#%E2%83%A3-98-%E9%AA%8C%E8%AF%81%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-5)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-5)
          - [解法](#%E8%A7%A3%E6%B3%95-3)
      - [2021-05-05](#2021-05-05)
        - [1️⃣ 701. 二叉搜索树中的插入操作](#%E2%83%A3-701-%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E6%8F%92%E5%85%A5%E6%93%8D%E4%BD%9C)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-6)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-6)
          - [解法](#%E8%A7%A3%E6%B3%95-4)
  - [📚 1️⃣.2️⃣ 链表](#-%E2%83%A3%E2%83%A3-%E9%93%BE%E8%A1%A8)
      - [2021-05-06](#2021-05-06)
        - [1️⃣ 83. 删除排序链表中的重复元素](#%E2%83%A3-83-%E5%88%A0%E9%99%A4%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-7)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-7)
          - [解法](#%E8%A7%A3%E6%B3%95-5)
      - [2021-05-07](#2021-05-07)
        - [1️⃣ 82.  删除排序链表中的重复元素 II](#%E2%83%A3-82--%E5%88%A0%E9%99%A4%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0-ii)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-8)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-8)
          - [解法](#%E8%A7%A3%E6%B3%95-6)
      - [2021-05-08](#2021-05-08)
        - [1️⃣ 206. 反转链表](#%E2%83%A3-206-%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-9)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-9)
          - [解法一](#%E8%A7%A3%E6%B3%95%E4%B8%80-2)
          - [解法二](#%E8%A7%A3%E6%B3%95%E4%BA%8C)
      - [2021-05-12](#2021-05-12)
        - [1️⃣ 92. 反转链表 II](#%E2%83%A3-92-%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8-ii)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-10)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-10)
          - [解法](#%E8%A7%A3%E6%B3%95-7)
      - [2021-05-13](#2021-05-13)
        - [1️⃣ 21. 合并两个有序链表](#%E2%83%A3-21-%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%9C%89%E5%BA%8F%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-11)
          - [解题思路](#%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF-11)
          - [解法](#%E8%A7%A3%E6%B3%95-8)
      - [2021-05-17](#2021-05-17)
        - [1️⃣ 86. 分隔链表](#%E2%83%A3-86-%E5%88%86%E9%9A%94%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-12)
          - [解法](#%E8%A7%A3%E6%B3%95-9)
      - [2021-05-18](#2021-05-18)
        - [1️⃣ 148. 排序链表](#%E2%83%A3-148-%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-13)
          - [解法](#%E8%A7%A3%E6%B3%95-10)
      - [2021-05-19~26](#2021-05-1926)
        - [1️⃣ 143. 排序链表](#%E2%83%A3-143-%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-14)
          - [解法](#%E8%A7%A3%E6%B3%95-11)
      - [2021-05-31](#2021-05-31)
        - [1️⃣ 141. 环形链表](#%E2%83%A3-141-%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-15)
          - [解法](#%E8%A7%A3%E6%B3%95-12)
      - [2021-06-01](#2021-06-01)
        - [1️⃣ 142. 环形链表 II](#%E2%83%A3-142-%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8-ii)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-16)
          - [解法](#%E8%A7%A3%E6%B3%95-13)
      - [2021-06-03](#2021-06-03)
        - [1️⃣ 234. 回文链表](#%E2%83%A3-234-%E5%9B%9E%E6%96%87%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-17)
          - [解法](#%E8%A7%A3%E6%B3%95-14)
      - [2021-06-06](#2021-06-06)
        - [1️⃣ 138. 复制带随机指针的链表](#%E2%83%A3-138-%E5%A4%8D%E5%88%B6%E5%B8%A6%E9%9A%8F%E6%9C%BA%E6%8C%87%E9%92%88%E7%9A%84%E9%93%BE%E8%A1%A8)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-18)
          - [解法](#%E8%A7%A3%E6%B3%95-15)
  - [📚 1️⃣.3️⃣ 栈和队列](#-%E2%83%A3%E2%83%A3-%E6%A0%88%E5%92%8C%E9%98%9F%E5%88%97)
      - [2021-06-07](#2021-06-07)
        - [1️⃣ 155. 最小栈](#%E2%83%A3-155-%E6%9C%80%E5%B0%8F%E6%A0%88)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-19)
          - [解法](#%E8%A7%A3%E6%B3%95-16)
      - [2021-06-09](#2021-06-09)
        - [1️⃣ 150. 逆波兰表达式求值](#%E2%83%A3-150-%E9%80%86%E6%B3%A2%E5%85%B0%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B1%82%E5%80%BC)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-20)
          - [解法](#%E8%A7%A3%E6%B3%95-17)
      - [2021-06-10](#2021-06-10)
        - [1️⃣ 394. 字符串解码](#%E2%83%A3-394-%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%A7%A3%E7%A0%81)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-21)
          - [解法](#%E8%A7%A3%E6%B3%95-18)
      - [2021-06-11](#2021-06-11)
        - [1️⃣ 94. 二叉树的中序遍历](#%E2%83%A3-94-%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E4%B8%AD%E5%BA%8F%E9%81%8D%E5%8E%86)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-22)
          - [解法](#%E8%A7%A3%E6%B3%95-19)
      - [2021-06-15](#2021-06-15)
        - [1️⃣ 133. 克隆图](#%E2%83%A3-133-%E5%85%8B%E9%9A%86%E5%9B%BE)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-23)
          - [解法](#%E8%A7%A3%E6%B3%95-20)
      - [2021-06-16](#2021-06-16)
        - [1️⃣ 200. 岛屿数量](#%E2%83%A3-200-%E5%B2%9B%E5%B1%BF%E6%95%B0%E9%87%8F)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-24)
          - [解法](#%E8%A7%A3%E6%B3%95-21)
      - [2021-06-24](#2021-06-24)
        - [1️⃣ 84. 柱状图中最大的矩形](#%E2%83%A3-84-%E6%9F%B1%E7%8A%B6%E5%9B%BE%E4%B8%AD%E6%9C%80%E5%A4%A7%E7%9A%84%E7%9F%A9%E5%BD%A2)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-25)
          - [解法一](#%E8%A7%A3%E6%B3%95%E4%B8%80-3)
          - [解法二](#%E8%A7%A3%E6%B3%95%E4%BA%8C-1)
      - [2021-07-11](#2021-07-11)
        - [1️⃣ 232. 用栈实现队列](#%E2%83%A3-232-%E7%94%A8%E6%A0%88%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97)
          - [**题目描述**](#%E9%A2%98%E7%9B%AE%E6%8F%8F%E8%BF%B0-26)
          - [解法一](#%E8%A7%A3%E6%B3%95%E4%B8%80-4)
      - [2021-08-13](#2021-08-13)
        - [1️⃣ *102. 二叉树的层序遍历(BFS)](#%E2%83%A3-102-%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%B1%82%E5%BA%8F%E9%81%8D%E5%8E%86bfs)
        - [2️⃣ *542. 01 矩阵(BFS)](#%E2%83%A3-542-01-%E7%9F%A9%E9%98%B5bfs)
        - [3️⃣ *84. 柱状图中最大的矩形(单调栈)](#%E2%83%A3-84-%E6%9F%B1%E7%8A%B6%E5%9B%BE%E4%B8%AD%E6%9C%80%E5%A4%A7%E7%9A%84%E7%9F%A9%E5%BD%A2%E5%8D%95%E8%B0%83%E6%A0%88)
        - [4️⃣ *42. 接雨水(单调栈)](#%E2%83%A3-42-%E6%8E%A5%E9%9B%A8%E6%B0%B4%E5%8D%95%E8%B0%83%E6%A0%88)
        - [5️⃣ *239. 滑动窗口最大值(单调队列)](#%E2%83%A3-239-%E6%BB%91%E5%8A%A8%E7%AA%97%E5%8F%A3%E6%9C%80%E5%A4%A7%E5%80%BC%E5%8D%95%E8%B0%83%E9%98%9F%E5%88%97)
        - [6️⃣ *862. 和至少为 K 的最短子数组(单调队列)](#%E2%83%A3-862-%E5%92%8C%E8%87%B3%E5%B0%91%E4%B8%BA-k-%E7%9A%84%E6%9C%80%E7%9F%AD%E5%AD%90%E6%95%B0%E7%BB%84%E5%8D%95%E8%B0%83%E9%98%9F%E5%88%97)
  - [📚 1️⃣.4️⃣ 优先级队列 (堆)](#-%E2%83%A3%E2%83%A3-%E4%BC%98%E5%85%88%E7%BA%A7%E9%98%9F%E5%88%97-%E5%A0%86)
      - [2021-08-17](#2021-08-17)
        - [1️⃣ *703. 数据流中的第 K 大元素(heapq.heappush,heapq.heappop)](#%E2%83%A3-703-%E6%95%B0%E6%8D%AE%E6%B5%81%E4%B8%AD%E7%9A%84%E7%AC%AC-k-%E5%A4%A7%E5%85%83%E7%B4%A0heapqheappushheapqheappop)
        - [2️⃣ *378. 有序矩阵中第 K 小的元素(列有序的性质，第k个最小只可能在前k行中)](#%E2%83%A3-378-%E6%9C%89%E5%BA%8F%E7%9F%A9%E9%98%B5%E4%B8%AD%E7%AC%AC-k-%E5%B0%8F%E7%9A%84%E5%85%83%E7%B4%A0%E5%88%97%E6%9C%89%E5%BA%8F%E7%9A%84%E6%80%A7%E8%B4%A8%E7%AC%ACk%E4%B8%AA%E6%9C%80%E5%B0%8F%E5%8F%AA%E5%8F%AF%E8%83%BD%E5%9C%A8%E5%89%8Dk%E8%A1%8C%E4%B8%AD)
        - [3️⃣ *373. 查找和最小的K对数字(heapq,set)](#%E2%83%A3-373-%E6%9F%A5%E6%89%BE%E5%92%8C%E6%9C%80%E5%B0%8F%E7%9A%84k%E5%AF%B9%E6%95%B0%E5%AD%97heapqset)

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

---
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

---
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

---

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


---

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

---
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

---
#### 2021-05-03
#####  1️⃣ 98. [验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree/)

###### **题目描述**
> 给定一个二叉树，判断其是否是一个有效的二叉搜索树。

###### 解题思路
- 思路1：中序遍历后检查输出是否有序，缺点是如果不平衡无法提前返回结果。
- 思路2：分治法，一个二叉树为合法的二叉搜索树当且仅当左右子树为合法二叉搜索树且根结点值小于右子树最小值大于左子树最大值。缺点是若不用迭代形式实现则无法提前返回，而迭代实现又比较复杂。
- 思路3：利用二叉搜索树的性质，根结点为左子树的右边界，右子树的左边界，使用先序遍历自顶向下更新左右子树的边界并检查是否合法，迭代版本实现简单且可以提前返回结果。

###### 解法
```python
class Solution:
    def isValidBST(self, root: TreeNode) -> bool:
        
        if root is None:
            return True
        
        s = [(root, float('-inf'), float('inf'))]
        while len(s) > 0:
            node, low, up = s.pop()
            if node.left is not None:
                if node.left.val <= low or node.left.val >= node.val: # up更新为左子树的值
                    return False
                s.append((node.left, low, node.val))
            if node.right is not None:
                if node.right.val <= node.val or node.right.val >= up: # low更新为右子树的值
                    return False
                s.append((node.right, node.val, up))
        # 考虑一个有父节点和两个子节点的右节点，它要大于父节点并且要小于右节点
        return True
```

---
#### 2021-05-05
#####  1️⃣ 701. [二叉搜索树中的插入操作](https://leetcode-cn.com/problems/insert-into-a-binary-search-tree/)

###### **题目描述**
> 给定二叉搜索树（BST）的根节点和要插入树中的值，将值插入二叉搜索树。 返回插入后二叉搜索树的根节点。

###### 解题思路
思路：找到最后一个叶子节点满足插入条件即可。

###### 解法
```python
class Solution:
    def insertIntoBST(self, root: TreeNode, val: int) -> TreeNode:
        
        if root is None:
            return TreeNode(val)
        
        node = root
        while True:
            if val > node.val:
                if node.right is None:
                    node.right = TreeNode(val)
                    return root
                else:
                    node = node.right
            else:
                if node.left is None:
                    node.left = TreeNode(val)
                    return root
                else:
                    node = node.left
```


## 📚 1️⃣.2️⃣ 链表

---
#### 2021-05-06

#####  1️⃣ 83. [删除排序链表中的重复元素](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list/)

###### **题目描述**
> 给定一个排序链表，删除所有重复的元素，使得每个元素只出现一次。

###### 解题思路
常规思路
###### 解法
```python
class Solution:
    def deleteDuplicates(self, head: ListNode) -> ListNode:
        
        if head is None:
            return head
        
        current = head
        
        while current.next is not None:
            if current.next.val == current.val:
                current.next = current.next.next
            else:
                current = current.next
        
        return head
```

---
#### 2021-05-07

#####  1️⃣ 82. [ 删除排序链表中的重复元素 II](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list-ii/)

###### **题目描述**
> 存在一个按升序排列的链表，给你这个链表的头节点 head ，请你删除链表中所有存在数字重复情况的节点，只保留原始链表中 没有重复出现 的数字。

###### 解题思路
思路：链表头结点可能被删除，所以用 dummy node 辅助删除，current用来删除重复的第一个节点，peek删除重复的节点的第二个至第n个，最后判断peek是否删除过，还是最后删除一下。
###### 解法
```python
class Solution:
    def deleteDuplicates(self, head: ListNode) -> ListNode:
        
        if head is None:
            return head
        
        dummy = ListNode(next=head)
        
        current, peek = dummy, head
        find_dup = False
        while peek.next is not None:
            if peek.next.val == peek.val:
                find_dup = True
                peek.next = peek.next.next
            else:
                if find_dup:
                    find_dup = False
                    current.next = current.next.next
                else:
                    current = current.next
                peek = peek.next
        
        if find_dup:
            current.next = current.next.next
        
        return dummy.next
```

---
#### 2021-05-08

#####  1️⃣ 206. [反转链表](https://leetcode-cn.com/problems/reverse-linked-list/)

###### **题目描述**
> 给你单链表的头节点 head ，请你反转链表，并返回反转后的链表。

###### 解题思路
- 思路一：直接手动反转，tmp一直往后指，head不断更新最新的节点
- 思路二：采用递归，next的next指向自己，自己的next指向空
###### 解法一
```python
class Solution:
    def reverseList(self, head: ListNode) -> ListNode:
        
        if head is None:
            return head
        
        tail = head
        while tail.next is not None:
            # put tail.next to head  
            tmp = tail.next
            tail.next = tail.next.next
            tmp.next = head
            head = tmp
        
        return head

```
###### 解法二
```python
class Solution:
    def reverseList(self, head: ListNode) -> ListNode:
        
        if head is None or head.next is None:
            return head
        rev_next = self.reverseList(head.next)
        head.next.next = head
        head.next = None

        return rev_next
```

---

#### 2021-05-12

#####  1️⃣ 92. [反转链表 II](https://leetcode-cn.com/problems/reverse-linked-list-ii/)

###### **题目描述**
> 反转从位置  m  到  n  的链表。请使用一趟扫描完成反转。

###### 解题思路
- 思路：先找到 m 处, 再反转 n - m 次即可，核心点就是start处，要使用curr.next而不是start

###### 解法

```python
class Solution:
    def reverseBetween(self, head: ListNode, m: int, n: int) -> ListNode:
        
        if head is None:
            return head
        
        n -= m 
        
        curr = dummy = ListNode(next=head)
        while m > 1: 
            curr = curr.next
            m -= 1
        
        start = curr.next
        while n > 0: 
            tmp = start.next
            start.next = tmp.next
            tmp.next = curr.next # 这里不能用start，下面同样，主要是需要curr.next来连接，虽然start一直在变，而curr.next一直指着第一个start
            curr.next = tmp
            n -= 1
        return dummy.next
```

---


#### 2021-05-13

#####  1️⃣ 21. [合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists/)

###### **题目描述**
> 将两个升序链表合并为一个新的 升序 链表并返回。新链表是通过拼接给定的两个链表的所有节点组成的。 

###### 解题思路
- 思路：定义一个dummy，再用tail作为其移动指针，按照顺序连接

###### 解法

```python
class Solution:
    def mergeTwoLists(self, l1: ListNode, l2: ListNode) -> ListNode:
        
        tail = dummy = ListNode()
        while l1 is not None and l2 is not None:
            if l1.val > l2.val:
                tail.next = l2
                l2 = l2.next
            else:
                tail.next = l1
                l1 = l1.next
            tail = tail.next
                
        if l1 is None:
            tail.next = l2
        else:
            tail.next = l1

        return dummy.next
```

---

#### 2021-05-17

#####  1️⃣ 86. [分隔链表](https://leetcode-cn.com/problems/partition-list/)

###### **题目描述**
> 给定一个链表和一个特定值 x，对链表进行分隔，使得所有小于  x  的节点都在大于或等于  x  的节点之前。
###### 解题思路
- 思路：将大于 x 的节点，放到另外一个链表，最后连接这两个链表，当头节点不确定的时候，使用哑巴节点

###### 解法

```python
class Solution:
    def partition(self, head: ListNode, x: int) -> ListNode:
        p = l = ListNode()
        q = s = ListNode(next=head)
        
        while q.next is not None:
            if q.next.val < x:
                q = q.next
            else:
                p.next = q.next
                q.next = q.next.next
                p = p.next
        
        p.next = None
        q.next = l.next

        return s.next
            
```

---


#### 2021-05-18

#####  1️⃣ 148. [排序链表](https://leetcode-cn.com/problems/sort-list/)

###### **题目描述**
> 在  O(n log n) 时间复杂度和常数级空间复杂度下，对链表进行排序。
###### 解题思路
- 思路：归并排序，slow-fast找中点
  - 找中间节点方法：快慢指针，判断 fast 及 fast.Next 是否为 None 值
  - 递归 mergeSort 需要断开中间节点，mid.next = None
  - 递归返回条件为 head 为 None 或者 head.Next 为 None

###### 解法

```python

class Solution:
    def _merge(self, l1, l2): # 合并两个有序链表
        tail = l_merge = ListNode()

        while l1 is not None and l2 is not None:
            if l1.val > l2.val:
                tail.next = l2
                l2 = l2.next
            else:
                tail.next = l1
                l1 = l1.next
            tail = tail.next
        if l1 is not None:
            tail.next = l1
        else:
            tail.next = l2

        return l_merge.next

    def _findmid(self, head): # 找链表的中间节点
        slow, fast = head,head.next
        while fast is not None and fast.next is not None:
            fast = fast.next.next
            slow = slow.next

        return slow

    def sortList(self, head: ListNode) -> ListNode:
        if head is None or head.next is None:
            return head
        mid = self._findmid(head) # 先找中间节点
        tail = mid.next # tail指向下一半的第一个节点
        mid.next = None # 断开两个链表

        return self._merge(self.sortList(head),self.sortList(tail)) # 递归合并两个区间
            
```

---
#### 2021-05-19~26

#####  1️⃣ 143. [排序链表](https://leetcode-cn.com/problems/reorder-list/)

###### **题目描述**
> 给定一个单链表  L：L→L→…→L__n→L 将其重新排列后变为： L→L__n→L→L__n→L→L__n→…
###### 解题思路
- 思路：找到中点断开，翻转后面部分，然后左一个右一个地合并链表
  - 逆转链表的快速写法
  - 通过快慢指针找到中间节点，再左右开弓

###### 解法

```python

class Solution:
    def reverseList(self, head: ListNode) -> ListNode:
        # 逆转链表的快捷写法
        prev, curr = None, head
        while curr is not None:
            curr.next,prev,curr = prev,curr,curr.next

        return prev

    def reorderList(self, head: ListNode) -> None:
        """
        Do not return anything, modify head in-place instead.
        """
        if head is None or head.next is None or head.next.next is None:
            return

        slow, fast = head, head.next
        while fast is not None and fast.next is not None:
            fast = fast.next.next
            slow = slow.next

        h, m = head, slow.next
        slow.next = None

        m = self.reverseList(m)

        while h is not None and m is not None: # 左边链表一个，右边链一个地接合
            p = m.next
            m.next = h.next
            h.next = m
            h = h.next.next
            m = p
        return
      
```

---


#### 2021-05-31

#####  1️⃣ 141. [环形链表](https://leetcode-cn.com/problems/linked-list-cycle/)

###### **题目描述**
> 给定一个链表，判断链表中是否有环。
###### 解题思路
- 思路：快慢指针，快慢指针相同则有环
  - 证明：如果有环每走一步快慢指针距离会减 1
  - 空间复杂度 O(1) 最优
  - 时间复杂度 O(n) 但循环次数小于等于 n


###### 解法

```python

class Solution:
    def hasCycle(self, head: ListNode) -> bool:
        slow = fast = head
        while fast is not None and fast.next is not None:
            slow = slow.next
            fast = fast.next.next
            if fast == slow:
                return True

        return False
      
```

---
#### 2021-06-01

#####  1️⃣ 142. [环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii/)

###### **题目描述**
> 给定一个链表，返回链表开始入环的第一个节点. 如果链表无环，则返回`null`。
###### 解题思路
- 思路：快慢指针，快慢相遇之后，慢指针回到头，快慢指针步调一致一起移动，再次相遇点即为入环点。
  - 指针比较时直接比较对象，不要用值比较，链表中有可能存在重复值情况
  - 第一次相交后，快指针需要从下一个节点开始和头指针一起匀速移动
  - 时间复杂度 O(n) 但循环次数小于等于 n
  - fast 如果初始化为 head.Next 则中点在 slow.Next
  - fast 初始化为 head,则中点在 slow


###### 解法

```python

class Solution:
    def detectCycle(self, head: ListNode) -> ListNode:
        
        slow = fast = head
        
        while fast is not None and fast.next is not None:
            slow = slow.next
            fast = fast.next.next
            
            if slow == fast:
                slow = head
                while fast != slow:
                    fast = fast.next
                    slow = slow.next
                return slow

        return None
      
```

---
#### 2021-06-03

#####  1️⃣ 234. [回文链表](https://leetcode-cn.com/problems/palindrome-linked-list/)

###### **题目描述**
> 请判断一个链表是否为回文链表。
###### 解题思路
- 思路：O(1) 空间复杂度的解法需要破坏原链表
  - 找中点
  - 反转后半个list
  - 判断回文
  - 在实际应用中往往还需要复原（后半个list再反转一次后拼接），操作比较复杂
  - 可以采用只取值比较的做法


###### 解法

```python

class Solution:
    def isPalindrome(self, head: ListNode) -> bool:
        
        s = []
        slow = fast = head
        while fast is not None and fast.next is not None:
            s.append(slow.val)
            slow = slow.next
            fast = fast.next.next
        
        if fast is not None: # 中点是slow，如果是双数节点数，下一半的开头在slow.next
            slow = slow.next
        
        while len(s) > 0:
            if slow.val != s.pop():
                return False
            slow = slow.next
            
        return True
      
```

---
#### 2021-06-06

#####  1️⃣ 138. [复制带随机指针的链表](https://leetcode-cn.com/problems/copy-list-with-random-pointer/)

###### **题目描述**
> 给定一个链表，每个节点包含一个额外增加的随机指针，该指针可以指向链表中的任何节点或空节点。 要求返回这个链表的 深拷贝。
###### 解题思路
- 思路：利用collections.defaultdict()创造hash table，存储 random 指针的连接关系


###### 解法

```python
import collections

class Solution:
    def copyRandomList(self, head: 'Node') -> 'Node':
        
        if head is None:
            return None
        
        parent = collections.defaultdict(list) # 创造hash表结构

        
        out = Node(0)
        o, n = head, out
        while o is not None:
            n.next = Node(o.val) # 复制next结构
            n = n.next
            if o.random is not None:
                parent[o.random].append(n) # 存储random表
            o = o.next
            
        o, n = head, out.next
        while o is not None:
            if o in parent:
                for p in parent[o]: # o, n 同步后移，然后对parent[o]中所有值进行连接
                    p.random = n # 这里指向n是因为o,n同步移动，所以n跟o在同样的位置
            o = o.next
            n = n.next
        
        return out.next

      
```

## 📚 1️⃣.3️⃣ 栈和队列


---

#### 2021-06-07

#####  1️⃣ 155. [最小栈](https://leetcode-cn.com/problems/min-stack/)

###### **题目描述**
> 设计一个支持 push，pop，top 操作，并能在常数时间内检索到最小元素的栈。
###### 解题思路
- 思路：用元组来存储栈中的元素，第一个值为插入的值，第二个值为最小值，随着插入不断更新，保证当前最小值在栈顶即可。

###### 解法

```python
import collections

class MinStack:

    def __init__(self):
        """
        initialize your data structure here.
        """
        self.stack = []


    def push(self, val: int) -> None:
        if len(self.stack) > 0:
            self.stack.append((val,min(val,self.stack[-1][1])))
        else:
            self.stack.append((val,val))

    def pop(self) -> None:
        return self.stack.pop()[0]

    def top(self) -> int:
        return self.stack[-1][0]

    def getMin(self) -> int:
        return self.stack[-1][1]

      
```


---
#### 2021-06-09

#####  1️⃣ 150. [逆波兰表达式求值](https://leetcode-cn.com/problems/min-stack/)

###### **题目描述**
> 波兰表达式计算 > 输入: ["2", "1", "+", "3", "*"] > 输出: 9 解释: ((2 + 1) * 3) = 9
###### 解题思路
- 思路：通过栈保存原来的元素，遇到表达式弹出运算，再推入结果，重复这个过程

###### 解法

```python
import collections

class Solution:
    def evalRPN(self, tokens: List[str]) -> int:
        # 去掉括号后表达式无歧义
        # 遇到数字则入栈；遇到算符则取出栈顶两个数字进行计算，并将结果压入栈中。
        def comp(or1, op, or2):
            if op == '+':
                return or1 + or2
            if op == '-':
                return or1 - or2
            if op == '*':
                return or1 * or2
            if op == '/':
                abs_result = abs(or1) // abs(or2)
                return abs_result if or1 * or2 > 0 else -abs_result

        stack = []

        for token in tokens:
            if token in ['+', '-','*', '/']:
                or2 = stack.pop()
                or1 = stack.pop()
                stack.append(comp(or1,token,or2))
            else:
                stack.append(int(token))

        return stack[0]    
```

---
#### 2021-06-10

#####  1️⃣ 394. [字符串解码](https://leetcode-cn.com/problems/decode-string/)

###### **题目描述**
> 给定一个经过编码的字符串，返回它解码后的字符串。 s = "3[a]2[bc]", 返回 "aaabcbc". s = "3[a2[c]]", 返回 "accaccacc". s = "2[abc]3[cd]ef", 返回 "abcabccdcdcdef".
###### 解题思路
- 思路：通过两个栈进行操作，一个用于存数，另一个用来存字符串

###### 解法

```python
class Solution:
    def decodeString(self, s: str) -> str:
        
        stack_str = [''] # 栈初始化为字符串一定要注意
        stack_num = []
        
        num = 0
        for c in s:
            if c >= '0' and c <= '9':
                num = num * 10 + int(c)
            elif c == '[':
                stack_num.append(num)
                stack_str.append('')
                num = 0
            elif c == ']':
                cur_str = stack_str.pop()
                stack_str[-1] += cur_str * stack_num.pop() # 这里有一种情况："3[a2[c]]"括号里包括号，所以一定要先弹出，再合并，最后输出第一个元素
            else:
                stack_str[-1] += c
        
        return stack_str[0]
```

---


#### 2021-06-11

#####  1️⃣ 94. [二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/)

###### **题目描述**
> 给定一个二叉树，返回它的中序遍历。
###### 解题思路
- 思路：不断往左子树前进，进栈，若左子树为空，那么就弹出栈顶元素打印，再进行右子树进栈。

###### 解法

```python
class Solution:
    def inorderTraversal(self, root: TreeNode) -> List[int]:
        inorder, stack = [], []
        node = root

        while len(stack) > 0 or node is not None:
            if node is not None:
                stack.append(node)
                node = node.left
            else:
                node = stack.pop()
                inorder.append(node.val)
                node = node.right

        return inorder
        
```

---


#### 2021-06-15

#####  1️⃣ 133. [克隆图](https://leetcode-cn.com/problems/clone-graph/)

###### **题目描述**
> 给你无向连通图中一个节点的引用，请你返回该图的深拷贝（克隆）。
###### 解题思路
- 思路：BFS

###### 解法

```python
class Solution:
    def cloneGraph(self, node: 'Node') -> 'Node':
        if node is None:
            return None
            
        visited = {node:Node(node.val,[])}
        bfs = collections.deque([node])
        
        while len(bfs) > 0:
            curr = bfs.popleft() 
            curr_copy = visited[curr]
            for n in curr.neighbors:
                if n not in visited:
                    visited[n] = Node(n.val, [])
                    bfs.append(n)
                curr_copy.neighbors.append(visited[n])
        return visited[node]

        
```

---



#### 2021-06-16

#####  1️⃣ 200. [岛屿数量](https://leetcode-cn.com/problems/number-of-islands/)

###### **题目描述**
> 给定一个由  '1'（陆地）和 '0'（水）组成的的二维网格，计算岛屿的数量。一个岛被水包围，并且它是通过水平方向或垂直方向上相邻的陆地连接而成的。你可以假设网格的四个边均被水包围。
###### 解题思路
- 思路：沉岛思想：如果遇到一块陆地，DFS往四个方向搜索，把经过的陆地标记为湖水（沉岛，避免重复遍历）

###### 解法

```python
class Solution:
    def numIslands(self, grid: List[List[str]]) -> int:
        if not grid or not grid[0]:
            return 0

        m, n = len(grid), len(grid[0])

        def dfs_iter(i, j): # 非递归
            dfs = []
            dfs.append((i, j))
            while len(dfs) > 0:
                i, j = dfs.pop()
                if grid[i][j] == '1':
                    grid[i][j] = '0'
                    if i-1 >= 0:
                        dfs.append((i-1, j))
                    if j-1 >= 0:
                        dfs.append((i, j-1))
                    if i+1 < m:
                        dfs.append((i+1, j))
                    if j+1 < n:
                        dfs.append((i, j+1))
            return

        def dfs(grid, i, j): # 递归
            if not 0 <= i < m or not 0 <= j < n or grid[i][j] == '0': # 判断是否在某个范围之外 not 用法 很新奇
                return  # 碰到水或者出界
            grid[i][j] = '0'  # 将访问过的陆地标记为水面
            dfs(grid, i-1, j)  # 向上
            dfs(grid, i+1, j)  # 向下
            dfs(grid, i, j-1)  # 向左
            dfs(grid, i, j+1)  # 向右


        num_island = 0
        for i in range(m):
            for j in range(n):
                if grid[i][j] == '1':
                    num_island += 1
                    # dfs_iter(i, j)
                    dfs(grid, i, j)

        return num_island  
```

---
#### 2021-06-24

#####  1️⃣ 84. [柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/)

###### **题目描述**
> 给定 n 个非负整数，用来表示柱状图中各个柱子的高度。每个柱子彼此相邻，且宽度为 1 。 求在该柱状图中，能够勾勒出来的矩形的最大面积。
###### 解题思路
- 思路一：必会暴力法，比较每个以 i 开始 j 结束的最大矩形，A(i, j) = (j - i + 1) * min_height(i, j)，时间复杂度 O(n^2) 无法 AC。
- 思路二：包含当前 bar 最大矩形的边界为左边第一个高度小于当前高度的 bar 和右边第一个高度小于当前高度的 bar。暂时没看懂

###### 解法一

```python
class Solution:
    def largestRectangleArea(self, heights: List[int]) -> int:
        
        max_area = 0
        
        n = len(heights)
        for i in range(n):
            min_height = heights[i]
            for j in range(i, n):
                min_height = min(min_height, heights[j])
                max_area = max(max_area, min_height * (j - i + 1))
        
        return max_area

```
###### 解法二

```python
class Solution:
    def largestRectangleArea(self, heights: List[int]) -> int:
        
        n = len(heights)
        
        stack = [-1]
        max_area = 0
        
        for i in range(n):
            while len(stack) > 1 and heights[stack[-1]] > heights[i]:
                h = stack.pop()
                max_area = max(max_area, heights[h] * (i - stack[-1] - 1))
            stack.append(i)
        
        while len(stack) > 1:
            h = stack.pop()
            max_area = max(max_area, heights[h] * (n - stack[-1] - 1))
        
        return max_area
```

---


#### 2021-07-11

#####  1️⃣ 232. [用栈实现队列](https://leetcode-cn.com/problems/implement-queue-using-stacks/)

###### **题目描述**
> 使用栈实现队列
###### 解题思路
- 两个栈，一个进，一个出
- cache负责进数据，out负责出数据
- 当out为空时，将cache一股脑都倒进去，再弹出顶层元素
- 当out不为空时，就弹出它顶层元素

###### 解法一

```python
class MyQueue:

    def __init__(self):
        """
        Initialize your data structure here.
        """
        self.cache = []
        self.out = []

    def push(self, x: int) -> None:
        """
        Push element x to the back of queue.
        """
        self.cache.append(x)

    def pop(self) -> int:
        """
        Removes the element from in front of queue and returns that element.
        """
        if len(self.out) == 0:
            while len(self.cache) > 0:
                self.out.append(self.cache.pop())

        return self.out.pop()


    def peek(self) -> int:
        """
        Get the front element.
        """
        if len(self.out) > 0:
            return self.out[-1]
        else:
            return self.cache[0]
    
    def empty(self) -> bool:
        """
        Returns whether the queue is empty.
        """
        return len(self.cache) == 0 and len(self.out) == 0

```

---

#### 2021-08-13

#####  1️⃣ ![alt](https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-orange)102. [二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/)(BFS)
#####  2️⃣ ![alt](https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-orange)542. [01 矩阵](https://leetcode-cn.com/problems/01-matrix/)(BFS)
#####  3️⃣ ![alt](https://img.shields.io/badge/-%E5%9B%B0%E9%9A%BE-red)84. [柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/)(单调栈)
#####  4️⃣ ![alt](https://img.shields.io/badge/-%E5%9B%B0%E9%9A%BE-red)42. [接雨水](https://leetcode-cn.com/problems/trapping-rain-water/)(单调栈)
#####  5️⃣ ![alt](https://img.shields.io/badge/-%E5%9B%B0%E9%9A%BE-red)239. [滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum/)(单调队列)
#####  6️⃣ ![alt](https://img.shields.io/badge/-%E5%9B%B0%E9%9A%BE-red)862. [和至少为 K 的最短子数组](https://leetcode-cn.com/problems/shortest-subarray-with-sum-at-least-k/)(单调队列)

---

## 📚 1️⃣.4️⃣ 优先级队列 (堆)

#### 2021-08-17

#####  1️⃣ ![alt](https://img.shields.io/badge/-%E7%AE%80%E5%8D%95-green)703. [数据流中的第 K 大元素](https://leetcode-cn.com/problems/kth-largest-element-in-a-stream/)(heapq.heappush,heapq.heappop)
#####  2️⃣ ![alt](https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-orange)378. [有序矩阵中第 K 小的元素](https://leetcode-cn.com/problems/kth-smallest-element-in-a-sorted-matrix/)(列有序的性质，第k个最小只可能在前k行中)
#####  3️⃣ ![alt](https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-orange)373. [查找和最小的K对数字](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/)(heapq,set)

---

