INSTRUCCIONES PARA GITHUB PAGES

1) En tu repositorio, creá esta estructura:

   /index.html
   /vendor/zxing-browser.js

2) Subí el index.html incluido en esta carpeta.

3) Descargá la librería ZXing desde:

   https://unpkg.com/@zxing/browser@0.1.5/umd/zxing-browser.js

4) Guardala en tu repositorio exactamente como:

   /vendor/zxing-browser.js

5) Publicá/actualizá GitHub Pages y abrí la URL HTTPS.

IMPORTANTE:
- No abras el HTML como archivo local si querés usar cámara. Debe correr en HTTPS.
- Esta versión ya no intenta cargar ZXing desde un CDN dinámicamente.
- Si falta /vendor/zxing-browser.js, la cámara se ve pero no va a leer códigos.
