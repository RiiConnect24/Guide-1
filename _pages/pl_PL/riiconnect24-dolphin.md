---
title: "RiiConnect24"
---

{% include toc title="Zawartość" %}

![Logo RiiConnect24](/images/WiiRC24Logo.jpg)

Ten poradnik pomoże Ci zainstalować RiiConnect24 na Twoim Dolphin'ie.

If you need help for anything regarding this tutorial, please directly contact KcrPL#4625 on Discord, join the [RiiConnect24 Discord Server](https://discord.gg/rc24) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

### Czego będziesz potrzebował
* A computer with either Windows 7 or newer or any Unix based system
* [.VFF-File-Downloader-for-Dolphin](https://github.com/RiiConnect24/.VFF-File-Downloader-for-Dolphin/releases)
* [Dolphin](https://dolphin-emu.org/download/)
* [RiiConnect24 Patcher](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

#### Instrukcje

##### Sekcja I - Instalacja Dolphin

Jeżeli już zainstalowałeś Dolphin'a, przejdź do sekcji drugiej.
{: .notice--info}

1. Pobierz najnowszą wersję deweloperską Dolphin'a.
2. Wypakuj plik .7z programem takim jak 7Zip lub WinRAR.
3. Uruchom Dolphin'a
4. Naciśnij na `Tools` -> `Perform Online System Update` -> Wybierz swój region ![Perform Online System Update](/images/Dolphin_RC24/1.jpg)

##### Sekcja II - Instalowanie RiiConnect24.

1. Run `VFF-Downloader-for-Dolphin.bat` on Windows or `VFF-Downloader-for-Dolphin.sh` on Unix systems which you downloaded [here](https://github.com/RiiConnect24/.VFF-File-Downloader-for-Dolphin/releases)
2. Naciśnij `1` oraz naciśnij `ENTER` aby uruchomić program. ![Główne menu](/images/Dolphin_RC24/2.jpg)
3. Przejdź do konfiguracji programu.
4. Program się Ciebie zapyta czy chcesz go uruchamiać za każdym razem kiedy chcesz skorzystać z RiiConnect24 lub czy chcesz automatycznie uruchomić program w tle po włączeniu komputera. ![Wybierz jak uruchomić program](/images/Dolphin_RC24/3.jpg)

![Uruchom jeden raz](/images/Dolphin_RC24/4.jpg)

If you choose to manually run it, keep `VFF-Downloader-for-Dolphin.bat`. W głównym menu będzie opcja pozwalająca na jednorazowe uruchomienie programu.
{: .notice--info}

Jeżeli wybierzesz opcję, żeby uruchomić podczas włączania komputera, nie musisz nic robić. If you want to uninstall it in the future, come back to `VFF-Downloader-for-Dolphin.bat` or `VFF-Downloader-for-Dolphin.sh` and choose - Manage startup VFF Downloader.
{: .notice--info}

##### Sekcja III - Kończenie instalacji

1. On Windows run the `RiiConnect24Patcher.bat` or run the `RiiConnect24Patcher.sh` if you are on a Unix system that you downloaded [here](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)
2. Uruchom program oraz wybierz `Install RiiConnect24`. ![Wybierz "Custom"](/images/Dolphin_RC24/5.jpg)
3. Wybierz `Custom`. ![Wybierz "Check Mii Out Channel"](/images/Dolphin_RC24/6.jpg)
4. Wybierz `1` oraz wybierz Twój region i tylko włącz piątą opcję. Naciśnij `6` aby rozpocząć proces patchowania.
5. Po ukończeniu, w folderze `WAD` przy RiiConnect24Patcher.bat zobaczysz plik o nazwie `Mii Contest Channel (Europe) (Channel) (RiiConnect24).wad` lub `Check Mii Out Channel (USA) (Channel) (RiiConnect24).wad`
6. W Dolphin'ie, naciśnij na `Narzędzia`, `Zainstaluj WAD` oraz wybierz `Mii Contest Channel (Europe) (Channel) (RiiConnect24).wad` lub `Check Mii Out Channel (USA) (Channel) (RiiConnect24).wad`.

To tyle! Niestety, Nintendo Channel i Wii Mail jeszcze nie działają w Dolphinie.
{: .notice--info}
