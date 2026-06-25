---
tipo: mecanismo
eje: HMGB1/RAGE
nodo: senal-intracelular
farmaco: trimebutina
reposicionamiento: si
fecha: 2026-06-24
---

# ⚙️ Mecanismo: Trimebutina → bloqueo de la señal RAGE/TLR intracelular

> La **trimebutina** es un espasmolítico gastrointestinal aprobado, reposicionado como anti-inflamatorio. A diferencia del piruvato de etilo (que bloquea la **liberación** de HMGB1) y de la metformina (que **une** HMGB1 libre), la trimebutina actúa **dentro de la célula**: corta la **señal downstream** del receptor. Es el "cortacables" del eje.

---

## Cadena de acción (graduada)

### Eslabón 1 — Bloquea la señal RAGE→ERK1/2 (intracelular)
- **Estado:** 🟢 Demostrado
- **Mecanismo:** La trimebutina **no** inhibe fuerte la unión extracelular HMGB1–RAGE (ahí es más débil que la papaverina). En cambio **bloquea fuerte el reclutamiento de ERK1/2** a la cola intracelular de RAGE → ↓JNK → ↓NF-κB → ↓citoquinas.
- **Importancia:** ERK1/2 es **a la vez el cable inflamatorio y el cable proliferativo** (→ Ciclina D1). Cortar aquí es cortar dos motores.
- **Evidencia:** Taguchi et al., *BBRC* 2020 (PMID 33041002) — RAW264.7 + BMDM. In vitro.

### Eslabón 2 — Suprime TLR2/4/7/8/9 vía IRAK1 (brazo independiente de RAGE)
- **Estado:** 🟢 Demostrado
- **Mecanismo:** Inhibe **IL-1 receptor-associated kinase 1 (IRAK1)** → ↓ERK1/2, ↓JNK, ↓NF-κB. Suprime IL-6 inducida por LPS (TLR4) y por estimulantes de TLR2/7/8/9.
- **Hallazgo decisivo para el macrófago endotóxico:** funciona **incluso en macrófagos de ratones RAGE-KO** → su brazo TLR/IRAK1 es **independiente de RAGE**. El macrófago endotóxico está impulsado sobre todo por **TLR4**, así que este brazo es el más relevante para la endotoxemia.
- **Evidencia:** *Arch Biochem Biophys* 2021 (PMID 34517011) — macrophages + in vivo.

### Eslabón 3 — Reduce mortalidad en sepsis por LPS in vivo
- **Estado:** 🟢 Demostrado (in vivo)
- **Mecanismo:** "greatly reduces mortality in a mouse model of LPS-induced sepsis" (PMID 34517011).
- **Evidencia:** In vivo, ratón. Único modelo (merece réplica en sepsis subaguda/crónica).

### Eslabón 4 — Brazo antiproliferativo (glioma)
- **Estado:** 🟡 Bien fundado
- **Mecanismo:** ↓viabilidad/colonia/migración, ↑apoptosis (↑Bax, ↓Bcl-2, ↑caspasa-3), **↓AKT y ↓ERK**; inhibe xenotumor U-87 MG in vivo.
- **Evidencia:** Fan et al., *Front Pharmacol* 2018 (PMID 29977208) — glioma (SHG44, U251, U-87 MG). In vitro + in vivo (xenotumor).

### Eslabón 5 — Efecto antiinflamatorio tópico (córnea)
- **Estado:** 🟢 Demostrado (in vivo, tejido)
- **Mecanismo:** En quemadura alcalina de córnea (rata): ↓infiltración de macrófagos/neutrófilos, ↓IL-1β, ↓fibrosis.
- **Evidencia:** *Sci Rep* 2024 (PMID 38802470). In vivo, rata.

### Eslabón 6 — Derivados cromona con inhibición dual RAGE/TLR4
- **Estado:** 🟡 Bien fundado
- **Mecanismo:** Un derivado 3-estirilcromona convertido a partir del farmacóforo 3D de la trimebutina tiene efectos supresores **duales** sobre RAGE y TLR4.
- **Evidencia:** *BBRC* 2021 (PMID 34111666). Confirma que la trimebutina es un **andamiaje químico** fértil.

---

## 💊 Fármaco reposicionado — perfil y límites

- **Origen:** espasmolítico GI aprobado (dolor abdominal tipo colon irritable). Seguridad conocida, barato.
- **Nodo del eje:** nivel ③ (señal intracelular RAGE/TLR). Complementa, NO compite, con EP (nivel ①) y metformina (nivel ②).
- **Brazo único:** el efecto **TLR/IRAK1 independiente de RAGE** la hace especialmente relevante para la **endotoxemia** (donde TLR4/LPS es el driver principal del macrófago).

### ⚠️ Límite farmacocinético (crítico para uso oncológico sistémico)
Lin et al., *Nucl Med Biol* 2025 (PMID 39662136) — PET con [¹¹C]trimebutina:
- **Metabolismo ultrarrápido:** solo ~1,7% intacto a 60 min.
- **Sin acumulación tumoral selectiva** en glioma ortotópico C6.
- **Lectura:** el efecto antitumoral es real **in vitro**, pero la molécula parental es frágil in vivo. Su valor oncológico probable = **andamiaje químico** (derivados como 7M3TMSC), no el fármaco en sí.

### ⚠️ Tensión con la hipótesis de resolución
Su diana **IRAK1 se degrada durante la tolerancia a endotoxina** (PICS). Inhibir IRAK1/NF-κB de forma sostenida **podría MANTENER** el estado de macrófago tolerante/no resolutivo en vez de resolverlo. → Ver [[Hipótesis/Inhibicion vertical trifarmaco HMGB1-RAGE]] (eslabón crítico 2: supresión ≠ resolución).

---

## Veredicto global del mecanismo

| Eslabón | Estado | Modelo | PMID |
|--------|--------|--------|------|
| 1. Bloquea RAGE→ERK1/2 (intracelular) | 🟢 | in vitro | 33041002 |
| 2. Suprime TLR2/4/7/8/9 vía IRAK1 (RAGE-indep.) | 🟢 | in vitro | 34517011 |
| 3. ↓ Mortalidad en sepsis por LPS | 🟢 | **in vivo** | 34517011 |
| 4. Antiproliferativo en glioma | 🟡 | in vitro + in vivo | 29977208 |
| 5. Antiinflamatorio tópico (córnea) | 🟢 | in vivo (rata) | 38802470 |
| 6. Andamiaje químico (derivado dual RAGE/TLR4) | 🟡 | in vitro | 34111666 |

**Lectura:** cadena de acción intracelular 🟢 demostrada, con **brazo TLR4/IRAK1 independiente de RAGE** único entre los fármacos del vault. Límites: PK frágil para uso oncológico sistémico + tensión con la resolución macrofágica.

---

## ⚠️ Extrapolaciones a NO asumir

1. **"La trimebutina resuelve la inflamación"** — ❌ Solo demuestra **supresión** de señalización. No prueba switch pro-resolutivo.
2. **"Útil como antitumoral sistémico"** — 🔴 PK frágil (PMID 39662136); valor probable como andamiaje, no como fármaco.
3. **"Equivalente a otros anti-HMGB1"** — ❌ No une HMGB1 ni bloquea su liberación; corta **aguas abajo**, dentro de la célula. Nodo distinto.
4. **Eficacia clínica como anti-HMGB1/RAGE en humanos** — 🔴 sin ensayos clínicos. Todo preclínico.

---

## Conexiones

- [[Eje HMGB1-RAGE]] — mecanismo matriz (nivel ③ de la cadena)
- [[Piruvato de etilo]] — nivel ① (complementario, no redundante)
- [[Hipótesis/Inhibicion vertical trifarmaco HMGB1-RAGE]] — la tríada vertical
- [[Índice|← Índice del vault]]

---

## Fuentes verificadas (PMID · revista · año)

1. Taguchi et al. *Trimebutine attenuates HMGB1-RAGE inflammatory signaling pathways.* **BBRC. 2020;533(3):412-9.** PMID: **33041002**
2. *A 3-styrylchromone converted from trimebutine 3D pharmacophore possesses dual suppressive effects on RAGE and TLR4 signaling pathways.* **BBRC. 2021;570:80-6.** PMID: **34111666**
3. *Trimebutine suppresses Toll-like receptor 2/4/7/8/9 signaling pathways in macrophages.* **Arch Biochem Biophys. 2021;711:109029.** PMID: **34517011**
4. Fan et al. *Trimebutine Promotes Glioma Cell Apoptosis as a Potential Anti-tumor Agent.* **Front Pharmacol. 2018;9:805.** PMID: **29977208**
5. *Trimebutine prevents corneal inflammation in a rat alkali burn model.* **Sci Rep. 2024;14(1):12109.** PMID: **38802470**
6. Lin et al. *PET imaging of the anticancer drug candidate [¹¹C]trimebutine in a rat glioma model.* **Nucl Med Biol. 2025;134-135:108948.** PMID: **39662136**

> Citas verificadas vía NCBI E-utilities (PubMed) el 2026-06-24.
