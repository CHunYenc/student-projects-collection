# 學生專案整合倉庫（student-projects-collection）

本倉庫用於整合歷年學生課程作業與專案，方便管理、回顧與展示。

## 結構規劃

- `/java/`、`/python/`、`/web/` ...：各語言/課程分類資料夾，存放一般作業或練習題
- `/featured/`：特別專案，採用 submodule 管理，保留原 repo 歷史與獨立性

---

## Featured 專案

### [107-2_Java](https://github.com/CHunYenc/107-2_Java)
- Java 入門第一堂課的期末專案：GUI（JFrame）+ MySQL 連線登入系統
- 結構完整，附有簡報與詳細 README
- 具備個人特色與展示價值

---

## 如何加入特別專案（submodule）

```bash
git submodule add https://github.com/CHunYenc/107-2_Java.git featured/107-2_Java
```

---

> 本倉庫由 AI 協助初始化與規劃，如有建議歡迎討論！
