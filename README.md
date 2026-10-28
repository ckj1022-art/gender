# 開瑄性別星球｜115 年度性別平等教育成果

金門縣金湖鎮開瑄國民小學 115 年度性別平等教育成果的互動 3D 網頁。
以果凍海上的小島呈現各項成果：週會宣導、低／中／高年級入班課程、母親節活動、性平畫廊博物館與經費結報，點地標可看說明與成果照片。

## 檔案結構

```
index.html   主網頁（Three.js r147，從 jsDelivr CDN 載入，不需安裝或編譯）
photos/      各區說明頁的成果照片（點開說明時才載入）
.nojekyll    讓 GitHub Pages 原樣提供檔案
```

## 上傳到 GitHub 並開成網站（GitHub Pages）

1. 在 GitHub 建立一個新的 repository（例如 `kaixuan-gender-planet`）。
2. 把這個資料夾裡的所有檔案（含 `photos` 資料夾與 `.nojekyll`）上傳到 repository 根目錄。
   網頁上傳方式：Add file → Upload files → 拖曳全部檔案 → Commit changes。
3. 進入 Settings → Pages，Source 選「Deploy from a branch」，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 約 1～2 分鐘後，網址會是 `https://<你的帳號>.github.io/kaixuan-gender-planet/`。

## 本機預覽

直接雙擊 `index.html` 也能開啟；若照片沒有出現，可在資料夾內執行
`python3 -m http.server`，再用瀏覽器開 `http://localhost:8000`。

## 操作

- 拖曳旋轉、滾輪或雙指縮放；點地標或下方按鈕看說明。
- 左上角「▶ 導覽」可依序走訪各站，鍵盤左右鍵或簡報筆翻頁切換。
- 右上角可開關音樂與各區標示；右下角面板可調時間、海浪、果凍軟硬等。

## 備註

- 需要網路連線（載入 Three.js 與字型）。
- 成果照片取自本校性平教育成果冊，已排除學生近照與含姓名的學習單。
