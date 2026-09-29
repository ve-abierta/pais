# Gobernanza

Este documento explica quién decide qué en el proyecto País y cómo se toman esas decisiones. El objetivo es que el proceso sea transparente, que nadie pueda apropiarse del proyecto y que las buenas ideas avancen aunque no vengan de las personas más visibles.

---

## 1. Roles

### Contribuyentes
Cualquier persona que abre una Discusión, comenta, revisa o propone cambios. No hace falta pedir permiso ni registrarse más allá de tener una cuenta de GitHub.

### Revisores
Contribuyentes con aportes sostenidos en un área que ayudan a mejorar las propuestas antes de su votación. Su revisión es consultiva y no vinculante. Cualquier mantenedor puede nombrar a un revisor.

### Mantenedores de área
Responsables de cada área temática (economía, educación, seguridad, etc.). Sus funciones son:

- Asignar números definitivos a las VEP de su área.
- Moderar las discusiones y aplicar el Código de Conducta.
- Aprobar o rechazar propuestas según el proceso descrito abajo.
- Mantener actualizado el índice de propuestas del área.

Cada área tiene entre 2 y 5 mantenedores. Ninguna persona puede ser mantenedora de más de dos áreas a la vez.

### Consejo de Gobernanza
Un grupo de 5 personas que:

- Cuida el cumplimiento del [MANIFIESTO](MANIFIESTO.md).
- Resuelve conflictos entre áreas o apelaciones.
- Aprueba las VEP que modifican este documento o el Manifiesto.
- Nombra o destituye mantenedores cuando el área no puede hacerlo por sí misma.

El Consejo no decide sobre el contenido de las propuestas temáticas. Solo vela por el proceso.

---

## 2. Ciclo de vida de una propuesta (VEP)

```
Idea (Discusión) → Borrador (PR) → En revisión → Aceptada / Rechazada
                                              ↘ Retirada por el autor
Aceptada → Reemplazada (si una VEP posterior la supera)
```

1. **Idea.** Se abre una Discusión en la categoría del área. Sirve para comprobar si hay interés y recoger datos antes de redactar.
2. **Borrador.** El autor abre un Pull Request con la propuesta basada en la [plantilla](propuestas/VEP-0000-plantilla.md). Un mantenedor verifica que la estructura esté completa y le asigna número.
3. **En revisión.** Comienza un periodo de comentarios públicos de **al menos 21 días**. El autor incorpora cambios en el mismo PR.
4. **Decisión.** Al cerrar el periodo, los mantenedores del área deciden:
   - **Aceptada:** requiere la aprobación de al menos 2 mantenedores y ninguna objeción fundamentada sin resolver.
   - **Rechazada:** los motivos se documentan en la propia VEP, que se fusiona igualmente con estado `Rechazada`.
   - **Devuelta:** necesita más trabajo y vuelve a `Borrador`.

"Aceptada" significa que la propuesta cumple el estándar de calidad del proyecto y cuenta con respaldo de la comunidad. No significa que sea la única solución válida ni que sea política oficial.

### Objeciones fundamentadas
Una objeción bloquea la aceptación solo si aporta datos, identifica un riesgo no considerado o señala un conflicto con el Manifiesto. Una objeción del tipo "no me gusta" no bloquea.

### Propuestas que tocan varias áreas
Requieren la aprobación de al menos un mantenedor de cada área afectada.

---

## 3. Toma de decisiones

El proyecto busca **consenso aproximado**: no se requiere unanimidad, pero sí que las objeciones serias hayan sido respondidas. Cuando el consenso no es posible:

1. Los mantenedores del área votan por mayoría simple.
2. En caso de empate, o si el autor apela, decide el Consejo de Gobernanza.
3. Todas las votaciones son públicas y quedan registradas en el PR o la Discusión correspondiente.

---

## 4. Elección y renovación

- **Mantenedores:** los propone cualquier mantenedor del área o el Consejo, basándose en sus contribuciones. El nombramiento se anuncia públicamente con 7 días para objeciones.
- **Consejo:** se elige por votación entre todos los mantenedores activos. Cada mandato dura **1 año** y nadie puede ocupar el cargo más de 2 mandatos consecutivos.
- **Inactividad:** un mantenedor sin actividad durante 6 meses pasa a estado emérito y puede volver cuando quiera.
- **Destitución:** por incumplimiento grave del Código de Conducta o del Manifiesto, con decisión del Consejo por mayoría de 4 de 5.

---

## 5. Neutralidad y conflictos de interés

- Quien ocupa un cargo en un partido político, un gobierno o una campaña electoral no puede ser mantenedor ni formar parte del Consejo mientras dure ese cargo. Sí puede contribuir como cualquier otra persona.
- Quien tenga un interés económico directo en una propuesta debe declararlo en la VEP y abstenerse de decidir sobre ella.
- Las propuestas no pueden mencionar ni promover a personas, partidos o candidatos concretos.

---

## 6. Etapa fundacional

Mientras el proyecto no tenga al menos **3 mantenedores activos en 3 áreas distintas**, el fundador actúa como mantenedor de todas las áreas y como Consejo provisional. Esta etapa termina automáticamente al alcanzar ese umbral, y el primer Consejo debe elegirse en los 60 días siguientes.

---

## 7. Forks

El contenido está bajo licencia CC BY-SA 4.0. Cualquiera que no esté de acuerdo con el rumbo del proyecto puede hacer un fork y continuar por su cuenta. Consideramos esto una garantía, no una amenaza.

---

## 8. Cambios a este documento

Este documento solo puede modificarse mediante una VEP del área `gobernanza`, con un periodo de comentarios de 30 días y la aprobación de 4 de los 5 miembros del Consejo.
