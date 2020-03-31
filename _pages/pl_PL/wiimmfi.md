---
title: "Wiimmfi"
---

{% include toc title="Zawartość" %}

![Wiimmfi Logo](/images/WiiWiimmfiLogo.jpg)

Wiimmfi jest zamiennikiem już niedziałąjącego serwisu Nintendo Wi-Fi Connection.

[Tutaj znajduje się strona Wiimmfi.](https://wiimmfi.de/)

## Aplikacja Homebrew dla płyt
MrBean35000vr (twórca CTGP-R, paczki tras) stworzyć patcher dla Wiimmfi który pozwala Ci włożyć płytę i zastosować poprawkę "w locie", niestety musisz to uruchamiać co każde uruchomienie gry.

#### Czego będziesz potrzebował
* Karta SD
* Homebrew Channel (you should already have this installed)
* [Auto Wiimmfi Patcher](/assets/files/autowiimmfipatcher-0.6.zip)

#### Instrukcje

1. Wypakuj `Auto Wiimmfi Patcher` oraz skopiuj go do folderu `apps` na Twojej karcie SD.
1. Włóż kartę SD do Twojej Wii oraz uruchom Wiimmfi Patcher korzystając z Homebrew Channel.
1. Włóż płytę z grą (możesz ją włożyć przed lub po uruchomieniu, nie ma to znaczenia).
1. Poczekaj aż wszystko się ukończy a gra się uruchomi!

## Bez Homebrew (Płyta)
Dzięki wersji FlashHax Fullmetal5, MrBean35000vr stworzył patcher dla płyt który możesz uruchomić korzystając z Internet Channel.

#### Czego będziesz potrzebował
* Internet Channel

#### Instrukcje

1. Włóż płytę z grą.
1. Upewnij się że tryb ekranu w ustawieniach jest ustawiony na 60Hz.
1. Otwórz Internet Channel i otwórz [tą](http://chadsoft.co.uk/wiimmfi/) stronę.
1. Dodaj tą stronę do "Ulubionych" klikając na "Add Favorite"
1. Zamknij Internet Channel oraz powróć do Wii Menu (możesz również użyć przycisku Reset)
1. Otwórz Internet Channel oraz idź do ulubionych oraz kliknij na Wiimmfi.
1. Poczekaj aż gra się uruchomii.

## Patchowanie ISO

Być może nie chcesz uruchamiać patchera za każdym razem kiedy chcesz grać na Wiimmfi dlatego jeżeli masz USB Loader'a. Patchere ISO zostały stworzone dla gier.

#### Czego będziesz potrzebował.
* Kopia twojej gry (WBFS, ISO, cIOS lub w innych formatach jakie Wii może czytać).
* Patcher Wiimm'a: Będziesz potrzebował [tego](http://download.wiimm.de/wiimmfi/patcher/mkw-wiimmfi-patcher-v6.zip) jeżeli chcesz chcesz spatchować Mario Kart Wii, [tego](https://github.com/RiiConnect24/ACW-Patcher/releases) jeżeli patchujesz Animal Crossing Wii lub [tego](http://download.wiimm.de/wiimmfi/patcher/wiimmfi-patcher-v4.7z) jeżeli patchujesz inne gry takie jak Super Smash Bros: Brawl.
* USB Loader, cIOS i USB aby przechować grę (już to musisz mieć jeżeli korzystasz z USB Loader'a)

#### Instruckcje
1. Wypakuj Twój patcher do folderu oraz skopiuj kopię gry do tego folderu.
1. Uruchom skrypt dla twojego systemu: zazwyczaj plik kończy się z `.bat` dla Windows'a i `.sh` dla Mac/Linux'a
1. Kiedy wszystko zostanie zakończone, skopiuj grę z folderu `wiimmfi-images` i skopiuj go do Twojego USB.

## WiiWare Patching
Możesz spatchować gry WiiWare aby grać w nie na Wiimmfi

#### Czego będziesz potrzebował

- Kopia twojej gry, (w formacie WAD).
- [Auto WiiWare Patcher](https://github.com/RiiConnect24/auto-wiiware-patcher/releases)
- [Wii Mod Lite](https://github.com/RiiConnect24/Wii-Mod-Lite/releases)

[Jeżeli chcesz się dowiedzieć jak działa WiiWare Patcher, naciśnij tutaj!](wiiwarepatcher)
{: .notice--info}

Kroki:
1. Wypakuj .zip z najnowszą wersją Auto WiiWare Patcher do folderu i włóż plik WAD do niego.
1. Uruchom skrypt dla twojego systemu: dla Windows'a zakończy się na `.bat` a dla Mac/Linux'a `.sh`
1. Jeżeli wszystko przebiegło pomyślnie, zainstaluj WAD który pojawił się w `wiiware-wads` z Wii Mod Lite.

## Zawody Mario Kart Wii
Wiimmfi pozwala Ci uczestniczyć w zawodach Mario Kart Wii.

#### Czego będziesz potrzebował
* Mario Kart Wii Competition Patcher [Wii](https://competitions.wiimmfi.de/competition-tool-wii.zip) / [Wii U (vWii)](https://competitions.wiimmfi.de/competition-tool-wiiu.zip)

#### Instrukcje (dla Wii)

1. Wypakuj Patcher Mario Kart Wii Competition Patcher i skopiuj go do folderu `apps` na karcie SD.
1. Włóż kartę SD do Twojej Wii.
1. Uruchom oryginalną wersję Mario Kart Wii (bez patcha Wiimmfi).
1. Przejdź do Settings -> Network Settings (or Nintendo WFC Connection) -> Message Service. Jeżeli włączyłeś już tą opcje, wyłącz ją i włącz ponownie.
1. Uruchom Mario Kart Wii Competition Patcher.
1. Patcher wyszuka wszystkie zapisy gier z Mario Kart Wii oraz wyślę je do serwisu Wiimmfi. Ten zabieg jest robiony po to że jeżeli w twoim zapisie znajduje się jakiś plik zawodów z przeszłości które Wiimmfi nie ma na swoich serwerach, zostanie to wysłane do nich. Patcher również zastosuje poprawkę na Twoją konsolę aby uruchomić zawody.

Jeżeli używać Wii U, będziesz musiał uruchomić competition patcher zawsze jeżeli będziesz chciał sprawdzić czy istnieją nowe zawody, ponieważ WiiConnect24 nie jest dostępne na Wii U.
{: .notice--info}

## CTGP-R (Mario Kart Wii)
MrBean35000vr i Chadderz zrobili niesamowitą dystrybucję CTGP-R, ta aplikacja pozwoli Ci używać ich dystrybucję. Przejdź do strony [ChadSoft Website](http://chadsoft.co.uk) oraz pobierz ich aplikację oraz instrukcję do niej.

## MKW Hack Pack (Mario Kart Wii)
Huili stworzył bardzo dobrą kolekcję niestandardowych tras oraz hacków nazwaną MKW Hack Pack oraz pozwala to podłączyć się do Wiimmfi. Aby się dowiedzieć jak go ustawić, wejdź na [stronę wiki](http://wiki.tockdom.com/wiki/MKW_Hack_Pack).
Huili has put together a really good collection of custom tracks and hacks called MKW Hack Pack, and it allows you to connect to Wiimmfi. To learn how to set it up, go to the [wiki page](http://wiki.tockdom.com/wiki/MKW_Hack_Pack).

[Naciśnij tutaj! Mamy również wiele innych poradników które możesz przejrzeć :)](site-navigation)
{: .notice--info}
