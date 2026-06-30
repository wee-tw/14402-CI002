# LeetCode 1845 - Seat Reservation Manager

題目連結：[LeetCode 1845 - Seat Reservation Manager](https://leetcode.com/problems/seat-reservation-manager/description/)

## 題目總結

實作可保留最小可用座位、也可釋放座位的管理器。

## 關鍵技巧

- min heap 保存目前可用座位編號，reserve 取最小值，unreserve 放回 heap。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(log n) per operation
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
