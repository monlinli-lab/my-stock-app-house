# 台房智選 PRO03

這是一個以 **Streamlit** 製作的台灣房地產試算與模擬推薦工具，可直接部署到 **Streamlit Cloud**，也可在本機執行。

## 專案內容

- `台房智選PRO03_app.py`：主程式
- `台房智選PRO03_requirements.txt`：Python 套件需求
- `.streamlit/config.toml`：Streamlit 介面設定
- `.gitignore`：Git 忽略設定

## 本機執行方式

1. 安裝套件

```bash
pip install -r 台房智選PRO03_requirements.txt
```

2. 啟動程式

```bash
streamlit run 台房智選PRO03_app.py
```

## 部署到 Streamlit Cloud

1. 將整個專案上傳到 GitHub Repository
2. 前往 Streamlit Cloud
3. 選擇你的 GitHub Repository
4. Main file path 請填入：

```text
台房智選PRO03_app.py
```

5. 部署即可

## 功能說明

- 全台主要縣市與行政區選擇
- 每月可負擔房貸、自備款、貸款年限、利率試算
- 五項優勢加權
- 五項嫌惡設施扣分
- 模擬成交 / 下架案源過濾
- 房源推薦卡片展示
- 深色科技風介面

## 注意事項

本專案中的房價、房源、嫌惡設施與推薦結果屬於展示用途的模擬資料，不代表真實市場資訊。
