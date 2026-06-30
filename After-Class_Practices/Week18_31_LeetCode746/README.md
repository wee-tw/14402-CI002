# LeetCode 746 - Min Cost Climbing Stairs

題目連結：[LeetCode 746 - Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/description/)

## 題目總結

每次可爬 1 或 2 階，求到達頂端的最低成本。

## 關鍵技巧

- DP 只需保存到前兩階的最低成本，頂端可從最後一階或倒數第二階上來。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
