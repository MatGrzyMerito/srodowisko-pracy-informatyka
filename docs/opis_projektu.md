# Opis projektu — Aplikacja do pielęgnacji roślin "Zielony Dom"

## Cel:
* Ułatwić domownikom i hobbystom dbanie o kondycję roślin doniczkowych.
* Zminimalizować ryzyko uschnięcia lub przelania roślin poprzez automatyzację przypomnień.
* Stworzyć centralne miejsce wiedzy o posiadanych gatunkach i ich wymaganiach.

## Problem:
* Zapominanie o regularnym podlewaniu w natłoku codziennych obowiązków.
* Brak wiedzy na temat specyficznych wymagań (np. ilość światła, wilgotność) dla konkretnych gatunków.
* Trudność w diagnozowaniu problemów (dlaczego liście żółkną?) bez szybkiego dostępu do historii pielęgnacji.

## Odbiorcy:
* Hobbyści i miłośnicy "Urban Jungle".
* Osoby zapracowane, które chcą mieć zielone mieszkanie, ale potrzebują zewnętrznego wsparcia w organizacji.
* Osoby początkujące, które dopiero zaczynają przygodę z roślinami.

## Kluczowe funkcje:
1.  **Baza roślin** (karta rośliny ze zdjęciem i wymaganiami).
2.  **Inteligentny harmonogram** (podlewanie, zraszanie, nawożenie).
3.  **Powiadomienia PUSH** przypominające o akcjach w odpowiednim czasie.
4.  **Historia pielęgnacji** (dziennik zdarzeń dla każdej rośliny).
5.  **Baza wiedzy** (porady dla konkretnych gatunków).
6.  **Tryb wakacyjny** (możliwość udostępnienia harmonogramu osobie opiekującej się mieszkaniem).
7.  **Galeria postępów** (zdjęcia "przed i po" wzrostu).

## Wymagania funkcjonalne:
* Dodawanie, edycja i usuwanie roślin z "mojego ogrodu".
* Konfiguracja częstotliwości powiadomień (cykliczne / jednorazowe).
* Możliwość odhaczenia zadania ("Podlane") lub przesunięcia go ("Przypomnij jutro").
* Filtrowanie roślin po pomieszczeniach (np. Salon, Kuchnia).
* Działanie bazy danych w trybie offline.

## Wymagania niefunkcjonalne:
* Niskie zużycie baterii (optymalizacja procesów w tle).
* Intuicyjny interfejs (maksymalnie 3 kliknięcia do potwierdzenia podlania).
* Skalowalność bazy danych (płynne działanie przy >50 roślinach).
* Estetyczny, "zielony" design sprzyjający relaksowi (UI/UX).

## MVP (priorytet):
1.  Dodawanie rośliny (nazwa + zdjęcie).
2.  Ręczne ustawienie interwału podlewania (np. co 7 dni).
3.  System powiadomień systemowych (Push).
4.  Lista "Do zrobienia na dziś".
5.  Baza wiedzy dla 5-10 najpopularniejszych gatunków.

## Scenariusze użytkownika / user stories:
* **Jako zapracowany pracownik biurowy** chcę otrzymać powiadomienie rano w sobotę, abym nie musiał pamiętać o podlewaniu przez cały tydzień.
* **Jako początkujący** chcę wiedzieć, czy ta konkretna paprotka lubi dużo słońca, by postawić ją w dobrym miejscu.
* **Jako hobbysta** chcę widzieć historię nawożenia, by nie przenawozić swoich okazów.

## Metryki sukcesu:
* Współczynnik "przeżywalności" roślin (ankiety okresowe u użytkowników).
* Regularność reagowania na powiadomienia (Time-to-action).
* Liczba dodanych roślin na użytkownika.
* Retencja użytkowników po 3 miesiącach (czy dalej dbają o rośliny z aplikacją).

## Bezpieczeństwo i prywatność:
* Dane o lokalizacji i zdjęcia przechowywane lokalnie na urządzeniu (chyba że włączono backup w chmurze).
* Brak udostępniania danych marketingowych bez wyraźnej zgody.
* Możliwość wykonania pełnego eksportu danych o swoich roślinach.

## Propozycje technologiczne (orientacyjne):
* **Frontend:** Flutter / React Native (jedna baza kodu na iOS i Android).
* **Backend:** Firebase (Authentication, Cloud Messaging do powiadomień) lub rozwiązanie Serverless.
* **Baza danych:** SQLite (lokalna) + opcjonalna synchronizacja z chmurą.
* **AI (opcjonalnie w przyszłości):** Rozpoznawanie chorób roślin ze zdjęć (Computer Vision).

## Plan rozwoju:
* **Faza 0:** Makiety UX/UI, zdefiniowanie bazy gatunków.
* **Faza 1:** MVP (Lista roślin, Harmonogram, Powiadomienia).
* **Faza 2:** Rozbudowana baza wiedzy, profile pomieszczeń, tryb wakacyjny.
* **Faza 3:** Integracja z czujnikami wilgotności IoT, społeczność wymiany sadzonek.

## Krótka nota końcowa:
Aplikacja ma być "cichym asystentem" – nie powinna być natrętna, lecz budować nawyk regularnej i spokojnej dbałości o otoczenie.
