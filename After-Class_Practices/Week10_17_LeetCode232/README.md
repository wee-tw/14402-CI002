# LeetCode 232 - Implement Queue using Stacks

題目連結：[LeetCode 232 - Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/description/)

## 題目總結

只用 stack 實作 FIFO queue。

## 關鍵技巧

- in stack 負責 push，out stack 負責 pop/peek；out 空時才把 in 全部倒過去。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: Amortized O(1) per operation
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
