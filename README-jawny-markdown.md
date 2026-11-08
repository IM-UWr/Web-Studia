# Edycja działu Studia — jawny Markdown

Otwierając Pages CMS wybierz repozytorium Web-Studia i branch `main`. Wszystkie teksty działu Studia używają jawnego Markdownu.

- **Kierunki**: nazwy, treść Markdown PL/EN, dane, baner w jednym formularzu.
- **Specjalności**: wszystkie specjalności razem; Markdown, wybór opiekunów i seminariów, baner w jednym formularzu.
- **Strony**: wszystkie 15 pozostałych podstron Studiów, również w podfolderach. Zwykłe teksty, listy i tabele są opisane blokami `proza`; nagłówki mają stabilne kotwice.
- **Strona działu Studia** i **Rok akademicki**: również jawny Markdown, z komentarzami wyjaśniającymi położenie tekstu względem części generowanych z danych.
- Kafelki specjalności są częścią Markdownu **kierunku** (`:::specjalnosci`). Ich tekst i kolejność edytuje autor kierunku.
- Nagłówki można zmieniać; wyglądem sterują znaczniki `:::nazwa` i `::wstawka`. Komentarze przy blokach objaśniają zapis.
- Wszystkie pola Markdown PL/EN, także „Koniec strony” Roku akademickiego, używają kolorowanego edytora `code`. Dawny przełącznik „Bloki wzorca” zastępują jawne znaczniki.
- Opiekunów wybiera się poniżej treści. Nazwisko i kontakt podstrony pochodzą z Web-Pracownicy po ID; teksty kafelków pozostają redakcyjne.

[Pełna instrukcja nowego Markdownu i znaczników](https://github.com/IM-UWr/Web-Core/blob/main/dok/jawny-markdown.md).

`_cms/pracownicy` to katalog nazwisk do listy wyboru, bez danych kontaktowych. Nie edytuj go ręcznie. Po zmianie spisu pracowników odświeża go skrypt `synchronizuj-katalog-opiekunow.mjs` w Web-Core. Nie zmieniaj nazw plików istniejących pracowników: są identyfikatorami powiązań.

Treści wymagają odpowiadającego parsera w Web-Core/main. Gdy zmieniasz sam tekst w CMS, zachowaj znaczniki bloków i identyfikatory sekcji. Przy zmianach formatu trzeba aktualizować kod i treści razem.
