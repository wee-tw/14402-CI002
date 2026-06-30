# UVa 11063 - B2-Sequence

題目連結：[UVa 11063 - B2-Sequence](https://onlinejudge.org/external/110/11063.pdf)

## 題目總結

判斷序列是否嚴格遞增且任兩元素和皆不同。

## 關鍵技巧

- 先檢查正整數遞增，再用 set 檢查所有 i<=j 的 pair sum 是否重複。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n^2 log n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
