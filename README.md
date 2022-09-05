![red](https://github.com/MarianneTeixido/manifiestas/blob/main/img/icon2.png) 

# manifiest(ia)s

para intérprete vocal y live coder


# Partitura gráfica

El espacio de la [partitura](https://github.com/MarianneTeixido/manifiestas/blob/main/pdf/mnfts-scr.pdf) representa una cartografía sonora de la marcha del 8 de marzo en la Ciudad de México. El recorrido visual establece analogías del trayecto comprendido desde la Glorieta de Insurgentes a la Okupa feminsita en la CNDH en República de Cuba. En el sistema, la computadora y le intérprete vocal realizarán dicho recorrido retroalimentándonse. 

# Archivos de audio

Para la ejecución de la pieza, es necesario que une live coder compile en tiempo real el código de SuperCollider escrito para la obra. Para compilar el proyecto es necesario instalar la librería Realtime Audio Variational autoEncoder para usar los UGEN's de este Quark, además de tener un modelo de RAVE (Realtime Audio Variational autoEncoder) entrenado. Dicho modelo debe de estar entrenado con una acervo de audios normalizado. El entrenamiento del modelo para **manifiest(ia)s** usó una *small database* a partir de las grabaciones realizadas con la intérprete vocal Amanda Alfita. 

Del entrenamiento de la red neuronal, *RAVE* recontruyó la voz de Amanda

[Audios](https://github.com/MarianneTeixido/manifiestas/tree/main/audio) reconstruídos de la base de datos

Estos audios son usados como input en el sistema para la interacción durante la interpretación. 

# Electrónica al vuelo

El siguiente código está diseñado para ejecutarse y modificarse en tiempo real por une live coder. Este se encargará de conectar el audio a una salida cuadrafónica, así como recibir la señal del micrófono como fuente de entrada para SuperCollider. Por otro lado, desplegará la consola en un sistema de proyección para imprimir las frases reconstruídas de la base de datos de textos de **manifiest(ia)s** 

Código [SuperCollider](https://github.com/MarianneTeixido/manifiestas/blob/main/sc/manifiest(ia)s.scd) - audio  

Código [Python](https://github.com/MarianneTeixido/manifiestas/blob/main/manifiestas.py)               - texto  

# Recursos
- [Repositorio RAVE](https://github.com/acids-ircam/RAVE)

# Licencia

manifiest(ia)s es una obra sonoro-textual con electrónica al vuelo disponible bajo los término establecidos en la Licencia de producción de pares feministas (F2F). Para mayor información sobre su uso y posibilidades visitar la página del hacklab feminista [La Bekka](https://labekka.red/licencia-f2f/)


