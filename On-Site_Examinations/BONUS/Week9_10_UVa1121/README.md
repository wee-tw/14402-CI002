# UVa 1121 - Subsequence

題目連結：[UVa 1121 - Subsequence](https://onlinejudge.org/external/11/1121.pdf)

## 題目總結

找總和至少 S 的最短連續子陣列。

## 關鍵技巧

- 數列為正數，可用 sliding window 收縮左界。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
