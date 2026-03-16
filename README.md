# 📐 Organizador de Carrera — Profesorado en Matemática
### IES Recreo

Aplicación web interactiva para hacer seguimiento del progreso académico en el Profesorado de Educación Secundaria en Matemática.

---

## 🚀 Cómo usar

1. Descargá el archivo `organizador_profesorado_matematica.html`
2. Abrilo en cualquier navegador (Chrome, Firefox, Edge, Safari)
3. No requiere internet, servidor ni instalación

---

## ✨ Funcionalidades

### 📚 Plan de materias
- Las 38 materias del plan de estudios organizadas por año (1° al 4°)
- Cada materia se muestra como una tarjeta interactiva con su estado actual

### 🎨 Estados de cada materia
| Estado | Color | Significado |
|---|---|---|
| ✅ Aprobada | 🟢 Verde | Final rendido y aprobado |
| 📝 Regular | 🟡 Amarillo | Cursada y regularizada |
| 📖 Cursando | 🟣 Violeta | Actualmente cursando |
| 🔵 Puede Cursarse | 🔵 Azul | Correlativas cumplidas para cursar |
| 🟠 Lista p/ Final | 🟠 Naranja | Regular y con correlativas para rendir |
| 🔒 Bloqueada | 🔴 Rojo | Faltan correlativas previas |

### 🔒 Validación de correlatividades
El sistema aplica automáticamente las reglas del plan de estudios:
- **Para cursar** una materia: las correlativas requeridas deben estar en estado *Regular* o *Aprobada* según corresponda
- **Para aprobar** una materia: las correlativas para acreditar deben estar *Aprobadas*
- Si intentás marcar un estado inválido, aparece un aviso explicando exactamente qué materia te falta y en qué condición

### ⭐ Planificación recomendada
- Lista de finales ordenados estratégicamente: los que más materias desbloquean aparecen primero
- Lista de materias habilitadas para cursar en el próximo período

### 🔍 Filtros
- Por año: 1°, 2°, 3°, 4°
- Por estado: Habilitadas, Para rendir final, En curso, Aprobadas, Bloqueadas

### 💾 Guardado automático
El progreso se guarda en el navegador con `localStorage`. No se pierde al cerrar la pestaña ni reiniciar el equipo.

---

## 📋 Plan de estudios incluido

| N° | Materia | Año | Período |
|---|---|---|---|
| 1 | Pedagogía | 1° | 1° Cuatrimestre |
| 2 | Didáctica General | 1° | 2° Cuatrimestre |
| 3 | Instituciones Ed. y Cont. Comunitario | 1° | Anual |
| 4 | Álgebra Conjuntista | 1° | Anual |
| 5 | Geometría Métrica y Euclidiana | 1° | Anual |
| 6 | Cálculo Aritmético y Trigonométrico | 1° | 1° Cuatrimestre |
| 7 | Aritmética Formal | 1° | 2° Cuatrimestre |
| 8 | Unidad de Definición Institucional I | 1° | Anual |
| 9 | Sociología de la Educación | 2° | 1° Cuatrimestre |
| 10 | Psicología Educacional | 2° | Anual |
| 11 | Curriculum y Prog. de la Enseñanza | 2° | Anual |
| 12 | Álgebra Lineal | 2° | Anual |
| 13 | Geometría Analítica del Plano y el Espacio | 2° | Anual |
| 14 | Análisis Mat. de Variable Real | 2° | Anual |
| 15 | Introducción a la Física | 2° | 2° Cuatrimestre |
| 16 | Didáctica de la Mat. — Ciclo Básico | 2° | 1° Cuatrimestre |
| 17 | Didáctica de la Geometría | 2° | 2° Cuatrimestre |
| 18 | Unidad de Definición Institucional II | 2° | Anual |
| 19 | Ética y Construcción Ciudadana | 3° | 2° Cuatrimestre |
| 20 | TIC Aplicadas a la Educación | 3° | Anual |
| 21 | Historia y Política de la Ed. Argentina | 3° | 1° Cuatrimestre |
| 22 | Educación Sexual Integral | 3° | 2° Cuatrimestre |
| 23 | Práctica de la Enseñanza | 3° | Anual |
| 24 | Análisis Mat. Multivariado | 3° | Anual |
| 25 | Probabilidad | 3° | 1° Cuatrimestre |
| 26 | Estadística | 3° | 2° Cuatrimestre |
| 27 | Didáctica de la Mat. — Ciclo Orientado | 3° | 1° Cuatrimestre |
| 28 | Unidad de Definición Institucional III | 3° | Anual |
| 29 | Filosofía de la Educación | 4° | 1° Cuatrimestre |
| 30 | Problemática de la Ed. Secundaria | 4° | 2° Cuatrimestre |
| 31 | Práctica Docente y Residencia | 4° | Anual |
| 32 | Fundamentos de la Matemática | 4° | Anual |
| 33 | Análisis de Variable Compleja | 4° | 1° Cuatrimestre |
| 34 | Ecuaciones Diferenciales | 4° | 2° Cuatrimestre |
| 35 | Epistemología e Hist. de la Matemática | 4° | 1° Cuatrimestre |
| 36 | Matemática Aplicada | 4° | 2° Cuatrimestre |
| 37 | Sujeto de la Ed. Secundaria | 4° | Anual |
| 38 | Unidad de Definición Institucional IV | 4° | Anual |

---

## 🛠️ Tecnologías

- **React 18** (via CDN, sin build step)
- **Babel Standalone** (JSX en el navegador)
- **HTML/CSS puro** — sin frameworks externos
- **localStorage** — persistencia local sin backend
- Fuentes: [Syne](https://fonts.google.com/specimen/Syne) + [Outfit](https://fonts.google.com/specimen/Outfit)

---

## 📁 Estructura del proyecto
```
organizador_profesorado_matematica.html   ← archivo único, todo incluido
```

El logo del IES Recreo está embebido en base64 directamente en el HTML, por lo que el archivo es completamente autónomo.

---

## 👤 Créditos

- Plan de estudios: **Profesorado de Educación Secundaria en Matemática — IES Recreo**
- Aplicación generada con asistencia de **Claude (Anthropic)**
