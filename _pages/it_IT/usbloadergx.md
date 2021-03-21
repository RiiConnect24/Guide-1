---
title: "USB Loader GX"
---

{% include toc title="Table of Contents" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

Questa è una veloce guida su come usare USB Loader GX, un popolare USB loader per la Wii che è usato per giocare a giochi da un dispositivo USB.

![USB Loader GX](/images/usbloadergx.png)

#### Di cosa hai bisogno

* Una Wii
* Un dispositivo USB
* [USB Loader GX](https://hbb1.oscwii.org/hbb/usbloader_gx/usbloader_gx.zip)

Assicurati di avere installato [cIOS](/cios) prima di seguire questa guida!
{: .notice--info}

Consigliamo di copiare i giochi con [Wii Backup Manager](/wiibackupmanager) se usi Windows, oppure [Witgui](https://desairem.com/wordpress/category/witgui-download/) se usi macOS.
{: .notice--info}

Se non stai copiando giochi usando Wii Backup Manager o Witgui, crea una cartella chiamata "wbfs" nella root del tuo dispositivo USB o della tua scheda SD e mettici all'interno i giochi.
{: .notice--info}

Per giocare a vari giochi, consigliamo di usare un hard drive esterno per la tua Wii. Anche i flash drives dovrebbero essere compatibili, ma gli hard drives esterni sono consigliati perchè sono più affidabili, e possono conservare più giochi.
{: .notice--info}

Assicurati che il tuo dispositivo USB sia formattato a FAT32 o NTFS. Non formattarla ad altri tipi tipo extFS o WBFS, esso è un vecchio formato per contenere giochi Wii.
{: .notice--info}

#### Istruzioni

##### Scaricare

1. Estrarre USB Loader GX e mettilo nella cartella `apps` del tuo dispositivo USB o scheda SD.
2. Inserisci il tuo dispositivo USB, e la scheda SD se la stai usando, nella tua Wii e carica USB Loader GX dall'Hombrew Channel.

##### Iniziare

Non c'è nessuna "guida" su come usare l'applicazione USB Loader GX. Noi vogliamo aiutarti ad imparare ad usarlo, dandoti una veloce partenza. Dovresti riuscire a capire tutte le fantastiche caratteristiche di USB Loader GX semplicemente usandolo.
{: .notice--info}

* Se USB Loader GX dice "Waiting for HDD..." con un conto alla rovescia di 20 secondi, è probabile che non riesce a trovare il dispositivo USB. Prova ad uscire dall'applicazione, poi avviala nuovamente dopo aver spostato il dispositivo USB nell'altra porta della Wii.
* Puoi premere il pulsante 1 sul tuo telecomando Wii per aprire un dialogo per scaricare copertine ed artwork da [GameTDB](https://gametdb.com/). Potrebbe richiedere un po' di tempo per scaricare le copertine ed artwork, in base a quanti giochi hai.
* Ci sono dei WAD che possono aprire USB Loader GX se lo carichi dal Menù Wii. Si chiama forwarder WAD. Un ufficiale creatore di shortcut WAD può essere trovato [qui](https://sourceforge.net/projects/usbloadergx/files/Releases/Forwarders/USB%20Loader%20GX-UNEO_Forwarder_5_1_AHBPROT.wad), e una versione per il vWii (Wii U) può essere trovato [qui](https://sourceforge.net/projects/usbloadergx/files/Releases/Forwarders/USB%20Loader%20GX-UNEO_Forwarder_5_1_AHBPROT_vWii%20%28Fix%29.wad).
* Giochi Wii "personalizzati" e GameCube potrebbero non avere la copertina personalizzata che usa USB Loader GX. Per impostarle, scrivi `CustomBannersURL = http://banner.rc24.xyz/` in config/GXGlobal.cfg sul tuo dispositivo USB. Poi puoi usare il "Custom Banner" download premendo il pulsante 1 sul tuo telecomando Wii.

##### Interfaccia

Ci sono vari pulsanti nell'interfaccia di USB Loader GX.

###### Menù Principale

Questi sono le funzioni dei tasti che si trovano sopra il menù principale, da sinistra a destra:

* Star - Mostra i giochi che hai scelto come "preferiti".
* Search - Ti permette di cercare giochi dal nome.
* Sort - Imposta il metodo per disporre i giochi.
* Platform - Scegli di disporre giochi in base alla piattaforma.
* Category - Dispone i giochi in base alla loro categoria.
* List - Mostra i giochi tramite una lista.
* Multi-Cover View - Mostra i giochi nella modalità multi-cover.
* Cover Carousel View - Mostra i giochi nella modalità carousel.
* Wii Menù View - Mostra i giochi nella modalità Menù Wii.
* Parental Control - Blocca USB Loader GX.
* Disc - Carica i giochi dal disco.

Premendo su qualunque gioco ti permetterà di giocarlo premendo "Start".

Ci sono anche altri tasti:

* (+) Icon - "Installa" un gioco, cioè lo carica dal disco copiandolo.
* Ingranaggi - Impostazioni di USB Loader GX.
* Scheda SD - Guarda la scheda SD.
* Homebrew - Carica le applicazioni Homebrew.
* Wii - Apre il Menù HOME, che è accessibile anche premendo il pulsante HOME sul telecomando Wii.
* Pulsante di spegnimento - Spegne la tua Wii.

Nel mezzo della schermata inferiore, puoi vedere quanto spazio è libero sul tuo dispositivo USB e quanti giochi hai.

##### Opzioni una volta completate

[Continua a navigare nel sito](site-navigation)<br> Abbiamo molti altri tutorial che potrebbero interessarti.
{: .notice--info}
