# LeetCode 414 - Third Maximum Number

題目連結：[LeetCode 414 - Third Maximum Number](https://leetcode.com/problems/third-maximum-number/description/)

## 題目總結

找出陣列中第三大的不同數字；若不存在則回傳最大值。

## 關鍵技巧

- 用 set 去重並保持排序，超過三個元素時刪掉最小值，最後依大小回傳。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n log 3)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
