---
tipo: mecanismo
eje: HMGB1/RAGE
nodo: liberacion-de-HMGB1
farmaco: piruvato-de-etilo
reposicionamiento: si
fecha: 2026-06-24
---

# ⚙️ Mecanismo: Piruvato de etilo → supresión de HMGB1

> El **piruvato de etilo** (EP) es un éster lipófilo del ácido pirúvico. Actúa **aguas arriba** del eje HMGB1/RAGE: **bloquea la liberación de HMGB1** antes de que se secreta. Es uno de los supresores de HMGB1 con evidencia preclínica más robusta — pero con un **límite de traslación crítico** (ver sección final).

---

## Cadena de supresión (graduada)

### Eslabón 1 — EP bloquea la translocación nuclear → citoplasmática de HMGB1
- **Estado:** 🟢 Demostrado
- **Mecanismo:** Para que HMGB1 se secretara, debe salir del núcleo al citoplasma. EP **retiene a HMGB1 en el núcleo**, impidiendo ese primer paso.
- **Evidencia:** Davé et al., *J Leukoc Biol* 2009 (PMID 19454652) — colitis murina IL-10⁻/⁻ + macrófagos LPS; Bhat et al., *Respir Res* 2019 (PMID 30728013) — epitelio respiratorio BEAS-2B. **In vitro + in vivo** (ratón/rata).

### Eslabón 2 — EP inhibe p38 MAPK y NF-κB
- **Estado:** 🟢 Demostrado
- **Mecanismo:** EP inhibe específicamente la activación de **p38 MAPK** y **NF-κB** → bloquea la transcripción de citoquinas y la señal que ordena secretar HMGB1.
- **Matiz fino (importante):** EP **no bloquea la translocación nuclear de NF-κB**; atenúa su **unión al DNA** (Davé 2009). Actúa aguas abajo del paso nuclear.
- **Evidencia:** **Ulloa, Yang, Tracey & Fink**, *PNAS* 2002 (PMID 12209006) — macrófagos. **Artículo fundacional** del EP como anti-HMGB1.

### Eslabón 3 — EP induce HO-1 (causal) + es scavenger directo de ROS
- **Estado:** 🟢 Demostrado
- **Mecanismo:** EP induce **HO-1 (hemo oxigenasa-1)**, y ese aumento es **causal**: al bloquear HO-1 con ZnPP, el efecto supresor de EP desaparece (Seo 2019).
- **Brazo paralelo (química):** el piruvato **neutraliza H₂O₂** directamente. Cinética confirmada en condiciones biológicas por Guarino et al., *Sci Rep* 2019 (PMID 31862934).
- **Evidencia:** Davé 2009 (PMID 19454652); Seo et al., *J Clin Med* 2019 (PMID 31072024) — células tubulares renales en isquemia/reperfusión.

### Eslabón 4 — EP reduce HMGB1 circulante y mejora supervivencia in vivo
- **Estado:** 🟢 Demostrado (in vivo, múltiples modelos)
- **Hallazgo estrella:** Ulloa 2002 — tratamiento iniciado **24 h DESPUÉS** de la perforación cecal (sepsis ya establecida) → supervivencia **30% → 88%**, con caída de HMGB1 sérico.
- **Replicaciones:** colitis (Davé 2009); pulmón por polvo orgánico (Bhat 2019); neuroinflamación (Olcum 2021).

### Eslabón 5 — EP atenúa el inflamasoma NLRP3 vía HMGB1/NF-κB
- **Estado:** 🟡 Bien fundado
- **Mecanismo:** EP ↓ caspasa-1 activa, IL-1β, IL-18. Conecta el eje HMGB1 con la **piroptosis/inflamasoma**.
- **Evidencia:** Olcum et al., *Antioxidants* 2021 (PMID 34066647) — microglía. Un solo grupo; merece réplica.

### Eslabón 6 — El descenso de HMGB1 se traduce en beneficio clínico
- **Estado:** 🔴 Extrapolación **REFUTADA** por ensayo clínico
- **Evidencia:** Bennett-Guerrero et al., fase II, *J Cardiothorac Vasc Anesth* 2009 (PMID 18835526). Ver sección 💊 abajo.

---

## 💊 Fármaco reposicionado con límite de traslación

> Esta sección es el corazón de la nota: **por qué el EP es un candidato elegante que NO cuajó en clínica — y qué nos enseña.**

### El estatus de reposicionamiento

- El **piruvato de etilo** es un derivado del ácido pirúvico, usado históricamente como **estabilizante en soluciones de perfusión** (Ringer-piruvato). Su perfil de seguridad en humanos era conocido, lo que lo hacía un candidato ideal de reposicionamiento como antiinflamatorio.
- Diana: un **mediador tardío** (HMGB1), no los tempranos (TNF, IL-1) que ya habían fracasado. La lógica de Ulloa/Tracey era sólida: el HMGB1 llega horas después del pico inicial → ventana terapéutica más amplia → "rescate" posible.

### El ensayo clínico que frenó todo

**Bennett-Guerrero et al., fase II (PMID 18835526)** — cirugía cardíaca de alto riesgo:
- **Diseño:** doble ciego, randomizado, placebo-controlado, **13 hospitales US**, 102 pacientes.
- **Dosis:** 90 mg/kg × 6 dosis (supera la dosis efectiva animal de 40 mg/kg).
- **Resultado:** *"no statistically significant differences… EP does not appear to confer any benefit."* Ninguna diferencia clínica ni en marcadores inflamatorios sistémicos.

### ⚠️ Lectura crítica (lo que SÍ y lo que NO refuta)

| Lo que el ensayo NO refuta | Lo que SÍ refuta |
|---|---|
| Que EP baje HMGB1 en humanos | Que ese descenso → beneficio clínico medible |
| El mecanismo molecular (eslabones 1–4) | La diana única HMGB1 como suficiente en clínica |
| El efecto preclínico en otros modelos | El contexto de **cirugía cardíaca programada** (IR aguda y breve) |

**Matiz decisivo:** el ensayo **NO midió HMGB1 sérico** como endpoint; midió muerte/ventilación/renal/vasoconstrictores a 28 días. Así que **no prueba que EP falle en bajar HMGB1 en humanos** — prueba que ese descenso, *en ese contexto*, no se traduce en mejoría.

### Por qué fracasó la traslación (3 hipótesis)

1. **Modelo inadecuado.** Cirugía cardíaca programada = isquemia/reperfusión aguda, breve y estereotipada. El daño es distinto al de la **sepsis polimicrobiana** o la **inflamación crónica no resolutiva** (tu tema). Generalizar de "funciona en sepsis murina" a "funciona en IR cardíaca" fue un salto optimista.
2. **Diana única ≠ resolución.** El eje HMGB1/RAGE es probablemente **necesario pero no suficiente**. Bajar HMGB1 sin resolver el estímulo inicial ni cambiar el fenotipo macrofágico (Nathan & Ding 2010) no cierra el bucle. Encaja con el **patrón universal de fracaso terapéutico en sepsis** (anti-TNF, anti-LPS, Xigris...).
3. **Ventana y PK.** 6 dosis en 30 h cubren la fase aguda, pero el HMGB1 que mata es el **tardío y persistente** (el "mediador tardío" de Wang 1999). Quizás la duración fue insuficiente.

### El punto débil estratégico (para tu línea)

El ensayo negativo NO se hizo en **inflamación crónica no resolutiva** — que es donde el bucle HMGB1/RAGE realmente sostiene la enfermedad. Ahí **no hay datos clínicos**. Esto es una **laguna**, no una refutación para tu marco. → ver [[Hipótesis/_Índice de hipótesis|Hipótesis]].

---

## Veredicto global del mecanismo

| Eslabón | Estado | Modelo | PMID |
|--------|--------|--------|------|
| 1. Bloquea translocación núcleo→cito de HMGB1 | 🟢 | in vitro + in vivo | 19454652, 30728013 |
| 2. Inhibe p38 MAPK + unión NF-κB al DNA | 🟢 | in vitro + in vivo | 12209006 |
| 3. Induce HO-1 (causal) + scavenger de H₂O₂ | 🟢 | in vitro + in vivo | 19454652, 31072024, 31862934 |
| 4. ↓ HMGB1 sérico + ↑ supervivencia (sepsis) | 🟢 | **in vivo** | 12209006 |
| 5. ↓ NLRP3 inflamasoma vía HMGB1 | 🟡 | in vitro (microglía) | 34066647 |
| 6. Beneficio clínico en humanos | 🔴 **REFUTADO** | **clínico fase II** | 18835526 |

**Lectura:** la **cadena de supresión (1→4) está sólidamente demostrada**. EP es un supresor de HMGB1 genuino. El **corte de traslación** ocurre en el eslabón 6: el descenso de HMGB1 no se traduce en beneficio clínico medible, al menos en cirugía cardíaca.

---

## ⚠️ Extrapolaciones a NO asumir

1. **"EP cura la inflamación clínica"** — ❌ Refutado en cirugía cardíaca (PMID 18835526). No hay ensayo positivo en humanos.
2. **"El ensayo negativo descarta utilidad en inflamación crónica"** — 🔴 No se probó en ese contexto. Extrapolación en ambos sentidos es injustificada.
3. **"EP es equivalente a otros anti-HMGB1"** — ❌ Diflunisal y metformina **unen HMGB1 directamente**; el EP actúa **aguas arriba** (bloquea su liberación). Distinto nodo, distinta lógica.
4. **Evidencia preclínica = evidencia clínica** — ❌ La brecha eslabón 4→6 es el ejemplo de manual de este vault.

---

## Conexiones

- [[Eje HMGB1-RAGE]] — el mecanismo matriz al que este fármaco apunta (eslabón de liberación)
- [[Papers/_Índice de papers|Índice de papers]] — nota del ensayo clínico negativo: [[Papers/Bennett-Guerrero 2009 - ensayo clinico negativo]]
- [[Hipótesis/_Índice de hipótesis|Hipótesis]] — pendiente: "¿en qué subgrupo/contexto el descenso de HMGB1 por EP SÍ importa clínicamente?"
- Comparar con otros anti-HMGB1: ácido anacárdico (↓ liberación vía HAT), diflunisal (une HMGB1), trimebutine (bloquea RAGE→ERK) — pendientes
- [[Índice|← Índice del vault]]

---

## Fuentes verificadas (PMID · revista · año)

1. Ulloa L, Ochani M, Yang H, et al. *Ethyl pyruvate prevents lethality in mice with established lethal sepsis and systemic inflammation.* **Proc Natl Acad Sci USA. 2002;99(19):12351-6.** PMID: **12209006** — *fundacional*
2. Davé SH, Tilstra JS, Matsuoka K, et al. *Ethyl pyruvate decreases HMGB1 release and ameliorates murine colitis.* **J Leukoc Biol. 2009;86(3):633-43.** PMID: **19454652**
3. Bhat SM, Massey N, Karriker LA, et al. *Ethyl pyruvate reduces organic dust-induced airway inflammation by targeting HMGB1-RAGE signaling.* **Respir Res. 2019;20(1):27.** PMID: **30728013**
4. Seo MS, Kim HJ, Kim H, Park SW. *Ethyl Pyruvate Directly Attenuates Active Secretion of HMGB1 in Proximal Tubular Cells via Induction of Heme Oxygenase-1.* **J Clin Med. 2019;8(5):629.** PMID: **31072024**
5. Olcum M, Tufekci KU, Durur DY, et al. *Ethyl Pyruvate Attenuates Microglial NLRP3 Inflammasome Activation via Inhibition of HMGB1/NF-κB/miR-223 Signaling.* **Antioxidants (Basel). 2021;10(5):745.** PMID: **34066647**
6. Guarino VA, Oldham WM, Loscalzo J, Zhang YY. *Reaction rate of pyruvate and hydrogen peroxide: assessing antioxidant capacity of pyruvate under biological conditions.* **Sci Rep. 2019;9(1):196.** PMID: **31862934**
7. Bennett-Guerrero E, Swaminathan M, Grigore AM, et al. *A phase II multicenter double-blind placebo-controlled study of ethyl pyruvate in high-risk patients undergoing cardiac surgery with cardiopulmonary bypass.* **J Cardiothorac Vasc Anesth. 2009;23(3):324-9.** PMID: **18835526** — *ensayo clínico negativo*

> Citas verificadas vía NCBI E-utilities (PubMed) el 2026-06-24. Primer autor confirmado en cada caso.
