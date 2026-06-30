# UVa 410 - Station Balance

題目連結：[UVa 410 - Station Balance](https://onlinejudge.org/external/4/410.pdf)

## 題目總結

把樣本分到 chamber 使 imbalance 最小。

## 關鍵技巧

- 補零到 2C 個後排序，最小和最大配對可平衡總重。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(C log C)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
