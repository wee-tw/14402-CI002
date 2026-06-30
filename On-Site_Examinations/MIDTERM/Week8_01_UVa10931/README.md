# UVa 10931 - Parity

題目連結：[UVa 10931 - Parity](https://onlinejudge.org/external/109/10931.pdf)

## 題目總結

輸出整數的二進位表示與 1 的個數。

## 關鍵技巧

- 反覆除以 2 建出 bit 字串，同時累計 parity。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
