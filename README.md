# 🎯 Caso PixelPerfect Studio
**Módulo 3 – Metodologías de organización y modularización de estilos**

---

## 📌 Descripción
Este proyecto corresponde al análisis y práctica del caso **PixelPerfect Studio**, donde se aplican metodologías de organización y modularización de estilos (BEM + SMACSS) para lograr un código CSS escalable, mantenible y colaborativo.

---

## 🎨 Branding
- **Paleta:** Celeste (#3498db), Verde (#10b981), Blanco (#ffffff).
- **Estilo:** Interfaces limpias, con bordes redondeados y sombras suaves.
- **Tipografía:** Jerarquía clara entre títulos, descripciones y botones.

---

## 📂 Estructura de carpetas

scss/ 
    ├── base/_reset.scss 
    ├── layout/_grid.scss 
    ├── components/_card.scss 
    ├── utilities/_variables.scss 
                /_mixins.scss 
    └── main.scss 
index.html


---

## 🧩 Convenciones BEM
- **Bloque:** `.card`
- **Elemento:** `.card__title`, `.card__description`, `.card__button`
- **Modificador:** `.card--dark`, `.card__button--primary`

---

## ✅ Checklist de buenas prácticas
- [ ] Usar nombres de clase BEM consistentes.  
- [ ] Definir variables globales en `utilities/_variables.scss`.  
- [ ] Reutilizar mixins para bordes, sombras y media queries.  
- [ ] Evitar reglas vacías y duplicadas.  
- [ ] Documentar cada componente en su archivo SCSS.  
- [ ] Verificar responsive y accesibilidad básica.  

---

## 🚀 Cómo ejecutar
1. Instalar **Live Sass Compiler** en VS Code.  
2. Compilar `main.scss` → genera `styles.css`.  
3. Instalar **Live Server** en VS Code.  
4. Abrir `index.html` y visualizar el componente.  

---

## ✨ Reflexión
Este enfoque permite mantener estilos organizados, escalables y fáciles de colaborar en equipos grandes, evitando conflictos y mejorando la productividad.

##Proyecto en proceso *