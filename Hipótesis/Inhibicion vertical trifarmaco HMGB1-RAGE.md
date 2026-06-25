---
tipo: hipotesis
eje: HMGB1/RAGE
linea: inflamacion-no-resolutiva
nodos: [liberacion, ligando-libre, senal-intracelular]
farmacos: [piruvato-de-etilo, metformina, trimebutina]
original: si
fecha: 2026-06-24
---

# 💡 Hipótesis: Inhibición vertical del eje HMGB1/RAGE con tres fármacos reposicionados

> **Línea de investigación del vault:** inflamación no resolutiva → falla del macrófago por endotoxemia → cáncer/procesos proliferativos. Esta hipótesis reformula la intuición de combinar tres fármacos como una predicción **testeable**, no como un hecho establecido.

---

## Enunciado

**Si** se combina (1) **piruvato de etilo** (bloquea la liberación de HMGB1) + (2) **metformina** (une HMGB1 libre y bloquea HMGB1/RAGE) + (3) **trimebutina** (corta la señal intracelular RAGE→ERK1/2 + TLR2/4/7/8/9),

**entonces** la inhibición simultánea de los tres nodos del eje será **sinérgica** (mayor que la suma de los efectos individuales) en reducir la inflamación no resolutiva y la proliferación patológica del macrófago endotóxico,

**porque** los tres actúan en niveles **no redundantes** del mismo eje, taponeando liberación → ligando libre → señal intracelular.

---

## El mapa de la tríada (inhibición vertical)

```
NIVEL ① LIBERACIÓN    ← PIRUVATO DE ETILO  retiene HMGB1 en núcleo + NF-κB↓ + HO-1↑
         ↓
NIVEL ② HMGB1 LIBRE   ← METFORMINA         une HMGB1 directo + ↓RAGE + ↓AGE + AMPK
         ↓
NIVEL ③ SEÑAL INTRA   ← TRIMEBUTINA        bloquea RAGE→ERK1/2→JNK→NF-κB + TLR vía IRAK1
```

Convergencia clave: **metformina y trimebutina hacen "pinza vertical" sobre ERK** — la metformina arriba (HMGB1/RAGE), la trimebutina abajo (RAGE→ERK). ERK1/2 es a la vez el cable inflamatorio Y el cable proliferativo (Ciclina D1) → diana doble.

---

## Eslabones especulativos de los que nace (graduados)

### 🟢 Lo que SÍ está demostrado (cada fármaco por separado)
- Cada uno golpea un nodo distinto y verificado del eje. → [[Mecanismos/Eje HMGB1-RAGE]]
- Los tres reducen HMGB1/inflamación en modelos preclínicos. → [[Mecanismos/Piruvato de etilo]]
- Brazo antiproliferativo individual documentado: EP en linfoma DLBCL (Cell Death Dis 2019, PMID 30988279); metformina en cáncer triple-negativo (Cells 2025, PMID 40277915); trimebutina en glioma (Front Pharmacol 2018, PMID 29977208).

### 🔴 Eslabón crítico 1 — La sinergia de los tres NO está probada
- **No existe ni un solo estudio** que haya probado la combinación de dos de estos fármacos, y mucho menos los tres. La no-redundancia mecanística hace la sinergia **plausible**, no **demostrada**.
- Advertencia histórica: combinaciones anti-citoquina con lógica similar ("taponear múltiples niveles") fracasaron en clínica de sepsis.

### 🔴 Eslabón crítico 2 — Supresión ≠ resolución (el punto más peligroso del modelo)
- Tu objetivo es **resolver** la inflamación (reprogramar el macrófago hacia fenotipo resolutivo), no solo **suprimirla**.
- Los tres fármacos son **supresores** de HMGB1/inflamación. **Ninguno está demostrado que impulse RESOLUCIÓN** (muerte limpia + eferocitosis, o switch fenotípico).
- La literatura afilada (Davan-Wetton et al., Cell Mol Life Sci 2021, PMID 33439271) advierte: los programas de muerte/senescencia son **pro-resolutivos por naturaleza**; la patología viene del fallo en COMPLETARlos o limpiarlos. Bloquear piroptosis/inflamación **sin resolver el estímulo** puede empujar al macrófago al **limbo no resolutivo** — justo lo que se quiere evitar.
- Caso específico de la trimebutina: su diana **IRAK1 se degrada durante la tolerancia a endotoxina** (parte de lo que hace al macrófago tolerante/inmunosuprimido, PICS). Inhibir IRAK1/NF-κB de forma sostenida **podría MANTENER** ese estado de limbo, no resolverlo. → [[Mecanismos/Trimebutina]]

---

## Tensión filosófica central del modelo

| Objetivo | ¿Lo cumplen los 3 fármacos? |
|----------|------------------------------|
| A. Suprimir inflamación/HMGB1 | ✅ Sí (los tres, preclínicamente) |
| B. Resolver (reprogramar macrófago a fenotipo resolutivo) | 🔴 **Ninguno demostrado** |

**De aquí nace la hipótesis derivada más fértil** (ver abajo): la tríada óptima no es "tres supresores", sino **supresión + pro-resolutor**.

---

## Hipótesis derivada (testeable y original)

> **H-d**: La sinergia óptima para la inflamación no resolutiva es **EP + trimebutina (supresión del daño) + un pro-resolutor** (¿metformina vía AMPK?, ¿resolvinas/lipoxinas/SPM?), donde el tercer componente impulsa el *switch de fenotipo*, no más supresión.

---

## Cómo se testaría

- **Modelo:**
  - In vitro: macrófagos (RAW264.7 / BMDM) estimulados con LPS (endotoxemia) → medir no-resolución.
  - In vivo: modelo de endotoxemia/sepsis subaguda en ratón (donde el bucle no resolutivo persiste, no la fase aguda).
- **Diseño factorial 2×2×2:** EP ±, metformina ±, trimebutina ± (8 grupos) → detecta **interacción/sinergia** estadística (no solo efecto individual).
- **Lecturas experimentales:**
  - De supresión: HMGB1 sérico/citoplasmático, NF-κB, IL-6/IL-1β, ERK1/2.
  - De resolución (las que importan para tu modelo): **eferocitosis** (macrófago fagocitando células apoptóticas), **switch M1→M2/pro-resolutivo** (iNOS↓/Arg1↑, o CD206, resolvinas), mortalidad tardía (no solo aguda).
  - Proliferación: Cyclin D1, Ki-67 en nicho tumoral/tejido.
- **Control crítico:** un grupo con los tres supresores + medir explícitamente si el macrófago queda en **limbo no resolutivo** (baja muerte + baja eferocitosis + señalización suprimida).

## Predicción que la FALSARÍA

1. Si la combinación triple **reduce HMGB1 e IL-6 pero NO mejora la eferocitosis ni el switch pro-resolutivo** (o lo empeora), la hipótesis de sinergia "beneficiosa" queda **refutada** — confirmaría que supresión ≠ resolución.
2. Si en el diseño factorial la interacción 2×2×2 **no es significativa** (efecto combinado ≈ suma de individuales), no hay sinergia real, solo aditividad.
3. Si la trimebutina, a pesar de ↓IRAK1, **profundiza la tolerancia/PICS** (macrófago en coma no resolutivo), queda refutado su papel como "resolutor".

---

## ⚠️ Límite de traslación (debero ético)

- Los tres fármacos son **preclínicos como anti-HMGB1** (EP incluso refutado en clínica: PMID 18835526). La combinación no tiene **ninguna** evidencia de seguridad/eficacia en humanos.
- Si esta hipótesis se mueve hacia uso off-label, el camino correcto es un **registro observacional con biomarcadores seriados** (HMGB1/sRAGE séricos, recuentos fenotípicos macrofágicos), NO administración empírica.
- PK de la trimebutina como antitumoral sistémico es frágil (metabolismo ultrarrápido, ~1,7% intacto a 60 min, sin acumulación tumoral; Lin, Nucl Med Biol 2025, PMID 39662136) → su valor oncológico puede ser como **andamiaje químico** (derivado 7M3TMSC), no como fármaco.

---

## Conexiones

- [[Mecanismos/Eje HMGB1-RAGE]] — mecanismo matriz
- [[Mecanismos/Piruvato de etilo]] — nivel ① (liberación)
- [[Mecanismos/Trimebutina]] — nivel ③ (señal intracelular) + brazo TLR en macrófago
- [[Mecanismos/Metformina]] — nivel ② (HMGB1 libre) — pendiente de crear
- [[Índice|← Índice del vault]]

---

## Fuentes verificadas (PMID · revista · año)

**Trimebutina:** 33041002 (BBRC 2020) · 34111666 (BBRC 2021) · 34517011 (Arch Biochem Biophys 2021) · 38802470 (Sci Rep 2024) · 29977208 (Front Pharmacol 2018, glioma) · 39662136 (Nucl Med Biol 2025, PET/PK)
**Piruvato de etilo:** 12209006 (PNAS 2002) · 19454652 (J Leukoc Biol 2009) · 30728013 (Respir Res 2019) · 31072024 (J Clin Med 2019) · 34066647 (Antioxidants 2021) · 31862934 (Sci Rep 2019) · 30988279 (Cell Death Dis 2019, DLBCL) · 18835526 (J Cardiothorac Vasc Anesth 2009, RCT negativo)
**Metformina:** 40277915 (Cells 2025, TNBC) · 41977331 (Int J Mol Sci 2026, C-terminal) · 28255209 (Int J Angiol 2017, AGE) · 31818258 (BMC Infect Dis 2019, TB-DM observacional)
**Eje / resolución:** 23504974 (Hepatology 2013, Pusterla) · 20303877 (Cell 2010, Nathan&Ding) · 33439271 (Cell Mol Life Sci 2021, Davan-Wetton)

> Citas verificadas vía NCBI E-utilities (PubMed) el 2026-06-24.
