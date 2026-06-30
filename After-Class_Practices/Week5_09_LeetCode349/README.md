# LeetCode 349 - Intersection of Two Arrays

題目連結：[LeetCode 349 - Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/description/)

## 題目總結

回傳兩陣列共同出現的不同元素。

## 關鍵技巧

- 用 unordered_set 去重與查詢，第二個陣列中存在於第一集合者放入答案集合。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n+m)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
