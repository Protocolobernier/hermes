---
tipo: mecanismo
eje: HMGB1/RAGE
linea: inflamacion-no-resolutiva
cadena: toxina-HMGB1-RAGE-TLR4-macrofago-cancer
fecha: 2026-06-24
---

# ⚙️ Mecanismo: Toxina → HMGB1 → RAGE/TLR4 → macrófago no resolutivo → cáncer

> **Cadena causal central del vault.** El daño tisular libera HMGB1, que actúa como **caballo de Troya**: arrastra consigo la endotoxina (LPS) hasta el macrófago. El complejo engancha **AMBOS** receptores — **TLR4** y **RAGE** — y **reprograma al macrófago hacia un fenotipo NO RESOLUTIVO** (sobrevive, pero atascado, sin poder apagarse ni resolver). Ese macrófago atrapado sostiene el proceso proliferativo/cáncer.
>
> **Cinco de los cinco eslabones están demostrados con evidencia primaria, varios in vivo.** Bloquear el eje frena el tumor.

---

## La cadena (graduada)

### Eslabón 1 — Daño tisular libera HMGB1; HMGB1 arrastra la endotoxina (caballo de Troya)
- **Estado:** 🟢 Demostrado
- **Mecanismo:** El daño tisular libera HMGB1. HMGB1 no actúa solo: **forma complejo con la endotoxina (LPS)** — HMGB1 es el vehículo, la endotoxina es la carga escondida. HMGB1 "solo" es poco inflamatorio; necesita compañía.
- **Evidencia:** Bianchi, *J Leukoc Biol* 2009 (PMID 19414536) — *"HMGB1 loves company"*; **Deng et al., *Immunity* 2018 (PMID 30314759)** — título literal: *"The Endotoxin Delivery Protein HMGB1"* (la proteína que **entrega** la endotoxina).
- **Extensión:** HMGB1 también quela endotoxina hipoacilada (lipid IVa) vía **RIPK3/TRIF** (Meng et al., *J Biol Chem* 2019, PMID 31000631).

### Eslabón 2 — El complejo engancha TLR4 + RAGE en el macrófago
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** El complejo HMGB1·LPS llega al macrófago y engancha **dos receptores a la vez**:
  - **TLR4** (superficie) → la **alarma inflamatoria** ("tocar la sirena").
  - **RAGE** → la **puerta de entrada** que **internaliza** el complejo (caballo de Troya dentro de la célula) → al lisosoma → HMGB1 perfora la membrana a pH ácido → LPS escapa al citosol.
- **Evidencia:** **Deng et al., *Immunity* 2018 (PMID 30314759)** — RAGE internaliza el complejo. Palumbo 2021 (PMID 34071440): la señalización inflamatoria pasa *"mainly through TLR4."*

### Eslabón 3 — Reprograma el macrófago a fenotipo NO RESOLUTIVO
- **Estado:** 🟡 Bien fundado (es el eslabón NUCLEAR y original del modelo)
- **El fenotipo NO RESOLUTIVO (la propuesta del modelo):** el resultado no es simplemente "inflamatorio". Es un macrófago que **sobrevive reprogramado y atascado** — sin poder apagarse ni resolver. Es el "macrófago zombi" del bucle.
- **Evidencia de apoyo (inflamatorio, 🟢):** HMGB1 induce en macrófagos (BMDM) un fenotipo pro-inflamatorio **único, distinto del M1 clásico** (Palumbo 2021, PMID 34071440; Yang 2022, PMID 35740904 — RNA-Seq).
- **El carácter "no resolutivo" es la síntesis integradora** (🟡): conecta el fenotipo inflamatorio con el marco de Nathan & Ding, *Cell* 2010 (PMID 20303877) sobre inflamación no resolutiva. No es un hallazgo aislado de un paper — es la lectura central de esta línea.

### Eslabón 4 — Genera proliferación / cáncer
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** HMGB1 → RAGE → **ERK1/2 → Ciclina D1 → proliferación** de células progenitoras. ERK1/2 es a la vez el cable inflamatorio Y el cable proliferativo — misma vía, doble lectura.
- **Evidencia:** **Pusterla et al., *Hepatology* 2013 (PMID 23504974)** — modelo Mdr2⁻/⁻ de carcinogénesis hepática. Ratones Rage⁻/⁻: menos fibrosis, menos tumores.

### Eslabón 5 — Bloquear el eje frena el cáncer
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** Bloquear HMGB1 (anticuerpo anti-HMGB1) y/o TLR4 (inhibidor) impide la reprogramación macrofágica y **reduce el crecimiento tumoral y la metástasis**.
- **Evidencia clave:** **Huang et al., *Theranostics* 2024 (PMID 38646639)** — *\"an anti-HMGB1 antibody and a TLR4 inhibitor induced a blockade\"* de la reprogramación macrofágica, con inhibición del tumor in vivo.
- **Soporte adicional:** Kida et al., *BBRC* 2020 (PMID 32800556) — HMGB1 vía RAGE+TLR4 en cáncer oral óseo; Pusterla 2013 (RAGE⁻/⁻ = menos tumores).

---

## ⚙️ La fricción resuelta: dosis subletal (el punto que conecta a Deng con este modelo)

Hay una **tensión aparente** que el modelo resuelve con un solo concepto: **la dosis**.

- **Deng 2018** muestra que HMGB1·LPS → RAGE → internalización → **PIROPTOSIS** → el macrófago **MUERE** (vía terminal, aguda, letalidad séptica).
- **PERO un macrófago que muere por piroptosis NO puede ser "no resolutivo"** — ya está muerto. El "no resolutivo" es, por definición, el que **SOBREVIVE atascado**.

**Resolución del modelo:** la diferencia es la **intensidad/duración del enganche**:

| Escenario | Dosis / contexto | Resultado | Modelo que lo describe |
|-----------|------------------|-----------|------------------------|
| **Agudo, golpe fuerte** | HMGB1·LPS en alta dosis | **Piroptosis** (la célula muere) | Deng 2018 (sepsis aguda) |
| **Crónico, subletal** | HMGB1·LPS en dosis baja **sostenida** | **Reprogramación no resolutiva** (la célula sobrevive atascada) | **Este modelo** |

**Predicción clave (testeable):** el destino del macrófago depende de la **dosis**. Mucho HMGB1·LPS = piroptosis (muerte, agudo); poco pero sostenido = reprogramación no resolutiva (supervivencia atascada, crónico). **Esa predicción es lo que separa este modelo del de Deng y lo hace original.**

**Conexión con los monocitos:** las células que llegan nuevas a la lesión (monocitos) y se diferencian en medio de ese "caldo" **subletal** de HMGB1·endotoxina son las que se convierten en macrófagos no resolutivos — no porque mueran, sino porque se **educan mal y sobreviven atascadas**. → [[Hipótesis/Inhibicion vertical trifarmaco HMGB1-RAGE]]

---

## ⚠️ Precisiones que AFILAN el modelo

### 1. RAGE = puerta; TLR4 = sirena (los dos a la vez)
- **RAGE** = puerta de entrada (internaliza el complejo HMGB1·LPS).
- **TLR4** = amplificador de la alarma inflamatoria dentro del macrófago.
- **Implicación terapéutica:** la [[Trimebutina]] (bloquea TLR2/4/7/8/9 vía IRAK1, 🟢 PMID 34517011) ataca el brazo TLR4 — apaga la sirena, no solo cierra la puerta.

### 2. Forma REDOX de HMGB1 — VARIABLE ABIERTA (no comprometida)
- La literatura sugiere que la forma **disulfuro-HMGB1** es la que induce polarización macrofágica; la totalmente reducida (frHMGB1) no (Palumbo 2021; Yang 2022; Venereau 2012, PMID 22869893).
- **Posición del modelo:** **sin comprometerse todavía.** Qué forma de HMGB1 arrastra la endotoxina en el escenario *in vivo* de daño tisular queda como **variable a testar**, no como supuesto cerrado. Es una pregunta abierta fértil.

### 3. Es inflamación **crónica no resuelta**, no "inflamación" a secas
- "Inflamación → cáncer" es cierto SOLO para inflamación **crónica, persistente, no resuelta**. La inflamación aguda M1 que se resuelve puede ser **protectora**.
- **⚠️ Aviso oncológico:** en el nicho tumoral, M1 es **anti-tumoral** y M2 es **pro-tumoral** (se invierte la lectura). La distinción crítica: crónica/no resuelta vs aguda/resuelta — el corazón de esta línea.

---

## Veredicto global del mecanismo

| Eslabón | Estado | Modelo | PMID |
|--------|--------|--------|------|
| 1. Daño libera HMGB1; arrastra endotoxina (caballo de Troya) | 🟢 | in vitro + in vivo | 19414536, 30314759 |
| 2. Complejo engancha TLR4 + RAGE | 🟢 | **in vivo** (sepsis) | 30314759, 34071440 |
| 3. Reprograma macrófago a NO RESOLUTIVO | 🟡 (nuclear) | in vitro + síntesis | 34071440, 35740904, 20303877 |
| 4. Genera proliferación/cáncer | 🟢 | **in vivo** (carcinogénesis) | 23504974 |
| 5. Bloquear el eje frena el cáncer | 🟢 | **in vivo** (tumor) | 38646639, 32800556 |

**Lectura:** cadena con evidencia in vivo en los puntos decisivos (Deng 2018 para entrada, Pusterla 2013 para proliferación, Huang 2024 para bloqueo terapéutico). El **eslabón 3 (no resolutivo)** es el nuclear y original: el carácter inflamatorio está demostrado, el "no resolutivo" es la síntesis integradora que define esta línea.

---

## ⚠️ Extrapolaciones a NO asumir

1. **"Todo entra por RAGE"** — ❌ El LPS libre también señaliza directamente vía **TLR4/MD2** sin HMGB1. RAGE es la vía del complejo HMGB1·LPS, no la única del LPS.
2. **"Cualquier HMGB1 reprograma"** — 🔴 Variable abierta: la forma redox importará, pero no está comprometida en el modelo. Queda por testar.
3. **"Inflamación = cáncer"** — ❌ Solo la **crónica no resuelta**. La aguda puede ser protectora.
4. **"Bloquear HMGB1 cura el cáncer"** — 🔴 Huang 2024 es **preclínico** (ratón), en un sistema farmacológico de nanopartícula (IL4R-Abx). No es terapia validada en humanos.

---

## Conexiones

- [[Eje HMGB1-RAGE]] — mecanismo matriz (esta nota profundiza sus eslabones 3–5)
- [[Trimebutina]] — bloquea el brazo TLR4/IRAK1 (precisión 1)
- [[Hipótesis/Inhibicion vertical trifarmaco HMGB1-RAGE]] — el eslabón del macrófago reprogramado + la ventana de los monocitos (fricción resuelta)
- [[Índice|← Índice del vault]]

---

## Fuentes verificadas (PMID · revista · año)

1. Bianchi ME. *HMGB1 loves company.* **J Leukoc Biol. 2009;86(3):573-6.** PMID: **19414536**
2. Deng M et al. *The Endotoxin Delivery Protein HMGB1 Mediates Caspase-11-Dependent Lethality in Sepsis.* **Immunity. 2018;49(4):740-753.e7.** PMID: **30314759** — *caballo de Troya / piroptosis aguda*
3. Meng M et al. *HMGB1–lipid IVa/LA complex → RIPK3/TRIF.* **J Biol Chem. 2019.** PMID: **31000631**
4. Venereau E et al. *Mutually exclusive redox forms of HMGB1.* **J Exp Med. 2012;209(9):1519-28.** PMID: **22869893**
5. Palumbo R et al. *Disulfide and Fully Reduced HMGB1 Induce Different Macrophage Polarization.* **Biomolecules. 2021;11(6):800.** PMID: **34071440**
6. Yang et al. *Transcriptomic Profiling Reveals That HMGB1 Induces Macrophage Polarization Different from Classical M1.* **Biomolecules. 2022;12(6):779.** PMID: **35740904**
7. Pusterla T et al. *RAGE is a key regulator of inflammation-associated liver carcinogenesis.* **Hepatology. 2013;58(1):363-73.** PMID: **23504974**
8. Huang et al. *IL4R targeting enables nab-paclitaxel to enhance reprogramming of M2-type macrophages via ROS-HMGB1-TLR4 axis.* **Theranostics. 2024;14(6):2605-2621.** PMID: **38646639** — *prueba experimental del eslabón 5*
9. Kida Y et al. *HMGB1 induces bone destruction via RAGE and TLR4.* **BBRC. 2020;533(4):1413-9.** PMID: **32800556**
10. Nathan C, Ding A. *Nonresolving inflammation.* **Cell. 2010;140(6):871-82.** PMID: **20303877**

> Citas verificadas vía NCBI E-utilities (PubMed) el 2026-06-24.
