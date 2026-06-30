# LeetCode 8 - String to Integer (atoi)

題目連結：[LeetCode 8 - String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/)

## 題目總結

依 atoi 規則將字串轉成 32-bit signed integer。

## 關鍵技巧

- 依序處理前導空白、正負號、數字；累積時先檢查是否會超過 INT_MAX/INT_MIN。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
