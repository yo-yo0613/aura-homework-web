# AURA LAB｜北科大創業課程作業分發系統

國立臺北科技大學 創新創業學程隨堂作業分發網站
* **課程名稱**：創業0到2的思維與實作
* **授課教師**：姚長安 老師
* **專案主題**：《AURA LAB：智慧情緒調香快閃終端》
* **核心規範**：嚴格剛好 4 頁整、查重率 < 25%、四位組員客觀專案數據一致

---

## 📁 檔案結構

```text
├── index.html       # 現代化響應式領取介面 (Tailwind CSS + Lucide Icons)
├── vercel.json      # Vercel 部署設定
└── downloads/       # 4 位組員經由本機 Word COM 轉出的標準 4 頁 PDF 與 Word 備用檔
    ├── 互動三_113AC1013_李承祐.pdf
    ├── 互動三_113AC1013_李承祐.docx
    ├── 互動三_113AC1002_組員A.pdf
    ├── 互動三_113AC1002_組員A.docx
    ├── 互動三_113AC1018_組員B.pdf
    ├── 互動三_113AC1018_組員B.docx
    ├── 互動三_113AC1025_組員C.pdf
    ├── 互動三_113AC1025_組員C.docx
    └── AURA_Homework_Team.zip
```

---

## 🚀 部署方式

### 方式 1：GitHub Pages 免費託管（最簡單）
1. 進入本倉庫 Settings -> **Pages**
2. Build and deployment -> Source 選擇 **Deploy from a branch**
3. Branch 選擇 **main** / **/(root)**，點擊 **Save**
4. 稍等 1 分鐘即可取得公開網址：`https://<帳號>.github.io/<倉庫名>/`

### 方式 2：Vercel 一鍵匯入
1. 前往 [vercel.com/new](https://vercel.com/new)
2. 匯入此 GitHub 倉庫，點擊 **Deploy** 即可
