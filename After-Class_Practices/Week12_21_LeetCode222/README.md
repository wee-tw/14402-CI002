# LeetCode 222 - Count Complete Tree Nodes

題目連結：[LeetCode 222 - Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/description/)

## 題目總結

計算 complete binary tree 的節點數。

## 關鍵技巧

- 比較左右最深高度；若相等代表滿二元樹可直接用 2^h-1，否則遞迴左右子樹。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(log^2 n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
