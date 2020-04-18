---
title: "Instalar RiiConnect24 en Dolphin"
---

{% include toc title="Tabla de contenido" %}

![Logotipo de RiiConnect24](/images/WiiRC24Logo.jpg)

En esta guía te explicaremos cómo instalar RiiConnect24 en tu instalación de Dolphin.

Si necesitas ayuda con alguna cosa relacionada con esta guía, puedes contactar a KcrPL#4625 en Discord, unirte a nuestro [servidor de Discord](https://discord.gg/b4Y7jfD) o [enviarnos un correo electrónico](mailto:support@riiconnect24.net) (soporte disponible sólo en Inglés).
{: .notice--info}

### Requisitos
* Una computadora con Windows 7 o superior.
* [.VFF-File-Downloader-for-Dolphin](https://github.com/RiiConnect24/.VFF-File-Downloader-for-Dolphin/releases)
* [Dolphin](https://dolphin-emu.org/download/)
* [RiiConnect24 Patcher](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

#### Instrucciones

##### Sección I - Instalando Dolphin

Si ya tienes Dolphin instalado, puedes omitir éste paso
{: .notice--info}

1. Descarga la versión de desarrollo de Dolphin más reciente.
2. Extrae el archivo 7z usando 7Zip o WinRAR.
3. Inicia Dolphin
4. Selecciona `Herramientas` -> `Actualizar la consola por Internet` -> y elige tu región ![Actualizar la consola por Internet](/images/Dolphin_RC24/1.jpg)

##### Sección II - Instalando RiiConnect24.

1. Ejecuta el archivo Install.bat que descargaste desde [aquí](https://github.com/RiiConnect24/.VFF-File-Downloader-for-Dolphin/releases)
2. Presiona `1` y después `ENTER` para iniciar el programa. ![Menú principal](/images/Dolphin_RC24/2.jpg)
3. Procede con la configuración del programa.
4. Te preguntará si deseas iniciar el programa manualmente cada vez que quieras usar RiiConnect24 en Dolphin o si prefieres que sea ejecutado en el arranque de forma automática. ![Elige cómo quieres iniciar el programa](/images/Dolphin_RC24/3.jpg)

![Run once (Ejecutar una vez)](/images/Dolphin_RC24/4.jpg)

Independientemente de la opción que hayas elegido, conserva el archivo Install.bat. Habrá una opción en el menú para ejecutar el programa manualmente.
{: .notice--info}

Si decidiste ejecutarlo en el arranque, entonces no tienes que hacer nada. Si quieres desinstalar el programa, vuelve a ejecutar Install.bat y elige la cuarta opción - Manage startup VFF Downloader (Administrar configuración de arranque del VFF Downloader).
{: .notice--info}

##### Sección III - Finalizando la instalación

1. Ejecuta el archivo RiiConnect24Patcher.bat que descargaste desde [aquí](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)
2. Inicia el programa y selecciona `Install RiiConnect24` (Instalar RiiConnect24). ![Selecciona Custom](/images/Dolphin_RC24/5.jpg)
3. Selecciona `Custom` (Instalación personalizada). ![Selecciona <code>Check Mii Out Channel</code> (Canal Miirame)](/images/Dolphin_RC24/6.jpg)
4. Presiona `1` para elegir la región de tu consola y sólo marca la quinta opción. Presiona `6` para comenzar el proceso.
5. Una vez que el proceso haya finalizado, encontrarás un archivo llamado `Mii Contest Channel (Europe) (Channel) (RiiConnect24).wad` o `Check Mii Out Channel (USA) (Channel) (RiiConnect24).wad` (dependiendo de la región que hayas elegido) dentro de una carpeta llamada WAD en la misma carpeta en la que está el archivo RiiConnect24Patcher.bat
6. Selecciona `Herramientas` y después `Instalar WAD`. Ahora sólo tienes que buscar y elegir el archivo `Mii Contest Channel (Europe) (Channel) (RiiConnect24).wad` o `Check Mii Out Channel (USA) (Channel) (RiiConnect24).wad`.

¡Ya has terminado! Desafortunadamente, el Canal Opiniones y el Canal Nintendo aún no funcionan en Dolphin.
{: .notice--info}
