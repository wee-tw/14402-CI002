# UVa 501 - Black Box

題目連結：[UVa 501 - Black Box](https://onlinejudge.org/external/5/501.pdf)

## 題目總結

依查詢順序輸出目前第 k 小元素。

## 關鍵技巧

- 用兩個 multiset 維護前 k 小與其餘元素，調整後 low 的最大值就是答案。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O((m+n) log m)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
