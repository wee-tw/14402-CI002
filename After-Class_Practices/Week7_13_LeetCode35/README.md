# LeetCode 35 - Search Insert Position

題目連結：[LeetCode 35 - Search Insert Position](https://leetcode.com/problems/search-insert-position/description/)

## 題目總結

在排序陣列中找 target，若不存在則回傳插入位置。

## 關鍵技巧

- lower_bound 語意：找第一個不小於 target 的位置。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(log n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
