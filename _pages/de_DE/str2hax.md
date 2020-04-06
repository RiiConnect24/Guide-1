---
title: "str2hax"
---

{% include toc title="Table of Contents" %}

Falls du irgendwelche Hilfe bezüglich der Anleitung benötigst, tritt bitte dem [RiiConnect24 Discord Server](https://discord.gg/b4Y7jfD)(empfohlen) bei, oder kontaktiere uns [per E-Mail unter support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

Wenn dein Internetdienstanbieter oder deine Netzwerkumgebung die Nutzung eines Custom DNS Server's verhindert dann wird str2hax nicht funktionieren und du solltest [einen anderen Exploit wählen](get-started).
{: .notice--info}

str2hax ist ein Exploit für die Wii, welcher ausgelöst wird mithilfe einer Sicherheitslücke in dem Endbenutzer-Lizenzvertrag. Es benötigt nichts anderes außer die Internetverbindung deiner Wii, die dich den DNS verändern lässt.

#### Voraussetzungen

* Eine Wii mit Internetverbindung und Systemversion 4.3

#### Anleitung

##### Abschnitt 1 - Verbinden

Damit dieser Exploit funktioniert, musst du deine DNS Einstellungen bearbeiten, damit sich deine Wii zu einem Server verbinden kann, der den Exploit auslöst.

1. Gehe in die `Wii-Optionen`. ![Wii Options](/images/RiiConnect24/Internet_1.png)
2. Gehe in die `Wii-Systemeinstellungen`. ![Wii Settings](/images/RiiConnect24/Internet_2.png)
3. Gehe auf `Seite 2`, wähle dann `Internet`. ![Internet](/images/RiiConnect24/Internet_3.png)
4. Gehe auf `Verbindungseinstellungen`. ![Connection Settings](/images/RiiConnect24/Internet_4.png)
5. Wähle deine derzeitige Verbindung aus. ![Current Connection](/images/RiiConnect24/Internet_5.png)
6. Gehe auf `Ändern`. ![Change Settings](/images/RiiConnect24/Internet_6.png)
7. Gehe auf `DNS automatisch beziehen` (Nicht IP-Adresse), wähle dann `Nein` und gehe dann auf `Detaileinstellungen`. ![Auto-Obtain DNS](/images/RiiConnect24/Internet_7.png)
8. Gebe `97.74.103.14` als primärer DNS-Server an.
9. Gebe `173.201.71.14` als sekundärer DNS-Server an.
10. Wähle `Bestätigen`, dann `Speichern`. ![Save DNS](/images/RiiConnect24/Internet_10.png)
11. Wähle `OK` um einen Verbindungstest durchzuführen. ![Connection Test](/images/RiiConnect24/Internet_11.png)
   - Wenn der Verbindungstest erfolgreich war, wähle `Nein`, um das Wii-Systemupdate zu überspringen. ![Connection Test Successful](/images/RiiConnect24/Internet_12.png)
   - If it was unsuccessful, then please use [another exploit](get-started).

##### Abschnitt 2 - Ausführen des Exploits

1. Gehe in den Bereich `Internet`, dann `Vertrag/Kontrakt`, dann `Ja`.
2. If you see a pony on the screen on a light blue background, you have set it up correctly. Wait 1-2 minutes for the exploit to trigger (it should take about 1 minute and 25 seconds). The exploit will download the HackMii Installer so you can continue.

If the HackMii Installer doesn't load and it instead freezes (you can't move your cursor) or it doesn't take 1-2 minutes to trigger, please restart your Wii and retry the exploit.

[Fahre nun fort mit der Homebrew-Kanal und BootMii-Installation](hbc)
{: .notice--info}
