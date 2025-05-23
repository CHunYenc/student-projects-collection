# 學生專案整合倉庫（student-projects-collection）

本倉庫用於整合歷年學生課程作業與專案，方便管理、回顧與展示。

## 結構規劃

- `/java/`、`/python/`、`/web/` ...：各語言/課程分類資料夾，存放一般作業或練習題
- `/featured/`：特別專案，採用 submodule 管理，保留原 repo 歷史與獨立性

---

## Featured 專案

### [107-2_Java 視窗化程式課程期末專案](https://github.com/yen-study-chu/1072_JavaSwift)
1. 完成時期：大二下學期（107-2）
2. 專案特色：
   - 技術整合：結合資料庫、視窗介面與使用者認證，展現基本開發能力
   - 自主學習：學習並應用 Java Swing、JDBC 等課程外的技術
3. 技術亮點：
   - Java Swing 視窗開發與介面設計
   - MySQL 資料庫設計與 JDBC 連線操作
   - NetBeans IDE 專案管理與建置
4. 專案完整度：
   - 附有完整技術簡報
   - 詳細的 README 安裝與使用說明
   - 包含原始碼、資料庫腳本與相依套件

> 本專案為課堂期末作品，已封存，僅供學習紀錄與展示。

---

### [108-2_Android Studio APP 開發期末專案](https://github.com/yen-study-chu/1082_AndroidFinal)
1. 完成時期：大三下學期（108-2）
2. 專案特色：
   - 前後端分離：Android app 以 RESTful API 方式與 Flask/Python 後端溝通
   - 使用者認證：支援註冊、登入、個人資料管理
   - 健康/運動數據管理：可上傳、查詢個人健康與運動紀錄
   - 多畫面設計：包含登入、註冊、資料查詢、互動等多個 UI 頁面
   - 資料儲存：後端採用 MySQL，前端支援本地與遠端資料互動
3. 技術亮點：
   - Android Java 原生開發，熟悉 Activity、Intent、RecyclerView 等元件
   - 後端採用 Flask + SQLAlchemy，具備 API 設計與資料庫操作經驗
   - 前後端資料驗證與錯誤處理
4. 專案完整度：
   - 附有後端原始碼與執行說明
   - 完整的 app 畫面設計（多個 XML layout）
   - 詳細的 README 與安裝指引
   - 支援多平台（模擬器或實機執行）

> 本專案為課堂期末作品，已封存，僅供學習紀錄與展示。

---

### [DromNet_LineBot](https://github.com/yen-study-chu/DromNet_LineBot)
1. 完成時期：工讀專案
2. 專案特色：
   - 實用性：為中華大學宿網會開發的 LINE 機器人，提供住宿同學可以進行網路報修、帳號密碼查詢等等簡易功能
   - 整合性：結合 LINE Messaging API 與自動化服務功能
   - 持續運行：目前仍在線上服務中
3. 技術亮點：
   - Python Flask 後端開發
   - LINE Bot SDK 整合
   - 雲端部署與持續運行
4. 專案完整度：
   - 功能完整的 LINE 機器人
   - 可擴展架構設計
   - 實際應用於校園服務

> 本專案為課外實用工具，持續維護中。

---

### FunAR 擴增實境畢業專案
1. 完成時期：大四畢業專案（109-2）
2. 專案特色：
   - 跨平台整合：結合 Unity AR、Vue.js 網頁前端與 Flask 後端
   - 擴增實境：使用 Unity 開發 AR 互動功能
   - 完整系統：包含使用者管理、內容展示與 AR 互動體驗
3. 技術亮點：
   - Unity 開發手機 AR
   - Vue.js 網頁前端
   - Flask RESTful API 後端
   - 跨平台資料整合
4. 專案完整度：
   - 完整的系統架構設計
   - 前後端分離開發
   - Android APK 發布

> 本專案為畢業作品。

---

## 學習專案

### [1072_Python](https://github.com/yen-study-chu/1072_Python)

- 完成時期：大二下學期（107-2）、部分 109-1 報名線上學分的課程作業
- 內容：Python 語言程式設計課程作業與練習
- 主要內容：
  - 資料處理
  - 資料視覺化呈現
  - 加密貨幣價格通知

### [1081_R 課堂作業](https://github.com/yen-study-chu/1081_R)

- 完成時期：大三上學期（108-1）
- 內容：R 語言程式設計課程作業與練習
- 主要內容：資料分析、統計運算、視覺化呈現

### [1082_Android 課堂作業](https://github.com/yen-study-chu/1082_Android)

- 完成時期：大三下學期（108-2）
- 內容：Android 應用程式開發課程練習
- 主要內容：基礎 UI 設計、Activity 生命週期、簡易功能實作

> 這些專案為課堂學習記錄，展示學習過程與基礎技能掌握。

---

## 如何加入特別專案（submodule）

```bash
git submodule add https://github.com/CHunYenc/107-2_Java.git featured/107-2_Java
```

---

> 本倉庫由 AI 協助初始化與規劃，如有建議歡迎討論！
