# UVa 11461 - Square Numbers

題目連結：[UVa 11461 - Square Numbers](https://onlinejudge.org/external/114/11461.pdf)

## 題目總結

計算區間內完全平方數個數。

## 關鍵技巧

- 答案是 floor(sqrt(b)) - ceil(sqrt(a)) + 1。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(1)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
