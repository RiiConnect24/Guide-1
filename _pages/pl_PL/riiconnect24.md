---
title: "RiiConnect24"
---

{% include toc title="Zawartość" %}

![RiiConnect24 Logo](/images/WiiRC24Logo.jpg)

[RiiConnect24](https://rc24.xyz/) jest serwisem który pozwala Ci korzystać z Forecast Channel, pisać mail pomiędzy Wii i PC, głosować na ankietach oraz korzystać z różnych innych funkcji WiiConnect24. Zastąpia on już nie wspierany serwis WiiConnect24.

Póki co, RiiConnect24 nie wspiera Wii U dlatego proszę, nie instaluj tego na Wii U.
<br>
Obecnie, wspieramy tylko News Channel, Forecast Channel oraz Everybody Votes Channel ale inne kanały [(`sprawdź stronę rozwoju`)](https://rc24.xyz/stats/index.html) są tworzone.
{: .notice--warning}

Aby zainstalować RiiConnect24, twoje Wii musi być na wersji systemu 4.3 - inaczej Wii Mail nie będzie działał.
{: .notice--info}

#### Czego będziesz potrzebował

* Wii z działającym połączeniem internetowym
* Karta SD z przynajmniej 128MB wolnej przestrzeni.
* Komputer (każdy system operacyjny)

* [RiiConnect24 Patcher](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

#### Instrukcje

##### Sekcja I - Stosowanie poprawki na IOS

[Masz jakieś problemy z instalacją RiiConnect24 na Twojej Wii? Chcesz się czegoś nas zapytąć? Wyślij mail'a do support@riiconnect24.net (Obsługa dostępne po polsku)](mailto:support@riiconnect24.net)
{: .notice--info}

[Jeżeli potrzebujesz dokładnego opisu tego jak zainstalować IOS i Everybody Votes Channel z poprawką po jego pobraniu, naciśnij tutaj!](wiimodlite)
{: .notice--info}

Zastosujemy teraz poprawkę na IOS `31` oraz `80`. Jest to wymagane aby korzystać z kanałów które wspieramy. Musimy zmienić klucz RSA który jest wymagany do podpisania plików przez nas, te poprawki również zawierają kilka rzeczy wymaganych do działania Wii Mail. Pobierzesz również Everybody Votes Channel.

1. Pobierz wymagane pliki dla twoje systemu operacyjnego. Dla Windows, uruchom `RiiConnect24Patcher.bat`, dla Linux'a oraz Mac'a `RiiConnect24Patcher.sh`.
1. (`Jeżeli użyłeś RiiConnect24 Patcher do skopiowania plików na kartę SD, pomiń ten krok`) Podążaj za podanymi instrukcjami podanymi przez program. Po zakończeniu, skopiuj folder `WAD` na Twoją kartę SD.
1. Powinieneś rónież pobrać Everybody Votes Channel. Musi być zainstalowany **nawet jeśli już masz EVC na twoim Wii ponieważ musisz zainstalować wersję z poprawką.**
1. (`Jeżeli użyłeś RiiConnect24Patcher.bat, pomiń ten krok`) Wypakuj Wii Mod Lite do folderu `apps` na Twojej karcie SD.
1. Włóż kartę SD do Twojej Wii.
1. Uruchom Homebrew Channel na Twojej Wii.
1. Uruchom Wii Mod Lite.
1. Używając D-Pad (+) na Twoim Wii Remote, wybierz `WAD Manager` oraz wybierz folder `WAD`.
1. Kiedy `IOS31.wad` jest podświetlone, wciśnij +. Zrób tak samo z `IOS80.wad` oraz `Everybody Votes Channel.wad`
1. Jeżeli otrzymasz błąd -1035 podczas instalacji IOS, cofnij się do wyboru WAD, zaznacz Everybody Votes Channel.wad oraz naciśnij "-" i "A". Potem spróbuj zainstlować to normalnie.
1. Kiedy instalacja zakończy się powodzeniem, naciśnij HOME aby powrócić do Homebrew Channel.

##### Sekcja II - Stosowanie poprawki na nwc24msg.cfg

Teraz zastosujemy poprawkę na plik `nwc24msg.cfg` który jest wymagany do korzystania z Wii Mail.

1. (`Jeżeli korzystałeś z RiiConnect24 Patcher, ten plik powinien już być na Twojej karcie SD`). Pobierz [RiiConnect24 Mail Patcher](https://github.com/RiiConnect24/Mail-Patcher/releases) oraz wypakuj go na Twoją kartę SD.
1. Podłącz kartę SD do Twojej Wii.
1. Uruchom Homebrew Channel na Twojej Wii.
1. Uruchom RiiConnect24 Mail Patcher.
1. Ten krok powinien zająć kilka sekund. Kiedy będzie gotowe, naciśnij HOME aby się cofnąć.

Jeżeli poprzedni krok zakończył się błędem `net_get_status: -24 - Couldn't request the data: -24` proszę sprawdzić Twoje połączenie z internetem na konsoli.
{: .notice--warning}

Jeżeli miałeś problem podczas stosowania poprawki na nwc24msg.cfg, napisz do nas na [support@riiconnect24.net](mailto:support@riiconnect24.net) (`Obsługa dostępna po polsku`)
{: .notice--info}

##### Sekcja III - Łączenie

1. Wejdź do `Wii Options`.
![Wii Options](/images/RiiConnect24/Internet_1.png)
1. Wejdź do`Wii Settings`.
![Wii Settings](/images/RiiConnect24/Internet_2.png)
1. Otwórz drugą stronę i naciśnij na `Internet`.
![Internet](/images/RiiConnect24/Internet_3.png)
1. Wejdź do `Connection Settings`.
![Connection Settings](/images/RiiConnect24/Internet_4.png)
1. Wybierz Twoje wybrane połączenie.
![Current Connection](/images/RiiConnect24/Internet_5.png)
1. Wejdź do `Change Settings`.
![Change Settings](/images/RiiConnect24/Internet_6.png)
1. Wejdź do `Auto-Obtain DNS` (`Nie IP Address`), wybierz nie `No` oraz wybierz `Advanced Settings`.
![Auto-Obtain DNS](/images/RiiConnect24/Internet_7.png)
1. Wpisz `164.132.44.106` w `Primary DNS`.
![Primary DNS](/images/RiiConnect24/Internet_8.png)
1. Wpisz `8.8.8.8` jako `Secondary DNS`.
![Secondary DNS](/images/RiiConnect24/Internet_9.png)
1. Wybierz `Confirm` oraz `Save`.
![Save DNS](/images/RiiConnect24/Internet_10.png)
1. Wybierz `OK` aby przeprowadzić test łączności.
![Connection Test](/images/RiiConnect24/Internet_11.png)
1. Jeżeli test zakończył się sukcesem, wybierz `No` aby pominąć aktualizacje systemu.
![Connection Test Successful](/images/RiiConnect24/Internet_12.png)
1. Wejdź do `WiiConnect24, potem `WiiConnect24` oraz upewnij się że jest włączone.
![WiiConnect24 1](/images/RiiConnect24/Internet_13.png)
![WiiConnect24 2](/images/RiiConnect24/Internet_14.png)
![WiiConnect24 3](/images/RiiConnect24/Internet_15.png)
1. W menu WiiConnect24, wejdź do `Standby Connection` i upewnij się że jest włączone.
![Standby Connection 1](/images/RiiConnect24/Internet_16.png)
![Standby Connection 2](/images/RiiConnect24/Internet_17.png)
![Standby Connection 3](/images/RiiConnect24/Internet_18.png)
1. W `Slot Illumination`, zalecamy aby ustawić na `Dim (ciemny)` lub `Bright (jasny)`, ale jest to opcjonalne.
![Slot Illumination 1](/images/RiiConnect24/Internet_19.png)
![Slot Illumination 2](/images/RiiConnect24/Internet_20.png)
![Slot Illumination 3](/images/RiiConnect24/Internet_22.png)
1. Na koniec, wejdź do `Internet` i `User Agreements or Agreement/Contact` i wybierz `Yes`<br>
   Proszę przeczytaj to i nie pomijaj tego ponieważ zawiera to ważne informacje o RiiConnect24 jako serwis!
![User Agreements 1](/images/RiiConnect24/Internet_23.png)
![User Agreements 2](/images/RiiConnect24/Internet_24.png)

Jeżeli dostajesz błąd 107245, wygląda na to że zainstalowałeś IOS błędnie.
{: .notice--info}

[Jeżeli dostajesz błąd FORE000006, będziesz musiał podążyć za tym poradnikiem aby go naprawić](riiconnect24-batteryfix)
{: .notice--warning}

[Jeżeli dostajesz błędy np. `Service Discontinuation` kiedy otwierasz News lub Forecast Channel, mamy instrukcje które mogą Ci się przydać.](riiconnect24-troubleshooting)
{: .notice--warning}
