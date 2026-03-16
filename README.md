# 聽寫語詞考試

課堂聽寫語詞考試工具：載入語詞組、計時唸題、預覽／下載 PDF 考試單。

## 使用方式

1. 用瀏覽器開啟 `dictation_exam.html`（建議用本地伺服器或 `file://` 開啟以正確載入字型）。
2. 從 Google 試算表載入語詞組，或點「載入本機 CSV」上傳 CSV。
3. 可切換模式：**編輯前次設定**／**考試中**／**對答案**／**全注音**。
4. 點計時圈開始倒數，每題會依設定秒數計時，並每 30 秒重複唸一次。
5. **定稿**可儲存顯示／隱藏設定；**預覽**與**下載 PDF** 會依目前模式產生考試單。

## 檔案說明

- `dictation_exam.html`：主程式（單一 HTML，含樣式與腳本）
- `BpmfSpecial/`：注音字型（BpmfZihiOnly-R.ttf）
- `Fonts_Kai (1)/`：楷體字型（TW-Kai-98_1.ttf）
- `ToneOZ-Tsuipita-TC/`：標音楷體（ToneOZ-Tsuipita-TC.ttf）
- `ToneOZ-RadicalZ-KaiTraditional.ttf`：部首標音字型

## 授權與字型

字型請依各資料夾內之授權說明使用（BpmfSpecial、全字庫、ToneOZ 等）。
