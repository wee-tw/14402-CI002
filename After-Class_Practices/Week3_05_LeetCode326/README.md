# LeetCode 326 - Power of Three

題目連結：[LeetCode 326 - Power of Three](https://leetcode.com/problems/power-of-three/description/)

## 題目總結

判斷整數 n 是否為 3 的冪次。

## 關鍵技巧

- 反覆除以 3，若最後能降到 1 就是 3 的冪；n<=0 直接 false。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於字串處理、雙指標、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時特別注意邊界條件，例如空輸入、單元素、溢位、或無法達成的情況。

## 複雜度

- Time: O(log n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
