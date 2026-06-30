# UVa 679 - Dropping Balls

題目連結：[UVa 679 - Dropping Balls](https://onlinejudge.org/external/6/679.pdf)

## 題目總結

模擬第 I 顆球在完全二元樹中落到哪個葉節點。

## 關鍵技巧

- 不必真的更新整棵樹；依 I 的奇偶決定往左或右並壓縮球序。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(depth)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
