---
title: "Kasowanie plików. VFF"
---

{% include toc title="Zawartość" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Logo RiiConnect24](/images/WiiRC24Logo.jpg)

Jeżeli otrzymujesz któryś z poniższych problemów (tylko te, nie inne), powinieneś być w stanie naprawić ten problem poprzez usunięcie plików VFF.

+ Discontinued Message
+ NEWS/FORE000001
+ NEWS/FORE000003
+ NEWS/FORE000005
+ NEWS/FORE000099

#### Będziesz potrzebował:
* Karta SD lub urządzenie USB
* [WiiXplorer](https://sourceforge.net/projects/wiixplorer/files/latest/download)

#### Foldery do usunięcia:

+ Forecast Channel
  + 48414645
  + 4841464a
  + 48414650

+ News Channel
  + 48414745
  + 4841474a
  + 48414750

#### Instrukcje

1. Uruchom WiiXplorer.
2. Przejdź do `Start` -> `Settings` -> `Boot Settings` -> `Enable NAND write access` i wybierz `Yes` dla obydwóch dialogów, które pojawią się na ekranie.
3. Naciskaj "Back" (Wstecz) dopóki nie dojdziesz do ekranu przeglądarki plików.
4. Naciśnij na mała niebieską ikonę karty SD oraz wybierz `NAND`.
5. Przejdź do folderu `title` -> `00010002` -> XXXXXXXX -> `data`. Zamień XXXXXXXX na jeden z folderów ukazanych powyżej w podpunkcie `Foldery do usunięcia`.
6. Najedź na `wc24dl.vff` i naciśnij przycisk + i wybierz `Delete`.

Spróbuj uruchomić kanał z którym miałeś/miałaś problem.

[Powróć do strony dotyczącej instalacji RiiConnect24](riiconnect24)
{: .notice--info}
