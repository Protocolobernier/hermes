---
tipo: mecanismo
eje: HMGB1/RAGE
fecha: 2026-06-24
---

# ⚙️ Mecanismo: Eje HMGB1 → RAGE → inflamación no resolutiva

> **HMGB1** (High Mobility Group Box 1) es una proteína nuclear que, cuando las células mueren por **necrosis** o la secretan activamente, se convierte en una **señal de peligro** (DAMP). Su receptor estrella es **RAGE**. El bucle HMGB1/RAGE sostiene la inflamación que no se resuelve — el centro de este vault.

---

## Eslabón 1 — La necrosis libera HMGB1; la apoptosis lo retiene
- **Estado:** 🟢 Demostrado
- **Evidencia:** Scaffidi, Misteli & Bianchi, *Nature* 2002 (PMID 12110890). In vitro + celular. Las células necróticas liberan HMGB1; las apoptóticas lo retienen en el núcleo (acetilación/cromatina), por eso la muerte "limpia" no infla pero la "sucia" sí.
- **Por qué importa:** define el disparador inicial del eje — daño no programado.

## Eslabón 2 — HMGB1 "solo" es poco inflamatorio; necesita compañía
- **Estado:** 🟢 Demostrado (conceptual, Bianchi)
- **Evidencia:** Bianchi, *"HMGB1 loves company"*, *J Leukoc Biol* 2009 (PMID 19414536). HMGB1 recombinante puro apenas activa; se vuelve **muy inflamatorio** formando **complejos**: HMGB1·LPS → TLR4, HMGB1·DNA/CpG → TLR9 (vía RAGE), HMGB1·IL-1β → IL-1R.
- **Matiz crítico:** HMGB1 es un **chaperón** de señales de peligro, no un mero activador por sí mismo.

## Eslabón 3 — El estado redox de HMGB1 decide su función
- **Estado:** 🟢 Demostrado
- **Evidencia:** Venereau et al., *J Exp Med* 2012 (PMID 22869893). Tres cisteínas (C23, C45, C106) definen formas **mutuamente excluyentes**:
  - **All-thiol** → complejo con CXCL12 → quimiotaxis vía CXCR4 (reclutamiento, **no** inflamatorio).
  - **Disulfuro** (C23–C45) → une RAGE/TLR4 → citoquinas proinflamatorias.
  - **Totalmente oxidado** → inerte (terminal).
- **Implicación terapéutica:** medir "HMGB1 total" en suero es engañoso; la **forma redox** es lo que define actividad.

## Eslabón 4 — RAGE internaliza el complejo HMGB1·LPS → piroptosis
- **Estado:** 🟢 Demostrado (in vivo)
- **Evidencia:** Deng et al., *"The Endotoxin Delivery Protein HMGB1"*, *Immunity* 2018 (PMID 30314759). HMGB1 une LPS → RAGE lo internaliza al lisosoma → a pH ácido HMGB1 perfora la membrana → LPS escapa al citosol → **caspasa-11** → **piroptosis** → letalidad séptica. Bloquear HMGB1, neutralizarlo o la deficiencia de RAGE salvan al ratón.

## Eslabón 5 — Señalización RAGE → NF-κB / ERK1/2 → citoquinas + proliferación
- **Estado:** 🟢 Demostrado
- **Evidencia:** Pusterla et al., *Hepatology* 2013 (PMID 23504974). In vivo (Mdr2⁻/⁻). **HMGB1 → RAGE → ERK1/2 → Ciclina D1 → proliferación** de células ovales (progenitores). Ratones Rage⁻/⁻: menos fibrosis, menos tumores. ERK1/2 es a la vez el **cable inflamatorio y el cable proliferativo** — misma vía, doble lectura.

## Eslabón 6 — El bucle de no-resolución
- **Estado:** 🟡 Bien fundado
- **Evidencia:** Nathan & Ding, *"Nonresolving inflammation"*, *Cell* 2010 (PMID 20303877). Marco conceptual: la inflamación daña tejido → necrosis → más HMGB1 → más inflamación. La no-resolución = **persistencia del estímulo + fallo del cambio de fenotipo** macrofágico. El eslabón exacto HMGB1→fallo de resolución se infiere del conjunto, no está demostrado como único responsable.
- **Antecedente causal:** Wang et al., *Science* 1999 (PMID 10398600) — HMGB1 como mediador **tardío** de letalidad por endotoxina (no el pico agudo, el que mata horas después). Esa "fase tardía" es la cara clínica del bucle.

---

## Veredicto global del mecanismo

| Eslabón | Estado | Modelo |
|--------|--------|--------|
| 1. Necrosis libera HMGB1 | 🟢 | in vitro + celular |
| 2. HMGB1 necesita "compañía" (complejos) | 🟢 | conceptual + in vitro |
| 3. Redox decide función | 🟢 | in vitro |
| 4. RAGE internaliza HMGB1·LPS → piroptosis | 🟢 | **in vivo** (sepsis) |
| 5. RAGE → ERK → citoquinas + proliferación | 🟢 | in vivo (carcinogénesis) |
| 6. Bucle de no-resolución | 🟡 | marco conceptual |

**Lectura:** la cadena núcleo (1→5) está **sólidamente demostrada**, con eslabón in vivo fuerte (Deng 2018, Pusterla 2013). La **no-resolución como consecuencia directa del bucle HMGB1/RAGE** es la extrapolación mejor fundada — coherente con el marco de Nathan & Ding pero aún sin causalidad única cerrada.

---

## ⚠️ Extrapolaciones a NO asumir (límites del modelo)

1. **"Todo PAMP/señal de peligro converge en HMGB1→RAGE"** — ❌ FALSO. El β-glucano reprograma vía **Dectin-1**, no HMGB1/RAGE (Domínguez-Andrés & Netea, PMID 29999546). Los lipopéptidos diacilados (FSL-1) son **TLR2/6**. Distintos PAMPs entan por puertas distintas y solo **convergen aguas abajo** en el re-rewiring epigenético/metabólico.
2. **Drogas (anacardic acid, diflunisal, trimebutine) como anti-HMGB1 clínicos** — 🔴 solo **preclínico**. Sin ensayos clínicos que validen estos fármacos como anti-HMGB1/RAGE en humanos. → ver [[Hipótesis/...]]
3. **HMGB1 como único driver** — el eje es **central**, no **exclusivo**. Caspasa-11/TLR4, RIPK3 (Meng 2019, PMID 31000631) y hepcidina-independiente (Guida, PMID 25662334) son brazos paralelos.

---

## Conexiones

- [[Índice|← Índice del vault]]
- Fármacos sobre el eje: pendiente (anacardic acid / diflunisal / trimebutine) → [[Hipótesis/_Índice de hipótesis|Hipótesis]]
- Papers fundacionales: [[Papers/_Índice de papers|Índice de papers]]

---

## Fuentes verificadas (PMID · revista · año)

1. Wang H et al. *HMG-1 as a late mediator of endotoxin lethality in mice.* **Science. 1999;285(5425):248-51.** PMID: **10398600**
2. Scaffidi P, Misteli T, Bianchi ME. *Release of chromatin protein HMGB1 by necrotic cells triggers inflammation.* **Nature. 2002;418(6894):191-5.** PMID: **12110890**
3. Bianchi ME. *HMGB1 loves company.* **J Leukoc Biol. 2009;86(3):573-6.** PMID: **19414536**
4. Venereau E et al. *Mutually exclusive redox forms of HMGB1 promote cell recruitment or proinflammatory cytokine release.* **J Exp Med. 2012;209(9):1519-28.** PMID: **22869893**
5. Deng M et al. *The Endotoxin Delivery Protein HMGB1 Mediates Caspase-11-Dependent Lethality in Sepsis.* **Immunity. 2018;49(4):740-753.e7.** PMID: **30314759**
6. Pusterla T et al. *RAGE is a key regulator of inflammation-associated liver carcinogenesis.* **Hepatology. 2013;58(1):363-73.** PMID: **23504974**
7. Nathan C, Ding A. *Nonresolving inflammation.* **Cell. 2010;140(6):871-82.** PMID: **20303877**

> Citas verificadas vía NCBI E-utilities (PubMed) el 2026-06-24.
