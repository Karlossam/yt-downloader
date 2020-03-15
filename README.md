# yt-downloader
Este es un pequeño proyecto para crear un programilla que nos permita descargar de sitis varios como youtube, soundcloud, etc ya sean playlist, canales, audio, video, etc. Espero que guste

Tiene 2 dependencias principales:

El módulo <strong>youtube-dl</strong> que lo consigues introduciendo el comando:

pip install youtube_dl

Y el programa ffmpeg para la conversión de video a audio, descargado de la página: https://www.ffmpeg.org/download.html

En el caso de linux no me dió problema, con descargarlo e instalarlo todo nice.

Con windows una vez descargado debes seguir ciertos pasos para añadirlo a las varaibles de entorno, pasos perfectamente descritos en: https://www.youtube.com/watch?v=DpsJH1keQPA&t


<h1>Pequeña guía de uso</h1>

Para usarlo vale introducir el comando:

python3 yt_downloader.py -u <url a descargar> #Esto descargará el video de lo que pongas

Tienes además la opción de añadir:
-a --> descarga el audio
-g <tag> --> añade tag al nombre del archivo descargado, puede servir para organizartelos luego.
  
Y yasta, así de facil. Al usarlo comprobara si tienes una carpeta llamada yt_downloads dentro de Descargas en tu carpeta de usuario, si no la creará.  


