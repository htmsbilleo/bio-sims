# bio-sims

教學用生物模擬器（相對單位）。數值只供課堂說明，不是真實 mmHg、mol/dm³、kPa 或臨床／實驗數據。

Educational biology simulators in **relative units**. Values are for classroom explanation only — not real mmHg, mol/dm³, kPa, or clinical / lab data.

## 流體壓力與滲透壓 / Fluid pressure and osmotic pressure

`index.html` 與 `hydrostatic-osmotic-pressure.html` 是同一頁（自含 HTML，無需建置）。

`index.html` and `hydrostatic-osmotic-pressure.html` are the same self-contained page (no build step).

- **微血管組織液交換（capillary）：** 小動脈 → 微血管網 → 小靜脈。以流體壓力（fluid pressure, FP）理解沿程血壓下降，並與滲透壓／膠體滲透壓（osmotic / oncotic pressure, OP）對照。簡化關係：淨壓 ≈ 血管流體壓力 − 有效滲透壓差。
- **Capillary tissue-fluid exchange:** arteriole → capillary network → venule. Fluid pressure falls along the bed and is set against a roughly steady osmotic / oncotic pressure. Simplified relation: net pressure ≈ vascular fluid pressure − effective osmotic-pressure difference.
- **植物例子：薯仔 × 蔗糖（potato × sucrose）：** 細胞內溶質固定在相對值約 40。稀蔗糖 → 膨脹；近等滲 → 萎軟；濃蔗糖 → 質壁分離。水勢以 ψ ≈ ψₛ + ψₚ（相對單位）表示。
- **Plant example: potato × sucrose:** internal solute stays near a relative value of 40. Dilute sucrose → turgid; near-isotonic → flaccid; concentrated sucrose → plasmolysis. Water potential is shown as ψ ≈ ψₛ + ψₚ in relative units.

網站：<https://htmsbilleo.github.io/bio-sims/>

Named page: <https://htmsbilleo.github.io/bio-sims/hydrostatic-osmotic-pressure.html>

## QDCS-lite 測驗（老師／學生分頁）

`qdcs/teacher.html` 是老師編輯版（出題、TXT／MD／DOCX／PDF／圖片匯入、掃描與圖片 OCR（Tesseract CDN）、短答／長答／論述、成績、Drive 匯出）。儲存後按「發佈為目前測驗」，學生開同一資料夾的 `qdcs/student.html`（同一瀏覽器）無需分享碼即可載入；分享碼仍可作備用。`qdcs/index.html` 是入口，連結兩邊，樣式在 `qdcs/styles.css`。根目錄 `qdcs-lite.html` 轉到該入口。資料存在瀏覽器 localStorage，不是伺服器成績庫。PDF 先抽文字層，不足才做掃描／圖片 OCR；OCR 準確度有限，首次需下載 CDN，最多約 12 頁。

`qdcs/teacher.html` is the teacher editor (authoring, TXT/MD/DOCX/PDF/image import, scan and image OCR via the Tesseract CDN, short/long/essay items, scores, Drive export). After **Publish as current quiz**, students open `qdcs/student.html` in the same folder and same browser and load it without a share code; a code still works as a fallback. `qdcs/index.html` is the hub and links both pages; layout is `qdcs/styles.css`. Root `qdcs-lite.html` redirects to that hub. Data stays in the browser’s localStorage, not on a server. PDF import uses the text layer first and falls back to scan/image OCR when that layer is too thin. OCR accuracy is limited, the first run downloads the CDN script, and it covers about 12 pages.

- 老師編輯版：<https://htmsbilleo.github.io/bio-sims/qdcs/teacher.html>
- 學生作答版（已發佈則免碼；備用示範碼 BIODEMO）：<https://htmsbilleo.github.io/bio-sims/qdcs/student.html>
- 入口：<https://htmsbilleo.github.io/bio-sims/qdcs/>
- 樣式：<https://htmsbilleo.github.io/bio-sims/qdcs/styles.css>
- 舊連結：<https://htmsbilleo.github.io/bio-sims/qdcs-lite.html>
