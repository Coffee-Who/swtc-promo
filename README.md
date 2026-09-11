# swtc-promo

實威國際行銷信件版型與圖片圖床。

## 內容

| 檔案 | 說明 |
|---|---|
| `index.html` | 版型索引頁 |
| `scanology_email.html` | SCANOLOGY 掃描體驗日信件 |
| `formlabs_email.html` | Formlabs 列印體驗日信件 |
| `images/` | 信件使用的圖片 |

## 需要的圖片

放進 `images/`，檔名必須一致：

**SCANOLOGY**
- `02_simscan.jpg` — SIMSCAN 機器主圖
- `03_nimbletrack.png` — NimbleTrack 機器主圖
- `04_controlx.jpg` — Control X 偏差色階圖
- `05_case_mold.jpg` — 模具/精密件檢測情境
- `06_case_large.jpg` — 大型工件現場掃描情境

**Formlabs**
- `01_form4.jpg` — Form 4 機器主圖
- `02_fuse.jpg` — Fuse 系列機器主圖
- `03_workflow.jpg` — 完整工作流程圖
- `04_case_proto.jpg` — 快速打樣情境
- `05_case_production.jpg` — 量產應用情境

> 注意：Formlabs 的 `02_fuse.jpg` 與 SCANOLOGY 的 `02_simscan.jpg` 檔名不衝突，但兩組都放在同一個 `images/` 資料夾，上傳前確認沒有覆蓋到。

## 啟用 GitHub Pages

Settings → Pages → Source 選 `main` 分支 / `root`，儲存後網址為：

```
https://coffee-who.github.io/swtc-promo/
```

## 更換圖片

直接覆蓋 `images/` 內的同名檔案，信件無須重新製作。

## 待辦

- [ ] 將 `https://forms.gle/your-form-link` 換成正式申請表網址（每份信件各 3 處）
- [ ] 補齊 `images/` 內的圖片
