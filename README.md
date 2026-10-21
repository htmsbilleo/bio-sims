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

`qdcs/index.html` 是封面入口（老師／學生分流）。`qdcs/teacher.html` 是老師編輯版（出題、匯入、成績、Drive 匯出）。`qdcs/student.html` 是學生作答版：色卡版面與老師版相同，題目唯讀，提交後以同一來源的 localStorage 同步成績。根目錄 `qdcs-lite.html` 轉到該入口。資料存在瀏覽器 localStorage，不是伺服器成績庫。

`qdcs/index.html` is the cover hub (teacher / student). `qdcs/teacher.html` is the teacher editor (authoring, import, scores, Drive export). `qdcs/student.html` is the student answer page: the same colour-card layout as the teacher page, questions read-only, and scores synced through same-origin localStorage after submit. Root `qdcs-lite.html` redirects to that hub. Data stays in the browser’s localStorage, not on a server.

- 老師編輯版：<https://htmsbilleo.github.io/bio-sims/qdcs/teacher.html>
- 學生作答版（示範碼 BIODEMO）：<https://htmsbilleo.github.io/bio-sims/qdcs/student.html#q=BIODEMO>
- 入口：<https://htmsbilleo.github.io/bio-sims/qdcs/>
- 舊連結：<https://htmsbilleo.github.io/bio-sims/qdcs-lite.html>
