# UVa 11136 - Hoax or what

題目連結：[UVa 11136 - Hoax or what](https://onlinejudge.org/external/111/11136.pdf)

## 題目總結

每天移除最高與最低帳單並累計差額。

## 關鍵技巧

- multiset 支援重複值與快速取得最小/最大。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(total bills log total bills)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
