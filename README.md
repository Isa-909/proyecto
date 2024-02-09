# proyecto
proyecto final
Servidor web NodeJs para mostrar histogramas, estadísticas y datos de viento en tiempo real.

Script Python para recoger y enviar datos de viento en tiempo real a través de TCP/IP.

UI:
Esta carpeta contiene los archivos nodejs. Ejecuta un servidor web, maneja websockets para la transmisión de datos en tiempo real, crea una base de datos y actúa como cliente TCP/IP para recibir datos del script python.

servidor:
esta carpeta contiene los archivos python. Muestrea la frecuencia en RaspberryPI pin3 y la convierte en la velocidad real del viento. Este script ejecuta un servidor TCP/IP en el puerto 2400. Cada cliente TCP/IP conectado recibe la velocidad actual del viento una vez por segundo.

licencia:
Todo el código del servidor es GNU General Public License v3. Estoy usando muchas librerías Javascript que tienen sus propias licencias (la mayoría MIT).

http://getbootstrap.com/getting-started/
http://d3js.org/
http://code.shutterstock.com/rickshaw/
http://jquery.com/
