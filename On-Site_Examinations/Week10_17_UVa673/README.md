# UVa 673 - Parentheses Balance

題目連結：[UVa 673 - Parentheses Balance](https://onlinejudge.org/external/6/673.pdf)

## 題目總結

判斷括號字串是否平衡。

## 關鍵技巧

- 用 stack 配對 () 與 []；空字串也算平衡。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
