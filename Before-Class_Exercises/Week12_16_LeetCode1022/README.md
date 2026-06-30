# LeetCode 1022 - Sum of Root To Leaf Binary Numbers

題目連結：[LeetCode 1022 - Sum of Root To Leaf Binary Numbers](https://leetcode.com/problems/sum-of-root-to-leaf-binary-numbers/description/)

## 題目總結

每條 root-to-leaf 路徑代表一個二進位數，求所有路徑數值總和。

## 關鍵技巧

- DFS 時把目前值左移一位再加當前節點值；到葉節點時回傳目前值。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
