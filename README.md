# IECED — reconstrucción visual local

Proyecto estático compatible con GitHub Pages. La navegación entre apartados se realiza dentro de `index.html?page=...`; los enlaces del menú no redirigen al dominio oficial.

## Archivos
- `index.html`: estructura principal.
- `styles.css`: estilos responsive.
- `app.js`: navegación interna y contenido por apartado.
- `assets/`: imágenes y recursos extraídos del respaldo proporcionado.

## Importante sobre fidelidad del contenido
El respaldo recibido contiene una captura HTML de la página de inicio y un paquete de recursos, no los HTML de todas las páginas internas. Se ha reconstruido la portada usando los textos e imágenes del respaldo y se han incorporado apartados internos con contenido verificado públicamente cuando estaba disponible. En las secciones cuyo contenido completo no estaba en el respaldo, se indica expresamente que falta la fuente original en lugar de inventar información médica, precios, coberturas o instrucciones.

## Publicar en GitHub Pages
Sube el contenido de esta carpeta al repositorio y configura Settings → Pages → Deploy from a branch → `main` → `/ (root)`. No agregues un dominio personalizado para la prueba.
