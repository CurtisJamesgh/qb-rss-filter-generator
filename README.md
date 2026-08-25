# qBittorrent RSS 過濾產生器

純前端單檔，離線可用。為 qBittorrent RSS 下載器產生 `Must contain` / `Must not contain` 正則（QRegularExpression / PCRE2）。

## 開啟方式

直接用瀏覽器開啟 `index.html` 即可（雙擊）。

## 功能

- **大小**：`小於 N GB` 快捷鍵 `<1 <5 <10 <20 <50`，支援黑名單/白名單；**區間模式**（進階折疊）支援 `A — B GB` 含小數點後2位，嚴格精確匹配
- **關鍵字**：一列四格 `包含AND / 包含OR / 排除OR / 排除AND`，逗號或換行分隔，預設不分大小寫（輸出 `(?i)`）
- **輸出**：`Must contain` / `Must not contain` 各一條，勾選 `Use regular expression` 後貼上
- **即時測試**：預載 `Call Me By Fire [3.94 GB]` / `Shrouding the Heavens [784.54 MB]` 等，支援自訂標題
