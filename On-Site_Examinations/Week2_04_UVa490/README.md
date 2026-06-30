# UVa 490 - Rotating Sentences

題目連結：[UVa 490 - Rotating Sentences](https://onlinejudge.org/external/4/490.pdf)

## 題目總結

將多行文字順時針旋轉 90 度。

## 關鍵技巧

- 先記錄最長行，短行缺少的位置輸出空白，從最後一行往第一行掃。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(rows * max_width)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
