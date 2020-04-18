---
title: "Instalar RSSMii"
---

{% include toc title="Tabla de contenido" %}

Si necesitas ayuda con alguna cosa relacionada con esta guía, puedes unirte a nuestro [servidor de Discord](https://discord.gg/b4Y7jfD) (recomendado) o [enviarnos un correo electrónico](mailto:support@riiconnect24.net) (soporte disponible sólo en Inglés).
{: .notice--info}

¿Te gustaría recibir actualizaciones RSS en tu tablón de Wii? En esta guía te explicaremos cómo instalar RSSMii.

![RSSMii](/images/rssmii.png)

#### Requisitos

* Una tarjeta SD
* [RSSMii](https://github.com/RiiConnect24/rssmii/releases)

#### Instrucciones
##### Sección I - Descarga/instalación

1. Extrae RSSMii a la carpeta `apps` en tu tarjeta SD o unidad USB.
2. Ahora necesitas crear un archivo llamado `feeds.xml` en la raíz de la tarjeta SD, para que de esta forma RSSMii pueda saber a qué fuentes quieres suscribirte.

Si tienes una PC con Windows, puedes usar un programa llamado RSS Feeds Creator creado por KcrPL. El programa se encargará de crear el archivo `feeds.xml` y de copiarlo a tu tarjeta SD automáticamente
{: .notice--info}

<b>Si no tienes una computadora con Windows, puedes copiar el siguiente ejemplo y usar un editor de texto para crear el archivo `feeds.xml`.</b>

```xml
<?xml version="1.0" encoding="utf-8"?>
<rss>
  <feed name="Fuente de ejemplo"><![CDATA[http://example.com/rss-feed]]></feed>
  <feed name="Otra fuente de ejemplo"><![CDATA[http://example.com/another_rss-feed]]></feed>
</rss>
```

Reemplaza el nombre con el título que quieras poner a la fuente. Asegúrate de que no sea muy largo, ya que el límite de caracteres es reducido. Después, reemplaza el enlace de ejemplo con el enlace de la fuente RSS. Puedes añadir tantas fuentes como quieras. No borres la parte que dice "CDATA".

```xml
<?xml version="1.0" encoding="utf-8"?>
<rss>
  <feed name="RiiConnect24 Medium"><![CDATA[https://medium.com/feed/riiconnect24]]></feed>
  <feed name="RiiConnect24 Twitter"><![CDATA[https://twitrss.me/twitter_user_to_rss/?user=RiiConnect24]]></feed>
  <feed name="Nintendo News"><![CDATA[https://www.nintendo.com/feed]]></feed>
</rss>
```

Guarda los cambios que hayas hecho al archivo.
3. Inicia RSSMii desde el Canal Homebrew.
4. Oprime A para confirmar que quieres suscribirte a las fuentes. Ignora el error que dice `ES_GetTitleID`, todo está bien.
5. Una vez que el proceso haya terminado, oprime el botón HOME para volver al Canal Homebrew. ¡Pronto deberías comenzar a recibir actualizaciones RSS en tu tablón de Wii!

¿No has recibido actualizaciones de ninguna fuente? Intenta suscribirte a una fuente que se actualice más a menudo, como por ejemplo, una fuente RSS de noticias. Si la fuente no se actualiza periódicamente, entonces no recibirás muchas actualizaciones.
{: .notice--warning}

Te recomendamos que sólo te suscribas a unas pocas fuentes, ya que si te suscribes a muchas, podrías recibir demasiados mensajes en el tablón de Wii.
{: .notice--info}

Si no empiezas a recibir actualizaciones al cabo de unos días, entonces tal vez tengas que volver a suscribirte a las fuentes RSS. Para hacer esto sólo tienes que volver a ejecutar RSSMii y la aplicación se encargará de crear nuevas suscripciones.
{: .notice--info}

[Desinstalar RSSMii](rssmii-remove)
{: .notice--info}
