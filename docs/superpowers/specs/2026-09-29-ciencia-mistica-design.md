# Ciencia Mística — Especificación inicial

## Objetivo
Crear una web estática para `valenfer.github.io/cienciamistica`, dedicada a explorar temas situados entre la física teórica, la filosofía, la mística y la literatura fronteriza.

## Alcance de la primera versión
- Página principal responsive.
- Cabecera de identidad visual tecnológica y mística.
- Nueve tarjetas de contenido.
- Cada tarjeta con imagen SVG local, categoría, título y resumen.
- Vista de artículo preparada para recibir contenido ampliado posteriormente.
- Navegación interna sin dependencias de backend.
- Imágenes y estilos locales para facilitar GitHub Pages.

## Dirección visual
- Fondo oscuro azul noche/negro.
- Acentos cian, violeta, dorado y magenta.
- Retículas orbitales, geometría dimensional, constelaciones, símbolos abstractos y brillos controlados.
- Tipografía sans geométrica con detalles monoespaciados técnicos.
- Tarjetas con bordes luminosos sutiles, profundidad y estados hover/focus.

## Arquitectura
- `index.html`: estructura semántica, tarjetas y contenedor de artículos.
- `assets/*.svg`: ilustraciones locales propias.
- CSS embebido para mantener la primera versión portable.
- JavaScript embebido para abrir/cerrar artículos, navegación y filtro visual básico si procede.
- `README.md`: instrucciones locales y notas de publicación.

## Contenido inicial
1. Dimensiones extra y compactificación Kaluza-Klein.
2. Teoría de cuerdas, supergravedad y variedades de Calabi-Yau.
3. Branas, bulk, modelos ADD y Randall-Sundrum.
4. Agujeros de gusano, métrica de Alcubierre y energía negativa.
5. Efecto Casimir y teleportación cuántica.
6. Propulsión warp, WHIP y manipulación de la métrica.
7. Energía de punto cero, campos de torsión, psicotrónica y teleportación anómala como literatura fronteriza.
8. Una ruta de estudio y conceptos clave en inglés.
9. Enlaces a arXiv, APS, DTIC, Kaku y otros recursos.

## Verificación
- Comprobar que `index.html` y todos los SVG responden con HTTP 200 mediante servidor local.
- Verificar interacción de apertura y cierre de artículos.
- Comprobar renderizado de escritorio y móvil.
- Confirmar ausencia de desbordamiento horizontal en viewport móvil.
- Generar una captura de preview local.

## Fuera de alcance
- Redacción completa de artículos.
- Publicación automática en GitHub.
- Sistema de administración de contenidos.
- Fuentes externas de imágenes.
