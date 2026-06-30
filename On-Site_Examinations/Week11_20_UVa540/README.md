# UVa 540 - Team Queue

題目連結：[UVa 540 - Team Queue](https://onlinejudge.org/external/5/540.pdf)

## 題目總結

維護隊伍內成員相鄰的特殊排隊規則。

## 關鍵技巧

- 外層 queue 存目前有人的 team，內層 queue 存各 team 成員。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(commands)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
