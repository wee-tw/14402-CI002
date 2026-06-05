以下整理 UVA 1062 - Containers。

題目給一串貨櫃字母，例如：

ACMICPC

貨櫃要依序處理，每個貨櫃可以放到某一疊 stack 上。規則是：

新貨櫃 c 可以放到某疊上面，條件是該疊最上面的字母 top >= c。

也就是說，從上往下看，字母要越來越大或相等。

![alt text](image.png)