# 部落格系統

**開發類型**：個人自主專案  
**累積成果**：部署運行、500+ 次閱讀

---

## 📋 專案概述

此為自學完成的個人部落格系統，採純 PHP + MVC 架構開發，無依賴外部框架。系統提供文章發布、留言互動、搜尋功能與基礎 SEO 優化，展示原生 PHP 開發能力與系統設計思想。

---

## 🛠 技術棧

| 分類 | 技術 |
|------|------|
| **後端語言** | 純 PHP（無框架）|
| **架構模式** | MVC（Model-View-Controller）|
| **資料庫** | MySQL |
| **前端** | HTML5、CSS3、JavaScript |
| **部署** | LAMP 環境（Linux + Apache + MySQL + PHP）|
| **版本控制** | Git / GitHub |

---

## ✨ 主要功能

### 文章管理
- 文章 CRUD（新增、檢視、更新、刪除）
- 文章分類與標籤
- 發布日期與編輯時間紀錄

### 留言系統
- 支援訪客留言
- 留言審核機制
- 留言數計數

### 搜尋與導航
- 全文搜尋功能
- 分類檢索
- 標籤雲展示

### SEO 優化
- 自訂網頁 title 與 meta description
- 友善的 URL 結構
- Sitemap 自動生成

---

## 📊 系統架構

```
MVC 架構
├── Model（模型層）
│   ├── Article（文章模型）
│   └── Comment（留言模型）
├── View（視圖層）
│   ├── article_list.php
│   ├── article_detail.php
│   └── admin_panel.php
└── Controller（控制層）
    ├── ArticleController
    └── CommentController
      ↓
   資料庫（MySQL）
```

---

## 🎯 核心成就

- ✅ 從零開始實現完整的 MVC 模式，無框架依賴
- ✅ 自主設計資料庫表結構與關聯
- ✅ 實現功能完整的留言系統
- ✅ 已部署至網路環境，累積 500+ 次閱讀
- ✅ 通過 SEO 優化提升搜尋引擎收錄

---

## 💡 關鍵學習點

1. **原生 PHP**：物件導向設計、PDO 資料庫操作
2. **MVC 架構**：職責分離、代碼重用性
3. **資料庫設計**：正規化、索引優化、查詢效率
4. **前端開發**：表單驗證、非同步請求 (AJAX)
5. **伺服器部署**：LAMP 棧配置、檔案權限管理

---

## 📁 專案結構

```
blog/
├── app/
│   ├── models/
│   │   ├── Article.php
│   │   └── Comment.php
│   └── controllers/
│       ├── ArticleController.php
│       └── CommentController.php
├── views/
│   ├── articles/
│   ├── comments/
│   └── layouts/
├── public/
│   ├── css/
│   ├── js/
│   └── uploads/
├── config/
│   └── database.php
└── index.php（路由入口）
```

---

## 🚀 使用方式

### 環境需求
- PHP 7.4+
- MySQL 5.7+
- Apache（支援 .htaccess）
- 現代瀏覽器

### 安裝步驟
```bash
# 複製專案至網頁根目錄
cp -r blog /var/www/html/

# 建立資料庫
mysql -u root -p < database.sql

# 設定設定檔（如有）
# cp config/database.example.php config/database.php
# 編輯連線資訊

# 存取應用
# 開啟瀏覽器進入 http://localhost/blog
```

---

## 🔗 相關連結

- **GitHub 倉庫**：[連結待補](https://github.com/yourname/blog-system)
- **線上版本**：[待補充]
- **文件**：主 Readme 中有完整履歷

---

## 📈 效能指標

- **頁面載入時間**：< 500ms
- **資料庫查詢**：經索引優化，平均 < 100ms
- **閱讀人次**：500+

---

## 📝 備註

這個專案展示了對 PHP 原生開發與系統設計的理解。如有興趣深化或商轉需求，歡迎聯系討論。

