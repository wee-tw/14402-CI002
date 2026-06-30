# UVa 10035 - Primary Arithmetic

題目連結：[UVa 10035 - Primary Arithmetic](https://onlinejudge.org/external/100/10035.pdf)

## 題目總結

計算兩個十進位整數相加時產生幾次進位。

## 關鍵技巧

- 從個位數往高位逐位相加，上一位的 carry 會影響下一位。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(digits)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
