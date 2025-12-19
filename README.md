# Laboratorio: Ingeniería de Micro-interacciones SVG Asistidas por IA

**Autora**: Marjorie Lisseth Jiménez Jiménez  
**Asignatura**: Interfaces y Multimedia  
**Institución**: Universidad Internacional del Ecuador (UIDE)  
**Fecha**: 19 de diciembre de 2025  

---

## 📌 Descripción

Este laboratorio implementa dos micro-interacciones funcionales basadas en **SVG optimizado**, siguiendo los principios de diseño minimalista (interfaces planas, colores contrastantes y tipografía legible) y accesibilidad (WCAG AA). El objetivo es reemplazar animaciones pesadas (como GIFs) por soluciones ligeras, escalables y controlables mediante CSS y JavaScript.

No se utilizaron bibliotecas externas: todo el código es **puro HTML, CSS y JavaScript**, con SVG limpio y refactorizado tras asistencia inicial de IA (prompt engineering + refactorización manual).

---

## 🛠 Micro-interacciones implementadas

| Componente | Estados | Tecnologías |
|-----------|---------|-------------|
| **Botón de cambio de modo claro/oscuro** | ☀️ Sol → transición suave → 🌙 Luna | SVG + CSS transitions + JS (event listener, `aria-label` dinámico) |
| **Botón de descarga** | ↓ Flecha → ⭕ Spinner giratorio → ✓ Check → reset | SVG + `@keyframes` + JS con temporizadores simulados (1.8 s descarga, 2 s feedback) |

Ambas micro-interacciones incluyen:
- ✅ Feedback visual inmediato (micro-escala en clic)
- ✅ Soporte de modo oscuro/claro coherente
- ✅ Accesibilidad: atributos ARIA, contraste adecuado, sin dependencia solo de color

---


> 🌐 El archivo `.html` es **autocontenidos**: basta abrirlo en cualquier navegador moderno para ejecutarlo.

---

## 🧪 Validación

- ✅ Probado en Chrome 129, Firefox 131 y Edge 129 (Windows)
- ✅ Cumple con criterios de usabilidad: cambio de estado perceptible en < 300 ms
- ✅ Código optimizado: paths SVG simplificados, sin metadatos, uso de `currentColor`

---

## 📚 Referencias (APA 7.ª ed.)

Nielsen, J., & Budiu, R. (2012). *Mobile usability*. Nielsen Norman Group.  
Garrett, J. J. (2010). *The elements of user experience: User-centered design for the web and beyond* (2.ª ed.). New Riders.  
W3C. (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. https://www.w3.org/TR/WCAG22/

---

> ✨ *“Las micro-interacciones no son decoración: son el lenguaje no verbal de la interfaz.”*  
> — Laboratorio entregado como parte del cumplimiento de ODS 4 (Educación de Calidad).
