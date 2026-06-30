# LeetCode 74 - Search a 2D Matrix

題目連結：[LeetCode 74 - Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/description/)

## 題目總結

在每列遞增且列與列之間也有序的矩陣中搜尋 target。

## 關鍵技巧

- 把 m x n 矩陣視為長度 m*n 的一維排序陣列，二分後用 index/n 與 index%n 取值。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(log(mn))
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
