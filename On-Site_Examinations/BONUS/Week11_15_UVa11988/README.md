# UVa 11988 - Broken Keyboard

題目連結：[UVa 11988 - Broken Keyboard](https://onlinejudge.org/external/119/11988.pdf)

## 題目總結

處理 Home/End 鍵造成的文字插入位置切換。

## 關鍵技巧

- 用 list 與 iterator 模擬游標，遇到 [ 移到 begin，遇到 ] 移到 end。
- 注意 UVa 的輸入通常是多筆測資，輸出格式要完全符合題目要求。

## 解法概念

依題目限制選擇直接模擬、排序、貪心、二分、stack/queue 或 DP。實作時先把資料轉成容易維護的狀態，再依題目規則逐步更新答案。

## 複雜度

- Time: O(n)
- Space: 依資料結構需求，通常為 O(n) 或 O(1)。
