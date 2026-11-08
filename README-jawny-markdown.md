# Kierunki i specjalności — wersja testowa

Zmiany znajdują się na branchu `markdown-jawne-bloki-2026-11`. Otwierając Pages CMS wybierz ten branch.

- **Kierunki**: nazwy, treść Markdown PL/EN, dane, baner w jednym formularzu.
- **Specjalności**: wszystkie specjalności razem; Markdown, wybór opiekunów i seminariów, baner w jednym formularzu.
- Kafelki specjalności są częścią Markdownu **kierunku** (`:::specjalnosci`). Ich tekst i kolejność edytuje autor kierunku.
- Nagłówki można zmieniać; wyglądem sterują znaczniki `:::nazwa` i `::wstawka`. Komentarze przy blokach objaśniają zapis.
- Opiekunów wybiera się poniżej treści. Nazwisko i kontakt podstrony pochodzą z Web-Pracownicy po ID; teksty kafelków pozostają redakcyjne.

[Pełna instrukcja nowego Markdownu i znaczników](https://github.com/IM-UWr/Web-Core/blob/markdown-jawne-bloki-2026-11/dok/jawny-markdown.md).

`_cms/pracownicy` to katalog nazwisk do listy wyboru, bez danych kontaktowych. Nie edytuj go ręcznie. Po zmianie spisu pracowników odświeża go skrypt `synchronizuj-katalog-opiekunow.mjs` w Web-Core. Nie zmieniaj nazw plików istniejących pracowników: są identyfikatorami powiązań.

Ta wersja treści wymaga odpowiadającego brancha Web-Core. Do testu służy izolowany workflow w Web-Podglad, który tworzy artefakt bez publikowania. Przed późniejszym wdrożeniem zmiany kodu i danych trzeba skoordynować; ta instrukcja nie oznacza zgody na scalenie do main.
