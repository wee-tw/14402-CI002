# UVa 102 - Ecological Bin Packing

題目連結：[UVa 102 - Ecological Bin Packing](https://onlinejudge.org/external/1/102.pdf)

## 題目總結

決定三個箱子的瓶色配置，使搬動瓶數最少。

## 關鍵技巧

- 枚舉 6 種顏色排列，照題目要求以字典序處理平手。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(1)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
