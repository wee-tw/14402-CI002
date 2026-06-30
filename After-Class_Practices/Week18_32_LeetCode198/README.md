# LeetCode 198 - House Robber

題目連結：[LeetCode 198 - House Robber](https://leetcode.com/problems/house-robber/description/)

## 題目總結

不能偷相鄰房子，求可偷到的最大金額。

## 關鍵技巧

- DP 狀態為偷到目前位置的最大值：max(不偷目前, 偷目前加上 i-2 最佳)。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
