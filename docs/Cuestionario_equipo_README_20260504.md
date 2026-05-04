# Cuestionario de equipo — README del proyecto P8

> **Propósito:** recoger las respuestas del equipo en la reunión para personalizar el `README.md` que JJ presentará en su rama `v_01`.
>
> **Cómo usarlo:** marca con `[X]` las opciones elegidas, escribe texto libre donde se pida, y deja en blanco lo que no aplique. Las preguntas que se puedan saltar están marcadas con *(opcional)*.
>
> **Formato de respuesta:** Y = Sí, N = No, NS = No sé / Lo decidimos después.
>
> **Tiempo estimado de la reunión para responder:** 20–30 minutos.

---

## Bloque 0 — Aprobación general del README propuesto

P0.1: ¿Aprobáis el README propuesto en la rama `v_01` como base de trabajo?
- [ ] Y — Aprobado tal cual.
- [ ] Y — Aprobado con cambios menores (ver bloques siguientes).
- [ ] N — Necesita cambios estructurales (especificar al final, sección "Comentarios libres").
- [ ] NS

P0.2: ¿La rama destino final del README es `develop`, `main` u otra?
- [ ] develop
- [ ] main
- [ ] Otra: ____________________

P0.3: ¿Quién o quiénes deben aprobar la PR antes de hacer merge?
- [ ] Solo Product Owner (Juanma).
- [ ] Solo Scrum Master (Naiza).
- [ ] Ambos (Juanma y Naiza).
- [ ] Todo el equipo.
- [ ] Otra configuración: ____________________

---

## Bloque 1 — Datos generales del proyecto (a confirmar por el equipo)

P1.1: ¿Confirmáis "Bootcamp IA P6 — Factoría F5 Madrid" como identificador del bootcamp en el README?
- [ ] Y
- [ ] N → corrección: ____________________

P1.2: ¿Confirmáis que el proyecto se llama "P8 — Análisis del Mercado AirBnB"?
- [ ] Y
- [ ] N → nombre alternativo: ____________________

P1.3: ¿Las seis ciudades del análisis son Sydney, Nueva York, Madrid, Londres, Milán y Tokio?
- [ ] Y
- [ ] N → corrección: ____________________

P1.4: ¿Hay una **fuente oficial del dataset** que debamos citar en el README? *(ejemplo: Inside Airbnb, Kaggle, dataset interno P4, etc.)*
- [ ] Y → fuente: ____________________
- [ ] N
- [ ] NS

P1.5: ¿Los datasets vienen suministrados por la promoción **P4** y los usamos en **P6**? ¿Conviene mencionarlo explícitamente en el README?
- [ ] Y, mencionar.
- [ ] N, omitir.
- [ ] NS

---

## Bloque 2 — Equipo y roles

P2.1: ¿Confirmáis los roles tal y como aparecen en el README?
- Juanma — Product Owner: [ ] Y  [ ] N
- Naiza — Scrum Master: [ ] Y  [ ] N
- Andy — Data Analyst: [ ] Y  [ ] N
- JJ — Data Analyst: [ ] Y  [ ] N
- Pal — Data Analyst: [ ] Y  [ ] N

P2.2: ¿Queréis que aparezcan **apellidos** además de los nombres de pila?
- [ ] Y → indicar apellido de cada uno:
  - Juanma: ____________________
  - Naiza: ____________________
  - Andy: ____________________
  - JJ: Ramírez y Sánchez-Escobar
  - Pal: ____________________
- [ ] N, solo nombres de pila.

P2.3: ¿Queréis que aparezca el **handle de GitHub** de cada miembro?
- [ ] Y → indicar handle de cada uno:
  - Juanma: @____________________
  - Naiza: @____________________
  - Andy: @____________________
  - JJ: @Jose-JulioRamirezySanchez-Escobar
  - Pal: @____________________
- [ ] N

P2.4: ¿Queréis añadir una **sub-especialización** debajo del rol? *(ejemplo: "Data Analyst — EDA y homogeneización", "Data Analyst — Visualización interactiva")*
- [ ] Y → especialización de cada uno:
  - Andy: ____________________
  - JJ: ____________________
  - Pal: ____________________
- [ ] N

---

## Bloque 3 — Stack tecnológico

P3.1: ¿La sección de **Análisis de datos** está completa? Marca lo que falte añadir:
- [ ] NumPy
- [ ] Matplotlib
- [ ] Scikit-learn
- [ ] SciPy
- [ ] Statsmodels
- [ ] Otro: ____________________
- [ ] Nada que añadir.

P3.2: ¿La sección de **Visualización y reporting** está bien planteada (Power BI principal, Looker Studio como alternativa futura)?
- [ ] Y
- [ ] N → corrección: ____________________

P3.3: ¿La sección del **frontend** refleja correctamente el stack del repo de Naiza?
- [ ] Y
- [ ] N → corrección: ____________________

P3.4: ¿Falta alguna herramienta de **gestión / colaboración** que usemos como equipo?
- [ ] Discord / Slack — ¿cuál? ____________________
- [ ] Notion / Google Drive
- [ ] Figma / Miro
- [ ] Otro: ____________________
- [ ] Nada que añadir.

P3.5: ¿Queréis que el README incluya **versiones específicas** de las herramientas? *(ejemplo: Python 3.13, Node 18+, etc.)*
- [ ] Y, indicar versiones siempre que se conozcan.
- [ ] N, solo nombres.

---

## Bloque 4 — Frontend (Naiza)

> Estas preguntas son para que Naiza valide cómo se referencia su trabajo en el README, sin entrar en su documentación técnica detallada.

P4.1: ¿Confirmas que el repositorio de referencia es <https://github.com/Delo-sangeles/Data_Analysis>?
- [ ] Y
- [ ] N → URL correcta: ____________________

P4.2: ¿La rama por defecto del repo del frontend es `develop` o `main`?
- [ ] develop
- [ ] main
- [ ] Otra: ____________________

P4.3: ¿Quieres que aparezcas en el README como **"Autora de referencia"** del frontend?
- [ ] Y
- [ ] N → forma preferida: ____________________

P4.4: ¿El stack listado (React + TypeScript + Vite + Tailwind + Recharts + Leaflet) está completo?
- [ ] Y
- [ ] N → falta o sobra: ____________________

P4.5: ¿Quieres que el README mencione que el frontend usa actualmente **datos hardcodeados de demostración** y que `apiClient.ts` está preparado para un backend futuro?
- [ ] Y, mencionarlo.
- [ ] N, omitirlo.
- [ ] Solo mencionarlo si Juanma está de acuerdo.

P4.6: ¿Quieres que el README enlace a algún documento concreto **dentro** del repo del frontend? *(ejemplo: README.md, SETUP.md, BACKEND_EXAMPLES.md)*
- [ ] Y → cuáles:
  - [ ] README.md
  - [ ] SETUP.md
  - [ ] BACKEND_EXAMPLES.md
  - [ ] Otro: ____________________
- [ ] N, basta con el enlace al repo.

P4.7: ¿Hay alguna **captura de pantalla oficial** del dashboard que prefieras que se incluya, o ninguna por ahora?
- [ ] Y → ruta o enlace: ____________________
- [ ] N, sin capturas.

P4.8: ¿Algún comentario o aclaración sobre cómo describir tu trabajo en el README?
> ____________________________________________________________

---

## Bloque 5 — Power BI (Juanma)

> Estas preguntas son para que Juanma valide cómo se referencia su trabajo en el README.

P5.1: ¿Confirmas que el enlace a la presentación es <https://drive.google.com/file/d/1i-yYdaCaJXoN9tgTbRrr-hGYlZb4Lhlo/view?usp=sharing>?
- [ ] Y
- [ ] N → URL correcta: ____________________

P5.2: ¿El enlace de Drive es de **solo visualización** o de **descarga / edición**? ¿Tiene los permisos correctos para evaluadores externos?
- [ ] Solo visualización, permisos correctos.
- [ ] Descarga, permisos correctos.
- [ ] No estoy seguro de los permisos → revisar antes de la entrega.

P5.3: ¿Quieres que aparezcas como **"Autor de referencia"** del entregable Power BI?
- [ ] Y
- [ ] N → forma preferida: ____________________

P5.4: ¿El requisito técnico que figura ("Power BI Desktop solo Windows, o Power BI Web") es correcto?
- [ ] Y
- [ ] N → corrección: ____________________

P5.5: ¿El archivo Power BI requiere alguna **cuenta concreta** o es accesible con cuenta personal de Microsoft?
- [ ] Cuenta personal de Microsoft basta.
- [ ] Requiere cuenta de organización.
- [ ] Otro: ____________________

P5.6: ¿Quieres que el README incluya un **resumen de 2–3 líneas** de qué muestra la presentación Power BI? *(ejemplo: "Comparativa de precios y ocupación en las 6 ciudades, con desglose por barrio y tipología de alojamiento")*
- [ ] Y → resumen propuesto:
> ____________________________________________________________
- [ ] N, basta con el enlace.

P5.7: ¿Hay un **archivo `.pbix`** alojado en algún repositorio o solo está en Drive?
- [ ] Solo en Drive.
- [ ] En Drive y en repo: ____________________
- [ ] Otra ubicación: ____________________

P5.8: ¿Algún comentario o aclaración sobre cómo describir tu trabajo en el README?
> ____________________________________________________________

---

## Bloque 6 — EDA y notebooks (Andy)

> Estas preguntas son para que Andy valide cómo se referencia su trabajo en el README.

P6.1: ¿El EDA está alojado en el repo del equipo `P8_Data_Analysis` o en un repo aparte?
- [ ] En el repo del equipo, dentro de carpeta: ____________________
- [ ] En repo aparte: ____________________

P6.2: ¿Cuáles son los **notebooks principales** del EDA? *(ejemplos típicos: 00_homogenizacion.ipynb, 01_eda.ipynb, 02_visualizaciones.ipynb)*
- Notebook 1: ____________________
- Notebook 2: ____________________
- Notebook 3: ____________________
- Notebook 4: ____________________

P6.3: ¿Quieres aparecer como **"Autor de referencia"** del EDA en el README?
- [ ] Y
- [ ] N → forma preferida: ____________________

P6.4: ¿Hay un **informe de conclusiones del EDA** (Markdown, PDF, Word) que debamos enlazar?
- [ ] Y → ruta o enlace: ____________________
- [ ] N

P6.5: ¿Quieres que el README mencione las **principales preguntas de negocio** que responde el EDA? *(ejemplo: precios medios por ciudad, distribución por barrio, peso del segmento superhost)*
- [ ] Y → preguntas:
> ____________________________________________________________
- [ ] N, basta con el enlace.

P6.6: ¿El EDA requiere algún **dataset descargado aparte** que no esté en el repo? ¿Dónde se documenta?
- [ ] Y → ubicación documentada en: ____________________
- [ ] N, todo está en el repo.

P6.7: ¿Algún comentario o aclaración sobre cómo describir tu trabajo en el README?
> ____________________________________________________________

---

## Bloque 7 — Roadmap y Kanban

P7.1: ¿La URL del Kanban es <https://github.com/orgs/Bootcamp-IA-P6/projects/46/views/1>?
- [ ] Y
- [ ] N → URL correcta: ____________________

P7.2: ¿Las áreas grandes listadas en la sección 5 del README cubren bien el roadmap?
- [ ] Y
- [ ] N → áreas a añadir/quitar/renombrar: ____________________

P7.3: ¿Queréis añadir una **fecha de entrega** o una fecha de presentación visible en el README?
- [ ] Y → fecha: ____________________
- [ ] N

P7.4: ¿Queréis incluir un mini **estado actual** ("Fase 3 de 5: visualización en curso")?
- [ ] Y → estado a fecha de hoy: ____________________
- [ ] N

---

## Bloque 8 — Cómo contribuir

P8.1: ¿Aprobáis el flujo de ramas propuesto (`feature/*` → `develop` → `main`)?
- [ ] Y
- [ ] N → flujo alternativo: ____________________

P8.2: ¿Adoptáis **Conventional Commits** (`feat:`, `fix:`, `docs:`, etc.)?
- [ ] Y, oficial.
- [ ] N, formato libre.
- [ ] Recomendado pero no obligatorio.

P8.3: ¿Vais a usar una **plantilla de Pull Request** (`.github/PULL_REQUEST_TEMPLATE.md`)?
- [ ] Y
- [ ] N
- [ ] NS

P8.4: ¿Vais a usar un **CODEOWNERS** o asignación automática de revisores?
- [ ] Y
- [ ] N
- [ ] NS

P8.5: ¿Cuántas **aprobaciones mínimas** se requieren para mergear a `develop`?
- [ ] 1
- [ ] 2
- [ ] Todo el equipo
- [ ] Sin requisito formal

---

## Bloque 9 — Licencia y atribución

P9.1: ¿Confirmáis licencia **MIT**?
- [ ] Y
- [ ] N → otra licencia: ____________________

P9.2: ¿La línea de copyright debe poner "Bootcamp IA P6 — Factoría F5 Madrid", los nombres del equipo, o ambas?
- [ ] Solo Bootcamp IA P6 — Factoría F5 Madrid.
- [ ] Solo nombres del equipo (Juanma, Naiza, Andy, JJ, Pal).
- [ ] Ambas cosas.
- [ ] Otra: ____________________

---

## Bloque 10 — Otros aspectos del README

P10.1: ¿Queréis incluir una sección de **"Capturas de pantalla"** del proyecto?
- [ ] Y → de qué (Power BI / frontend / notebooks): ____________________
- [ ] N

P10.2: ¿Queréis incluir una sección de **"Agradecimientos"** (profesorado, mentores, fuentes de datos)?
- [ ] Y → texto: ____________________
- [ ] N

P10.3: ¿Queréis añadir **badges adicionales** además de los actuales (License, Status, Bootcamp)?
- [ ] Python version
- [ ] Node version
- [ ] Última actualización
- [ ] Tamaño del repo
- [ ] Otros: ____________________
- [ ] N, basta con los actuales.

P10.4: ¿Queréis añadir una sección **"FAQ"** o **"Preguntas frecuentes"** para evaluadores?
- [ ] Y → temas: ____________________
- [ ] N

P10.5: ¿Queréis añadir un **diagrama de arquitectura** del proyecto (ASCII art o imagen)?
- [ ] Y → quién lo prepara: ____________________
- [ ] N

P10.6: ¿Versión bilingüe ES/EN?
- [ ] Sí, ambos idiomas en archivos separados (`README.md` y `README.en.md`).
- [ ] Sí, ambos idiomas en el mismo archivo.
- [ ] No, solo castellano (decisión actual).
- [ ] Más adelante, no en esta iteración.

---

## Bloque 11 — Comentarios libres de Pal

> Espacio para que Pal aporte cualquier observación, sugerencia, corrección, idea o duda sobre el README, el proyecto, el flujo de trabajo o cualquier otro aspecto que considere relevante.

> ____________________________________________________________
> ____________________________________________________________
> ____________________________________________________________
> ____________________________________________________________

---

## Bloque 12 — Comentarios libres del resto del equipo

> Espacio común para cualquier observación que no haya encajado en los bloques anteriores.

**Juanma:**
> ____________________________________________________________

**Naiza:**
> ____________________________________________________________

**Andy:**
> ____________________________________________________________

**JJ:**
> ____________________________________________________________

---

## Bloque 13 — Acuerdos de la reunión (a rellenar al final)

P13.1: Próxima fecha de revisión del README: ____________________

P13.2: Persona responsable de aplicar los cambios al README: ____________________

P13.3: ¿Hay algún punto que requiere segunda reunión para decidir?
- [ ] Y → cuáles: ____________________
- [ ] N

P13.4: Versión del README tras esta ronda:
- [ ] v_02
- [ ] Otra: ____________________

---

*Cuestionario generado el 2026-05-04 para personalizar el `README.md` propuesto en la rama `v_01` del repo `Bootcamp-IA-P6/P8_Data_Analysis`. Las respuestas servirán como insumo para generar la siguiente versión del README.*
