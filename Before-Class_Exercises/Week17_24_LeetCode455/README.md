# LeetCode 455 - Assign Cookies

題目連結：[LeetCode 455 - Assign Cookies](https://leetcode.com/problems/assign-cookies/description/)

## 題目總結

用餅乾滿足小孩胃口，求最多能滿足幾個小孩。

## 關鍵技巧

- 胃口與餅乾尺寸排序，從小到大用最小可滿足的餅乾配給目前小孩。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n log n + m log m)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
