# LeetCode 950 - Reveal Cards in Increasing Order

題目連結：[LeetCode 950 - Reveal Cards in Increasing Order](https://leetcode.com/problems/reveal-cards-in-increasing-order/description/)

## 題目總結

安排牌堆初始順序，使依規則翻牌時看到遞增序列。

## 關鍵技巧

- 排序牌面，queue 存索引模擬翻一張、移一張到底部的流程，把小牌放到依序翻出的索引。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n log n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
