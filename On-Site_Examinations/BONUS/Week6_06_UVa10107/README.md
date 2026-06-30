# UVa 10107 - What is the Median?

題目連結：[UVa 10107 - What is the Median?](https://onlinejudge.org/external/101/10107.pdf)

## 題目總結

動態輸入數字並輸出目前中位數。

## 關鍵技巧

- 維持排序陣列，插入時用 lower_bound 找位置。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n^2) total
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
