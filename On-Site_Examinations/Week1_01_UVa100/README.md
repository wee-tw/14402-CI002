# UVa 100 - The 3n + 1 Problem

題目連結：[UVa 100 - The 3n + 1 Problem](https://onlinejudge.org/external/1/100.pdf)

## 題目總結

I/O 與 Collatz 序列模擬。

## 關鍵技巧

- 保留原輸入順序輸出，區間計算時先轉成小到大；序列過程用 long long 避免中間值溢位。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(|a-b| log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
