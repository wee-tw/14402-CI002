# UVa 12503 - Robot Instructions

題目連結：[UVa 12503 - Robot Instructions](https://onlinejudge.org/external/125/12503.pdf)

## 題目總結

依指令左右移動，SAME AS 會複製之前某一步。

## 關鍵技巧

- 把每一步轉成 -1 或 +1 存起來，遇到 SAME AS 直接查表。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
