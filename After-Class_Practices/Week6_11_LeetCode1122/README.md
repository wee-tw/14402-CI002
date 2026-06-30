# LeetCode 1122 - Relative Sort Array

題目連結：[LeetCode 1122 - Relative Sort Array](https://leetcode.com/problems/relative-sort-array/)

## 題目總結

依 arr2 的順序排序 arr1 中出現的元素，其餘元素升序放在最後。

## 關鍵技巧

- 題目值域小，可用計數陣列；先照 arr2 消耗計數，再升序輸出剩餘值。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n + value_range)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
