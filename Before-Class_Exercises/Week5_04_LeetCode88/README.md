# LeetCode 88 - Merge Sorted Array

題目連結：[LeetCode 88 - Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/description/)

## 題目總結

將兩個已排序陣列合併到 nums1，nums1 後方有足夠空間。

## 關鍵技巧

- 從尾端往前放較大的元素，避免覆蓋 nums1 前段尚未處理的值。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(m+n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
