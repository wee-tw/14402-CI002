這題是 queue 的進階版：不是單純排人，而是「同隊的人要排在一起」，所以會用一個總隊伍 queue 加上每個 team 自己的 queue。

每個人都屬於某一個 team，當一個人進隊伍時，如果他的隊友已經在隊伍中，他要排在該 team 的最後面；如果他的 team 目前沒人在隊伍中，這個 team 才排到整體隊伍最後。

![alt text](image.png)
MAP作用是查詢每個人屬於哪個TEAM

![alt text](image-2.png)

![alt text](image-3.png)