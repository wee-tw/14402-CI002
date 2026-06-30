# UVa 10252 - Common Permutation

題目連結：[UVa 10252 - Common Permutation](https://onlinejudge.org/external/102/10252.pdf)

## 題目總結

輸出兩個字串共同擁有的字元，且按字元排序。

## 關鍵技巧

- 統計兩邊各字元次數，輸出每個字元的 min 次數。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n + charset)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
