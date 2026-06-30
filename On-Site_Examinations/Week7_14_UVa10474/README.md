# UVa 10474 - Where is the Marble?

題目連結：[UVa 10474 - Where is the Marble?](https://onlinejudge.org/external/104/10474.pdf)

## 題目總結

排序彈珠後回答查詢值第一次出現的位置。

## 關鍵技巧

- sort 後用 lower_bound 找第一個不小於查詢值的位置。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n log n + q log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
