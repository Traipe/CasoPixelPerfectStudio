# 🎯 Caso PixelPerfect Studio
**Módulo 3 – Metodologías de organización y modularización de estilos**

---

## 📌 Descripción
Este proyecto aplica metodologías de organización y modularización de estilos (**BEM + SMACSS**) para lograr un código CSS escalable, mantenible y colaborativo en el desarrollo de interfaces modernas.

---

## 🎨 Branding & Design System
- **Paleta:** Celeste (`#3498db`), Verde (`#10b981`), Blanco (`#ffffff`).
- **Estilo:** Interfaces limpias, bordes redondeados y sombras suaves.

### Componentes Principales:
* **Card:** Pieza central para información jerarquizada.
    * *Path:* `scss/components/_card.scss` | *Selector:* `.card` | *Variante:* `.card--dark`.
* **Button:** Elemento de acción atómico y reutilizable.
    * *Path:* `scss/components/_buttons.scss` | *Selector:* `.btn` | *Variantes:* `--primary`, `--success`.

---

## 📂 Estructura de carpetas
Se utiliza una arquitectura inspirada en SMACSS para separar responsabilidades:

```text
scss/ 
 ├── abstracts/    <-- Variables y Mixins (No generan CSS)
 │    ├── _variables.scss 
 │    └── _mixins.scss 
 ├── base/         <-- Reset y estilos globales
 │    └── _reset.scss 
 ├── layout/       <-- Estructuras de página
 │    └── _grid.scss 
 ├── components/   <-- Bloques reutilizables (BEM)
 │    ├── _card.scss
 │    └── _buttons.scss
 └── main.scss     <-- Punto de entrada de compilación

 🚀 Retos Técnicos y Aprendizajes
Durante el desarrollo de PixelPerfect Studio, el principal desafío fue transicionar de un CSS monolítico a una arquitectura modular basada en SMACSS.

La solución: Implementé la metodología BEM para evitar la colisión de estilos y garantizar que los componentes sean "atómicos". Esto significa que un botón no depende de estar dentro de una tarjeta para funcionar, reduciendo la deuda técnica y facilitando el trabajo en equipo.

✅ Checklist de buenas prácticas
[x] Naming BEM consistente.

[x] Variables globales en abstracts/_variables.scss.

[x] Mixins reutilizables para responsive y efectos.

[x] Código limpio (sin reglas vacías).

[x] Accesibilidad básica (Aria-labels y semántica).

🛠️ Cómo ejecutar
Clonar el repositorio.

Abrir con VS Code.

Asegurarse de tener Live Sass Compiler configurado (Autoprefixer activado).

El compilador generará automáticamente el archivo styles.css al guardar main.scss.

👷 Proyecto en proceso...
Desarrollado por Jimena Traipe.

