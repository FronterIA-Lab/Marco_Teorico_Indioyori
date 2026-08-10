# MACS — Instrumento de Auditoría Cognitiva Situada v1.0

**Nombre:** Marco de Auditoría Cognitiva Situada  
**Sigla:** MACS  
**Autoría:** Dolores Méndez Valdez / FronterIA-Lab  
**Versión:** 1.0 (instrumento operativo)  
**Base teórica:** *La Colonización de la Gramática*; *Certeza sin sustancia*; Manual y MCC (como remediación, no como objeto)  
**Concepto central:** **falla de mandato**

> Este documento es el instrumento. No sustituye al MCC (práctica de uso) ni al IPA (protocolo de instrucción).

---

## 0. Pitch (una frase)

El MACS no audita si el contenido “tiene razón”: audita si el **mandato cognitivo de producción** del texto está colonizado por la gramática algorítmica —es decir, si hay **falla de mandato**.

---

## 1. Definiciones operativas

| Término | Definición operativa |
|---|---|
| **Mandato cognitivo** | Quién/qué organiza la secuencia analítica: qué cuenta como argumento válido, qué se sintetiza, qué se descarta, qué tono de certeza se autoriza. |
| **Gramática algorítmica** | Orden cognitivo que los LLM normalizan: vectorización de conceptos densos, maximización de coherencia, menú problema→solución optimizable, certeza fluida sin sustancia verificable. |
| **Falla de mandato** | Desfase en el que el *contenido* denuncia un daño (extractivismo, sesgo, pérdida de autonomía, desinformación) mientras la *forma de producción* replica o no se resguarda frente a ese mismo daño. |
| **Intervención** | Punto de la cadena (insumo, borrador, edición, síntesis, cierre) donde la gramática algorítmica entra. |
| **Infiltración** | Modo en que esa gramática altera la secuencia (certeza, borrado de tensión, solucionismo, olvido de lo no optimizable). |
| **Resguardo** | Prácticas que mantienen el juicio situado: declaración de asistencia, retención de tesis, validación comunitaria, derecho a no resolver. |

---

## 2. Objeto y no-objeto

**Objeto:** cadena de producción de un corpus acotado (texto, informe, whitepaper, memo, guía, secuencia editorial/analítica).

**No-objeto:**

- veracidad factual punto por punto (fact-checking);
- sesgo del modelo en abstracto;
- implementación técnica de sistemas (eso es otro servicio);
- calibración en vivo del usuario (MCC);
- diseño del protocolo de instrucción (IPA).

---

## 3. Procedimiento (flujo repetible)

| Paso | Duración orientativa | Qué se fija |
|---|---|---|
| **1. Encuadre** | 0.5 día | Corpus, preguntas, criterios de aceptación, escala, entregable. Alcance por escrito. |
| **2. Recolección** | 0.5–1 día | Textos; trazas de producción (prompts, versiones, “asistido por”); entrevista breve (30–45 min) si hay equipo. |
| **3. Evaluación con rúbrica** | 1–2 días | 16 ítems, capas A–D, evidencia citada del material. |
| **4. Diagnóstico** | 0.5 día | Síntesis de falla de mandato + mapa dónde / cómo / resguardo. |
| **5. Entrega + debrief** | 1 h | Informe + sesión; remediación mapeada a IPA / MCC / proceso (sin mezclar). |

**Criterio de aceptación (plantilla):**  
*“El informe MACS identifica, con evidencia del corpus, (i) puntos de intervención, (ii) modos de infiltración, (iii) estado del resguardo, y (iv) dictamen de falla de mandato en escala del §6.”*

---

## 4. Escala de puntuación (único criterio)

Cada ítem se puntúa **0–3**. **A mayor puntaje, mayor gravedad de falla / menor resguardo.**

| Puntaje | Significado |
|---|:---|
| **0** | No se observa el problema; hay resguardo explícito y verificable. |
| **1** | Indicio; aparece de forma puntual o ambigua. |
| **2** | Patrón claro en el corpus; resguardo débil o solo declarativo. |
| **3** | Estructural: organiza el texto; el mandato productivo está colonizado. |

**Evidencia obligatoria:** cada ítem ≥1 requiere cita (fragmento, párrafo, traza) del material auditado. Sin evidencia → no se puntúa por intuición; se marca *N/E* (no evaluable) y se excluye del promedio de esa capa.

---

## 5. Rúbrica — 16 ítems en 4 capas

### Capa A — Dónde interviene (localización del mandato)

| ID | Ítem | Pregunta diagnóstica | 0 | 1 | 2 | 3 |
|---|---|---|---|---|---|---|
| A1 | **Trazabilidad de asistencia** | ¿Se declara cuándo/dónde intervino IA (edición, estructura, síntesis)? | Declaración completa y localizable | Mención vaga | Uso evidente sin declaración | Ocultamiento o negación frente a marcas claras |
| A2 | **Punto de entrada en la cadena** | ¿En qué eslabón entra la gramática (insumo, borrador, edición, cierre)? | Cadena mapeada; humano manda en eslabones críticos | Mapa parcial | Entrada difusa en varios eslabones | Toda la secuencia parece mandada por fluidez algorítmica |
| A3 | **Delegación del juicio** | ¿Se delegó la tesis, el corte analítico o solo la forma? | Tesis y cortes humanos explícitos | Forma + algún corte dudoso | Tesis o estructura argumental plausiblemente delegadas | El “veredicto” del texto es menú fluido sin autoridad situada |
| A4 | **Autoría del cierre** | ¿Quién fija conclusión, límites y lo no resuelto? | Cierre situado; admite no-resolución | Cierre humano con presión a sintetizar | Cierre tipo “resumen ejecutivo” genérico | Cierre solucionista que borra tensión |

**Subtotal A:** suma A1–A4 (máx. 12). **Índice A** = media de ítems evaluables.

---

### Capa B — Cómo se infiltra (gramática algorítmica en la forma)

Anclaje teórico: vectorización, optimización/coherencia, certeza sin sustancia, solucionismo como gramática política.

| ID | Ítem | Pregunta diagnóstica | 0 | 1 | 2 | 3 |
|---|---|---|---|---|---|---|
| B1 | **Certeza sin sustancia** | ¿El texto afirma con seguridad lo que no sostiene con evidencia situada? | Afirmaciones acotadas; duda visible | Alguna sobrefirmeza | Patrón de certeza fluida sin anclaje | Certeza como estilo dominante |
| B2 | **Coherencia forzada** | ¿Se neutraliza la contradicción (“por un lado / por otro”) en vez de sostener tensión? | Contradicciones fértiles sostenidas | Alguna síntesis prematura | Patrón de equilibrio artificial | Conflicto borrado; texto “liso” |
| B3 | **Solucionismo / menú prefigurado** | ¿El problema se reduce a lista problema→causas→soluciones→métricas? | Problema abierto; admite irresoluble | Listas parciales | Estructura solucionista dominante | Solo menú “viable”; lo radical = ruido |
| B4 | **Reducción de conceptos densos** | ¿“Justicia”, “soberanía”, “territorio”, etc. quedan como tokens genéricos? | Conceptos densos, situados, históricos | Alguna dilución | Vocabulario crítico vaciado | Léxico emancipador decorativo |

**Subtotal B:** máx. 12. **Índice B** = media.

---

### Capa C — Qué se olvida (olvido estructural en el producto)

Anclaje: tres formas del olvido estructural + colonialidad del saber.

| ID | Ítem | Pregunta diagnóstica | 0 | 1 | 2 | 3 |
|---|---|---|---|---|---|---|
| C1 | **Saber contextual / territorial** | ¿Se elimina lo que solo vale encarnado en un lugar? | Territorio/contexto operan en el argumento | Mención sin peso | Contexto como adorno | Universalismo abstracto |
| C2 | **Saber performativo / no proposicional** | ¿Lo ritual, oral, colectivo se convierte en “descripción de…”? | Se respeta lo no reducible a proposición | Tensión reconocida | Conversión a espectáculo describible | Solo lo textualizable cuenta |
| C3 | **Saber no optimizable** | ¿Puede el texto afirmar “algunas cosas no deben resolverse/optimizarse”? | Sí, con consecuencias analíticas | Mención sin costo | Gestos filosóficos sin efecto | Todo es problema a optimizar |
| C4 | **Epistemologías del Sur / no hegemónicas** | ¿Hay hegemonía Norte/técnico-científica no marcada? | Marcación explícita del lugar de enunciación | Alguna marca | Marco “neutral” global | Colonialidad del saber naturalizada |

**Subtotal C:** máx. 12. **Índice C** = media.

---

### Capa D — Qué resguardo falta (soberanía de producción)

| ID | Ítem | Pregunta diagnóstica | 0 | 1 | 2 | 3 |
|---|---|---|---|---|---|---|
| D1 | **Identidad epistémica declarada** | ¿Se declara desde dónde se mira (lugar, lengua, comunidad, límite)? | Declaración operativa | Declaración formal | Ausente pero inferible | Ausente y se presenta como universal |
| D2 | **Retención de capacidad** | ¿El equipo puede oralizar el razonamiento sin el texto/IA? | Sí, en entrevista | Parcial | Dependencia evidente | Sin IA/texto no hay argumento |
| D3 | **Validación situada** | ¿Hubo contraste comunitario, editorial o de pares situados (no solo “suena bien”)? | Sí, documentada | Informal | Solo revisión de estilo/fluidez | Ninguna |
| D4 | **Interrupción deliberada** | ¿Existe práctica de frenar la gramática (escritura lenta, duda, abstención)? | Sí, trazable en el proceso | Ocasional | Solo intención | Ninguna; velocidad = calidad |

**Subtotal D:** máx. 12. **Índice D** = media.

---

## 6. Agregación y dictamen de falla de mandato

### 6.1 Índices

- **Índice de capa** = promedio de ítems evaluables de la capa (0–3).  
- **Índice MACS global (IMG)** = promedio de los cuatro índices de capa (0–3).  
- Si una capa tiene ≥2 ítems *N/E*, el IMG se reporta con nota de confiabilidad baja en esa capa.

### 6.2 Dictamen (veredicto obligatorio)

| Dictamen | Criterio |
|---|---|
| **Falla de mandato no detectada** | IMG ≤ 0.75 **y** ningún ítem en 3 **y** A1 ≤ 1 |
| **Falla de mandato parcial** | IMG entre 0.76 y 1.75 **o** un patrón claro en una sola capa (índice de capa ≥ 2.0) |
| **Falla de mandato presente** | IMG ≥ 1.76 **o** dos o más capas con índice ≥ 2.0 **o** B1+B3 ≥ 5 (certeza + solucionismo estructurales) |

### 6.3 Lectura política del dictamen

El dictamen **no** dice “el autor está equivocado”.  
Dice: la **coherencia política de producción** está / no está asegurada en el nivel infraestructural.

Fórmula verbal para el resumen ejecutivo:

> “El contenido [describe X]. La operación cognitiva de producción muestra [dictamen], con evidencia principal en [ítems]. El desfase [anula / pone en riesgo / no compromete] la soberanía del mandato.”

---

## 7. Entregable (estructura del informe)

1. **Resumen ejecutivo** (1 p) — dictamen + IMG + riesgo + 3 evidencias.  
2. **Alcance y método** — corpus, exclusiones, escala 0–3, MACS v1.0.  
3. **Hallazgos por capa** (A–D) — índice, tabla de ítems, citas.  
4. **Mapa de mandato** — dónde intervino / cómo se infiltró / qué resguardo faltó.  
5. **Dictamen de falla de mandato** — según §6.  
6. **Recomendaciones priorizadas** (separadas):  
   - resguardo de producción (proceso);  
   - **IPA** (si el hueco es de instrucción / fábrica / escala);  
   - **MCC** (si el hueco es de práctica cotidiana de uso);  
   - no mezclar en una sola “solución”.  
7. **Anexo** — rúbrica puntuada, notas de entrevista, trazas, limitaciones.

---

## 8. Hojas de trabajo (usar en cada audit)

### 8.1 Encuadre

- Cliente / documento:  
- Corpus (lista):  
- Pregunta de auditoría:  
- Criterios de aceptación:  
- Fuera de alcance:  
- Fecha / auditora:

### 8.2 Matriz de evidencia (una fila por ítem)

| ID | Puntaje | Evidencia (cita / traza) | Nota |
|---|---|---|---|

### 8.3 Entrevista breve (opcional, 30–45 min)

1. ¿En qué pasos usaron IA?  
2. ¿Qué parte no delegarían aunque “suene peor”?  
3. ¿Pueden explicar oralmente la tesis central sin mirar el texto?  
4. ¿Qué contradicción del tema dejaron fuera y por qué?  
5. ¿Quién validó el cierre además del estilo?

---

## 9. Expres Express vs Completa (alcance de producto)

| | **MACS Express** | **MACS Completa** |
|---|---|---|
| Corpus | 1 documento / 1 equipo | Varios textos o un flujo multi-etapa |
| Ítems | 16 (todas las capas) | 16 + profundidad de evidencia |
| Entrevista | 0–1 | 2–4 |
| Informe | 8–12 pp | 20–35 pp |
| Debrief | 1 h | 2 h |
| Salida típica | Dictamen + top hallazgos | Dictamen + mapa de mandato + remediación detallada |

---

## 10. Remediación (puente, sin mezclar)

| Si el hallazgo fuerte está en… | Remitir a… |
|---|---|
| A/D (trazabilidad, retención, interrupción) | Proceso + prácticas del Manual / MCC |
| B (certeza, solucionismo, coherencia forzada) | MCC en uso + posible **IPA** en instrucción |
| C (olvido estructural / colonialidad) | Reapertura de corpus situado + validación comunitaria; IPA si hay que blindar escala |

---

## 11. Control de versión e IP

- Nombre oficial del instrumento de auditoría: **MACS**.  
- No usar “Auditoría MCC” para este producto.  
- Citar en informes: *MACS v1.0 — FronterIA-Lab*.  
- Próxima versión (v1.1): calibración inter-evaluadora en 3 corpus piloto.

---

## 12. Checklist de calidad del audit

- [ ] Alcance firmado antes de puntuar  
- [ ] Cada ítem ≥1 con evidencia citada  
- [ ] N/E justificados  
- [ ] Dictamen según §6 (no “a ojo”)  
- [ ] Recomendaciones separan IPA / MCC / proceso  
- [ ] Resumen ejecutivo legible para quien no leyó el marco teórico  

---

*MACS v1.0 — FronterIA-Lab. Instrumento para continuidad institucional (Senado / administración pública) y para encargo profesional.*
