# LeetCode 179 - Largest Number

題目連結：[LeetCode 179 - Largest Number](https://leetcode.com/problems/largest-number/description/)

## 題目總結

重新排列非負整數，使串接後形成最大的數字。

## 關鍵技巧

- 排序比較 a+b 與 b+a，若 a+b 較大則 a 應排在 b 前面；最後處理全 0 情況。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n log n * k)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
