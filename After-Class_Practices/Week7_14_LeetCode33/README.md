# LeetCode 33 - Search in Rotated Sorted Array

題目連結：[LeetCode 33 - Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)

## 題目總結

在無重複、旋轉過的排序陣列中搜尋 target。

## 關鍵技巧

- 二分時至少有一半仍是有序區間，判斷 target 是否落在有序半邊來縮小範圍。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(log n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
