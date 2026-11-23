# Max Verstappen F1 個人知識庫 (MV1 Knowledge Base)

以 **Oracle Red Bull Racing** 賽車結構與遙測面板為設計靈感的 F1 車手個人知識庫網頁，結合結構化 Markdown 知識目錄（`AGENTS.md`、`index.md`、`wiki/`、`raw/`），可直接上傳至 GitHub 並透過 **GitHub Pages** 部署為線上網站。

## 目錄結構

```text
max-verstappen-wiki/
├── index.html          # Red Bull Racing 風格 F1 遙測主網頁
├── style.css           # 碳纖維紋理、賽車結構透視與 RWD 樣式表
├── script.js           # 賽車結構熱點互動、隊友篩選器與知識庫瀏覽器
├── README.md           # GitHub 專案說明與部署指南
├── AGENTS.md           # 知識庫維護與更新規範
├── index.md            # Markdown 知識庫總目錄
├── raw/                # 原始賽事資料與新聞歸檔區
└── wiki/               # 結構化知識條目
    ├── concepts/       # 地面效應等核心賽車概念
    ├── regulations/    # F1 技術規則演進筆記
    ├── entities/       # 所屬車隊與紅牛體系譜系
    └── teammates/      # 歷代隊友對決檔案
```

## 如何部署至 GitHub Pages

1. 在 GitHub 建立一個新的 Repository（例如 `max-verstappen-wiki`）。
2. 將本資料夾內的所有檔案上傳（Push）至 Repository 的 `main` 分支根目錄。
3. 前往 Repository 的 **Settings → Pages**。
4. 在 **Build and deployment → Source** 選擇 `Deploy from a branch`，Branch 選擇 `main` 與 `/ (root)`，點擊 **Save**。
5. 等待約 1 分鐘，即可透過 `https://<你的帳號>.github.io/max-verstappen-wiki/` 瀏覽網站。
