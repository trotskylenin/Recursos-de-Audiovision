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


[*VOLVER AL INDICE*](README.md)
