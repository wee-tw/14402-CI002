# UVa 10008 - What's Cryptanalysis?

題目連結：[UVa 10008 - What's Cryptanalysis?](https://onlinejudge.org/external/100/10008.pdf)

## 題目總結

統計文章中各英文字母出現次數。

## 關鍵技巧

- 大小寫視為同一字母，排序依次數遞減、字母遞增。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n + 26 log 26)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
