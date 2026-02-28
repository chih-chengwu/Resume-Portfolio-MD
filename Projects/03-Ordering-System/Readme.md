# 線上訂餐系統

**開發類型**：個人自主專案  
**技術特色**：PHP + LAMP 環境  
**評價**：獲老師高度評價

---

## 📋 專案概述

此為自學開發的線上訂餐平台，採 PHP 實現，提供完整的訂餐流程。系統涵蓋會員管理、菜單展示、購物車、訂單處理與付款流程，部署於 LAMP 環境運行穩定。

---

## 🛠 技術棧

| 分類 | 技術 |
|------|------|
| **後端語言** | PHP 7.x / 8.x |
| **架構模式** | MVC |
| **資料庫** | MySQL |
| **前端** | HTML5、CSS3、JavaScript |
| **部署環境** | LAMP（Linux + Apache + MySQL + PHP）|
| **版本控制** | Git / GitHub |

---

## ✨ 主要功能

### 會員系統
- 使用者註冊與登入
- 會員帳戶管理
- 訂餐歷史紀錄
- 個人偏好設定

### 菜單管理
- 菜單分類展示
- 商品詳細說明
- 圖片上傳與展示
- 價格與庫存管理

### 購物流程
- 購物車操作（新增、移除、修改數量）
- 結帳頁面
- 配送地址管理
- 訂單確認

### 付款系統
- 線上支付流程
- 付款狀態追蹤
- 訂單號生成與管理

### 後台管理（可選）
- 菜單上架/下架
- 訂單管理與狀態更新
- 銷售統計

---

## 📊 系統架構

```
PHP 應用
├── 控制層（Controllers）
│   ├── OrderController
│   ├── MenuController
│   └── UserController
├── 資料層（Models）
│   ├── Order
│   ├── Menu
│   └── User
├── 視圖層（Views）
│   ├── menu.php
│   ├── cart.php
│   └── order.php
└── 輔助層
    ├── Database（MySQL 連線）
    ├── PaymentGateway（支付整合）
    └── Validation（表單驗證）
```

---

## 🎯 核心成就

- ✅ 完整實現訂餐業務流程，從瀏覽→購物→支付
- ✅ 菜單管理模組靈活易用
- ✅ 支付流程安全可靠
- ✅ 系統穩定運行，獲老師認可
- ✅ 資料庫結構清晰，查詢高效

---

## 💡 關鍵學習點

1. **業務流程設計**：訂餐系統的完整工作流
2. **狀態管理**：訂單各階段狀態轉移
3. **支付整合**：第三方支付 API 對接
4. **庫存控制**：菜單數量動態管理
5. **用戶體驗**：購物流程最適化

---

## 📁 專案結構

```
ordering-system/
├── app/
│   ├── models/
│   │   ├── Order.php
│   │   ├── Menu.php
│   │   └── User.php
│   └── controllers/
│       ├── OrderController.php
│       ├── MenuController.php
│       └── UserController.php
├── views/
│   ├── menu/
│   ├── cart/
│   ├── order/
│   └── layouts/
├── public/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── uploads/
├── config/
│   └── database.php
├── database/
│   └── schema.sql
└── index.php（入口）
```

---

## 🚀 使用方式

### 環境需求
- PHP 7.4+
- MySQL 5.7+
- Apache（支援 mod_rewrite）
- Linux 伺服器（推薦 Ubuntu 20.04）

### 安裝步驟
```bash
# 複製專案
git clone <repository-url>
cd ordering-system

# 建立資料庫
mysql -u root -p < database/schema.sql

# 設定連線資訊
cp config/database.example.php config/database.php
# 編輯 database.php，填入 MySQL 登入資訊

# 設定檔案權限
chmod -R 755 public/
chmod -R 775 public/uploads/

# 啟動 Apache（如未啟動）
sudo systemctl start apache2

# 存取應用
# 開啟瀏覽器進入 http://your-domain/ordering-system
```

---

## 🔗 相關連結

- **GitHub 倉庫**：[連結待補](https://github.com/yourname/ordering-system)
- **線上展示**：[待部署]
- **相關文件**：主 Readme 中有完整履歷

---

## 📝 備註

此專案展示了實務訂餐系統開發能力。如有改進需求或商轉機會，歡迎聯系討論。

