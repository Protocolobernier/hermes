---
tipo: mecanismo
eje: HMGB1/RAGE
linea: inflamacion-no-resolutiva
cadena: toxina-HMGB1-RAGE-TLR4-macrofago-cancer
fecha: 2026-06-24
---

# ⚙️ Mecanismo: Toxina → HMGB1 → RAGE/TLR4 → macrófago inflamatorio → cáncer

> **Cadena causal central del vault.** Una toxina (endotoxina/LPS) se une a HMGB1, entra vía RAGE, y la señal (amplificada por TLR4) reprograma al macrófago hacia un fenotipo inflamatorio no resolutivo que sostiene el proceso proliferativo/cáncer. **Cinco de los cinco eslabones están demostrados con evidencia primaria, varios in vivo.** Bloquear el eje frena el tumor.

---

## La cadena (graduada)

### Eslabón 1 — La toxina (LPS) se une a HMGB1
- **Estado:** 🟢 Demostrado
- **Mecanismo:** HMGB1 actúa como chaperón: forma complejo con LPS (y con CpG/IL-1β/nucleosomas). HMGB1 "solo" es poco inflamatorio; necesita compañía.
- **Evidencia:** Bianchi, *J Leukoc Biol* 2009 (PMID 19414536); **Deng et al., *Immunity* 2018 (PMID 30314759)** — "The Endotoxin Delivery Protein HMGB1".
- **Extensión:** HMGB1 también quela endotoxina hipoacilada (lipid IVa) vía **RIPK3/TRIF** (Meng et al., *J Biol Chem* 2019, PMID 31000631) — un segundo eje de muerte, paralelo a caspasa-11.

### Eslabón 2 — El complejo entra vía RAGE
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** RAGE internaliza el complejo HMGB1·LPS al lisosoma → a pH ácido HMGB1 perfora la membrana → LPS escapa al citosol → caspasa-11 → piroptosis → letalidad séptica. Bloquear HMGB1 o la deficiencia de RAGE **salvan al ratón**.
- **Evidencia:** **Deng et al., *Immunity* 2018 (PMID 30314759).** Laboratorio de Tracey/Billiar/Lu — *"Key Lab of Non-resolving Inflammation and Cancer"*.

### Eslabón 3 — Reprograma el macrófago a fenotipo inflamatorio
- **Estado:** 🟢 Demostrado (transcriptómica)
- **Mecanismo:** HMGB1 induce en macrófagos (BMDM) un fenotipo **pro-inflamatorio único**, distinto del M1 clásico, que secreta citoquinas y migra.
- **Matiz crítico (forma redox):** SOLO la forma **disulfuro-HMGB1** induce polarización; la totalmente reducida (frHMGB1) **NO**. → Venereau et al., *J Exp Med* 2012 (PMID 22869893): formas redox mutuamente excluyentes.
- **Evidencia:** Palumbo et al., *Biomolecules* 2021 (PMID 34071440); Yang et al., *Biomolecules* 2022 (PMID 35740904) — RNA-Seq.

### Eslabón 4 — Genera proliferación / cáncer
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** HMGB1 → RAGE → **ERK1/2 → Ciclina D1 → proliferación** de células progenitoras. ERK1/2 es a la vez el cable inflamatorio Y el cable proliferativo — misma vía, doble lectura.
- **Evidencia:** **Pusterla et al., *Hepatology* 2013 (PMID 23504974)** — modelo Mdr2⁻/⁻ de carcinogénesis hepática. Ratones Rage⁻/⁻: menos fibrosis, menos tumores.

### Eslabón 5 — Bloquear el eje frena el cáncer
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** Bloquear HMGB1 (anticuerpo anti-HMGB1) y/o TLR4 (inhibidor) impide la reprogramación macrofágica y **reduce el crecimiento tumoral y la metástasis**.
- **Evidencia clave:** **Huang et al., *Theranostics* 2024 (PMID 38646639)** — *"an anti-HMGB1 antibody and a TLR4 inhibitor induced a blockade"* de la reprogramación M2→M1, con inhibición del tumor in vivo.
- **Soporte adicional:** Kida et al., *BBRC* 2020 (PMID 32800556) — HMGB1 vía RAGE+TLR4 en cáncer oral óseo; Pusterla 2013 (RAGE⁻/⁻ = menos tumores).

---

## ⚠️ Tres precisiones que AFILAN el modelo (no lo refutan)

### 1. No es solo RAGE — es RAGE **+ TLR4**
- RAGE = **puerta de entrada** del complejo HMGB1·LPS (internalización).
- **TLR4 = amplificador** de la señal inflamatoria dentro del macrófago. Palumbo 2021: *"dsHMGB1 mediates cytokine secretion mainly through TLR4."*
- **Implicación terapéutica:** la [[Trimebutina]] (bloquea TLR2/4/7/8/9 vía IRAK1, 🟢 PMID 34517011) ataca justo este segundo brazo. Cobra sentido como pieza del modelo.

### 2. La forma REDOX decide el fenotipo
- **Disulfuro-HMGB1** → induce fenotipo inflamatorio (Palumbo 2021, Yang 2022). ✅
- **Totalmente oxidada** → inerte (terminal). 
- **Implicación metodológica:** medir "HMGB1 total" en suero es engañoso. Hay que medir la **forma disulfuro**, la única que reprograma.

### 3. "Inflamatorio no resolutivo" — el eslabón más delicado
- **Inflamatorio:** 🟢 Demostrado (eslabón 3).
- **No resolutivo:** 🟡 Inferencia integradora (correcta, pero no un hallazgo aislado de un solo paper). Conecta el fenotipo inflamatorio con el marco de Nathan & Ding, *Cell* 2010 (PMID 20303877) sobre inflamación no resolutiva.
- **⚠️ Aviso oncológico:** en el nicho tumoral, M1 es **anti-tumoral** y M2 es **pro-tumoral**. "Inflamación → cáncer" es cierto solo para inflamación **crónica, persistente, no resuelta**. La inflamación aguda M1 puede ser **protectora**. La distinción crítica: crónica/no resuelta vs aguda/resuelta — el corazón de esta línea.

---

## Veredicto global del mecanismo

| Eslabón | Estado | Modelo | PMID |
|--------|--------|--------|------|
| 1. Toxina (LPS) se une a HMGB1 | 🟢 | in vitro + in vivo | 30314759, 31000631 |
| 2. Complejo entra vía RAGE | 🟢 | **in vivo** (sepsis) | 30314759 |
| 3. Reprograma macrófago a inflamatorio | 🟢 | in vitro (RNA-Seq) | 34071440, 35740904 |
| 4. Genera proliferación/cáncer | 🟢 | **in vivo** (carcinogénesis) | 23504974 |
| 5. Bloquear el eje frena el cáncer | 🟢 | **in vivo** (tumor) | 38646639, 32800556 |

**Lectura:** cadena de **cinco eslabones demostrados**, con evidencia in vivo en los puntos más decisivos (Deng 2018 para entrada, Pusterla 2013 para proliferación, Huang 2024 para bloqueo terapéutico). Es el núcleo mejor fundamentado del vault. El único matiz de gradación es "no resolutivo" como síntesis interpretativa (🟡), no como hallazgo aislado.

---

## ⚠️ Extrapolaciones a NO asumir

1. **"Todo entra por RAGE"** — ❌ El LPS libre también señaliza directamente vía **TLR4/MD2** sin HMGB1. RAGE es la vía del complejo HMGB1·LPS, no la única del LPS.
2. **"Cualquier HMGB1 reprograma"** — ❌ Solo la forma **disulfuro**. La reducida no lo hace.
3. **"Inflamación = cáncer"** — ❌ Solo la **crónica no resuelta**. La aguda puede ser protectora.
4. **"Bloquear HMGB1 cura el cáncer"** — 🔴 Huang 2024 es **preclínico** (ratón), en un sistema farmacológico de nanopartícula (IL4R-Abx). No es terapia validada en humanos.

---

## Conexiones

- [[Eje HMGB1-RAGE]] — mecanismo matriz (esta nota profundiza sus eslabones 3–5)
- [[Trimebutina]] — bloquea el brazo TLR4/IRAK1 (precisión 1 de arriba)
- [[Hipótesis/Inhibicion vertical trifarmaco HMGB1-RAGE]] — el eslabón del macrófago reprogramado es el blanco de la tríada
- [[Índice|← Índice del vault]]

---

## Fuentes verificadas (PMID · revista · año)

1. Bianchi ME. *HMGB1 loves company.* **J Leukoc Biol. 2009;86(3):573-6.** PMID: **19414536**
2. Deng M et al. *The Endotoxin Delivery Protein HMGB1 Mediates Caspase-11-Dependent Lethality in Sepsis.* **Immunity. 2018;49(4):740-753.e7.** PMID: **30314759**
3. Meng M et al. *HMGB1–lipid IVa/LA complex → RIPK3/TRIF.* **J Biol Chem. 2019.** PMID: **31000631**
4. Venereau E et al. *Mutually exclusive redox forms of HMGB1.* **J Exp Med. 2012;209(9):1519-28.** PMID: **22869893**
5. Palumbo R et al. *Disulfide and Fully Reduced HMGB1 Induce Different Macrophage Polarization.* **Biomolecules. 2021;11(6):800.** PMID: **34071440**
6. Yang et al. *Transcriptomic Profiling Reveals That HMGB1 Induces Macrophage Polarization Different from Classical M1.* **Biomolecules. 2022;12(6):779.** PMID: **35740904**
7. Pusterla T et al. *RAGE is a key regulator of inflammation-associated liver carcinogenesis.* **Hepatology. 2013;58(1):363-73.** PMID: **23504974**
8. Huang et al. *IL4R targeting enables nab-paclitaxel to enhance reprogramming of M2-type macrophages via ROS-HMGB1-TLR4 axis.* **Theranostics. 2024;14(6):2605-2621.** PMID: **38646639** — *prueba experimental del eslabón 5*
9. Kida Y et al. *HMGB1 induces bone destruction via RAGE and TLR4.* **BBRC. 2020;533(4):1413-9.** PMID: **32800556**
10. Nathan C, Ding A. *Nonresolving inflammation.* **Cell. 2010;140(6):871-82.** PMID: **20303877**

> Citas verificadas vía NCBI E-utilities (PubMed) el 2026-06-24.
