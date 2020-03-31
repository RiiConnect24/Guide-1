---
title: "str2hax"
---

{% include toc title="Indice" %}

str2hax è un exploit per Wii che si attiva utilizzando l'EULA. Richiede soltanto una connessione internet..

#### Ciò di cui hai bisogno

* Una Wii aggiornata alla 4.3 connessa ad Internet

#### Istruzioni

##### Sezione 1 - Connessione

Questo exploit ha bisogno di impostare due DNS particolari per funzionare.

1. Vai in `Opzioni Wii`.
![Wii Options](/images/RiiConnect24/Internet_1.png)
1. Vai in `Impostazioni Wii`.
![Wii Settings](/images/RiiConnect24/Internet_2.png)
1. Vai alla `Pagina 2`, e clicca su `Internet`.
![Internet](/images/RiiConnect24/Internet_3.png)
1. Vai in `Impostazioni di Connessione`.
![Connection Settings](/images/RiiConnect24/Internet_4.png)
1. Seleziona la connessione che utilizzi.
![Current Connection](/images/RiiConnect24/Internet_5.png)
1. Vai in `Cambia Impostazioni`.
![Change Settings](/images/RiiConnect24/Internet_6.png)
1. Vai in `Ottieni Automaticamente il DNS`, e seleziona `No`, dopo vai in `Impostazioni Avanzate`.
![Auto-Obtain DNS](/images/RiiConnect24/Internet_7.png)
1. Digita `216.69.185.14` come DNS primario.
1. Digita `173.201.71.14` come DNS secondario.
1. Seleziona `Conferma`, e dopo seleziona `Salva`.
![Save DNS](/images/RiiConnect24/Internet_10.png)
1. Seleziona `OK` per fare un test di connessione.
![Connection Test](/images/RiiConnect24/Internet_11.png)
1. Se il test ha avuto successo, seleziona `No` per saltare l'aggiornamento di sistema.
![Connection Test Successful](/images/RiiConnect24/Internet_12.png)

##### Sezione 2 - Attivare l'exploit

1. Vai nella sezione `Internet`, e dopo `Accordo/Contatto`, e premi `Si`.
1. Se vedi un pony con uno sfondo azzurro chiaro sullo schermo, l'exploit ha avuto successo. Aspetta 1-2 minuti affinchè l'exploit si attivi (dovrebbe metterci circa 1 minuto e 25 secondi). L'exploit scaricherà l'HackMii Installer e potrai continuare.

Se l'HackMii Installer non carica o si blocca (non è possibile muovere il cursore), riavvia la Wii e ripeti la procedura.

[Continua l'installazione dell'Homebrew Channel e di BootMii](hbc)
{: .notice--info}
