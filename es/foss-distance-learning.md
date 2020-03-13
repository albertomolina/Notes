# Software libre para el aprendizaje a distancia

Estas son algunas notas sobre software libre (FOSS) que pueden ser
útiles para aprendizaje a distancia, aquel que se realiza remotamente
para ayudar a personas en su proceso de aprendizaje.

Realizar sesiones de aprendizaje a distancia y producir materiales
incluye diferentes aspectos. Este documento intenta incluir
herramientas para diferentes escenarios, pero el principal sería:

* Producción de materiales multimedia (*screencast*, grabación de
  charlas con presentaciones, grabación de resolución de ejercicios,
  etc.), grabar mientras se habla presentando diferentes materiales,
  normalmente sobre la pantalla del ordenador. Algunos de estos
  materiales pueden grabarse y subirse posteriormente a algún servidor
  de vídeo (Youtube, Twitch o Vimeo entre otros) o ser emitidos en
  directo (*streamed live*).
  
* Editar esos materiales multimedia.

* Realizar videoconferencias con estudiantes, para clases habituales, 
  para sesiones de dudas, etc.

* Mantener contacto social con el grupo de estudiantes mediante alguna
  aplicación de mensajería o chat.

## Videoconferencia

* [Jitsi](https://jitsi.org). Conjunto de herramientas para crear
  sistemas de videoconferencia simplemente con un navegador
  ([Meet.jit.si](https://meet.jit.si). No es necesario abrir una
  cuenta, simplemente se decide el nombre de la sala y comienza una
  nueva reunión. Hay que darle permiso de acceso al micrófono y cámara
  web, compartir el enlace con los estudiantes y todo está listo para 
  empezar. También se puede usar Jitsi desde Riot (y otros clientes,
  tal como aparecen más abajo) o incluso hacer desarrollo propio
  (véase las notas sobre despliegue más abajo)

[Utilizable en la mayoría de navegadores]

## Emisión de vídeo y grabación

* [OBS Studio](https://obsproject.com/), de Open Broadcaster Software,
  una potente y completa aplicación para la emisión en directo o
  grabación. Incluye *screencast* del escritorio, grabación de la
  cámara web o desde otras fuentes de audio o vídeo. Puede usarse para
  emisión en directo o para subir a Youtube, Twitch, etc.

[Utilizable en Linux, Windows, Mac]

* [Peek](https://github.com/phw/peek). Herramienta muy sencilla para
  la grabación de *screencasts*.

[Utilizable en Linux]

* [Kazam](https://launchpad.net/kazam). Herramienta muy sencilla para
  la grabación de *screencasts*, incluyendo audio.

[Utilizable en Linux]

* [Gromit-MPX](https://github.com/bk138/gromit-mpx) una herramienta
  para anotar cualquier cosa en el escritorio. Dibujar líneas o
  cualquier cosa encima de cualquier ventana o aplicación del
  escritorio mediante un puntero o similar.

[Utilizable en Linux]

## Edidión de vídeo

* [VLC](https://vlc.media/) es principalmente un reproductor, pero con
  algunas funcionalidades de edición. Puede leer sobre éstas en 
  [A Full Guide to Use VLC as An Video Editor](https://videoconverter.wondershare.com/vlc/how-to-use-vlc-as-a-video-editor.html)
  (en inglés).

[Utilizable en Linux, Windows, Mac, Android, iOS, etc.]

* [OpenShot](https://www.openshot.org/) editor de vídeo relativamente
  sencillo, pero adecuado en muchos casos. Su principal ventaja es su
  sencillez de manejo.

[Utilizable en Linux, Windows, Mac]

* [Kdenlive](https://kdenlive.org/) Editor de vídeo relativamente
  avanzado, pero bastante sencillo de usar.

[Utilizable en Linux, Windows]

## Grupos de chat

* [Matrix](https://matrix.org/) es el estándar para comunicación en
  tiempo real. Se pueden establecer mensajes a grupos de una forma muy
  similar a Whatsapp o Telegram, pero de forma federada (se puede
  elegir el proveedor de Matrix, pero los mensajes llegarán al resto
  de personas a través de cualquier proveedor de Matrix). Una
  herramienta popular para utilizar Matrix es
  [Riot.im](https://riot.im/), que puede usarse simplemente con un
  navegador, aplicación para el móvil o aplicación de
  escritorio. Desde Riot.im también se pueden iniciar sesiones de
  Jitsi (para tener videoconferencia con las personas del grupo de
  chat).

[Utilizable en la mayorías de los navegadores, Android, iOS, Linux]

# Trucos útiles

* [How do I highlight my mouse pointer while screen recording?](https://askubuntu.com/questions/777896/how-do-i-highlight-my-mouse-pointer-while-screen-recording)
  (en inglés y para Linux).

# Todo junto

Entradas y tutoriales sobre cómo configurar todas estas herramientas
juntas y su combinación en algunos casos con herramientas que no son
de software libre o servicios:

* [Teaching on Twitch](http://matthematics.com/teach-on-twitch/) y 
  [Teaching on Twitch II: My Rig](http://matthematics.com/teach-on-twitch-my-setup/)
  de Matt Salomone (en inglés). Características, entre otras el uso de
  herramientas no libres y servicios, OBS. Incluye detalles sobre la
  configuración de hardware a usar.

# Notas sobre despliegues e instalaciones

* Jitsi (servidor) se pude desplegar de forma sencilla en una máquina
  Linux (hay paquetes para Debian y Ubuntu por ejemplo), o mediante un
  [contenedor Docker](https://github.com/jitsi/docker-jitsi-meet).

# Licencia y contribuciones

Este documento se distribuye bajo la licencia
[Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/)
(CC BY-SA 4.0) y es una traducción del [original](https://github.com/jgbarah/Notes/foss-distance-learning.html)

Todo el contenido original de este documento se puede encontrar en un
[repositorio de GitHub](https://github.com/jgbarah/Notes/).

Si quiere contribuir, por favor
[abra un *issue* con sus comentarios, sugerencias o contribuciones en este repositorio](https://github.com/jgbarah/Notes/issues/new),
o incluso mejor, [envíe una *pull request* al mismo](https://github.com/jgbarah/Notes/pulls).
