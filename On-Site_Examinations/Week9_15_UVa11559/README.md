# UVa 11559 - Event Planning

題目連結：[UVa 11559 - Event Planning](https://onlinejudge.org/external/115/11559.pdf)

## 題目總結

在預算和床位限制下找最低旅館費用。

## 關鍵技巧

- 每家旅館只要任一週床位足夠就可考慮，維護最低合法總價。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(h*w)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
