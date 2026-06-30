# UVa 10954 - Add All

題目連結：[UVa 10954 - Add All](https://onlinejudge.org/external/109/10954.pdf)

## 題目總結

每次合併兩個數的成本為其和，求最小總成本。

## 關鍵技巧

- Huffman greedy：每次取最小兩個合併。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
