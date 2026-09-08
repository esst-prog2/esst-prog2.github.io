# ESST-PROG2 — Advanced Programming

ELTE Faculty of Social Sciences · Survey Statistics and Data Analytics MA · 2026/27/1

A kurzus nyilvános felülete: <https://esst-prog2.github.io>

| | |
|---|---|
| `index.html` | A kurzus honlapja — óralista, aktuális dia |
| `01.pdf` … | Az előadásdiák, alkalmanként |
| `betuk/` | A kurzus betűtípusai, helyben (a vetítés nem függ hálózattól) |

Új dia kirakása:

```sh
cp ../prezi/prezi-02.pdf 02.pdf
git add 02.pdf && git commit -m "2. előadás diái" && git push
```

Utána az `index.html`-ben az „aktuális" kártyát és az óralista sorát kell átlinkelni.

Következő évfolyam: a mostani anyag `2026/` almappába kerül, a gyökérbe az új év
honlapja — így az `esst-prog2.github.io` cím évről évre ugyanaz marad.
