# UVa 11292 - Dragon of Loowater

題目連結：[UVa 11292 - Dragon of Loowater](https://onlinejudge.org/external/112/11292.pdf)

## 題目總結

用最少花費找騎士砍掉所有龍頭。

## 關鍵技巧

- 龍頭與騎士排序，對每個最小龍頭配能處理它的最小騎士。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O((n+m) log(n+m))
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
