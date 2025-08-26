# 圖書館預約系統 (Time Library System)

<img width="1915" height="861" alt="image" src="https://github.com/user-attachments/assets/9190796d-c2f8-4004-944a-4832ee007aef" />

##  專案簡介
一個現代化的圖書館管理系統，提供書籍預約、座位預約、會員管理等功能。

##  主要功能
🔐 會員管理

支援註冊、登入、JWT 驗證

權限區分一般會員與管理員

📚 圖書管理與查詢

書籍列表、分類查詢、詳細資料瀏覽

使用 Elasticsearch 實現快速模糊搜尋與全文檢索

📖 借閱系統

借書、還書功能

借閱紀錄查詢與逾期提醒

🪑 座位預約系統

使用者可預約圖書館座位

支援即時查詢座位狀況與取消預約

💬 書籍評論與評分

使用者可對書籍留言、評論與評分

協助其他讀者參考選書

🛠️ 管理員後台

書籍 CRUD 操作（新增、修改、刪除）

使用者與借閱紀錄管理

座位與評論審核功能

🌐 郵遞區號資料匯入

使用 Python 腳本匯入政府開放郵遞區號資料

提供地址欄位自動填寫輔助功能

🚀 容器化部署

使用 Docker 快速啟動前端、後端與資料庫服務

可輕鬆部署至本機或雲端伺服器

##  技術架構

本系統採用 前後端分離 + 混合式資料處理架構，整體設計模組化，利於擴充與維護，並結合全文搜尋、資料前處理與容器化部署。 架構可分為以下層級：

前端：Nuxt3 + Vue3（單頁式應用 SPA）

後端：Spring Boot + RESTful API（Java 17, Maven 3.9.9）

資料前處理：Python 腳本（清洗與轉換後同步至資料庫與搜尋引擎）

資料庫：

MySQL（儲存結構化資料）

Elasticsearch（支援全文搜尋）

部署：Docker（前後端與資料庫容器化）

通訊格式：JSON（前後端透過 API 傳輸資料）

版本控管：Git / GitHub

##  快速開始

### 後端啟動
```bash
cd TimeLibrary-backend
mvn spring-boot:run
```

### 前端啟動
```bash
cd TimeLibrary-frontend
pnpm install
pnpm dev
```

### Docker 啟動
```bash
cd TimeLibrary-backend
docker-compose up -d
```
