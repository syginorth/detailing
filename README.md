# NOCTIS — strona studia detailingu

Jednostronicowa strona fikcyjnego studia detailingu premium (korekta lakieru, ceramika, folie PPF, wnętrza).
Styl według pliku DESIGN.md (czarno-złoty system inspirowany Lamborghini): czarne tło, złote przyciski CTA,
ogromne nagłówki wersalikami, zero zaokrągleń, heksagonalne motywy.

## Jak otworzyć

Wystarczy otworzyć `index.html` w przeglądarce. Nie trzeba niczego instalować.

Publikacja na GitHub Pages: **Settings → Pages → Source: Deploy from a branch → `main` / root**.

## Co jest na stronie

- Hero z pokazem 3 slajdów, paskiem postępu i heksagonalnym przyciskiem pauzy
- Manifest z napisem „zapalającym się” przy przewijaniu
- 6 usług z cenami i czasem realizacji (przycisk „Wybierz” ustawia usługę w formularzu)
- Sekcja studia
- Suwak „Przed / Po”
- 3 pakiety, 4 kroki procesu, FAQ
- Formularz rezerwacji z walidacją i potwierdzeniem
- Pełnoekranowe menu (Esc zamyka), wersja mobilna

## Do podmiany przed startem

- **Dane kontaktowe** (adres, telefon, e-mail) są przykładowe: szukaj `ul. Nocna 12`, `+48 500 000 000`, `noctis.example`.
- **Ceny, statystyki i gwarancje** są przykładowe.
- **Formularz** nigdzie jeszcze nie wysyła danych. W `index.html` znajdź komentarz
  `Tu podłącz prawdziwą wysyłkę` i podłącz np. Formspree albo własne API.
- **Zdjęcia** pochodzą z Unsplash i leżą w folderze `img/` (lista i źródła w `img/README.md`).
  Na stronie firmowej najlepiej zastąpić je zdjęciami własnych realizacji, pod tymi samymi nazwami plików.
- **Font**: LamboType z DESIGN.md nie jest publicznie dostępny, więc użyty jest Archivo (Google Fonts) w wąskiej szerokości.
