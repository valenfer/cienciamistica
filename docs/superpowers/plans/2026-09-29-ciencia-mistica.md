# Ciencia Mística Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Crear una primera web estática responsive para Ciencia Mística con nueve tarjetas ilustradas y vistas de artículo preparadas para contenido futuro.

**Architecture:** Una página HTML autocontenida con CSS y JavaScript embebidos, más nueve ilustraciones SVG locales. Los datos de las tarjetas vivirán en un array JavaScript para que añadir artículos después sea sencillo.

**Tech Stack:** HTML5, CSS3, JavaScript vanilla, SVG, servidor HTTP local de Python para verificación.

**Spec:** `docs/superpowers/specs/2026-09-29-ciencia-mistica-design.md`

## Global Constraints

- Guardar el proyecto bajo `C:\proyectos\ciencia-mistica\`.
- Mantener la primera versión estática y sin dependencias de backend.
- Usar imágenes SVG locales propias.
- Incluir diseño responsive, foco visible, botones de mínimo 44px y `prefers-reduced-motion`.
- Verificar HTTP 200, interacción, escritorio y móvil.

---

### Task 1: Crear ilustraciones SVG locales

**Files:**
- Create: `assets/dimensiones.svg`, `assets/cuerdas-calabi-yau.svg`, `assets/branas.svg`, `assets/agujeros-gusano.svg`, `assets/casimir-teleportacion.svg`, `assets/warp-whip.svg`, `assets/frontera.svg`, `assets/ruta-estudio.svg`, `assets/recursos.svg`

- [ ] Crear nueve SVG con fondo oscuro, gradientes, líneas orbitales y texto visual abstracto coherente.
- [ ] Comprobar que los nueve archivos existen y son XML legible.

### Task 2: Construir la página principal

**Files:**
- Create: `index.html`

- [ ] Crear el HTML semántico con cabecera, navegación, introducción, rejilla de tarjetas y panel de artículo.
- [ ] Añadir CSS responsive con breakpoints para móvil, tablet y escritorio, foco visible, `min-height:44px`, sin overflow horizontal y reducción de movimiento.
- [ ] Añadir el array de nueve contenidos con título, resumen, categoría, imagen SVG y cuerpo introductorio.
- [ ] Implementar JavaScript para abrir artículos, cerrar artículos, volver al índice, actualizar hash de URL y permitir navegación por teclado.
- [ ] Añadir metadatos, `lang="es"`, viewport y textos alternativos significativos.

### Task 3: Documentar y preparar ejecución local

**Files:**
- Create: `README.md`

- [ ] Documentar la estructura, ejecución con `python -m http.server`, ruta prevista de GitHub Pages y cómo añadir artículos.
- [ ] Mantener la documentación libre de credenciales y dependencias innecesarias.

### Task 4: Verificar el artefacto real

**Files:**
- Create: `preview.png` mediante captura del navegador si está disponible.

- [ ] Servir el directorio con HTTP local y comprobar `index.html` y los nueve SVG con HTTP 200.
- [ ] Comprobar por inspección que aparecen las nueve tarjetas y que el panel de artículo cambia al abrir una tarjeta.
- [ ] Verificar viewport móvil de 390px sin overflow horizontal y viewport escritorio.
- [ ] Generar preview y limpiar procesos temporales.
