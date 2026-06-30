# UVa 10908 - Largest Square

題目連結：[UVa 10908 - Largest Square](https://onlinejudge.org/external/109/10908.pdf)

## 題目總結

對每個中心找同字元最大奇數邊長正方形。

## 關鍵技巧

- 從中心逐層擴張，邊界合法且整層字元相同才更新答案。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(q * max_radius^2)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
