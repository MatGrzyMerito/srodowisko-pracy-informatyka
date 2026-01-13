# Diagram przepływu aplikacji

Poniższy diagram przedstawia ścieżkę użytkownika w aplikacji "Zielony Dom".

```mermaid
graph TD
    Start([START APLIKACJI]) --> Login[EKRAN LOGOWANIA]
    
    Login --> AddPlant[DODAJ NOWĄ ROŚLINĘ]
    Login --> ListPlants[LISTA ROŚLIN]

    %% Ścieżka dodawania
    AddPlant --> Choice(Wybór gatunku)
    Choice --> Schedule[USTAW HARMONOGRAM]
    Schedule --> Save(Zapisz do bazy)

    %% Ścieżka przeglądania
    ListPlants --> Click(Kliknięcie w roślinę)
    Click --> Details[SZCZEGÓŁY I HISTORIA]
    Details --> Water(Oznacz jako podlane)

    %% Wyjście
    Save --> End([KONIEC / WYJŚCIE])
    Water --> End
