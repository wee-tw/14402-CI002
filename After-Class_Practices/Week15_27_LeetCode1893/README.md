# LeetCode 1893 - Check if All the Integers in a Range Are Covered

題目連結：[LeetCode 1893 - Check if All the Integers in a Range Are Covered](https://leetcode.com/problems/check-if-all-the-integers-in-a-range-are-covered/description/)

## 題目總結

判斷 [left,right] 中每個整數是否都被至少一個區間覆蓋。

## 關鍵技巧

- 值域小，可用差分陣列標記區間覆蓋，再掃描目標範圍。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(ranges + value_range)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
