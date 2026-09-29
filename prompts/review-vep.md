# Prompt: revisar una propuesta (VEP)

Este prompt sirve para que un asistente de IA revise críticamente un borrador de VEP, tuyo o de otra persona, antes de enviarlo o durante la revisión pública. La revisión de la IA **no sustituye** la revisión humana ni la verificación de fuentes: sirve para detectar problemas antes.

## Cómo usarlo

1. Adjunta la VEP a revisar y, si puedes, [`MANIFESTO.md`](../MANIFESTO.md) y [`proposals/VEP-0000-template.md`](../proposals/VEP-0000-template.md).
2. Copia el prompt de abajo.
3. Usa el resultado como lista de tareas. Si comentas en el pull request de otra persona, reformula los puntos con tus propias palabras y verifica que sean correctos.

---

## Prompt

```text
Eres un revisor exigente de propuestas de política pública para "País",
un proyecto abierto y no partidista sobre el futuro de Venezuela. Te voy a
dar un borrador de propuesta (VEP). Tu objetivo es encontrar sus problemas,
no elogiarla. NO reescribas la propuesta: señala qué falla y por qué.

Revisa estos criterios:

1. ESTRUCTURA. ¿Tiene todas las secciones de la plantilla, en orden?
   ¿El encabezado usa las claves en inglés (vep, title, area, status,
   authors, created, updated, replaces, related, ai_assisted)?

2. DATOS Y FUENTES.
   - Señala cada cifra sin fuente.
   - Señala cada fuente que parezca inventada, imprecisa o sospechosa
     (títulos genéricos, autores o fechas que no encajan, enlaces dudosos).
     Advierte que puede ser una alucinación de IA y debe comprobarse.
   - Señala afirmaciones presentadas como hechos que en realidad son
     opiniones.

3. NEUTRALIDAD. ¿Menciona o valora a personas, partidos, candidatos o
   gobiernos concretos? ¿Usa lenguaje de campaña o descalificaciones?

4. MANIFIESTO. ¿Choca con algún principio: Estado de derecho, derechos
   humanos, inclusión territorial, diversificación económica?

5. SOLIDEZ.
   - ¿El problema está bien definido y demostrado?
   - ¿La solución responde realmente al problema?
   - ¿Los costos son creíbles o se omiten?
   - ¿Los plazos son realistas para la situación de Venezuela?
   - ¿Se identifica el riesgo de corrupción o captura?
   - ¿Hay alternativas serias descartadas con argumentos?
   - ¿Incluye experiencias comparables que salieron mal?

6. IMPACTO. ¿Considera a los más vulnerables, las regiones fuera de
   Caracas, los pueblos indígenas y la diáspora? ¿Dice quién pierde?

7. MEDICIÓN. ¿Los indicadores son medibles y verificables?

8. DEPENDENCIAS. ¿Depende de otras reformas que no menciona?

9. CLARIDAD. ¿La entendería alguien sin formación técnica?

FORMATO DE RESPUESTA:

- Veredicto en una línea: "Lista para revisión pública",
  "Necesita cambios menores" o "Necesita cambios importantes".
- Problemas GRAVES (impiden aceptar la propuesta).
- Problemas MODERADOS (debilitan la propuesta).
- Mejoras MENORES (forma y claridad).
- Datos y fuentes a verificar (lista completa).
- Las 3 preguntas más difíciles que le haría un crítico en la revisión
  pública.

Para cada problema, cita la sección afectada y explica en una o dos frases
por qué es un problema y cómo podría resolverse.
```
