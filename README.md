# 圖書館預約系統 (Time Library System)

<img width="1915" height="861" alt="image" src="https://github.com/user-attachments/assets/9190796d-c2f8-4004-944a-4832ee007aef" />

一個現代化的圖書館管理系統，提供書籍預約、座位預約、會員管理等功能。

## 🚀 主要功能

### 📚 書籍管理
- **書籍搜尋與瀏覽** - 支援多種搜尋條件和篩選
- **書籍預約系統** - 線上預約書籍，自動通知功能
- **書籍推薦系統** - 基於用戶行為的智慧推薦
- **書籍資訊管理** - 詳細的書籍資訊和狀態追蹤

### 🪑 座位預約
- **座位地圖** - 視覺化座位選擇介面
- **時段預約** - 靈活的時間段選擇
- **預約管理** - 查看、修改、取消預約
- **即時狀態更新** - 座位使用狀態即時顯示

### 👥 會員系統
- **用戶註冊/登入** - 安全的身份驗證
- **個人資料管理** - 會員資訊維護
- **借閱記錄** - 完整的借閱歷史
- **違規管理** - 違規記錄和處理

### 📢 資訊服務
- **最新消息** - 圖書館公告和活動
- **意見回饋** - 用戶意見收集系統
- **排行榜系統** - 熱門書籍和借閱排行
- **活動管理** - 圖書館活動資訊

### 🛠️ 管理功能
- **帳戶管理** - 管理員權限控制
- **書籍管理** - 書籍資料維護
- **座位管理** - 座位配置和維護
- **違規處理** - 違規記錄管理

## 🛠️ 技術架構

### 後端 (Backend)
- **Java 17** - 主要開發語言
- **Spring Boot 3.4.5** - 應用框架
- **Spring Data JPA** - 資料持久化
- **MySQL 8.0** - 主要資料庫
- **Elasticsearch** - 搜尋引擎
- **Lombok** - 程式碼簡化
- **OpenAPI 3** - API 文件
- **Kaptcha** - 驗證碼生成
- **Spring Mail** - 郵件通知服務

### 前端 (Frontend)
- **Nuxt.js 3** - Vue.js 全端框架
- **Vue 3** - 前端框架
- **TypeScript** - 型別安全
- **Tailwind CSS** - 樣式框架
- **Radix Vue** - UI 組件庫
- **Leaflet** - 地圖功能
- **Axios** - HTTP 客戶端
- **Vue Router 4** - 路由管理

### 開發工具
- **Maven** - Java 專案管理
- **pnpm** - Node.js 套件管理
- **Docker** - 容器化部署
- **Git** - 版本控制

## 📁 專案結構

```
Time-Library-System/
├── TimeLibrary-backend/          # 後端 Java 專案
│   ├── src/main/java/           # Java 原始碼
│   ├── src/main/resources/      # 配置檔案
│   ├── pom.xml                  # Maven 配置
│   └── docker-compose.yml       # Docker 配置
├── TimeLibrary-frontend/         # 前端 Nuxt.js 專案
│   ├── pages/                   # 頁面組件
│   ├── components/              # Vue 組件
│   ├── composables/             # 組合式函數
│   ├── nuxt.config.ts          # Nuxt 配置
│   └── package.json            # 套件配置
└── README.md                    # 專案說明文件
```

## 🚀 快速開始

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

## 🔧 環境需求

- **Java 17+**
- **Node.js 18+**
- **MySQL 8.0+**
- **Elasticsearch 7+**
- **Maven 3.6+**
- **pnpm 8+**

## 📧 功能特色

- **響應式設計** - 支援各種裝置尺寸
- **多語言支援** - 繁體中文介面
- **即時通知** - 郵件和系統通知
- **安全認證** - 驗證碼和權限控制
- **資料備份** - 自動資料備份機制
- **API 文件** - 完整的 API 說明

