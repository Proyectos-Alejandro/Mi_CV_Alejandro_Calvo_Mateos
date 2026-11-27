# CV de Alejandro Calvo Mateos

Mi currículum como página web: estudiante de 2º de ASIR en la UAX, con especialización en ciberseguridad en Xtart.

**Verlo en línea:** https://proyectos-alejandro.github.io/Mi_CV_Alejandro_Calvo_Mateos/

## Qué tiene

- Una sola página en HTML y CSS, sin frameworks ni JavaScript (solo el botón de imprimir).
- Modo claro y oscuro según el sistema.
- Adaptada a móvil.
- Botón **Descargar en PDF**: abre la impresión del navegador con un diseño pensado para A4, y en papel se ven las direcciones de los enlaces.
- La franja de colores de arriba sigue el orden de un cable de red T568B, y esos mismos colores marcan proyectos y habilidades.

## Estructura

```
index.html               el CV
assets/css/cv.css
assets/img/favicon.svg
```

## Cómo cambiarlo

- **Foto:** guarda la foto como `assets/img/foto.jpg` y sustituye el `div` con las iniciales (hay un comentario en `index.html` que lo explica).
- **Contenido:** cada sección está en un `<section class="bloque">` de `index.html`.

Para verlo en local basta con abrir `index.html` en el navegador, o servir la carpeta:

```bash
python -m http.server 8000
```

Se publica con GitHub Pages desde la rama `main`.
