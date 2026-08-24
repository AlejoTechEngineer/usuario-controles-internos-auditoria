<div align="center">

# 🛡️ El Usuario Como Pieza Fundamental Del Despliegue De Controles Internos

### *Factor Humano en los SGSI y su Verificación en el Proceso Auditor — Calidad y Auditoría de SI*

[![Asignatura](https://img.shields.io/badge/Asignatura-Calidad%20y%20Auditoría%20de%20SI-blueviolet.svg)]()
[![Status](https://img.shields.io/badge/Status-Completado-success.svg)]()
[![Norma](https://img.shields.io/badge/Norma-ISO%2FIEC%2027001%3A2022-orange.svg)]()
[![Norma](https://img.shields.io/badge/Norma-ISO%2019011%3A2018-005571.svg)]()

**[Descripción](#-descripción-del-proyecto) • [Alcance del Análisis](#-alcance-del-análisis) • [Arquitectura](#️-arquitectura) • [Contenido](#-contenido-del-repositorio) • [Hallazgos](#-hallazgos-principales) • [Fundamento Normativo](#-fundamento-normativo-utilizado) • [Autor](#-autor)**

<img src="https://img.shields.io/badge/Enfoque-Factor%20Humano-blue?style=flat-square" alt="Enfoque"/>
<img src="https://img.shields.io/badge/Preguntas-3%20Ejes%20de%20Análisis-green?style=flat-square" alt="Preguntas"/>
<img src="https://img.shields.io/badge/Tablas-5%20de%20Elaboración%20Propia-red?style=flat-square" alt="Tablas"/>
<img src="https://img.shields.io/badge/Idioma-Español-lightgrey?style=flat-square" alt="Idioma"/>

</div>

---

## 📋 Tabla de Contenidos

- [🎯 Descripción del Proyecto](#-descripción-del-proyecto)
- [📐 Alcance del Análisis](#-alcance-del-análisis)
- [🏗️ Arquitectura](#️-arquitectura)
- [🔁 Ciclo PHVA Aplicado al Programa de Concienciación](#-ciclo-phva-aplicado-al-programa-de-concienciación)
- [📁 Contenido del Repositorio](#-contenido-del-repositorio)
- [💡 Hallazgos Principales](#-hallazgos-principales)
- [📚 Fundamento Normativo Utilizado](#-fundamento-normativo-utilizado)
- [🔍 Contenido del Informe](#-contenido-del-informe)
- [👨‍💻 Autor](#-autor)

---

## 🎯 Descripción del Proyecto

Este repositorio contiene el informe desarrollado para el **Laboratorio No. 2** de la asignatura
**Calidad y Auditoría de Sistemas de Información**, centrado en el rol del usuario como
componente esencial de los controles internos de seguridad de la información.

El trabajo parte del **Kit de Concienciación de INCIBE** como caso de referencia y analiza tres
cuestiones centrales: si un **SGSI** puede cumplir sus expectativas imponiendo únicamente un
marco tecnológico y normativo, cuáles son las consecuencias de que los usuarios no comprendan las
medidas de seguridad, y por qué y cómo un auditor debe evaluar la brecha entre las políticas
declaradas y el uso real de la tecnología.

### 🌟 ¿Por qué este análisis es relevante?

- 🧑‍💻 **El usuario como control, no solo como riesgo**: se argumenta que el factor humano es un
  elemento activo del control interno, no únicamente una vulnerabilidad a mitigar con tecnología.
- 📉 **Diagnóstico de la brecha declarado vs. real**: se identifican las técnicas con las que un
  auditor puede detectar la distancia entre la política de seguridad documentada y su
  cumplimiento efectivo por parte de los usuarios.
- 🧪 **Kit de Concienciación como control auditable**: se propone mapear el Kit de INCIBE sobre
  el ciclo **PHVA**, convirtiendo un programa de sensibilización en evidencia verificable de
  auditoría.
- 📊 **Cinco tablas de elaboración propia**: sistematizan los elementos del SGSI, las
  consecuencias de la falta de comprensión, las técnicas de evaluación de la brecha y los
  indicadores propuestos para la verificación auditora.

---

## 📐 Alcance del Análisis

<div align="center">

| Pregunta de Análisis | Foco | Resultado |
|:---|:---|:---|
| 1 — Suficiencia del marco tecnológico y normativo | Límites de un SGSI centrado solo en tecnología y norma | El marco por sí solo no garantiza el cumplimiento de expectativas del SGSI |
| 2 — Consecuencias de la falta de comprensión | Efectos de que el usuario no entienda las medidas de seguridad | Tipología de consecuencias operativas, normativas y reputacionales |
| 3 — Evaluación auditora de la brecha | Técnicas de auditoría sobre política declarada vs. uso real | Indicadores y técnicas de recopilación de evidencia del factor humano |
| — | Propuesta de aplicación | Kit de Concienciación de INCIBE mapeado sobre el ciclo PHVA como control auditable |

</div>

---

## 🏗️ Arquitectura

```mermaid
flowchart TD
    A[Kit de Concienciación INCIBE] --> B[Marco de Referencia - El Usuario en el Control Interno]
    N[ISO/IEC 27001:2022 - Clausula 7.3 y Anexo A 6.3] --> B
    M[ISO 19011:2018 - Directrices de Auditoria] --> B
    B --> C[Pregunta 1 - Suficiencia del Marco Tecnologico y Normativo]
    B --> D[Pregunta 2 - Consecuencias de la Falta de Comprension]
    B --> E[Pregunta 3 - Evaluacion Auditora de la Brecha]
    C & D & E --> F[Propuesta - Kit de Concienciacion como Control Auditable]
    F --> G[Conclusiones]
```

---

## 🔁 Ciclo PHVA Aplicado al Programa de Concienciación

```mermaid
flowchart LR
    P[Planear - Alcance y Autorizacion] --> V1[Verificar - Linea Base con Ataques Dirigidos]
    V1 --> H[Hacer - Nueve Recursos Formativos]
    H --> V2[Verificar - Medicion Final Comparable]
    V2 --> A[Actuar - Encuesta y Plan de Mejora]
    A --> P
```

---

## 📁 Contenido del Repositorio

<table align="center">
  <tr>
    <th>Archivo</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td><code>Desarrollo_Proyecto_Alejandro_De_Mendoza_Tovar.pdf</code></td>
    <td>📄 Informe completo del laboratorio: marco de referencia, desarrollo de las tres preguntas, propuesta de aplicación del Kit de Concienciación y conclusiones</td>
  </tr>
</table>

> ℹ️ El repositorio versiona **únicamente el informe final en PDF**. Los documentos editables
> (`.docx`, `.pptx`, etc.) y la carpeta de trabajo de la actividad quedan excluidos vía
> `.gitignore` y permanecen solo en local.

---

## 💡 Hallazgos Principales

- **El marco tecnológico y normativo es necesario pero no suficiente**: un SGSI que se apoya
  únicamente en controles técnicos y documentación de políticas, sin intervenir sobre la
  comprensión del usuario, no garantiza el cumplimiento de sus propias expectativas de seguridad.
- **La falta de comprensión genera consecuencias en cascada**: desde incidentes operativos
  evitables hasta hallazgos de no conformidad en auditoría y exposición reputacional o legal,
  incluyendo implicaciones bajo la Ley 1581 de 2012 de protección de datos.
- **La brecha declarado vs. real es evaluable**: un auditor cuenta con técnicas concretas
  (entrevistas, observación directa, pruebas dirigidas, revisión de evidencia de formación) para
  contrastar lo que la política dice con lo que el usuario efectivamente hace.
- **El Kit de Concienciación como evidencia auditable**: mapeado sobre el ciclo PHVA, un programa
  de sensibilización deja de ser una actividad aislada y se convierte en un control verificable,
  con línea base, ejecución y medición final comparable.

---

## 📚 Fundamento Normativo Utilizado

<div align="center">

![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-orange?style=for-the-badge)
![ISO 27002](https://img.shields.io/badge/ISO%2FIEC-27002%3A2022-005571?style=for-the-badge)
![ISO 19011](https://img.shields.io/badge/ISO-19011%3A2018-4B8BBE?style=for-the-badge)
![Ley 1581](https://img.shields.io/badge/Ley-1581%20de%202012-B22222?style=for-the-badge)

</div>

- **ISO/IEC 27001:2022** → Cláusula 7.3 (Toma de conciencia) y control A.6.3 del Anexo A
  (Concienciación, educación y formación).
- **ISO/IEC 27002:2022** → Guía de implementación de los controles de seguridad.
- **ISO 19011:2018** → Fuentes de información y técnicas de recopilación de evidencia de
  auditoría.
- **Ley 1581 de 2012** → Régimen colombiano de protección de datos personales.

---

## 🔍 Contenido del Informe

<details>
<summary><b>📖 Ver detalle de las cinco tablas de elaboración propia</b></summary>

1. Elementos de implantación de un SGSI y efecto de su omisión.
2. Tipología de consecuencias derivadas de la falta de comprensión de las medidas de seguridad.
3. Técnicas de evaluación de la brecha entre política declarada y uso real.
4. Indicadores propuestos para la verificación auditora del factor humano.
5. Mapeo del Kit de Concienciación sobre el ciclo PHVA y evidencia auditable resultante.

</details>

---

## 👨‍💻 Autor

<div align="center">

**Alejandro De Mendoza Tovar**

Este laboratorio fue desarrollado en el marco de la asignatura **Calidad y Auditoría de Sistemas
de Información**, bajo la dirección del **Ing. y Dr. Wilson Castaño Galvis**, en la
**Fundación Universitaria Internacional de La Rioja (UNIR)**, Bogotá D.C.

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejoTechEngineer)

</div>

---

<div align="center">

### 🛡️ *Cuando la norma se declara pero no se comprende, el control interno se rompe en el usuario, no en la tecnología*

</div>
