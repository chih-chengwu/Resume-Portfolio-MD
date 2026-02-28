# E-commerce 線上購物平台

**專案時期**：2024年2月 – 6月（大四專題）  
**專題評分**：優等

---

## 📋 專案概述

此為大學校專題，開發一個完整的線上購物平台，模擬電商營運流程。系統提供會員管理、商品展示、購物車、訂單管理與支付等核心功能，結合現代 Web 技術與設計思想。

---

## 🛠 技術棧

| 分類 | 技術 |
|------|------|
| **後端框架** | Laravel 10 |
| **前端** | Blade 模板、Tailwind CSS |
| **資料庫** | MySQL |
| **API 設計** | RESTful API |
| **支付整合** | Stripe |
| **版本控制** | Git / GitHub |

---

## ✨ 主要功能

### 會員系統
- 使用者註冊、登入與身分驗證
- 會員資料管理
- 訂單歷史紀錄

### 商品管理
- 商品分類展示
- 商品詳細頁面
- 搜尋與篩選功能

### 購物與訂單
- 購物車新增/刪除/更新
- 訂單結帳流程
- 第三方支付（Stripe）整合

### 後端管理（可選）
- 商品上架/下架
- 訂單管理與追蹤
- 銷售統計

---

## 📊 系統架構

```
Laravel 10 應用
├── Routes（路由層）
├── Controllers（控制層）
├── Models（資料層）
├── Views（視圖層 - Blade 模板）
└── Middleware（驗證層）
      ↓
   MySQL 資料庫
```

---

## 🎯 核心成就

- ✅ 完整實現 MVC 架構，程式碼結構清晰易維護
- ✅ 成功整合 Stripe 第三方支付 API
- ✅ 資料庫設計符合正規化規範，查詢效能良好
- ✅ 前端採 Tailwind CSS 實現響應式設計
- ✅ 專題簡報獲系上競賽優等評價

---

## 💡 關鍵學習點

1. **Laravel 框架深度應用**：路由、中間件、模型關聯
2. **資料庫設計**：關聯式資料表設計、SQL 查詢優化
3. **API 設計**：RESTful 原則、JSON 序列化
4. **前端整合**：模板引擎、CSS 框架、表單驗證
5. **安全性**：CSRF 防護、輸入驗證、身分驗證

---

## 📁 專案結構

```
ecommerce/
├── app/
│   ├── Models/
│   ├── Controllers/
│   └── Http/
├── resources/
│   ├── views/
│   └── css/
├── routes/
├── database/
│   └── migrations/
└── public/
```

---

## 🚀 使用方式

### 環境需求
- PHP 8.x
- Laravel 10
- MySQL 5.7+
- Composer

### 安裝步驟
```bash
# 複製專案
git clone <repository-url>
cd ecommerce

# 安裝依賴
composer install

# 設定環境
cp .env.example .env
php artisan key:generate

# 資料庫遷移
php artisan migrate

# 啟動伺服器
php artisan serve
```

---

## 🔗 相關連結

- **GitHub 倉庫**：[連結待補](https://github.com/yourname/ecommerce)
- **線上展示**：[待部署]
- **相關文件**：主 Readme 中列有完整履歷

---

## 📝 備註

此為教學專題，功能仍有優化空間。如需完整功能或商轉部署，歡迎聯系討論。

