SANDINO LOGISTICA — VERSION PARA REPOSITORIO / PWA ANDROID

Esta versión conserva el programa inicial (index.html) y elimina los archivos PNG/JPG.
Incluye únicamente HTML, webmanifest, JavaScript del Service Worker y un icono vectorial SVG escrito como texto.

SUBIR A GITHUB:
1. Descomprimir el ZIP.
2. Subir los cuatro archivos a la raíz del repositorio: index.html, manifest.webmanifest, icon.svg y sw.js.
3. Activar GitHub Pages desde Configuración > Pages > Implementar desde una rama > main > /(root).
4. Después de publicar, abrir la URL y analizarla con PWABuilder.

Nota: PWABuilder/Android puede requerir iconos rasterizados PNG para el empaquetado TWA/Android. Esta versión evita archivos PNG/JPG en el repositorio, pero no garantiza compatibilidad de empaquetado en todos los servicios.
Los registros del programa se guardan localmente en el navegador del dispositivo.
