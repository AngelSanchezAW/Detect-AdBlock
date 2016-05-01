<h1>Detect AdBlock</h1>
<strong>Detect AdBlock</strong> es una aplicación que nos ayuda a identificar que usuarios están utilizando un bloqueador de anuncios y que usuarios no lo hacen, con dicha aplicación se pueden desarrollar soluciones ante esta problemática, desde recolectar datos con Google Analitics hasta bloquear contenido.
<br><br>
Detect AdBlock funciona de una manera muy simple. Cuando uno visita un sitio web se descarga el fichero HTML junto con sus referencias a ficheros JavaSript, CSS, imágenes, videos, etc. AdBlock analiza todos los ficheros y realiza una comparativa con su “lista negra”, si encuentra alguna coincidencia, ese dato no se carga. Teniendo conocimiento de cómo funciona AdBlock nosotros podemos crear un archivo que coincida con la lista negra (advertisement.js) y verificar si este se carga o no, si el archivo se carga damos por hecho que el usuario no está utilizando un bloqueador de anuncios, de lo contrario nos damos cuenta que hace uso de uno. De esta manera es como funciona Detect AdBlock.
<h2>Uso simple de Detect AdBlock</h2>
1.-Descargamos el archivo “advertisement.js” que se encuentra en la carpeta JS y lo colocamos dentro de una carpeta en tu proyecto.
2.-Copiar el código del archivo index.html que se encuentra dentro de la carpeta DetectarAdBlock y colócalo en la página que deseas analizar.
<br><br>
Nota: Hay que modificar el código que copiamos de index.html: cambia la url del archivo “advertisement.js” y coloca que acción se realizara cuando se detecte el uso de AdBlock y cuando no se detecte.
<h2>Detect AdBlock + Google Analytics</h2>
1.-Descargamos el archivo “advertisement.js” que se encuentra en la carpeta JS y lo colocamos dentro de una carpeta en tu proyecto.
2.-Copiar el código del archivo index.html que se encuentra dentro de la carpeta GoogleAnalytics y colocalo en la página que deseas analizar.
<br><br>
Nota: Hay que modificar el código que copiamos de index.html: cambia la url del archivo “advertisement.js”. El segundo script debe de ir después del código de seguimiento de Google Analitics.
<br><br>
Para ver si funciona, iremos a Google Analytics &gt; Tiempo real &gt; Eventos. En la pantalla podremos ver el número de usuarios que tienen activo o no el bloqueo de publicidad.
<br><br>
Para analizar los datos recogidos a lo largo del tiempo hay que ir a Comportamiento &gt; Eventos &gt; Visión general para ver los eventos recogidos.
<br><br>
Si pinchamos en el evento que nos interesa (“ADBLOCK”) veremos la siguiente pantalla.
<br><br>
Así, “active” se refiere a los usuarios que tienen instaladas aplicaciones que bloquean anuncios, mientras que “off” hace referencia a la cantidad de usuarios que no están bloqueando los anuncios de tu web.
<br><br>
Con estos datos podemos decidir qué acción tomar con dicho usuario. Por ejemplo, mostrar un mensaje de aviso y no dejarles acceder a la información.