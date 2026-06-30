# LeetCode 31 - Next Permutation

題目連結：[LeetCode 31 - Next Permutation](https://leetcode.com/problems/next-permutation/description/)

## 題目總結

將排列改成字典序下一個排列；若已最大則變成最小排列。

## 關鍵技巧

- 從右找第一個下降點，再找右側剛好比它大的元素交換，最後反轉後綴。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
