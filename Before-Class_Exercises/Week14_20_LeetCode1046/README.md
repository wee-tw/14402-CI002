# LeetCode 1046 - Last Stone Weight

題目連結：[LeetCode 1046 - Last Stone Weight](https://leetcode.com/problems/last-stone-weight/description/)

## 題目總結

每次取兩顆最重石頭互撞，求最後剩餘重量。

## 關鍵技巧

- max heap 可快速取出目前最大兩個重量，差值非 0 時再放回。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n log n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
