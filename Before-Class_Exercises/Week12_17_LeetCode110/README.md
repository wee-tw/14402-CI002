# LeetCode 110 - Balanced Binary Tree

題目連結：[LeetCode 110 - Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/description/)

## 題目總結

判斷二元樹每個節點的左右子樹高度差是否不超過 1。

## 關鍵技巧

- 後序 DFS 同時計算高度；若子樹已不平衡就回傳 -1 早停。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
