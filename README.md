# 管理框架知識星系 · Management Framework Knowledge Galaxy

STATON 仕坦登企業管理顧問 — 39 個管理框架的 3D 互動知識圖譜。

- **1,500** 個管理節點,依「單一工具 → 整合方法論」的複雜度分層
- **4,169** 條方法連結,含框架內組成與跨框架的先修依賴
- 柱狀星系結構:底部寬(具體工具),頂部窄(整合方法論)
- 點擊任一節點,追溯它所依賴的一切,其餘節點淡出
- 六大類別以品牌色系區分:目標戰略 / 專案執行 / 問題解決 / 決策風控 / 創新模式 / 核心整合

## 品牌識別

Navy #000e2f · Gold #f4b702 · Noto Serif TC · Cormorant Garamond

## 執行方式

必須透過網頁伺服器開啟(不能直接雙擊,因為要載入 JSON):

```
python3 -m http.server 8000
# 開 http://localhost:8000
```

部署到 GitHub Pages:Settings → Pages → Source 選 main / root。

## 檔案結構

- `index.html` — 主程式(Three.js 已內含於 vendor/,無外部 CDN 依賴)
- `vendor/three.min.js` — Three.js r128
- `data/graph.json` — 1,500 節點 + 4,169 連結的圖譜資料

## 涵蓋的 39 個框架

一、目標設定與戰略規劃:OGSM、OKR、BSC、SWOT、PESTEL、五力分析、GE-McKinsey、BCG、Ansoff、阿米巴經營
二、專案與執行管理:PDCA、OODA、RACI、SMART、甘特圖、CPM、PERT、看板、Scrum
三、問題解決與流程優化:3D GPS、5 Why、魚骨圖、MECE、精益思維、精實管理、六標準差、價值流程圖、JIT
四、決策與風險控管:決策矩陣、RAPID、風險矩陣、蒙地卡羅模擬
五、創新與商業模式:商業模式九宮格、設計思維、藍海策略
