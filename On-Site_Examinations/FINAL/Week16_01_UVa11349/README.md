# UVa 11349 - Symmetric Matrix

題目連結：[UVa 11349 - Symmetric Matrix](https://onlinejudge.org/external/113/11349.pdf)

## 題目總結

判斷矩陣是否非負且中心對稱。

## 關鍵技巧

- 展平成一維陣列後比較 i 與 n*n-1-i，並檢查是否有負數。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n^2)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
