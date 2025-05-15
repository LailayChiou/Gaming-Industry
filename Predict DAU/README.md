# 📊 Predict DAU in Gaming Industry

本專案以實際遊戲公司數據為基礎，預測每日活躍設備數（DAU），作為預算規劃與成長策略的依據。

## 🧠 方法概覽

- 分析各同期群留存率並以冪次模型配適 $y = ax^b$
- 考慮同比率遞減（如 0.997、0.995 等）與臨界天數修正
- 預測 DOU（Daily Old Users）與 RNU（Retained New Users）
- 組合為每日 DAU 預估值

## 📌 專案亮點

- 使用真實留存數據與模型結合推估未來用戶動態
- 保留期別對應的模型參數 (a, b, rate, limit) 與自動分類邏輯
- 結合每日新增設備預估、活動效益與假日效果
- 含圖文解釋與推導公式，清晰易懂

## 🔍 技術使用

- Python（Pandas, NumPy, Matplotlib）
- Jupyter Notebook 說明與公式推導
- 專案結構清晰，便於維護與擴展


