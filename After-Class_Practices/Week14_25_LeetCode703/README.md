# LeetCode 703 - Kth Largest Element in a Stream

題目連結：[LeetCode 703 - Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/description/)

## 題目總結

維護資料流中的第 k 大元素。

## 關鍵技巧

- 用大小最多為 k 的 min heap 保存目前最大的 k 個元素，heap top 即第 k 大。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(log k) per add
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
