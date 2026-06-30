# UVa 12049 - Just Prune The List

題目連結：[UVa 12049 - Just Prune The List](https://onlinejudge.org/external/120/12049.pdf)

## 題目總結

刪除兩個 list 中無法配對的元素數量。

## 關鍵技巧

- 用頻率差的絕對值總和代表需要刪掉的元素。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n+m) average
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
