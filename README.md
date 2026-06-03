# GitHub Pages 上傳說明

這是一個可直接放到 GitHub Pages 的靜態甜點頁，版型沿用原本母版網站。

## 檔案

- `index.html`：主網頁
- `assets/portrait.jpg`：首屏形象照

## 需要替換的地方

打開 `index.html`，搜尋以下文字：

- `#live`：替換成直播網址
- `#youtube`：替換成 YouTube / Shorts 網址
- `TikTok`、`Instagram`、`LINE`、`領取表單` 附近的 `href="#"`：替換成正式導流網址

## 更換影片

在 `index.html` 找到：

```html
<source src="https://ik.imagekit.io/wmb06guhs/MTVideo%20(1).mp4/ik-video.mp4?updatedAt=1779855409297" type="video/mp4">
```

把 `src` 換成你的正式影片網址。

影片區已移到 03 鎖頭區塊下方、直播資訊區塊上方。
