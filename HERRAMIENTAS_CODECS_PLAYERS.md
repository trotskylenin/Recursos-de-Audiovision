## HERRAMIENTAS TÉCNICAS, CODECS Y PLAYERS ##  

**-MediaInfo (Linux, Mac, Windows):**  
Herramienta fundamental para todo el que trabaja con distintos tipos
de video, sea su rol el de editor, postproductor, productor, asistente,
etc. Permite ver toda la metadata de los archivos de media, esto quiere
decir, codecs, empaquetadores, framerates, timecode y tipo de timecode,
bitrate, etc. Muy útil cuando llega un video y no sabemos con qué corno
abrirlo o como procesarlo.  
**LINK:** ***<https://mediaarea.net/es/MediaInfo>***

**-Gspot (Windows):**  
Actualmente discontinuado y de utilidad similar a MediaInfo. El punto
fuerte de este programa es que permite ver en detalle el group of
pictures (GOP) que se usa generalmente en codificaciones MPEG2 o MPEG4 y
así identificar problemas a nivel estructural dentro del video.  
**LINK:** ***<http://www.headbands.com/gspot/v26x/index.htm>***

**-Avidemux (Windows, Linux, Mac, OpenBSD):**  
Un sencillito editor de video que permite quitar algún fragmento/clip
de un video, demuxear (sacar el stream de video o audio por separado) y
que se caracteriza por tener el tipo de cuadro de cada frame, por lo que
cortando cuadros intraframe permite lograr el conocido d/efecto de
datamosh.  
**LINK:** ***<http://fixounet.free.fr/avidemux/>***  
**COMO HACER DATAMOSH:** ***<https://www.youtube.com/watch?v=mi82zK3A6bk>***

**-GraphStudioNext (Windows):**  
Visualizador en nodos de filtros directShow utilizados para reproducir
y decodificar videos. Es útil para analizar en detalle cómo se
decodifica un video al reproducirse y permite encontrar problemas o
faltantes de codecs.  
**LINK:** ***<https://github.com/cplussharp/graph-studio-next>***

**-QCTools (Windows, Linux, Mac):**  
De los creadores de MediaInfo, un toolkit de herramientas para hacer
control de calidad de videos. Sirve para ver rápidamente si un video
incumple algún estándar de difusión para TV (Croma o luma elevado,
niveles de loudness fuera del standard, etc.). No reemplaza a los
instrumentos diseñados para ello pero es bueno para hacer QC rápido y de
forma casera.  
**LINK:** ***<https://mediaarea.net/QCTools>***

**-TCCalc (Windows):**  
Calculadora de timecodes. Ideal para cuando hay que calcular
duraciones, convertir a frames, convertir entre timecodes dropframe y no
dropframe, etc.  
**LINK:** ***<http://www.drastic.tv/productsmenu-56/videoiosoftwarelist/76-videosw/utilities/181-tccalc-drastic-time-code-calculator>***

**-FFMPEG (Windows, Linux, Mac):**  
Un kit de herramientas de video que permiten stremear, transcodificar,
grabar, reproducir y analizar video. Funciona por línea de comandos pero
también hay varias interfaces graficas que se pueden bajar.  
**LINK:** ***<https://ffmpeg.org/>***  
**ALGUNAS GUI:** ***<https://github.com/amiaopensource/ffmpeg-amia-wiki/wiki/3)-Graphical-User-Interface-Applications-using-FFmpeg>***

**-Handbrake (Windows, Linux, Mac):**  
Uno de los pocos transcoders con interfaz gráfica gratuitos que
conozco. De fondo usa FFMPEG, sirve para transcodificar solo a los
formatos más populares. La curiosidad es que soporta el códec de última
generación h265.  
**LINK:** ***<https://handbrake.fr/>***

**-Super (Windows):**  
Un gui de FFMPEG que permite convertir a video 3D en distintos
formatos así como también reproducir ese tipo de contenido.  
**LINK:** ***<http://www.erightsoft.com/SUPER.html>***

**-FFMPEG Batch converter (Windows):**  
Otro gui de FFMPEG que permite convertir multiples videos en simultaneo a distintos formatos.  
**LINK:** ***<https://sourceforge.net/projects/ffmpeg-batch/>***

**-Shutter Encoder (Windows, Linux, Mac):**  
La mejor y mas completa GUI de FFMPEG ideal para editores. Soporta muchisimas funciones y codecs profesionales de edicion y transmision (incluyendo codecs aun experimentales como AV1). Además de eso soporta funciones de Rewrapping, deteccion de cortes, deteccion de Media Offline, descarga de videos directo de Youtube, carga automatica a Wetransfer o envio por FTP o mail, pegado de subtitulos, etc.  
Sin dudas el transcoder gratuito mas completo y mas simple de usar que existe. Incluye para Windows una version portable y para Linux una version Appimage, por lo que practicamente puede correr en cualquier distribucion.  
**LINK:** ***<https://www.shutterencoder.com/en/>***  

**-FFASTrans (Windows):**  
Una gui gratuita de FFMPEG y AVISynth que permite armar workflows automaticos de transcoding
basados en nodos al estilo similar de Telestream Vantage (un sistema que vale decenas
de miles de dolares). Permite ejecutarse como servicio y ser controlado via
Rest API, asi como realizar la transcodificacion usando un farm de equipos, realizar quemado de timecode,
insercion de logos, bumpers, closes, etc. Una herramienta gratis excelente y única en su estilo.  
**LINK:** ***<http://www.ffastrans.com>***  

**-OpenDCP (Windows, Linux, Mac):**  
Un transcoder multiplataforma dedicado a convertir video a paquetes
DCP, el tipo de formato que se utiliza para la reproducción en cines
digitales.  
**LINK:** ***<https://www.opendcp.org/>***

**-K-lite Codec Pack (Windows):**  
Conjunto de codecs y filtros directshow para reproducir una gran
variedad de formatos populares de video en cualquier reproductor
multimedia.  
**LINK:** ***<https://www.codecguide.com/download_kl.htm>***

**-Avid Codecs LE (Windows, Mac):**  
Codecs para reproducir formatos de Avid en reproductor Quicktime. Hoy
en día Quicktime esta discontinuado en PC, por lo que es INSEGURO Y
ALTAMENTE NO RECOMENDABLE utilizarlo en Windows.  
**LINK:** ***<http://avid.force.com/pkb/articles/en_US/download/Avid-QuickTime-Codecs-LE>***

**-VLC (Windows, Linux, Mac, Android):**  
No hay que presentarlo mucho, es un reproductor que corre en todas las
plataformas y que reproduce casi todo tipo de video. Es tan bueno que
hasta te chamuya los videos que están corruptos.  
**LINK:** ***<http://www.videolan.org/vlc/index.es.html>***

**-Sony XDCAM Viewer (Windows):**  
Player de facto para reproducir contenido MXF XDCAM HD, estándar en la
industria televisiva. La mayoría de los materiales en los canales de
televisión se manejan en formato MXF.  
**LINK:** ***<http://www.pro.sony.eu/pro/lang/en/is/support/software/1237485726571>***

**-GoPro VR Player (Windows, Linux, Mac):**  
Reproductor de videos en 360.  
**LINK:** ***<http://www.kolor.com/gopro-vr-player/>***

**-Plex Media Server (Windows, Linux, Mac y otros):**  
No es del ambito laboral pero merecía una mención. Básicamente es un
servidor de archivos multimedia basado en el antiguo XBMC que tiene
clientes para android, smarts tv, playstation3 y largo etc. Un golazo
para el coleccionista de cine y series (principalmente si se lo combina
con Couchpotato y Sickrage!)  
**LINK:** ***<https://www.plex.tv>***  
**PARA LOS CURIOSOS:** ***<https://github.com/htpcBeginner/AtoMiC-ToolKit>***  

**-Youtube-dl (Windows, Linux, Mac):**  
Este potente script desarrollado en Python de codigo abierto y gratuito permite descargar rapidamente video de mas de 200 paginas web incluyendo Facebook, Youtube, Vimeo y otras.
Su funcionamiento es por linea de comando, pero es bastante sencillo de usar. El unico prerequisito que tiene es instalar previamente Python2 o 3.  
**LINK:** ***<https://yt-dl.org/>***  
**EXPLICACION DE INSTALACION Y USO:** ***<https://www.genbeta.com/a-fondo/asi-es-youtube-dl-un-software-libre-para-bajar-videos-de-youtube-o-facebook-desde-la-linea-de-comandos>***  

**-Youtube-DLG (Windows, Linux, Mac):**  
Youtube-DLG es una interfaz gráfica de Youtube-dl. Permite descargar videos de varias paginas web, incluyendo Youtube, Vimeo, Facebook y otras, pero en vez de funcionar por linea de comandos como youtube-dl, tiene una interfaz intuitiva, comoda, facil y rapida para el usuario final. La facilidad de actualizar el binario de Youtube-dl desde la misma aplicacion, es otra gran ventaja que tiene este software.  
**LINK:** ***<https://mrs0m30n3.github.io/youtube-dl-gui/>***  

**-Avidd (Android):**  
Interfaz gráfica de Youtube-dl que corre en cualquier celular con Android. Permite bajar facilmente videos de muchisimas webs.
Por razones obvias no está disponible en el Google Play Store, por lo que hay que bajar directamente el apk desde la web e instalarlo en el celular.  
**LINK:** ***<http://www.aviddapp.com/>***  

**-SpotifyDownload (Windows, Linux, Mac):**  
Spotify Download es un script desarrollado completamente en Go Lang que hace uso de la descarga de Youtube y la posibilidad de exportar las listas de Spotify en formato .json para descargar de forma automatica todas las canciones de una Playlist de Spotify desde Youtube.  
El funcionamiento es bastante sencillo, aunque requiere tener Spotify Premium y conocimientos básicos de uso de CMD / terminal:  
Primero se abre en Spotify la playlist que se desea descargar, se presiona en la opcion de compartir y luego en la que dice "Copiar enlace de la lista".  
Ya con ese link copiado se ejecuta desde la terminal del sistema operativo el script y cuando el script lo solicita se le pega la url de la lista copiada y se le da Enter.  
El programa se encargara de generar la carpeta con el nombre de la playlist y bajar todas las canciones que pueda de Youtube y luego convertirlas a mp3 usando FFMPEG.  
Probablemente no encuentre todas, pero nos ahorrará el trabajo de descargar manualmente una buena cantidad de ellas.  
**LINK:** ***<https://github.com/schollz/spotifydownload>***  

**-Spotify-Downloader (Windows, Linux, Mac):**  
Una variante al script anterior, pero este está realizado completamente en Python3.  
La instalacion se hace con pip por lo que requiere conocimientos de programacion basicos, en contraparte ofrece muchas mas opciones que el script anterior y permite incluso bajar las canciones desde listas de Youtube directamente o elegir manualmente que cancion bajar, entre otras opciones varias.  
**LINK:** ***<https://github.com/ritiek/spotify-downloader>***  

**-RClone (Windows, Linux, Mac):**  
Considerado "La navaja suiza del storage en la red", este programa por linea de comandos permite administrar contenido en mas de 40 servicios distintos de almacenamiento en la nube, incluyendo entre otros Amazon S3, Mega, Box, Dropbox, Google Drive, OneDrive, ownCloud, Yandex, SugarSync, etc.  
**LINK:** ***<https://rclone.org/>***  

**-Captura (Windows):**  
Programa gratuito y de código abierto, con una versión portable, que permite grabar la pantalla de manera muy sencilla, asi como tambien el audio del equipo, las teclas presionadas y los clicks del mouse. Interesante alternativa gratuita a Camstasia.
Permite sacar el video resultante en distintos formatos, pero para ello necesita tener instalado previamente FFMPEG y configurar la ruta donde se encuentra.  
**LINK:** ***<https://mathewsachin.github.io/Captura/>***  

**-Flameshot (Linux):**  
Programa gratuito y de código abierto para tomar capturas de pantallas y hacer anotaciones. Se consigue precompilado para Linux, para Windows hay que compilarlo manualmente, aunque para este último sistema existen alternativas mas completas como Greenshot.  
**LINK:** ***<https://github.com/flameshot-org/flameshot>***  

**-Greenshot (Windows):**  
Programa gratuito para tomar capturas de pantallas (o partes de ella) y hacer anotaciones sobre ellas. Solo corre en Windows.  
**LINK:** ***<https://getgreenshot.org/>***  

[*VOLVER AL INDICE*](README.md)
