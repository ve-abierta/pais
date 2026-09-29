# Política de uso de inteligencia artificial

La inteligencia artificial puede ayudar mucho a un proyecto como País: a redactar, traducir, resumir, buscar fuentes o automatizar tareas. También puede llenar el repositorio de datos inventados, citas falsas y contenido de baja calidad. Esta política establece cómo se usa la IA en el proyecto para aprovechar lo primero sin caer en lo segundo.

La regla de fondo es sencilla: **la IA es una herramienta, no un autor. Quien firma una contribución responde de todo su contenido.**

---

## 1. Usos permitidos

Puedes usar herramientas de IA para:

- Redactar borradores, reorganizar textos o mejorar la redacción.
- Traducir o resumir documentos.
- Buscar fuentes, datos o experiencias de otros países.
- Revisar la estructura de una propuesta frente a la plantilla.
- Escribir código, scripts o automatizaciones del repositorio.
- Preparar versiones divulgativas, como resúmenes o *policy briefs*.

## 2. Responsabilidad de quien contribuye

Si usas IA, sigues siendo responsable de tu contribución. Eso significa:

- **Verificar cada dato.** Los modelos de IA inventan cifras con total seguridad. Ninguna cifra entra al repositorio sin una fuente comprobada.
- **Leer cada fuente que citas.** Los modelos inventan también referencias, estudios y enlaces. Nunca cites un documento que no has abierto y leído.
- **Entender lo que envías.** Debes poder explicar y defender tu propuesta en la revisión sin depender de la herramienta.
- **Revisar el sesgo.** Los modelos pueden reproducir visiones parciales o poco informadas sobre Venezuela. Contrasta con fuentes locales.

## 3. Declaración de uso

El uso de IA **se declara**, sin que eso suponga ningún juicio negativo:

- En las VEP, mediante el campo `ai_assisted: true` del encabezado y una línea en el historial de cambios que explique para qué se usó (por ejemplo, "borrador inicial y traducción").
- En los pull requests, marcando la casilla correspondiente de la plantilla.
- Las traducciones automáticas se identifican como tales y se indica si una persona las ha revisado.

### Prompts del proyecto

La carpeta [`prompts/`](prompts/) contiene prompts para [redactar](prompts/draft-vep.md) y [revisar](prompts/review-vep.md) propuestas. Están diseñados para que la IA respete el Manifiesto y marque los datos pendientes en lugar de inventarlos. Usarlos no exime de verificar el resultado.

## 4. Usos prohibidos

- **Inventar o "completar" datos o fuentes** con IA.
- **Contribuciones masivas generadas automáticamente**, como pull requests o comentarios en serie sin revisión humana. Se tratan como spam.
- **Cuentas automatizadas que se hacen pasar por personas** en las Discusiones o revisiones.
- **Usar IA para identificar, perfilar o vigilar** a los participantes, por ejemplo analizando su estilo de escritura para descubrir quién está detrás de un seudónimo. Se considera una falta de tolerancia cero según el [Código de Conducta](CODE_OF_CONDUCT.md).
- **Introducir datos personales o información confidencial en servicios de IA de terceros**, como reportes de conducta, datos de contacto o información sobre otros participantes.
- **Generar imágenes, audios o vídeos de personas reales**, o contenido que pueda confundirse con documentos, declaraciones o fotografías auténticas.

## 5. Uso de la IA por parte del proyecto

El propio proyecto puede usar IA, con estas reglas:

- **Los bots se identifican siempre como automáticos**, en su nombre y en cada mensaje.
- **La IA no toma decisiones.** Puede ayudar a clasificar Discusiones, detectar enlaces rotos o preparar resúmenes, pero la aprobación de propuestas, la moderación y las sanciones las deciden siempre personas, según [GOVERNANCE](GOVERNANCE.md).
- **Las herramientas preferidas son las que respetan la privacidad**: modelos que se puedan ejecutar en infraestructura propia o servicios que no usen los datos para entrenar.
- **Transparencia:** el proyecto publica qué herramientas de IA usa y para qué.

## 6. Derechos y licencia

Al contribuir con contenido generado con ayuda de IA, garantizas que tienes derecho a publicarlo bajo la licencia [CC BY-SA 4.0](LICENSE) del proyecto y que no reproduce contenido protegido de terceros.

## 7. Declaración del propio proyecto

Los documentos fundacionales de País (este archivo incluido) y las primeras VEP se redactaron con asistencia de IA, a partir de las ideas y decisiones del fundador, que los revisó antes de publicarlos. Sus datos y fuentes están sujetos a verificación comunitaria como cualquier otra contribución.

---

*Esta política se revisará periódicamente, porque la tecnología cambia rápido. Los cambios se proponen mediante una VEP del área `governance`.*
