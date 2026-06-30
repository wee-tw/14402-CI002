# UVa 12347 - Binary Search Tree

題目連結：[UVa 12347 - Binary Search Tree](https://onlinejudge.org/external/123/12347.pdf)

## 題目總結

由 BST preorder 輸出 postorder。

## 關鍵技巧

- preorder 第一個是根，後續依小於/大於根分成左右子樹遞迴。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n^2) worst case
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
