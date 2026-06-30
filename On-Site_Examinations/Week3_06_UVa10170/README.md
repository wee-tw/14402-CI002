# UVa 10170 - The Hotel with Infinite Rooms

題目連結：[UVa 10170 - The Hotel with Infinite Rooms](https://onlinejudge.org/external/101/10170.pdf)

## 題目總結

從第 S 天開始累加住宿人數，找累計達到 D 的那一天。

## 關鍵技巧

- 依序累加 S, S+1, ...，第一次累計不少於 D 時輸出當天。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(answer-S)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
