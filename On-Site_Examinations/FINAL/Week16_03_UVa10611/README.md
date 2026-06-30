# UVa 10611 - The Playboy Chimp

題目連結：[UVa 10611 - The Playboy Chimp](https://onlinejudge.org/external/106/10611.pdf)

## 題目總結

對每個身高查詢較矮最高與較高最低者。

## 關鍵技巧

- 排序資料上使用 lower_bound 與 upper_bound。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(q log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
