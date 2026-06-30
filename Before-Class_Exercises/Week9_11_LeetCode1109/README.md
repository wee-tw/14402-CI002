# LeetCode 1109 - Corporate Flight Bookings

題目連結：[LeetCode 1109 - Corporate Flight Bookings](https://leetcode.com/problems/corporate-flight-bookings/description/)

## 題目總結

多筆區間加總訂位，輸出每個航班的總座位數。

## 關鍵技巧

- 使用差分陣列：區間 [l,r] 加 seats 時 diff[l]+=seats、diff[r+1]-=seats，最後做 prefix sum。
- LeetCode 題目通常只需要提交 `class Solution` 或指定類別；本 repo 的 `src` 保留必要 include，方便閱讀與練習。

## 解法概念

先辨認題型屬於位元運算、排序、二分、stack/queue、greedy 或 DP，再把狀態縮小到題目真正需要維護的資訊。實作時注意邊界條件，例如空集合、單元素、全 0、或無法達成的情況。

## 複雜度

- Time: O(n+bookings)
- Space: 視資料結構而定，通常為 O(1) 到 O(n)。
