# LeetCode 70 - Climbing Stairs

題目連結：[LeetCode 70 - Climbing Stairs](https://leetcode.com/problems/climbing-stairs/description/)

## 題目總結

每次爬 1 或 2 階，求到第 n 階的方法數。

## 關鍵技巧

- Fibonacci 型 DP：ways[n] = ways[n-1] + ways[n-2]，只需保存前兩項。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
