# UVa 732 - Anagrams by Stack

題目連結：[UVa 732 - Anagrams by Stack](https://onlinejudge.org/external/7/732.pdf)

## 題目總結

列出用 stack push/pop 把一字串變成另一字串的所有操作。

## 關鍵技巧

- DFS 嘗試 push 或在 stack top 符合目標時 pop，先確認兩字串是 anagram。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: exponential
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
