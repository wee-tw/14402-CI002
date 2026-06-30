# UVa 11450 - Wedding Shopping

題目連結：[UVa 11450 - Wedding Shopping](https://onlinejudge.org/external/114/11450.pdf)

## 題目總結

在預算內每類衣服各買一件並最大化花費。

## 關鍵技巧

- DP 記錄每一類處理後可達到的花費。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(C*M*K)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
