# UVa 11034 - Ferry Loading IV

題目連結：[UVa 11034 - Ferry Loading IV](https://onlinejudge.org/external/110/11034.pdf)

## 題目總結

計算渡輪運完所有車需要幾趟。

## 關鍵技巧

- 左右岸各一個 queue，每趟盡量裝目前岸邊可上的車後換岸。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(m)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
