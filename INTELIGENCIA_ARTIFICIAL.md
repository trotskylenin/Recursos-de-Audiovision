## INTELIGENCIA ARTIFICIAL ##

**-DAIN-APP (Windows):**  
DAIN-APP es una aplicación gratuita con interfaz gráfica que utiliza de fondo el codigo de DAIN (Depth Aware Video Frame Interpolation).
DAIN es básicamente un algoritmo de IA que permite aumentar la resolución temporal o cadencia de cuadros por segundo que tiene un video.
Para ello reconoce la profundidad de las imagenes y recrea (interpola) cuadros nuevos en base al movimiento de los objetos que predominan en una secuencia de cuadros, es decir, los que estan mas al frente por sobre los que estan en el fondo. Solo funciona con placas NVIDIA compatibles con CUDA.  
**LINK:** ***<https://grisk.itch.io/dain-app?fbclid=IwAR1xZxwA4QG8EioRL4avmmhT0Y6-7JyLM0ZOdMckZHBcK7CmQixAqU4nmf4>***  

**-DeOldify (Linux, Google Colab):**  
DeOldify es un proyecto basado en Deep Learning para colorear y restaurar imágenes y videos en blanco y negro.
Este software es ideal para modernizar fotografias o videos antiguos.  
**EJEMPLO:** ***<https://www.youtube.com/watch?v=2Jdkur3-Hns&fbclid=IwAR2Kfd-KrvTcWEsiBxAH3v2oeJNhGtENeHzgyOBb7eIBSQjuks-JljNBMuk>***  
**EXPLICACION DE USO (En Ingles):** ***<https://www.youtube.com/watch?v=VaEl0faDw38>***  
**LINK:** ***<https://github.com/jantic/DeOldify>***  

**-DeepRemaster (Linux):**
Este codigo fuente de una investigación realizada para un paper presentado en el SIGGRAPH ASIA 2019 permite remasterizar semiautomáticamente videos antiguos utilizando Deep Convolutional Networks (un tipo de redes neuronales). Esta red es entrenada con vides de deterioro basados en ejemplos, lo que luego permite eliminar automáticamente los ruidos de la película, mejorar el contraste y la nitidez, y agregar color basado en marcos de color de referencia creados manualmente.  
**LINK:** ***<https://github.com/satoshiiizuka/siggraphasia2019_remastering>***  


**-Gigapixel AI for video (Windows):**  
Gigapixel AI for video es un programa pago de la suite de aplicaciones Topaz, que por medio del uso de algoritmos de inteligencia artificial permite escalar videos a resoluciones de hasta 8K, recreando los píxeles faltantes reconociendo los elementos de la imagen.
Los resultados que se obtienen son bastante superiores a los que se pueden obtener con los metodos tradicionales de interpolación de pixeles.
Si bien el software es pago, al estar la version para video todavia en su versión beta se puede descargar y utilizar de forma gratuita.  
**COMPARACION CON OTROS METODOS:** ***<https://www.youtube.com/watch?v=HTcJjCwsY_Q>***  
**LINK:** ***<https://videoai.topazlabs.com/beta>***  

**-DeepFaceLab (Windows, forks para Linux y Google Colab):**  
DeepFaceLab se autoproclama como el lider del software para crear DeepFakes (mas del 95% de los videos de DeepFake son hechos con este software). Los Deep Fakes son básicamente videos que se logran utilizando algoritmos de inteligencia artificial que logran identificar los rasgos y gestos de la cara de una persona y reemplazarlos con los de otra persona, logrando resultados sumamente realistas.
Para obtener buenos resultados todos los programas de Deep Fake requieren entrenar durante dias a la inteligencia artificial para construir primero un modelo de las caras que desea aprender en base a un conjunto de fotografias de la misma, y luego un tiempo para realizar la composición propiamente dicha de forma semi automatica. Los mejores y mas rapidos resultados se logran utilizando placas de video NVIDIA muy potentes como las Tesla.  
Tambien es posible correr este software en plataformas de computación en la nube como Google Colab, que nos proporciona placas de video potentes para realizar este tipo de tareas.  
**LINK:** ***<https://github.com/iperov/DeepFaceLab>***  
**GUIA PARA PRINCIPIANTES:** ***<https://www.youtube.com/watch?v=t59gRbpYMiY>***  
**LINK A FORK PARA  LINUX:** ***<https://github.com/lbfs/DeepFaceLab_Linux>***  
**LINK A FORK PARA GOOGLE COLAB:** ***<https://github.com/chervonij/DFL-Colab>***  

**-FaceSwap (Windows, Linux, Mac):**  
Faceswap también se autoproclama como el líder del software multiplataforma gratuito y de código abierto de DeepFake. El mismo proporciona diversos algoritmos de inteligencia artificial para hacer el reemplazo de caras y usando una interfaz gráfica amigable con el usuario, que lo hace mas simple de usar que DeepFaceLab.
Se caracteriza además por su buena y completa documentación.  
**LINK:** ***https://faceswap.dev/?fbclid=IwAR2k9pwRHVotKllmQbUZwlM_5x7z06LbkQ4QejSmzbpNrHMjZBtGytngLfg***

**-The Sound of Pixels (Linux):**  
ECCV18, también conocido como "The Sound of Pixels", es un algoritmo de IA que aprende de qué zonas de un video provienen los sonidos y permite separar en pistas esas zonas para poder luego hacer retoques en la mezcla.  
Actualmente funciona solo con dúos instrumentales, pero están en vistas de agrandar la base de datos de instrumentos y la cantidad de instrumentos simultáneos.  
**LINK:** ***<https://github.com/hangzhaomit/Sound-of-Pixels>***  

**-DEMUCS (Windows, Mac):**  
DEMUCS, un proyecto reciente desarrollado por Facebook, basado en IA, para deconstruir canciones en cuatro pistas: voces, batería, línea de bajo y otros (que incluye teclados y guitarras, por ejemplo).
Con algunas canciones funciona de maravilla, con otras no tanto. Lo bueno es que logra mejores resultados que tecnologías anteriores, como Open Unmix, Spleeter y Wave U Net, entre otras.  
Se puede probar en Windows y en macOS. Por el momento no existe ninguna interfaz gráfica para usarlo. Hay que instalar Anaconda (plataforma libre de Python orientada a data science y deep learning) y tirar comandos en la consola, con privilegios de administrador.  
Al ejecutarlo, se descarga una gran base de datos de casos previos (pesa 2,5 GB aprox). Si contamos con una tarjeta gráfica con más de 8 GB se puede usar un comando alternativo, que demora diez veces más, pero logra aún mejores resultados (mayor calidad y menor contaminación entre pistas separadas).  
**LINK:** ***<https://github.com/facebookresearch/demucs>***  

[*VOLVER AL INDICE*](README.md)
