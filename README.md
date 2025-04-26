# 學生專案整合倉庫（student-projects-collection）

本倉庫用於整合歷年學生課程作業與專案，方便管理、回顧與展示。

## 結構規劃

- `/java/`、`/python/`、`/web/` ...：各語言/課程分類資料夾，存放一般作業或練習題
- `/featured/`：特別專案，採用 submodule 管理，保留原 repo 歷史與獨立性

---

## Featured 專案

### [107-2_Java 視窗化程式課程期末專案](https://github.com/CHunYenc/107-2_Java)
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

---

## 如何加入特別專案（submodule）

```bash
git submodule add https://github.com/CHunYenc/107-2_Java.git featured/107-2_Java
```

---

> 本倉庫由 AI 協助初始化與規劃，如有建議歡迎討論！
