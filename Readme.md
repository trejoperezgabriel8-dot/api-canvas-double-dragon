# 🎮 Ninja Double Dragon 3 - Graficación por Matriz de Índices

Este proyecto es parte del **Examen de la Unidad 1** para la materia de **Graficación por Computadora**. Consiste en el renderizado de un sprite de alta fidelidad de un Ninja del videojuego *Double Dragon 3*, utilizando exclusivamente la API de Canvas de HTML5 y lógica de programación basada en matrices.

## 🚀 ¿Qué hace esta página?
La aplicación toma una estructura de datos bidimensional (matriz) de **30x41 píxeles** y traduce cada índice numérico en un color específico sobre un lienzo digital. A diferencia de cargar una imagen `.png` o `.jpg`, aquí cada "píxel" es una figura geométrica (`rect`) dibujada individualmente mediante código.

## 🛠️ ¿Cómo funciona?

El funcionamiento se divide en tres pilares técnicos:

1. **Matriz de Índices (`Ninja_Matriz`)**: Una constante que almacena 1,230 valores numéricos. Cada número (0-4) representa una parte del diseño (piel, ropa, contorno, etc.).
2. **Diccionario de Colores (`PALETTE`)**: Un objeto que mapea los índices de la matriz con códigos hexadecimales reales extraídos del sprite original.
3. **Algoritmo de Renderizado**: Un bucle anidado (`forEach`) que recorre las 30 filas y 41 columnas, calculando la posición exacta $(x, y)$ en el Canvas para dibujar cada cuadro.

### Especificaciones Técnicas:
* **Resolución del Sprite**: 30 x 41 px.
* **Escala de Dibujo**: 1:8 (Cada píxel del sprite mide 8x8 px en pantalla).
* **Tecnologías**: HTML5 (Canvas), JavaScript Vanilla, Bootstrap 5 (Layout).

## 📂 Estructura del Proyecto
De acuerdo con los requerimientos de la actividad:
* `/assets/js/main.js` - Lógica de renderizado y matriz.
* `/assets/css/styles.css` - Estilos personalizados.
* `/assets/img/` - Recursos visuales y favicon.
* `index.html` - Estructura principal y visualización.

---
**Programador:** Gabriel Trejo Pérez  
**Materia:** Graficación por Computadora  
**Semestre:** 7mo Semestre