# LeetCode 304 - Range Sum Query 2D - Immutable

題目連結：[LeetCode 304 - Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/description/)

## 題目總結

多次查詢不可變矩陣的子矩形和。

## 關鍵技巧

- 建立二維 prefix sum，查詢時用 inclusion-exclusion 扣掉多算區域。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(mn) build, O(1) query
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
