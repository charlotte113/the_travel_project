# 旅遊平台專案介紹
專案名稱: 締杉旅遊

專案簡介: 此專案是一個專門為旅行者設計的平台，在小組裡，我負責的項目是行程及購物車的版面和內容設計，透過按照主題、關鍵字搜索及篩選功能，讓用戶能精準找到符合需求的旅遊行程後，結算並接入付款頁面完成訂購。
採用 RWD 切版技術，確保用戶在各種裝置上均能享有流暢且友好的瀏覽體驗。  

前端技術棧:  
React 函式庫 Next.js 框架  
  
後端技術棧:  
Express 框架  

第三方支付: 綠界科技ECPAY  

## 導入模組
需確認已安裝 Node.js 和 XAMPP ,然後在 XAMPP 控制面板中，開啟 Apache 和 MySQL 。 

在開始使用這個專案之前，你需要先安裝必要的依賴。請在 next 和 express 的資料夾路徑下各自執行以下命令：  

在終端機輸入 npm i 

## 資料庫建置
在 phpMyAdmin 新增權限帳號  
1. 使用者名稱：the_travel_project
2. 主機名稱：localhost
3. 密碼: 無

在 phpMyAdmin 建立名字為 the_travel_project 的資料庫，然後匯入 the_travel_project (1).sql 檔案

## 開始使用
在前後端各自終端機輸入 npm run dev

## 網址
http://localhost:3000  

## 備註 
旅遊平台會員登入  
帳號: group3@gmail.com 
密碼: 123456  

綠界科技的使用:  
根據以下圖片內容去填寫支付資訊
![綠界科技支付資訊](./next/public/pics/綠界科技.png)
