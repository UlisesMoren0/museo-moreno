# Museo de la Evolución Gráfica

Museo web de Ulises Moreno para la Misión 1 de graficación (Reconstruye el Núcleo Cromático). Explica cómo evolucionó la graficación por computadora y cómo se convierte un color de RGB a HSV.

## Qué contiene

1. **Portada:** título, autor y definición propia de graficación, con una pieza central que muestra RGB(64, 128, 192) en RGB, HSV y HSL.
2. **Cinco momentos:** Whirlwind (1951), Sketchpad (1963), imágenes rasterizadas y Xerox Alto (1973), GeForce 256 (1999), Canvas y WebGL (2004 y 2011). Cada sala tiene limitación anterior, cambio, impacto, ejemplo actual, imagen y fuente.
3. **Aplicación real:** planificador de rutas a pie con la cadena usuario → problema → datos → representación → decisión y una propuesta de modelo de color.
4. **Laboratorio de color:** tres experimentos con predicción, RGB, CMY, HSV, HSL, máximo, mínimo, delta y conclusión, más una comparación de dos regiones de una imagen.
5. **Algoritmo:** pseudocódigo, función `convertRGBtoHSV(r, g, b)`, explicación de delta = 0 y tabla de pruebas.
6. **Glosario:** catorce términos con ejemplo.
7. **Conclusión, fuentes y créditos.**

## Archivos

```
index.html      página completa
styles.css      estilos propios (responsivos, foco visible, movimiento reducido)
assets/         ilustraciones SVG y favicon (ver assets/README.md)
README.md       este archivo
```

No usa frameworks, ni JavaScript, ni recursos externos: funciona como sitio estático.

## Verlo localmente

Abre `index.html` con doble clic en cualquier navegador.

## Publicarlo

1. Crea un repositorio público en GitHub y sube `index.html`, `styles.css`, `README.md` y la carpeta `assets/`.
2. En Vercel, importa el repositorio y conserva la configuración de sitio estático (sin comando de build).
3. Abre la URL de GitHub y la URL `*.vercel.app` en una ventana privada para comprobar que cargan.

## Créditos

Las ilustraciones de `assets/` son esquemas hechos para este museo con apoyo de IA (Claude, de Anthropic); no reproducen fotografías históricas. Las fuentes de cada dato están en la sección “Fuentes y créditos” de la página.
