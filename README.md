# Customer Tracker 系統

本系統是一套基於 Flask + Firebase 的顧客與專案追蹤管理平台，提供以下功能：

- 使用者登入與角色區分（顧客 / 業務 / 後台管理）
- 專案進度追蹤與時間紀錄
- 後台管理者可新增專案、編輯步驟、授權使用者
- 支援自訂步驟圖示上傳
- 使用 Firestore 儲存資料，支援多人授權與分權管理

## 📁 專案架構

```bash
.
├── app.py                  # 主程式（Flask 伺服器）
├── firebase_config.json    # Firebase 設定檔（已列入 .gitignore）
├── requirements.txt        # 套件清單
├── .gitignore              # 忽略項目
├── templates/              # HTML 模板（Flask Jinja2）
└── static/icons/           # 步驟圖示上傳資料夾
