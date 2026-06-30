# LeetCode 64 - Minimum Path Sum

題目連結：[LeetCode 64 - Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/description/)

## 題目總結

在非負矩陣中只能向右或向下走，求路徑最小總和。

## 關鍵技巧

- 原地 DP，grid[i][j] 加上上方與左方可達成本的較小者。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(m*n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
