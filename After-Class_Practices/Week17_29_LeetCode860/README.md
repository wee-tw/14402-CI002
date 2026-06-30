# LeetCode 860 - Lemonade Change

題目連結：[LeetCode 860 - Lemonade Change](https://leetcode.com/problems/lemonade-change/description/)

## 題目總結

依序收款賣檸檬水，判斷是否能正確找零。

## 關鍵技巧

- 貪心保留 5 元與 10 元數量；遇到 20 元優先用 10+5 找零，否則用三張 5。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
