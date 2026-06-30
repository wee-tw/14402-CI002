# UVa 11321 - Sort! Sort!! and Sort!!!

題目連結：[UVa 11321 - Sort! Sort!! and Sort!!!](https://onlinejudge.org/external/113/11321.pdf)

## 題目總結

依題目指定的 mod、奇偶、大小規則排序。

## 關鍵技巧

- 比較器照規則實作：mod 小者先，奇數先，奇數大到小，偶數小到大。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
