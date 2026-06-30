# UVa 10282 - Babelfish

題目連結：[UVa 10282 - Babelfish](https://onlinejudge.org/external/102/10282.pdf)

## 題目總結

用字典把外語單字翻成英文。

## 關鍵技巧

- 先讀到空行建立 foreign->english map，查不到輸出 eh。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(1) average per query
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
