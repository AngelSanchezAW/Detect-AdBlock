<h1>Detect AdBlock</h1>
<a href="#simple">Uso simple de Detect AdBlock</a>
<a href="analytics">Detect AdBlock + Google Analytics</a>
<strong>Detect AdBlock</strong> es una aplicación que nos ayuda a identificar que usuarios están utilizando un bloqueador de anuncios y que usuarios no lo hacen, con dicha aplicación se pueden desarrollar soluciones ante esta problemática, desde recolectar datos con <strong>Google Analitics</strong> hasta bloquear contenido.
<br><br>
<strong>Detect AdBlock</strong> funciona de una manera muy simple. Cuando uno visita un sitio web se descarga el fichero HTML junto con sus referencias a ficheros <strong>JavaScript, CSS, imágenes, videos, etc.</strong> AdBlock analiza todos los ficheros y realiza una comparativa con su <strong>“lista negra”</strong>, si encuentra alguna coincidencia, ese dato no se carga. Teniendo conocimiento de cómo funciona <strong>AdBlock</strong> nosotros podemos crear un archivo que coincida con la lista negra <strong>(advertisement.js)</strong> y verificar si este se carga o no, si el archivo se carga damos por hecho que el usuario no está utilizando un bloqueador de anuncios, de lo contrario nos damos cuenta que hace uso de uno. De esta manera es como funciona Detect AdBlock.
<a name="simple"><h2>Uso simple de Detect AdBlock</h2></a>
<strong>1.-</strong>Descargamos el archivo <strong>“advertisement.js”</strong> que se encuentra en la carpeta <strong>JS</strong> y lo colocamos dentro de una carpeta en tu proyecto.
<br>
<strong>2.-</strong>Copiar el código del archivo <strong>index.html</strong> que se encuentra dentro de la carpeta <strong>DetectarAdBlock</strong> y colócalo en la página que deseas analizar.
<br><br>
<i><strong>Nota:</strong> Hay que modificar el código que copiamos de index.html: cambia la url del archivo “advertisement.js” y coloca que acción se realizara cuando se detecte el uso de AdBlock y cuando no se detecte.</i>
<a name="analytics"><h2>Detect AdBlock + Google Analytics</h2></a>
<strong>1.-</strong>Descargamos el archivo <strong>“advertisement.js”</strong> que se encuentra en la carpeta <strong>JS</strong> y lo colocamos dentro de una carpeta en tu proyecto.
<br>
<strong>2.-</strong>Copiar el código del archivo <strong>index.html</strong> que se encuentra dentro de la carpeta <strong>GoogleAnalytics</strong> y colocalo en la página que deseas analizar.
<br><br>
<i><strong>Nota:</strong> Hay que modificar el código que copiamos de index.html: cambia la url del archivo “advertisement.js”. El segundo script debe de ir después del código de seguimiento de Google Analitics.</i>
<br><br>
Para ver si funciona, iremos a Google Analytics &gt; Tiempo real &gt; Eventos. En la pantalla podremos ver el número de usuarios que tienen activo o no el bloqueo de publicidad.
<br>
<img src="http://www.azulweb.net/wp-content/uploads/2016/05/1.png">
<br><br>
Para analizar los datos recogidos a lo largo del tiempo hay que ir a Comportamiento &gt; Eventos &gt; Visión general para ver los eventos recogidos.
<br>
<img src="http://www.azulweb.net/wp-content/uploads/2016/05/2.png">
<br><br>
Si pinchamos en el evento que nos interesa (“ADBLOCK”) veremos la siguiente pantalla.
<br>
<img src="http://www.azulweb.net/wp-content/uploads/2016/05/4.png">
<br><br>
Así, “active” se refiere a los usuarios que tienen instaladas aplicaciones que bloquean anuncios, mientras que “off” hace referencia a la cantidad de usuarios que no están bloqueando los anuncios de tu web.
<br>
<img src="http://www.azulweb.net/wp-content/uploads/2016/05/5.png">
<br><br>
Con estos datos podemos decidir qué acción tomar con dicho usuario. Por ejemplo, mostrar un mensaje de aviso y no dejarles acceder a la información.