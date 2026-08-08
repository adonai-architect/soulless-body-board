# EV-Mimic Delivery Systems — Research Note

**For:** Soulless Body / pineal recess / GBM path work  
**Date:** 2026-08-08  
**Status:** Open research

---

## Why this matters here

Our kill_test used a **naked anionic PS⁺ EV-mimic** (zeta −15 to −28 mV).  
Our help_test blocks docking via **HSPG + anti-TIM4 Fab**.  
Real delivery systems that behave like GBM-EVs (or that we might use therapeutically) fall into the categories below.

---

## Classes of EV-mimic / EV-inspired carriers

### 1. Fully synthetic EV-biomimetic liposomes (bottom-up)
- Built from defined lipids to match natural EV size, charge, and lipid ratios
- Typical size: ~90–220 nm
- Zeta: anionic (≈ −47 mV) to near-neutral
- Example lipid mixes from EV lipidomics: Chol / SM / PE / PC / **PS** ratios tuned to cancer EV profiles
- Advantages: scalable, controllable, high particle yield (10¹²/mL range reported)
- Use: study uptake physics; drug/gene cargo; reproducible "GBM-EV-class" test particles for our harness

### 2. Protein-functionalized liposomes (PFLs)
- Liposomes + inserted full-length membrane proteins (cell-free synthesis or reconstitution)
- Examples: CD47 (don't-eat-me), CD39, N-Cadherin, targeting ligands
- Preserves protein orientation/function better than peptide-only decoration

### 3. Hybrid vesicles (EV ⊕ liposome fusion)
- Freeze-thaw, extrusion, or incubation fusion of natural EVs with synthetic liposomes
- Combines EV targeting/biocompatibility with liposome loading capacity and tunability
- Used for glioma: e.g. blood-exosome + peptide-modified liposome hybrids for BBB transcytosis + tumor peptide guidance

### 4. Cell-derived nanovesicles (top-down)
- Shear/extrude whole cells into nano-vesicles
- High yield vs classical exosome isolation; retain membrane proteins
- Can be further hybridized with liposomes

### 5. PS-targeted systems (directly relevant to TIM4 / GBM)
- **SapC-DOPS** nanovesicles: saposin C + dioleoylphosphatidylserine — targets externalized PS on tumor cells and tumor vasculature; crosses blood–brain *tumor* barrier; anti-GBM activity in models
- **PS-targeted liposomes** (antibody or ligand to exposed PS on tumor endothelium) — glioma imaging and cargo delivery via disrupted/tumor BBB
- **PC-SA cationic liposomes** — affinity for surface PS on cancer cells; direct cytotoxicity + drug complexation
- **PLA2 + PS-liposome "mix & act"** — selective, reversible BBB opening assist for brain delivery

---

## Physicochemical knobs that change uptake

| Parameter | Effect (from synthetic EV-liposome studies) |
|-----------|-----------------------------------------------|
| Size ↓ (toward ~100 nm) | Generally ↑ internalization |
| Zeta less negative / neutral | Often ↑ uptake vs strongly anionic |
| PS in outer leaflet | Engages TIM-4 / other PS receptors; tumor/apoptotic targeting |
| Protein corona / specific surface proteins | Homing, immune evasion (e.g. CD47), receptor-mediated uptake |

Our kill_test anionic window (−15 to −28 mV) sits in the documented cancer-EV zeta range.

---

## CNS / glioma delivery angles

- Natural and hybrid EVs can cross BBB or BBTB better than many synthetic NPs
- PS exposure on tumor endothelium and GBM cells is a real target (SapC-DOPS, PS-Ab liposomes)
- For **CSF / recess path** (our model): delivery does not require classical BBB crossing if the route is CSF → discontinuous recess ependyma; still need stability in CSF and docking control (HSPG/TIM4)
- FUS (our help_test params: 220 kHz, MI 0.3–0.4) remains a separate permeability tool for barrier interfaces

---

## Implications for chassis tests

1. **kill_test particles** can be implemented as PS-containing anionic liposomes (Chol/PC/PS ± SM/PE) at zeta −15 to −28 mV, 100–200 nm — literature-backed EV-mimic recipe space
2. **help_test** still blocks the docking face (HSPG electrostatic + TIM4 PS receptor) independent of exact carrier brand
3. Therapeutic inversion: same PS⁺ EV-mimic chassis could carry protective cargo *if* docking is steered away from pinealocytes or paired with the filter
4. SapC-DOPS and PS-targeted liposomes are the closest clinical-adjacent analogues that already exploit PS for glioma targeting

---

## Key references (entry points)
- Synthetic EV-like liposomes for cancer EV uptake studies (bioinspired liposome libraries, size/zeta control)
- Bottom-up EV mimetics with cell-free membrane proteins
- SapC-DOPS nanovesicles for PS-selective GBM targeting
- PS-targeted liposomes for glioma imaging/delivery
- Hybrid EV–liposome systems for BBB/brain tumor delivery
- EV lipidomics-guided Chol/SM/PE/PC/PS formulations

---

*Open research. Use it.*
