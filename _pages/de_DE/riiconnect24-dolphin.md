---
title: "RiiConnect24"
---

{% include toc title="Inhaltsverzeichnis" %}

![RiiConnect24-Logo](/images/WiiRC24Logo.jpg)

Diese Anleitung wird dir dabei helfen, RiiConnect24 in deiner Dolphin-Installation zu installieren.

Falls du irgendwelche Hilfe bezüglich der Anleitung benötigst, schreibe bitte direkt KcrPL#4625 auf Discord an, tritt dem [RiiConnect24 Discord Server](https://discord.gg/b4Y7jfD) bei, oder kontaktiere uns [per E-Mail unter support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

### Voraussetzungen
* Ein Computer mit Windows 7 oder neuer oder ein Unix-basiertes System
* [.VFF-File-Downloader-for-Dolphin](https://github.com/RiiConnect24/.VFF-File-Downloader-for-Dolphin/releases)
* [Dolphin](https://dolphin-emu.org/download/)
* [RiiConnect24 Patcher](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

#### Anleitung

##### Abschnitt 1 - Dolphin installieren

Falls du Dolphin bereits installiert hast, gehe direkt zu Abschnitt 2 über
{: .notice--info}

1. Lade die aktuellste Dolphin-Entwicklerversion herunter.
2. Entpacke die `.7z`-Datei mit einem Programm wie 7Zip oder WinRAR.
3. Starte Dolphin
4. Wähle `Extras`-> `Online-Systemaktualisierung durchführen` -> Wähle dann deine Region ![Perform Online System Update](/images/Dolphin_RC24/1.jpg)

##### Abschnitt 2 - RiiConnect24 installieren.

1. Führe `VFF-Downloader-for-Dolphin.bat` auf Windows oder `VFF-Downloader-for-Dolphin.sh` auf Unix-Systemen aus, welche du [here](https://github.com/RiiConnect24/.VFF-File-Downloader-for-Dolphin/releases) herunterlädst
2. Drücke `1` und dann `ENTER`, um das Programm zu starten. ![Hauptmenü](/images/Dolphin_RC24/2.jpg)
3. Fahre mit der Einrichtung des Programmes fort.
4. Du wirst gefragt, ob du das Programm jedes Mal, wenn du RiiConnect24 in Dolphin benutzen möchtest, von Hand ausführst oder ob es beim Hochfahren automatisch ausgeführt werden soll. ![Choose how to boot the program](/images/Dolphin_RC24/3.jpg)

![Run once](/images/Dolphin_RC24/4.jpg)

Wenn du es manuell ausführen möchtest, behalte `VFF-Downloader-for-Dolphin.bat`. Es gibt einen Eintrag zum Ausführen im Menü.
{: .notice--info}

Wenn du es beim Hochfahren starten lässt, musst du gar nichts machen. Wenn du es in Zukunft deinstallieren möchtest führe `VFF-Downloader-for-Dolphin.bat` oder `VFF-Downloader-for-Dolphin.sh` erneut aus und wähle - Manage startup VFF Downloader.
{: .notice--info}

##### Abschließen der Installation

1. On Windows run the `RiiConnect24Patcher.bat` or run the `RiiConnect24Patcher.sh` if you are on a Unix system that you downloaded [here](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)
2. Starte den Patcher, wähle dann `Install RiiConnect24`. ![Select Custom](/images/Dolphin_RC24/5.jpg)
3. Waähle dann `Custom`. ![Select Check Mii Out Channel](/images/Dolphin_RC24/6.jpg)
4. Drücke `1` um deine Region auszuwählen und aktiviere nur den fünften Eintrag. Drücke `6`, um das Patchen zu starten.
5. Nach Abschluss befindet sich eine `Mii Contest Channel (Europe) (Channel) (RiiConnect24).wad`- oder `Check Mii Out Channel (USA) (Channel) (RiiConnect24).wad`-Datei im `WAD`-Ordner neben der `RiiConnect24Patcher.bat`
6. In Dolphin, wähle `Extras` und dann `WAD installieren...`, und wähle `Mii Contest Channel (Europe) (Channel) (RiiConnect24).wad` oder `Check Mii Out Channel (USA) (Channel) (RiiConnect24).wad`.

Du bist fertig! Unfortunately, Nintendo Channel and Wii Mail don't work in Dolphin yet.
{: .notice--info}
