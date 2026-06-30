# UVa 10420 - List of Conquests

題目連結：[UVa 10420 - List of Conquests](https://onlinejudge.org/external/104/10420.pdf)

## 題目總結

統計每個國家出現次數並按國名排序。

## 關鍵技巧

- 每行第一個 token 是國名，map 自然提供字典序輸出。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
