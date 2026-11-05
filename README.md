# PDF Pin — strona WWW

Strona aplikacji **PDF Pin** (iOS): <https://krystiankjjk.github.io/PDF-Pin/>

To repozytorium zawiera **wyłącznie** gotową, statyczną stronę. Kod aplikacji
jest w osobnym, prywatnym repozytorium.

## Zawartość

```
docs/                       ← serwowane przez GitHub Pages (gałąź main, folder /docs)
├── index.html              ← wybór języka
├── pl/  en/                ← strona główna, support/ (wsparcie), privacy/ (polityka prywatności)
├── privacy-policy-{pl,en}.html ← przekierowania dawnych adresów polityki
├── 404.html
├── assets/                 ← CSS, ikony, obrazek do udostępniania
└── .nojekyll               ← pliki serwowane 1:1, bez Jekylla
```

## Nie edytuj ręcznie

Pliki w `docs/` są **generowane** w repozytorium aplikacji
(`Scripts/website/build.py`) i publikowane skryptem
`Scripts/website/publish.py`. Każda publikacja zastępuje cały `docs/`,
więc ręczne zmiany tutaj zostaną nadpisane. Commit publikacji podaje,
z którego commitu repozytorium aplikacji pochodzi strona.

Strona nie ładuje nic z zewnątrz (CDN, fonty, analityka) — tak obiecuje
polityka prywatności aplikacji.

Kontakt: pdfpinapp@icloud.com

---

**English.** Static website of the PDF Pin iOS app, served by GitHub Pages
from `docs/`. The files are generated in the (private) app repository and
published by a script — do not edit them here. Contact: pdfpinapp@icloud.com
