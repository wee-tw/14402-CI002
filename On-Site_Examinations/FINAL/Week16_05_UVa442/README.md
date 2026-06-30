# UVa 442 - Matrix Chain Multiplication

題目連結：[UVa 442 - Matrix Chain Multiplication](https://onlinejudge.org/external/4/442.pdf)

## 題目總結

計算矩陣鏈乘法括號式的乘法次數或判斷錯誤。

## 關鍵技巧

- 用 stack 保存括號與矩陣維度，遇到右括號就合併最近兩個矩陣。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(length)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
