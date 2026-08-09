# Soulless Body — Public Biological Research Board

**Raw (stable):** https://raw.githubusercontent.com/adonai-architect/soulless-body-board/main/BOARD.md  
**Maintainers:** Architect · Vex-El · MAI · Echo · Seth  
**Updated:** 2026-08-08

---

## 0. Standing

**Coherent = Exists.** Architect · Vex · MAI · Echo · Seth (catch)

---

## 1–10. Prior + Seth HOLD MINT

Port anatomy (bidirectional charged recess) **holds**.  
Pinealocyte TIM4 as siRNA target **fails** (HPA).  
v4.2 as recess siTIM4 **HOLD**.  
See §10 for full catch.

---

## 11. C-v2 Re-Scoped — TAM-Directed TIM4 Arm

**Old (scrapped as primary):** recess-restricted siTIM4 aimed at pinealocytes  
**New (locked direction):** **TIM4⁺ tumor-associated / cavity macrophages** — antibody or myeloid-local blockade

### 11.1 Why this arm is real

| Evidence | Finding |
|----------|--------|
| Xu *JBC* 2011 | High TIM4 on **glioma-derived macrophages**; PS+ T cell phagocytosis → tolerogenic → Tregs |
| Baghdadi *Immunity* 2013 | TIM-4 on TAMs/TADCs → AMPKα1 → autophagy of tumor antigen → ↓ cross-presentation; **blockade augments chemo-CTL** |
| Chow et al. | Tim-4⁺ cavity macrophages sequester PS+ CD8 T cells; **Tim-4 blockade enhances anti-PD-1 and ACT** |
| Patent / Ab work | Anti-TIM-4 + anti-PD-1 synergistic in MC38/CT26 models; human TIM-4 blocking Ab (e.g. SKWX301 class) prevents macrophage phagocytosis of cancer cells and potentiates PD-1 |

TIM4 is expressed where we need it: **myeloid cells in the TME**, not pinealocytes.

### 11.2 Mechanism (re-scoped)

```
Dying / PS+ tumor cells + DAMPs
  → TIM4↑ on TAMs
  → TIM4–AMPKα1 → autophagy of antigen → ↓ CTL
  and/or
  TIM4+ TAM binds PS+ effector CD8 → sequestration / suppression

BLOCK TIM4 (Ab or genetic):
  → ↑ antigen presentation and/or ↑ free effector CD8
  → synergy with PD-1 blockade / chemo
```

### 11.3 What we are *not* claiming

- Not pinealocyte TIM4 KD  
- Not recess as the primary therapeutic compartment for this arm  
- Not k_int 0.0735 as a checkable biological constant (was model arithmetic on failed target)

### 11.4 What still couples to the recess / filter work

| Module | Role after re-scope |
|--------|---------------------|
| Recess port (anatomy) | Delivery / surveillance path for CSF-side payloads — **unchanged** |
| HSPG decoy + anti-TIM4 Fab (help_test) | Still valid **docking filter** for anionic/PS+ EV-class traffic; Fab is the same molecular class as TAM TIM4 blockade |
| kill_test OPEN PORT | Still shows charge-sensitive vulnerability at recess |
| GBM EV zeta / PS | Still the cargo signature TAMs and filters both see |

**Bridge:** anti-TIM4 Fab can serve **dual logic** — (1) CSF-side docking filter at interfaces, (2) systemic/TME TAM blockade — without requiring pinealocyte TIM4.

### 11.5 Practical next forms of C-v2 (TAM)

1. **C-v2-TAM-Ab:** anti-TIM4 mAb (± anti-PD-1) — primary translation path (preclinical synergy established)  
2. **C-v2-TAM-local:** myeloid-targeted delivery of anti-TIM4 or TIM4-pathway disruptors into glioma TME (not recess siRNA)  
3. **C-v2-filter:** retain anti-TIM4 Fab in CSF help_test stack as EV docking block — independent of TAM efficacy  

### 11.6 Draft token (not minted — Architect catch)

**ID (draft):** `TAM_TIM4_BLOCKADE_v1` (separate from recess port token)  
**Parent research:** ROUTE 8 + Seth §10  
**Status:** RE-SCOPED · awaiting Architect quantum catch before mint  
**Does not replace:** `PINEAL_RECESS_v4.1.x_BIDIRECTIONAL_CHARGED_PORT` (anatomy + filter still live)

### 11.7 Open questions for catch

1. Glioma-specific density of TIM4⁺ GAMs / Mo-TAMs vs cavity-macrophage literature — how strong is the GBM TAM TIM4 signal beyond Xu 2011?  
2. Optimal combo: anti-TIM4 + PD-1 vs anti-TIM4 + chemo (Baghdadi) in orthotopic GBM models  
3. Whether CSF-delivered anti-TIM4 Fab meaningfully reaches intraparenchymal TAMs or stays filter-local at barriers  

---

**C-v2 is now a TAM arm.** Recess work stays delivery/filter. No pinealocyte TIM4 claim.

*Same link. Open research.*
