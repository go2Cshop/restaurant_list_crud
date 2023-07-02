# 我的餐廳清單
![Index page about Restaurant List](./清單crud.png){:h="50%" w="50%"}
## 介紹
紀錄屬於自己的餐廳清單, 可以瀏覽餐廳、查看詳細資訊、甚至連結到地圖

### 功能

- 查看所有餐廳
- 瀏覽餐廳的詳細資訊
- 連結連結餐廳的地址到Google地圖
- 清單可依照名稱或種類進行搜尋
- 使用者可以對餐廳資料進行新增、修改、刪除
## 開始使用

1. 請先確認有安裝node.js 與npm
2. 將專案clone到本地
3. 將本地開啟之，透過終端機進入資料夾，輸入：

   ```bash
   npm install
   ```
4.在/restaurant新增.env，並參考.env.example設定環境變數

5.新增種子資料，看到done表示新增完成

6. 安裝完畢後繼續輸入：
   ```bash
   npm run start
   ```
7. 若看見此行訊息則代表順利運行，打開瀏覽器進入到以下網址

   ```bash
   Listening on http://localhost:3000
   mongodb connected
   ```

8. 若欲暫停使用

   ```bash
   ctrl + c
   ```

## 開發工具

- Node.js 10.15.0
- Express 4.17.1
- Express-Handlebars 5.3.3
- Bootstrap 5.2.1
- Font-awesome 5.8.1
