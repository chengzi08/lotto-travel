# 妍妍子京都賭徒之旅 (Kyoto Gambler Tour)

這是一個簡易的 PWA 網頁應用程式，結合了柏青哥拉霸機與預算輪盤的趣味抽籤工具，幫助你決定京都旅行中的下一餐或下一個行程。

## 功能特色

- **拉霸機抽籤**：隨機決定吃什麼（燒肉、壽司、拉麵...等）。
- **預算輪盤**：中獎後轉動輪盤決定預算等級（高、中、低）。
- **自訂資料**：可自由輸入各類別的口袋名單與連結。
- **PWA 支援**：支援手機「加入主畫面」，可離線開啟。

## 如何部署到 GitHub Pages

將此專案發布到網路上，讓大家都能用手機開啟：

### 1. 建立 GitHub Repository

1. 登入 [GitHub](https://github.com/)。
2. 點選右上角 `+` -> `New repository`。
3. Repository name 輸入 `kyoto-gambler` (或你喜歡的名字)。
4. 勾選 `Public`。
5. 點選 `Create repository`。

### 2. 上傳程式碼

如果你已經安裝 Git，請在專案資料夾執行以下指令（請將 URL 換成你剛建立的網址）：

```bash
git init
git add .
git commit -m "Initial commit: 妍妍子京都賭徒之旅"
git branch -M main
git remote add origin https://github.com/你的帳號/kyoto-gambler.git
git push -u origin main
```

### 3. 開啟 GitHub Pages

1. 進入剛建立的 GitHub Repository 頁面。
2. 點選上方的 `Settings` 分頁。
3. 左側選單點選 `Pages`。
4. 在 **Build and deployment** 下的 **Branch** 選擇 `main`，資料夾選 `/(root)`。
5. 按下 `Save`。
6. 等待約 1-2 分鐘，上方會出現你的專案網址（例如：`https://你的帳號.github.io/kyoto-gambler/index.html`）。

### 4. 手機安裝

1. 用手機瀏覽器開啟該網址。
2. iPhone (Safari): 按下分享按鈕 -> 「加入主畫面」。
3. Android (Chrome): 按下選單 -> 「加到主畫面」或「安裝應用程式」。
