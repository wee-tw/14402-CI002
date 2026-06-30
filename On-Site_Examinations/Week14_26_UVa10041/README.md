# UVa 10041 - Vito's Family

題目連結：[UVa 10041 - Vito's Family](https://onlinejudge.org/external/100/10041.pdf)

## 題目總結

選一個地址使到所有親戚家的距離總和最小。

## 關鍵技巧

- 一維絕對距離和的最佳點是中位數。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
