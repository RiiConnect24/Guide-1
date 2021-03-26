---
title: "cIOS"
---

{% include toc title="Inhaltsverzeichnis" %}

Diese Anleitung wird dir zeigen, wie du cIOS (custom IOS) installieren kannst. Dies ist zwingend erforderlich, wenn du Spiele mit einem USB-Loader starten möchtest. Manche Homebrew-Applikationen funktionieren mit cIOS besser.

![d2x cIOS Installer](/images/cios/cIOS.png)

Der Versuch ein anderes cIOS auf einer Wii mini zu installieren, wird nicht funktionieren. Wenn du eine Wii mini besitzt, installiere stattdessen [dieses cIOS](cios-mini).
{: .notice--info}

#### Voraussetzungen

* Eine Wii mit Internetverbindung
* Eine SD-Karte oder ein USB-Laufwerk
* [d2x cIOS Installer](/assets/files/d2x-cIOS-Installer-Wii.zip)

Wenn du eine SD-Karte verwendest stelle sicher, dass der Schieber für den Schreibschutz nicht aktiviert ist. Ansonsten wird es dir nicht möglich sein, die korrekten Optionen im Installer auszuwählen
{: .notice--warning}

#### Anleitung

##### Abschnitt 1 - Herunterladen

1. Lade den d2x cIOS Installer herunter und entpacke ihn in den `apps`-Order auf deiner SD-Karte oder deines USB-Laufwerks.
1. Verbinde deine SD-Karte oder dein USB-Laufwerk mit deiner Wii und starte den d2x cIOS Installer über den Homebrew-Kanal.

##### Abschnitt 2 - Installieren

1. Drücke auf Fortfahren, stelle dann folgende Optionen ein:
```
Wähle cIOS: v10 beta52 d2x-v10-beta52
Wähle cIOS base: 57
Wähle cIOS slot: 249
Wähle cIOS version: 65535
```
![Installiere cIOS 249](/images/cios/Install249.png)
1. Wenn du damit fertig bist, drücke zweimal auf A um die Installation zu starten.
1. Wenn die Installation abgeschlossen ist, drücke A um zurückzugehen und stelle dann folgende Optionen ein:
```
Wähle cIOS: v10 beta52 d2x-v10-beta52
Wähle cIOS base: 56
Wähle cIOS slot: 250
Wähle cIOS version: 65535
```
![Installiere cIOS 250](/images/cios/Install250.png)
1. Wenn du damit fertig bist, drücke zweimal auf A um die Installation zu starten.
1. Wenn die Installation abgeschlossen ist, drücke A um zurückzugehen und stelle dann folgende Optionen ein:
```
Wähle cIOS: v10 beta52 d2x-v10-beta52
Wähle cIOS base: 38
Wähle cIOS slot: 251
Wähle cIOS version: 65535
```
![Installiere cIOS 251](/images/cios/Install251.png)
1. Wenn du damit fertig bist, drücke zweimal auf A um die Installation zu starten, und verlasse nach Abschluss das Programm.

{% capture bruh %}
Auch wenn die meisten Spiele mit den Standardeinstellungen sofort funktionieren sollten, benötigen einige Spiele ein spezielles cIOS um zu funktionieren, oder bestimmte Eigenschaften innerhalb des Spiels zu nutzen.<br> Beispiele beinhalten:
* Verwendung einer Tastatur in Animal Crossing: Let’s Go to the City.
* Verwendung von SpongeBob's Boating Bash.

Eine umfassendere (aber weiterhin unvollständige) Liste kann kann [**hier**](https://wiki.gbatemp.net/wiki/Wii_cIOS_base_Compatibility_List)<br> gefunden werden. Um das cIOS für ein spezielles Spiel zu ändern, folge dieser Anleitung:
{% endcapture %}
<div class="notice--warning">{{ bruh | markdownify }}</div>

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'usbloadergx')">USB Loader GX</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'wiiflow')">WiiFlow</button>

<div id="usbloadergx" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_24_Pdwrc!!Wähle das Spiel welches nicht funktioniert. !!crwdP_25_Pdwrc!!Wähle Einstellungen. !!crwdP_26_Pdwrc!!Wähle <code>Game Load</code>. !!crwdP_27_Pdwrc!!Scrolle herunter zu <code>Game IOS</code>. !!crwdP_28_Pdwrc!!Gibt den IOS-Slot welchen du verwenden möchtest ein.
  </p>
  
  <ul>
    <li>
      Versuche 250 oder 251, falls 249 nicht funktioniert. !!crwdP_29_Pdwrc!!Drücke auf ok und versuche das Spiel zu laden.
    </li>
  </ul>
</div>

<div id="wiiflow" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_30_Pdwrc!!Wähle das Spiel welches nicht funktioniert. !!crwdP_31_Pdwrc!!Klicke auf das Zahnrad-Symbol. !!crwdP_32_Pdwrc!!Gehe zu cIOS und nutze die Pfeile um den zu verwendenden IOS-Slot auszuwählen.
  </p>
  
  <ul>
    <li>
      Versuche 250 oder 251, falls 249 nicht funktioniert. !!crwdP_33_Pdwrc!!Drücke Speichern und versuche das Spiel zu laden.
    </li>
  </ul>
</div>
##### Möglichkeiten nach Abschluss

[Fortfahren zum Homebrew-Browser](hbb)<br> Der Homebrew-Browser ist ein guter Ort um Homebrew für deine Wii zu beziehen. Diesen zu installieren ist nicht zwingend erforderlich.
{: .notice--info}

[Fortfahren in der Seitennavigation](site-navigation)<br> Wir haben viele weitere Tutorials, welche dir gefallen könnten.
{: .notice--info}

Du kannst nun Homebrew wie beispielsweise [USB Loader GX](usbloadergx) oder [WiiFlow](wiiflow) verwenden.
{: .notice--info}

<script>
    let tabcontent = document.getElementsByClassName("blanktabcontent");
    let tablinks = document.getElementsByClassName("tablinks");!!crwd_CB_10_BC_dwrc!!</script>

