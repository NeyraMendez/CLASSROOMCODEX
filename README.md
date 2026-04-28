# CLASSROOMCODEX
# CLASSROOMCODEX
# Actividad de GitHub Classroom: **Asistente de Estudio en Terminal**

## 1) Descripción general
En esta actividad **vas a diseñar la propuesta de una práctica temática pequeña** que pueda desarrollarse en un repositorio de GitHub Classroom.

El objetivo principal **no es programar mucho**, sino demostrar que sabes:
- delimitar un problema realista,
- justificar una solución técnica simple,
- organizar un repositorio con estructura clara,
- y documentar cómo se va a probar y usar.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** úsalo solo si tu programa será **muy pequeño** (por ejemplo: operaciones básicas, conversión simple, lectura de argumentos y salida en terminal). No se espera un sistema complejo en Assembly.

La práctica debe ser pequeña para que puedas trabajarla aun con herramientas gratuitas (como Codex u otras IAs con límites de uso), sin depender de infraestructura pesada.

---

## 2) Objetivo de la tarea
Diseñar y documentar una propuesta de proyecto que resuelva un caso de uso concreto en terminal, con alcance acotado y viable en 1–2 semanas de trabajo académico.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta estructura base:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende de tu lenguaje: `s` (ARM64), `c`, `py` o `sh`.

---

## 5) Instrucciones de contenido por archivo

### `README.md`
Debe funcionar como portada técnica del proyecto:
1. Nombre del proyecto.
2. Lenguaje elegido y justificación breve.
3. Problema que resolverá.
4. Alcance (qué sí hace y qué no hace).
5. Instrucciones mínimas para ejecutar (aunque sea versión preliminar).
6. Estructura de carpetas resumida.

---

### `docs/propuesta.md`
Incluye:
1. **Tema de la práctica** (ejemplo: productividad, monitoreo local, estudio, automatización simple).
2. **Objetivo general** y **2–3 objetivos específicos**.
3. **Descripción funcional corta** (flujo principal en 5–8 pasos).
4. **Requisitos mínimos** (SO, compilador/interprete, herramientas básicas).
5. **Limitaciones** (sin nube, sin BD, sin APIs pagadas, sin frameworks pesados).
6. **Cronograma breve** (tabla de 4 a 6 actividades).

---

### `docs/caso_de_uso.md`
Incluye:
1. Actor principal (quién usa la herramienta).
2. Necesidad o problema.
3. Escenario principal de uso.
4. Entradas esperadas.
5. Salidas esperadas.
6. Criterios de aceptación (mínimo 5, medibles).

Sugerencia de formato:
- **Caso de uso:** CU-01
- **Nombre:** “Generar resumen de …”
- **Precondiciones:** …
- **Flujo principal:** …
- **Postcondiciones:** …

---

### `docs/estructura_repositorio.md`
Incluye:
1. Árbol de carpetas propuesto.
2. Propósito de cada archivo.
3. Convenciones de nombres (archivos, funciones, scripts).
4. Estrategia de versionado (commits pequeños y mensajes claros).

Ejemplo de convención de commits:
- `docs: agrega caso de uso inicial`
- `feat: prototipo de lectura de argumentos`
- `test: agrega casos de prueba funcionales`

---

### `docs/plan_de_pruebas.md`
Incluye:
1. Estrategia general de pruebas (manuales o semiautomatizadas).
2. Tabla de casos de prueba con:
   - ID,
   - objetivo,
   - entrada,
   - resultado esperado,
   - resultado obtenido (pendiente al inicio).
3. Casos límite (mínimo 3).
4. Riesgos y mitigaciones técnicas básicas.

---

## 6) Restricciones de la actividad
Para mantener el proyecto pequeño y viable:
- No usar frameworks grandes.
- No usar servicios en la nube.
- No usar bases de datos.
- No usar APIs pagadas.
- No usar contenedores.
- Evitar dependencias difíciles de instalar.

Se evaluará más la **claridad de la propuesta y documentación** que la cantidad de código.

---

## 7) Ideas temáticas sugeridas (elige una o propón otra equivalente)
- Mini Toolkit en ARM64
- Asistente de Estudio en Terminal
- Reporteador de Información del Sistema
- Organizador de Archivos
- Juego de Aprendizaje en Línea de Comandos

---

## 8) Rúbrica sugerida (100 puntos)
- **Claridad del problema y objetivo** – 20 pts
- **Calidad de la propuesta técnica** – 20 pts
- **Caso de uso y criterios de aceptación** – 20 pts
- **Estructura del repositorio y convenciones** – 20 pts
- **Plan de pruebas (cobertura y calidad)** – 20 pts

---

## 9) Criterios de evaluación rápida (checklist)
Marca cada punto con ✅/❌:
- [ ] El lenguaje está claramente definido (ARM64, C, Python o Bash).
- [ ] El alcance es pequeño y realista.
- [ ] Existen los 4 documentos mínimos en `docs/`.
- [ ] El caso de uso tiene entradas/salidas y criterios medibles.
- [ ] El plan de pruebas incluye casos normales y límite.
- [ ] La estructura del repositorio es consistente con lo documentado.

---

## 10) Entrega en GitHub Classroom
1. Crea tu repositorio desde la invitación de Classroom.
2. Sube la estructura mínima de archivos.
3. Completa primero la documentación (`docs/`).
4. Agrega, si aplica, un prototipo mínimo en `src/`.
5. Haz commits pequeños con mensajes claros.
6. Entrega el enlace final del repositorio según indique el docente.

---

## 11) Recomendación final del instructor
Si tienes duda entre “hacer más código” o “documentar mejor”, en esta actividad conviene **documentar mejor**.
Primero demuestra que tu diseño es sólido; luego implementa solo lo esencial.
