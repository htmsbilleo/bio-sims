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

## QDCS-lite 課堂測驗 / Classroom quiz

`qdcs-lite.html` 與 `qdcs/index.html` 是同一頁（自含 HTML，無需建置）。香港中學科學課堂測驗：教師出題、分享碼作答、成績分析。資料存在瀏覽器 localStorage，不是伺服器成績庫。

`qdcs-lite.html` and `qdcs/index.html` are the same self-contained page (no build step). HK secondary-science classroom quiz: teacher builder, share-code attempts, and score analytics. Data stays in the browser’s localStorage, not on a server.

- 根路徑：<https://htmsbilleo.github.io/bio-sims/qdcs-lite.html>
- 資料夾入口（頁內分享連結以 `index.html#q=…` 表示，用這個網址較順）：<https://htmsbilleo.github.io/bio-sims/qdcs/>
