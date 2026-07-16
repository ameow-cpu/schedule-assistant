# 排課小助手 / Schedule Assistant

前端單頁工具，幫忙規劃雙主修 / 輔系 / 跨學院的修課計畫。

## 用法

直接打開 `index.html` 就會跑（純前端、沒有 backend、資料存在瀏覽器 localStorage）。

如果想直接從 GitHub 試用，可以用 [GitHub Pages](https://ameow-cpu.github.io/schedule-assistant/) 開。

## 功能

- **課程 CRUD**：學期、學分、prerequisite、時段
- **多時段方案**：同一門課可以列多個時段方案
- **匯出 / 匯入**：JSON 備份整個資料
- **自動排課**：含 prerequisite 拓樸排序、衝突偵測
- **學分門檻**：雙主修 / 輔系統計
- **PDF 匯出**

## 版本

| 檔案 | 說明 |
|------|------|
| [`index.html`](./index.html) | 當前主版本（v2.8.7） |
| [`v2.8.6-warning-redesign.html`](./v2.8.6-warning-redesign.html) | v2.8.6：警示重構 |
| [`v2.6-original.html`](./v2.6-original.html) | 最初 2026-07-13 上傳的版本（基本 CRUD + 自動排課） |

## 授權

MIT — 詳見 [LICENSE](./LICENSE)
