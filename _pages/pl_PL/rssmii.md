---
title: "Instalowanie RSSMii"
---

{% include toc title="Zawartość" %}

Chcesz otrzymywać kanały RSS na Twoim Wii Message Board? Ten poradnik pomoże Ci ustawić RSSMii.

![RSSMii](/images/rssmii.png)

#### Czego będziesz potrzebował

* Karty SD
* [RSSMii](https://github.com/RiiConnect24/rssmii/releases)

#### Instrukcje

##### Sekcja I - Pobieranie/Instalowanie

1. Wypakuj RSSMii do folderu `apps` na Twojej karcie SD.
1. Musimy stworzyć plik `feeds.xml` na Twojej karcie SD aby RSSMii wiedziało jakie kanały RSS chcezz zasubskrybować.

[Masz komputer z Windows'em? Pobierz nasz RSS Feeds Creator stworzony przez KcrPL (twórce polskiego tłumaczenia). Ten program automatycznie stworzy `feeds.xml` i skopiuje ten plik na Twoją kartę SD! Naciśnij tutaj aby go pobrać.](https://github.com/RiiConnect24/rssmii/releases)
{: .notice--info}

<B>Jeżeli nie masz komputera z Windows'em, użyj tego szablonu w Twoim ulubionym edytorze tekstu aby stworzyć plik `feeds.xml`. Jeżeli jest to zbyt skomplikowane dla Ciebie, napisz do nas [support@riiconnect24](mailto:support@riiconnect24.net) (Obsługa dostępna po polsku) a stworzymy ten plik specjalnie dla Ciebie!</b>

    ```
    <?xml version="1.0" encoding="utf-8"?>
    <rss>
      <feed name="Przykladowy-Kanal"><![CDATA[http://example.com/rss-feed]]></feed>
      <feed name="Jeszcze jeden przykladowy kanal"><![CDATA[http://example.com/another_rss-feed]]></feed>
    </rss>
    ```

	Zamień część "name" z nazwą kanału jaki chcesz dodać. Upewnij się że ta nazwa nie będzie za długa ponieważ jest pewne ograniczenie.
	Następnie, zamień część [CDATA] z linkiem do twojego kanału RSS. Możesz dodać tyle kanałów ile chcesz. 
    ```
    <?xml version="1.0" encoding="utf-8"?>
    <rss>
      <feed name="RiiConnect24 Medium"><![CDATA[https://medium.com/feed/riiconnect24]]></feed>
      <feed name="RiiConnect24 Twitter"><![CDATA[https://twitrss.me/twitter_user_to_rss/?user=RiiConnect24]]></feed>
      <feed name="Nintendo News"><![CDATA[https://www.nintendo.com/feed]]></feed>
    </rss>
    ```

	Wygląda świetnie! Teraz zapisz ten plik do `feeds.xml` na Twojej karcie SD.

1. Uruchom RSSMii używając Homebrew Channel.
1. Naciśnij "A" aby potweirdzić że chcesz zasubskrybować podane Kanały RSS. Zignoruj błąd o ES_GetTitleID.
1. Kiedy wszystko będzie gotowe, naciśnij HOME aby powrócić do Homebrew Channel. Wkrótcę powinieneś otrzymać aktualizacje z kanałów RSS na Twoim Wii.

Nie dostajesz żadnych aktualizacji? Spróbuj dodać kanał RSS który częściej się aktualizuje, na przykłąd kanał informacyjny. Jeśli kanał RSS nie jest aktualizowany często, nie otrzymasz dużo aktualizacji na Twoim Wii.
{: .notice--warning}

Zalecamy abyś tylko zasubskrybował do kilku kanałów ponieważ możesz otrzymać za dużo wiadomości na Twojej Wii.
{: .notice--info}

Jeżeli nie otrzymujesz aktualizacji przez kilka dni, spróbuj zasubskrybować kanały RSS ponownie. Uruchom RSSMii z Homebrew Chanel i spróbuj jeszcze raz.
{: .notice--info}

[Kasowanie RSSMii](rssmii-remove)
{: .notice--info}
