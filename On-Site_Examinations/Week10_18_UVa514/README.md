# UVa 514 - Rails

題目連結：[UVa 514 - Rails](https://onlinejudge.org/external/5/514.pdf)

## 題目總結

判斷目標列車順序能否透過一個 station stack 產生。

## 關鍵技巧

- 依序把 1..n 推入 stack，能彈出目標車廂就持續彈。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n) per sequence
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
