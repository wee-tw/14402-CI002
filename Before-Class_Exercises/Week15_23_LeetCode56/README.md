# LeetCode 56 - Merge Intervals

題目連結：[LeetCode 56 - Merge Intervals](https://leetcode.com/problems/merge-intervals/description/)

## 題目總結

合併所有重疊區間。

## 關鍵技巧

- 依左端點排序，若下一段左端不超過目前右端就合併，否則開新區間。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n log n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
