---
title: Instalar RiiConnect24 en vWii
---

{% include toc title="Tabla de contenido" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Logotipo de RiiConnect24](/images/WiiRC24Logo.jpg)

En esta guía te explicaremos cómo instalar [RiiConnect24](https://rc24.xyz) en el modo Wii de tu consola Wii U (vWii), junto con los canales Miirame, Nintendo, Opiniones y Noticias, además de un parche para forzar el formato de imágen 4:3.

Debido a que algunas funciones encontradas en el Wii original no están presentes en el vWii, sólo es posible usar RiiConnect24 de forma parcial. Echa un vistazo a la sección [Servicios soportados](#servicios-soportados) para más detalles.
{: .notice--warning}

#### Advertencias

**NO** nos haremos responsables si tu consola se brickea o la dañas de cualquier otra forma. Si sigues los pasos de esta guía de forma exacta, no deberías tener ningún tipo de problema.
{: .notice--warning}

**NO** uses esta guía en ninguna otra consola que no sea el vWii (modo Wii de Wii U). Si estás buscando instalar RiiConnect24 en un Wii original, por favor sigue [esta guía](riiconnect24). Si deseas usar RiiConnect24 en el emulador Dolphin, por favor sigue [esta guía](/riiconnect24-dolphin).
{: .notice--warning}

#### Requisitos

* Una computadora o dispositivo móvil con conexión a Internet y que pueda leer tarjetas SD.
* Una tarjeta SD de por lo menos 2GB formateada como FAT32. Las tarjetas SDXC formateadas como FAT32 también pueden funcionar.
* Una consola Wii U que sea capaz de lanzar el Homebrew Launcher (ya sea mediante el exploit del navegador de Internet, Haxchi o Coldboot Haxchi). **Si tu Wii U no está modificado, por favor sigue[esta guía](https://wiiuguide.xyz), así como también la [guía de modificación de vWii](https://wiiuguide.xyz/#/vwii-modding) y después regresa a esta guía.**
* [RiiConnect24 Patcher](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

Después de seguir la guía anteriormente mencionada, deberías de tener:
* Un respaldo de la NAND de tu vWii y sus respectivas claves (¡¡guarda estos archivos en un lugar seguro!!)
* Tener el Canal Homebrew instalado
* Tener los d2x cIOS instalados (IOS249, IOS250 e IOS251)
* Tener el IOS 80 parcheado
{: .notice--info}

#### Instrucciones

Si no puedes usar el parcheador, por favor [sigue la guía manual](https://pad.snopyta.org/s/rJ2N0B1XU), para instalar RiiConnect24. El resultado final será el mismo sin importar el método que hayas usado.
{: .notice--info}

##### Sección I - Ejecutando el parche

Usando el RiiConnect24 Patcher que has descargado en [los requisitos](#requisitos), estarás descargando y parcheando el IOS 31, así como los canales Noticias, Opiniones, Nintendo y Miirame para poder usarlos en tu vWii.

1. Ejecuta `RiiConnect24Patcher.bat` en Windows o `RiiConnect24Patcher.sh` en sistemas Unix al escribir bash y luego arrastra el `RiiConnect24Patcher.sh` en el terminal, luego presiona enter. Debería verse así `bash RiiConnect24Patcher.sh`. Sigue las instrucciones en pantalla

2. Confirma que después de ejecutar el parcheador, tengas 3 carpetas. Estarán en la misma carpeta donde se encuentra `RiiConnect24Patcher.bat` y en tu tarjeta SD (por supuesto, si seleccionaste una opción para que el patcher lo haga).
   - Si el parche no ha copiado los archivos a la tarjeta SD, por favor copia las tres carpetas anteriormente mencionadas a la raíz de tu tarjeta SD.

##### Sección II - Instalando los WADs parcheados

1. Abre el Canal Homebrew
2. Lanza Wii Mod Lite
3. Usando la cruz de control en tu Wiimote, selecciona `WAD Manager` (Administrador de WADs), y luego abre la carpeta `wad`.
4. Señala todos los WADs con `RiiConnect24` en el nombre, y presiona + para seleccionarlos. Cuando todos estén seleccionados, presiona A dos veces para instalar los WADs.
5. Una vez que se hayan instalado correctamente, oprime el botón HOME para volver al Canal Homebrew.

##### Sección III - Aplicación de parches a 43db para 16: 9 (opcional)

1. Abre el Canal Homebrew
2. Inicie el ww-43db-patcher

Si instala un tema, tendrá que ejecutar ww-43db-patcher una vez más
{: .notice--info}

##### Sección IV - Usando RiiConnect24

Después de seguir las secciones anteriores, casi podrá usar RiiConnect24 en su Wii U. Solo necesita realizar los siguientes pasos **después de cada reinicio de vWii**.

1. En el **Menú de Wii** del vWii, inicia el canal **ConnectMii**.
* Esto forzará la activación de los ajustes de WiiConnect24 y de la conexión en modo de espera que se desactivan cada vez que sales del vWii, y que son requeridos por los canales que usan WiiConnect24.
2. Abre los canales de WiiConnect24
* ¡Ahora debería poder utilizar todos los canales de WiiConnect24 que ha instalado!

#### Servicios soportados
Los siguientes servicios de RiiConnect24 son **funcionando** en el vWii:
* Canal Noticias
    * Éste canal se ve afectado por el error de las fechas. La hora que aparece en "Actualizado hace" y las fechas de los arículos serán incorrectas.
    * Los encabezados en el banner no se mostrarán, apareciendo el error `No se han podido descargar las noticias.` en su lugar.
* Canal de Clima
* Canal Nintendo
* Canal Opiniones
* Canal Concursos Mii
{: .notice--success}

Los siguientes servicios de RiiConnect24 son **no funcionando** en el vWii:
* Intercambio de mensajes mediante el tablón de Wii (la mayoría de la funcionalidad necesaria no está presente en el vWii)
    * Esto incluye enviar o recibir mensajes de amigos. Sólo podrás recibir mensajes globales y publicaciones de fuentes RSS mediante RSSMii (si lo tienes instalado).
* Todos los demás servicios que aparecen como no soportados en las [estadísticas de RiiConnect24](https://rc24.xyz/stats/index.html).
{: .notice--warning}
