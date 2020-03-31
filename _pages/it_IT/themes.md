---
title: "Installare temi Wii"
---

{% include toc title="Indice" %}

Sei stanco del noioso, e semplice tema bianco sul Menu della tua Wii, e vuoi invece un tema interessante? Questo tutorial ti aiuterà a installare un nuovo tema per il tuo Menu Wii!

In caso di brick, [installare Priiloader è un must.](/priiloader) Installa anche BootMii (su Boot2 se possiedi una Wii datata). Installando le varie protezioni dai brick seguendo le guide correttamente dovresti evitare ultimi.
{: .notice--warning}

Non installare temi personalizzati su vWii (Wii U)!
{: .notice--warning}

Per sicurezza, non usare nessun'altra versione di MyMenuify tranne quelle indicate qui sotto, dato che MyMenuify Mod è il modo più sicuro per installare un tema.
{: .notice--info}

#### Ciò di cui hai bisogno
* Una Wii
* Una SD con un minimo di 128 MB liberi
* Un PC con Windows (usa Wine su Linux/Mac)
* [MyMenuify Mod](/assets/files/MyMenuifyModv1.5.zip)
* [ThemeMii Mod](/assets/files/New_Thememii_MOD.rar)
* [Questo thread su GBAtemp](https://gbatemp.net/threads/wii-theme-team-creations-v2.336596/)

#### Istruzioni

##### Sezione 1 - Trovare il tema

1. Guarda il thread di GBAtemp, trovando un tema che ti piacerebbe installare. Alcuni hanno anche un video su YouTube che mostra come appare il tema, sfortunatamente alcuni di questi non sono disponibili.
1. Una volta trovato quello che ti piace, fai clic sul link per il download corrispondente alla versione del tuo menu Wii. **È molto importante scegliere quello giusto per evitare i brick.**
1. Probabilmente sceglierai il link per il download che dice 4.X, il che significa che il tema funzionerà sulle versioni 4.1, 4.2 e 4.3 del menu Wii.
1. Alcuni temi hanno link diversi per regioni diverse, quindi scegli quello corrispondente alla tua regione Wii.
1. Una volta scaricato il tema desiderato e ricontrollato hai ottenuto quello giusto, apri ThemeMii Mod.

##### Sezione 2 - Costruire il tema

1. Apparirà una finestra di dialogo che ti chiederà di installare i temi solo se hai la protezione dai brick. Se hai installato Priiloader e / o BootMii (vedi l'avviso all'inizio di questa guida), premi OK.
1. Vai su `Tools` > `Download Base App` > Versione del Menu Wii che hai installato > Regione del menu Wii che hai installato.
! [Common Key] (/images/Theme/common-key.png)
1. Apparirà una finestra di dialogo che ti chiederà di inserire un valore per creare una chiave. Inserisci ciò che dice, creerà una chiave che verrà utilizzata per decrittografare il menu Wii dai server Nintendo.
1. Una casella di selezione file ti chiederà dove salvare il file .app (che è il file del Menu Wii scaricato). Salvalo nella directory in cui è presente ThemeMii.
1. Vai in `Opzioni` > `Menu di sistema standard` > Versione del Menu Wii > Region del Menu Wii
1. Vai in `File` > `Apri`, e naviga tra le cartelle finchè non trovi il file .mym.
1. Premi su `Crea csm`, e seleziona una cartella in cui vuoi che venga salvato il tema. Dagli un po' di tempo per costruirlo
1. Una finestra di dialogo apparirà dicendo che il tema è stato costruito correttamente, e ti chiederà se vuoi salvare il .mym. Premi `No`.

##### Section III - Installing the Theme

1. Extract MyMenuify Mod and put it in the `apps` folder on your SD Card.
1. Put the .csm file you saved in a folder called `modthemes` on your SD Card.
1. Insert your SD Card into your Wii, and launch MyMenuify Mod from the Homebrew Channel.
1. After an introduction message, it will ask you what IOS you want to use in the app. If you have [installed cIOS](/pages/cios), use `IOS249`, or else use `IOS58`. If the former gives an `Exception DSI occurred!` error, press Reset on the Wii console, launch it again, then try `IOS250`.
1. Highlight the theme you want to install, then press A. Give it a moment to install the theme, then press any button to go to the Wii Menu. Hopefully, the theme installed correctly.

If you get an error saying "The system files are corrupted", don't panic as long as you installed Priiloader. Turn off your Wii, then hold down the RESET button down and turn on your Wii. You should be able to boot into the Priiloader menu, where you have some options to fix your Wii Menu. One of the options is to launch the Homebrew Channel, where you can launch MyMenuify Mod and press a button to download and install the original Wii Menu theme.
{: .notice--info}
