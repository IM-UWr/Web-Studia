# Web-Studia

Treści strony Instytutu Matematycznego UWr — Studia.

Edycja: [Pages CMS](https://app.pagescms.org) → wybierz repozytorium i gałąź. Formularze tej reorganizacji są na gałęzi `cms-reorganizacja-2026-11`; wybór `main` pokazuje poprzednie formularze.

Specjalności edytuje się w jednej kolekcji **Specjalności**: tekst PL/EN, baner, kafelek, kierunek, opiekunowie i seminaria. Wszystkie dane wpisu leżą w `src/content/specjalnosci/<id>.md`. Nie zmieniaj nazw istniejących plików, bo określają adresy.

**Status publikacji** zapisuje `oficjalna` (Opublikowana — strona oficjalna i podgląd) albo `podglad` (Tylko podgląd). Ten wybór na razie nie zmienia widoczności strony. Podgląd oraz repozytorium są publiczne.

Zmiany gałęzi roboczej nie uruchamiają publikacji z `main`. Izolowany test znajduje się w [Web-Podglad](https://github.com/IM-UWr/Web-Podglad), workflow „Test reorganizacji CMS (bez publikacji)”. Po przyszłym wdrożeniu zapisy w `main` uruchamiają obecną ścieżkę powiadomienia Web-Core → Web-Podglad.
