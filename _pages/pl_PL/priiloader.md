---
title: "Priiloader"
---

{% include toc title="Zawartość" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

Priiloader dodaje dodatkowy poziom ochrony przez brickiem na Twoje Wii. Ładuje się on przed Wii Menu. To narzędzie może również załadować hacki i może być użyte do uruchomienia Homebrew Channel, BootMii lub jakiegokolwiek homebrew chcesz uruchomić!

![Priiloader](/images/priiloader.jpg)

**Nie** instaluj Priiloadera na vWii (Trybie Wii w Wii U). Zbrickujesz Twoje vWii przez zrobienie tego.
{: .notice--warning}

#### Będziesz potrzebował
* Karta SD lub urządzenie USB.
* [Priiloader installer](assets/files/Priiloader_v0_9.zip)

#### Instrukcje
##### Sekcja I - Pobieranie/Instalowanie

1. Download the Priiloader installer and extract it to the `apps` folder on your SD card or USB drive.
    * Jeżeli ten folder nie istnieje, utwórz go.

##### Sekcja II - Instalowanie Priiloader'a

1. Otwórz Homebrew Channel na Twoim Wii.
2. Launch the Priiloader installer.
3. Naciśnij przycisk `+` na Twoim Wii Remote lub przycisk `A` na kontrolerze GameCube. ![Zainstaluj Priiloader'a](/images/Priiloader/installer.png) ![Zainstaluj](/images/Priiloader/installing.png)

##### Sekcja III - Uruchamianie oraz konfigurowanie Priiloader'a

1. Hold the RESET button while turning on your Wii.
    * If you are using a Wii mini, plug in a USB keyboard and hold escape while turning it on

![Włącz konsolę](/images/Priiloader/on.jpg) ![Przytrzymaj RESET](/images/Priiloader/reset.jpg)

2. Powinieneś zobaczyć menu główne Priiloader'a. ![Menu](/images/Priiloader/mainmenu.png)
3. Przejdź do `System Menu Hacks`.
4. We recommend you turn on the following hacks: `Region Free EVERYTHING`, `Block Disc Updates` and `Block Online Updates`. ![System Menu Hacks](/images/Priiloader/hacks.png)
1. Scroll down to `save settings` and press A, then press B to go back to the main menu of Priiloader.
1. Scroll to `Homebrew Channel` and press A to launch it.

## Lista hacków System Menu

Poniżej znajduje się lista hacków, które możesz włączyć w Priiloaderze.

| Hack                                    | Opis                                                                                                                                                             |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Block Disc Updates                      | Removes the "Wii System Update" screen included with some games that forces you to update the system to play the game.                                           |
| Block Online Updates                    | Blokuje wykonywania aktualizacji Twojej konsoli. Próby aktualizacji kończą się błędem 32007.                                                                     |
| Auto-Press A at Health Screen           | Automatycznie naciska A na ekranie "Health and Safety".                                                                                                          |
| Replace Health Screen with Backmenu     | Zamienia ekran "Health and Safety" na aminację kiedy wychodzisz z gry i uruchamiasz Wii Menu.                                                                    |
| Move Disc Channel                       | Pozwala Ci na przesuwanie Disc Channel gdziekolwiek chcesz. Normalnie, Disc Channel jest zablokowany w pierwszym miejscu u góry po lewej.                        |
| Wiimmfi Patch v3                        | Automatycznie patchuje wszystkie gry, które uruchamiasz za pomocą Disc Channel do użycia z Wiimmfi                                                               |
| 480p graphics fix in system menu        | Naprawia mały problem z rodzielczością 480p w Menu Wii.                                                                                                          |
| Remove NoCopy Save File Protection      | Pozwala na kopiowanie zapisów gier na Kartę SD z ekranu zarządzania pamięcią, których normalnie nie mógłbyś przenieść                                            |
| Region Free EVERYTHING                  | Włącza region free na wszystko co masz na Twoim Wii, łącznie z rzeczami pobranymi.                                                                               |
| Region Free GC Games (No VM Patch)      | Wyłącza blokadę regionową dla gier GameCube.                                                                                                                     |
| Region Free Wii Games                   | Wyłącza blokadę regionową dla gier Wii.                                                                                                                          |
| Region Free Channels                    | Wyłącza blokadę regionową dla zainstalowanych kanałów                                                                                                            |
| No System Menu Sounds AT ALL            | Wyłącza wszystkie efekty dźwiękowe Wii Menu.                                                                                                                     |
| No System Menu Background Music         | Wyłącza muzyke w tle Wii Menu.                                                                                                                                   |
| Re-Enable Bannerbomb v2                 | Pozwala na użycie exploitu "Bannerbomb" aby był używany w nowszych wersjach systemu Wii. Nie jest to potrzebne ponieważ masz już Homebrew Channel zainstalowane. |
| OSReport to UsbGecko(slot B)            | Pozwala na wysłanie logów Wii Menu do urządzenia debugującego w slocie B karty pamięci.                                                                          |
| OSReport to UsbGecko(GeckoOS,B)         | Pozwala na wysłanie logów Wii Menu do urządzenia debugującego w memory card slot B jeżeli system został uruchomiony przez Gecko OS.                              |
| Force Standard Recovery Mode            | Daje Ci dostęp do trybu awaryjnego aby uruchomić płyty recovery. Ten tryb służy do odbrickowania konsoli.                                                        |
| Remove Diagnostic Disc Check            | Wyłącza funkcje sprawdzającą czy w Wii jest włożona "Wii Startup Disc".                                                                                          |
| Lock System Menu with Black Screen      | Powoduje, że Twoje Wii Menu zacina się na czarnym ekranie, powodując, że nie możesz z niego korzystać. (Nie włączaj tego)                                        |
| No-Delete HAXX,JODI,DVDX,DISC,DISK,RZDx | Kanały z tymi ID skasowane przez Nintendo są ponownie widoczne.                                                                                                  |
| Force Disc Games to run under IOS249    | Powoduje że gry na płytach uruchamiają się z cIOS 249. While it cannot allow playing of burned games on its own, it is needed to play burned discs.              |


Kontynuuj do instalacji cIOS<br>
{: .notice--info}

cIOS są wykorzystywane aby grać w gry za pomocą USB Loader'a. Nawet jeśli nie chcesz tego robić, przydatne jest to dla wielu aplikacji homebrew.
{: .notice--info}

Jeżeli masz Wii Mini, skorzystaj z [tego poradnika](cios-mini), żeby zainstalować cIOS
{: .notice--info}

Jeżeli masz Wii Mini, skorzystaj z [tego poradnika](cios), żeby zainstalować cIOS
{: .notice--info}
