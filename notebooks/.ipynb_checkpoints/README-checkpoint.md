# MA 均線交叉策略回測 (2330.TW / 2317.TW)

本專案使用 Python 建立簡單的量化策略回測系統，測試 5 日與 20 日均線交叉於台灣股市之績效。

## 📊 策略說明
- 策略：5日上穿20日均線時買進，下穿時賣出
- 包含資金控管、停利/停損機制
- 使用 yfinance 擷取歷史資料

## 📁 專案內容
- `notebooks/`：策略分析與績效圖表
- `strategy/`：策略封裝模組
- `reports/`：結果輸出圖與報告

## ▶️ 快速執行
```bash
pip install -r requirements.txt
jupyter notebook
