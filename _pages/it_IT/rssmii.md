---
title: "Installare RSSMii"
---

{% include toc title="Table of Contents" %}

Se hai bisogno di qualsiasi informazione riguardante questo tutorial, entra nel [server discord di RiiConnect24 ](https://discord.gg/rc24)(raccomandato) oppure [scrivici una mail a support@riconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

Vorresti avere aggiornamenti del feed RSS sulla tua Wii Message Board? Questo tutorial ti dirà come impostare RSSMii.

![RSSMii](/images/rssmii.png)

#### Di cosa hai bisogno

* Una scheda SD
* [RSSMii](https://github.com/RiiConnect24/rssmii/releases)

#### Istruzioni
##### Sezione 1 - Scaricare/Installare

1. Estrai RSSMii mettilo nella cartella `apps` sulla SD.
2. Hai bisogno di creare il file `feeds.xml` nella root della SD in modo che l’app sappia da quali siti ti deve mandare i feed.

Se stai utilizzando un sistema operativo Windows, puoi utilizzare il programma [ RSS Feeds Creator ](https://github.com/RiiConnect24/rssmii/releases/download/v1.4.1/RSSFeedsCreator.bat) creato da KcrPL. Creerà automaticamente un file `feeds.xml` e lo copierà sulla tua scheda SD!
{: .notice--info}

<b>Se non hai un computer Windows, usa questa base ed usa il tuo editor di testo preferito per creare il `feeds.xml`.</b>

```xml
<?xml version="1.0" encoding="utf-8"?>
<rss>
  <feed name="Example-Feed"><![CDATA[http://example.com/rss-feed]]></feed>
  <feed name="One more Example-Feed!"><![CDATA[http://example.com/another_rss-feed]]></feed>
</rss>
```

Sostituisci la porzione "name" con il titolo che vuoi mettere al feed. Assicurati che non sia troppo lungo, siccome non c'è molto spazio. Poi, sostituisci la porzione del link con il link al feed RSS. Puoi mettere quanti feed vuoi. Non cancellare la parte "CDATA".

```xml
<?xml version="1.0" encoding="utf-8"?>
<rss>
  <feed name="RiiConnect24 Medium"><![CDATA[https://medium.com/feed/riiconnect24]]></feed>
  <feed name="RiiConnect24 Twitter"><![CDATA[https://nitter.net/riiconnect24/rss]]></feed>
</rss>
```

Salva il file che hai appena fatto nella root della tua SD.
3. Lancia RSSMii dall'Homebrew Channel.
4. Premi A per confermare che vuoi sottoscrivere ai feed Rss. Ignora l'errore ES_GetTitleID.
5. Una volta che ha terminato, premi HOME per tornare all'Homebrew Channel. Presto dovresti ricevere dei feed RSS sulla tua Wii, divertiti!

Non ti è ancora arrivato niente? Prova un feed RSS che si aggiorna più frequentemente, come una pagina di notizie. Se il feed RSS non si aggiorna spesso, allora non riceverai molti feed.
{: .notice--warning}

Ti consigliamo di usare solo pochi feed, perché se ti iscrivi a tanti feed avrai un sacco di e-mail sulla tua Wii.
{: .notice--info}

Se non stai ricevendo aggiornamenti dopo qualche giorno, forse dovrai iscriverti al feed RSS nuovamente. Carica RSSMii dall'Homebrew Channel nuovamente e lui creerà delle nuove iscrizioni.
{: .notice--info}

[Rimuovere RSSMii](rssmii-remove)
{: .notice--info}
