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

## 如何加入特別專案（submodule）

```bash
git submodule add https://github.com/CHunYenc/107-2_Java.git featured/107-2_Java
```

---

> 本倉庫由 AI 協助初始化與規劃，如有建議歡迎討論！
