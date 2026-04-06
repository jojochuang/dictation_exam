# 聽寫語詞考試

課堂聽寫語詞考試工具：載入語詞組、計時唸題、預覽／下載 PDF 考試單。

## 使用方式

### GitHub Pages

1. 在 repo 設定中啟用 **GitHub Pages**（Source: main branch）。
2. 開啟：**https://\<你的帳號\>.github.io/dictation_exam/**（主檔為 `index.html`）。教學入口見 [中文備課工具](https://jojochuang.github.io/)。

### 本機或檔案

1. 用瀏覽器開啟 `index.html`（建議用本地伺服器；純 `file://` 可能無法載入試算表 CSV）。
2. 從 Google 試算表載入語詞組，或點「載入本機 CSV」上傳 CSV。
3. 可切換模式：**編輯前次設定**／**考試中**／**對答案**／**全注音**。
4. 點計時圈開始倒數，每題會依設定秒數計時，並每 30 秒重複唸一次。
5. **定稿**可儲存顯示／隱藏設定；**預覽**與**下載 PDF** 會依目前模式產生考試單。

## 檔案說明

- `index.html`：主程式（單一 HTML，含樣式與腳本）
- `BpmfSpecial/`：注音字型（BpmfZihiOnly-R.ttf）
- `TW-Kai-98_1.woff2`：全字庫楷體（選用；亦可放在 `Fonts_Kai (1)/` 並搭配 `index.html` 內 `@font-face` 後備路徑）
- `ToneOZ-Tsuipita-TC/`：標音楷體（選用，見 `index.html` 內 `@font-face`）
- `ToneOZ-RadicalZ-KaiTraditional.ttf`：部首標音字型

## 授權與字型

字型請依各資料夾內之授權說明使用（BpmfSpecial、全字庫、ToneOZ 等）。
