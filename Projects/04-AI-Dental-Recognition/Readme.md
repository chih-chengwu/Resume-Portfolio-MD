# AI 牙齒 X 光影像辨識系統

**專案時期**：校內專題  
**專題評分**：佳作  
**核心技術**：機器學習、深度學習、影像處理

---

## 📋 專案概述

此為大學校內專題專案，開發一套利用 AI 技術自動辨識牙齒 X 光影像中的病灶區域。專案涵蓋資料前處理、特徵擷取、機器學習模型訓練與評估，旨在輔助牙醫診斷工作，提升診療效率。

---

## 🛠 技術棧

| 分類 | 技術 |
|------|------|
| **程式語言** | Python 3.8+ |
| **深度學習框架** | TensorFlow / Keras |
| **影像處理** | OpenCV、PIL、NumPy |
| **資料分析** | Pandas、Scikit-learn |
| **模型架構** | CNN（卷積神經網路）|
| **評估指標** | Precision、Recall、F1-Score、IoU |
| **開發工具** | Jupyter Notebook、Google Colab |

---

## ✨ 主要功能

### 資料準備
- X 光影像讀取與解析
- 影像正規化與標準化
- 資料增強（Data Augmentation）
- 訓練/驗證/測試集分割

### 特徵擷取
- 邊緣偵測
- 紋理分析
- 直方圖均等化
- 灰度轉換

### 模型訓練
- CNN 模型架構設計
- 超參數調整
- 過擬合防控
- 交叉驗證

### 預測與評估
- 影像分類預測
- 病灶區域定位
- 模型效能評估
- 混淆矩陣分析

---

## 📊 系統流程

```
數據集
  ↓
[資料前處理]
  ├── 影像讀取
  ├── 正規化
  └── 資料增強
  ↓
[特徵擷取]
  ├── OpenCV 處理
  └── 特徵向量生成
  ↓
[模型訓練]
  ├── CNN 架構
  ├── 梯度下降優化
  └── 交叉驗證
  ↓
[模型評估]
  ├── 準確度
  ├── 召回率
  └── F1-Score
  ↓
[預測輸出]
  └── 病灶辨識結果
```

---

## 🎯 核心成就

- ✅ 成功建立 CNN 模型，達到 **XX% 準確度**
- ✅ 完成 300+ 張牙齒 X 光影像標註與分類
- ✅ 實現影像預處理管線，提升模型效能
- ✅ 撰寫詳細的模型評估報告
- ✅ 專題獲系上競賽 **佳作** 評價

---

## 💡 關鍵學習點

1. **deep Learning 基礎**：CNN 架構、反向傳播、梯度下降
2. **影像處理**：濾波、邊緣偵測、特徵提取
3. **資料工程**：資料清理、正規化、增強策略
4. **模型評估**：混淆矩陣、ROC 曲線、精確率-召回率
5. **醫療 AI**：醫療影像分析的特殊考量、倫理問題

---

## 📁 專案結構

```
dental-recognition/
├── data/
│   ├── raw/（原始影像）
│   ├── processed/（處理後影像）
│   └── dataset.csv（標籤檔案）
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_evaluation.ipynb
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   ├── train.py
│   └── evaluate.py
├── results/
│   ├── model_weights.h5
│   ├── confusion_matrix.png
│   └── report.pdf
└── README.md
```

---

## 📈 效能指標

| 指標 | 數值 |
|------|------|
| 訓練集準確度 | XX% |
| 驗證集準確度 | XX% |
| 測試集準確度 | XX% |
| 精確率 (Precision) | XX% |
| 召回率 (Recall) | XX% |
| F1-Score | XX% |

---

## 🚀 使用方式

### 環境需求
- Python 3.8+
- TensorFlow 2.x
- OpenCV
- Jupyter Notebook（選擇性）

### 安裝步驟
```bash
# 複製專案
git clone <repository-url>
cd dental-recognition

# 建立虛擬環境
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 安裝依賴
pip install -r requirements.txt

# 執行 Jupyter Notebook
jupyter notebook notebooks/
```

### 訓練模型
```bash
# 執行訓練腳本
python src/train.py --epochs 100 --batch_size 32

# 評估模型
python src/evaluate.py --model_path results/model_weights.h5
```

---

## 📊 資料集說明

- **來源**：醫療機構提供的牙齒 X 光影像
- **數量**：300+ 張影像
- **分類**：正常 / 病灶（可進一步細分）
- **解析度**：原始影像經正規化至 256×256 像素
- **格式**：PNG / JPG

---

## 🔗 相關連結

- **GitHub 倉庫**：[連結待補](https://github.com/yourname/dental-recognition)
- **Colab 筆記本**：[待補充]
- **論文/報告**：[待補充]
- **相關文件**：主 Readme 中有完整履歷

---

## 🧠 未來改進方向

- 擴大訓練資料集規模
- 嘗試遷移學習（Transfer Learning）
- 實現即時預測 API
- 集成醫療系統介面
- 模型可解釋性分析 (XAI)

---

## 📝 備註

此專案展示了對機器學習與醫療 AI 的理解與實踐能力。如有進一步討論或合作機會，歡迎聯系。

