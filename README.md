# 學生專案整合倉庫（student-projects-collection）

本倉庫用於整合歷年學生課程作業與專案，方便管理、回顧與展示。

## 結構規劃

- `/java/`、`/python/`、`/web/` ...：各語言/課程分類資料夾，存放一般作業或練習題
- `/featured/`：特別專案，採用 submodule 管理，保留原 repo 歷史與獨立性

## 如何加入特別專案（submodule）

```bash
git submodule add <repo-url> featured/<repo-name>
```

## 推薦整理流程

1. 將一般作業依主題分類放入對應資料夾
2. 重要/代表性專案以 submodule 方式加入 `featured/`
3. 每個子資料夾可放置 README 說明用途
4. 歡迎持續補充、優化

---

> 本倉庫由 AI 協助初始化與規劃，如有建議歡迎討論！
