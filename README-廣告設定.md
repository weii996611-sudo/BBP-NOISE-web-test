# BBPATROL 廣告功能版

## 廣告設定
開啟 `index.html`，搜尋 `AD_SETTINGS`。

### 彈窗廣告
- `enabled`: 是否啟用
- `image`: 圖片檔名或完整網址
- `link`: 點擊後開啟的網址
- `closeDelayMs`: 幾毫秒後出現關閉按鈕，5000 = 5 秒

### Footer 輪播廣告
在 `items` 內新增或刪除：
- `image`
- `link`
- `alt`

`intervalMs` 控制自動輪播速度。

圖片可直接用相同檔名覆蓋，也可在設定中改成其他檔名。
