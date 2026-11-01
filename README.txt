THREAT INTEL REPORT

Sube el contenido de esta carpeta a tu alojamiento manteniendo su estructura:

index.html
fonts/manrope-variable.woff2
fonts/ibm-plex-mono-regular.woff2
fonts/barlow-condensed-semibold.woff2
licenses/

El HTML carga las fuentes desde ./fonts. No cambies los nombres de los archivos.
No necesitas instalar dependencias ni configurar una API. El alojamiento debe
servir los WOFF2 como font/woff2; los servidores estáticos habituales lo hacen.

Las licencias de las fuentes y del código geográfico están en licenses/.
Conserva esa carpeta cuando distribuyas el proyecto.

El dataset incluido es de demostración y está identificado en la interfaz.
La importación de CSV/JSON se procesa en el navegador y dura la sesión actual.
Los favoritos se guardan por separado para cada archivo de datos en ese navegador.
