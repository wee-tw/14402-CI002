# LeetCode 228 - Summary Ranges

題目連結：[LeetCode 228 - Summary Ranges](https://leetcode.com/problems/summary-ranges/description/)

## 題目總結

將排序且不重複的整數陣列壓縮成連續區間字串。

## 關鍵技巧

- 掃描每段連續區間的起點與終點，單點輸出 x，多點輸出 x->y。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
