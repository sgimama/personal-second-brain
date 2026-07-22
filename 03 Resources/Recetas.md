---
type: index
tags:
  - moc
---

# 🍽️ Recetas

Índice de todas las recetas del vault. Se actualiza solo a medida que añades notas en `03 Resources/Recetas/`.

> [!tip] Cómo añadir una receta
> Crea una nota nueva dentro de `03 Resources/Recetas/`, y aplícale la plantilla con
> `Cmd+P` → *Templater: Open insert template modal* → **Receta**.
> Rellena los campos del frontmatter (`tiempo` en minutos, `valoracion` de 1 a 5) para que aparezca bien en las tablas de abajo.

## 📋 Todas las recetas
```dataview
TABLE WITHOUT ID
  file.link AS "Receta",
  tiempo AS "⏱️ Min",
  dificultad AS "📊 Dificultad",
  valoracion AS "⭐",
  fuente AS "🔗 Fuente"
FROM "03 Resources/Recetas"
WHERE type = "receta"
SORT valoracion DESC
```

## ⚡ Rápidas (30 min o menos)
```dataview
LIST
FROM "03 Resources/Recetas"
WHERE type = "receta" AND tiempo <= 30
SORT tiempo ASC
```

## ⭐ Favoritas (valoración 4+)
```dataview
LIST
FROM "03 Resources/Recetas"
WHERE type = "receta" AND valoracion >= 4
SORT valoracion DESC
```
