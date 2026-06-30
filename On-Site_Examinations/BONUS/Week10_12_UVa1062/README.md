# UVa 1062 - Containers

題目連結：[UVa 1062 - Containers](https://onlinejudge.org/external/10/1062.pdf)

## 題目總結

求裝箱序列需要的最少堆數。

## 關鍵技巧

- 每個 container 放到頂端字母不小於它且最小的堆，沒有就開新堆。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n*piles)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
