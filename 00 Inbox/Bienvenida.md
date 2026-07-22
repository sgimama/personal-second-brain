---
title: Bienvenida — Cómo funciona este vault
created: 2026-07-22
tags: [meta, guia]
---

# 🧠 Bienvenida a tu Second Brain

Este vault está organizado con el método **PARA** (de Tiago Forte, *Building a Second Brain*).
La idea central: **no organizas por tema, sino por cuán accionable es algo ahora mismo** — de lo más urgente a lo más pasivo.

---

## Las 4 carpetas PARA

### 📥 `00 Inbox` — Bandeja de entrada
Buzón de **captura rápida**. Cuando se te ocurre una idea o lees algo interesante, lo tiras aquí sin pensar dónde va. Regla de oro: **capturar primero, ordenar después.** Vacía el inbox cada pocos días.

> Ejemplos: "Mirar ese curso de Rust", "Idea de regalo para X", un enlace que te mandaron.

### 🎯 `01 Projects` — Proyectos
Cosas con un **objetivo concreto y una fecha/final claro**. Tienen línea de meta: cuando lo terminas, se cierra.

> Ejemplos: "Renovar el pasaporte", "Lanzar el vault", "Planear las vacaciones de agosto".

### 🔄 `02 Areas` — Áreas de responsabilidad
Cosas que mantienes **de forma continua, sin fecha de fin**. No se terminan; solo mantienes un estándar.

> Ejemplos: "Salud", "Finanzas", "Carrera profesional", "Coche", "Casa".

**Projects vs Areas:** un proyecto termina; un área es para siempre.
- *"Correr una maratón"* → Proyecto (fecha + meta).
- *"Estar en forma"* → Área (continuo).

### 📚 `03 Resources` — Recursos
Temas que te **interesan** o material de **referencia**. Tu biblioteca personal.

> Ejemplos: "Recetas", "Fotografía", "Notas de libros", "Snippets de código".

### 🗄️ `04 Archive` — Archivo
Todo lo que **ya no está activo** de las otras tres categorías. No borras: archivas por si acaso.

> Ejemplos: un proyecto terminado, un hobby que dejaste, un recurso que ya no consultas.

---

## Carpetas extra

### 🗓️ `Daily` — Notas diarias
Una nota por día: bitácora de trabajo, tareas e ideas sueltas. Plantilla lista en `Templates/Daily Note.md`.

### 🧩 `Templates` — Plantillas
Plantillas reutilizables para no empezar de cero.

---

## El flujo diario

```
1. CAPTURA    →  cualquier cosa va a  00 Inbox
2. ORGANIZA   →  vacías el Inbox → Projects / Areas / Resources
3. ARCHIVA    →  lo inactivo va a  04 Archive
```

Para clasificar una nota, pregúntate **de arriba abajo** y quédate en la primera que encaje:

1. ¿Sirve para un **proyecto** activo? → `01 Projects`
2. Si no, ¿es un **área** que mantengo? → `02 Areas`
3. Si no, ¿es un **recurso** que me interesa? → `03 Resources`
4. Si no sirve para nada de eso → `04 Archive`

---

## Notas prácticas

- Este vault se versiona con **git** (`sgimama/personal-second-brain`) y vive fuera de iCloud para evitar conflictos de sincronización.
- Para sincronizar entre dispositivos: `git pull` / `git push`, o instala el plugin **Obsidian Git**.
- Las carpetas tienen un `.gitkeep` para que git las rastree vacías; puedes borrarlos cuando cada carpeta tenga notas reales.
