# Inspiracje (słowa, skojarzenia, pomysły)

* natura, zieleń, spokój, równowaga psychiczna (wellbeing)
* nawadnianie, cykl życia, pory roku, nasłonecznienie
* powiadomienia push, systematyczność, nawyk
* smart home, ekologia, "Urban Jungle"
* fotodziennik, timelapse wzrostu rośliny
* gamifikacja (odznaki za utrzymanie rośliny przy życiu)
* minimalizm w interfejsie, kolory ziemi, tryb ciemny/jasny
* metadata: gatunek, stanowisko, data zakupu, ostatnie podlanie

# Krótka lista elementów projektu

* interfejs użytkownika (Mobile App - iOS/Android)
* lokalna baza danych (SQLite / Realm) do przechowywania ustawień
* system harmonogramowania zadań w tle (Background Service)
* moduł powiadomień lokalnych (Push Notifications)
* baza wiedzy o gatunkach (statyczny plik JSON lub mini-CMS)
* moduł aparatu (dodawanie zdjęć roślin, przyszłościowo skaner QR)
* import/eksport danych (backup ustawień)
* prosty system tagowania (np. wg pomieszczeń)

# Wstępne dane wejściowe

* **lista kategorii roślin:** Sukulenty (mało wody), Paprocie (dużo wilgoci), Zioła kuchenne (codzienna pielęgnacja), Palmy domowe, Rośliny oczyszczające powietrze, Rośliny trujące dla zwierząt.
* **lista funkcji priorytetowych:**
    1.  Dodawanie nowej rośliny (zdjęcie + nazwa).
    2.  Konfiguracja harmonogramu (częstotliwość podlewania/zraszania).
    3.  Powiadomienia i przypomnienia na telefon.
    4.  Baza wiedzy (karta wymagań gatunku).
    5.  Widok "Mój Ogród" (lista wszystkich roślin).
    6.  Oznaczanie zadań jako wykonane (szybka akcja).
* **przykładowe tagi startowe:** #salon, #kuchnia, #balkon, #dużo_słońca, #cień, #wymagająca.
* **przykładowe metadane:** {nazwa_własna, gatunek, interwał_podlewania, data_ostatniego_podlania, url_zdjęcia, uwagi}.

# Lista źródeł pomysłu

* własna potrzeba: uschła mi bazylia w kuchni z braku regularności.
* znajoma: szukała aplikacji, która rozpozna roślinę po zdjęciu i powie jak o nią dbać.
* Pinterest: rosnący trend "Urban Jungle" i mody na zielone wnętrza.
* analiza konkurencji: istniejące aplikacje są często zbyt skomplikowane lub płatne (subskrypcje).
* obserwacja problemu: brak wiedzy o tym, dlaczego roślina choruje (przenawożenie vs przesuszenie).
