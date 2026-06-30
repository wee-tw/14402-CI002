# UVa 10935 - Throwing cards away I

題目連結：[UVa 10935 - Throwing cards away I](https://onlinejudge.org/external/109/10935.pdf)

## 題目總結

模擬丟牌與移牌直到剩最後一張。

## 關鍵技巧

- queue 正好對應牌堆頂端操作，記錄被丟棄的順序。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
