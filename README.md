# Advanced Programming — ELTE TáTK, 2026/27/1

A kurzus nyilvános felülete: <https://tatk-advp-2026.github.io>

| | |
|---|---|
| `index.html` | A kurzus honlapja — óralista, aktuális dia |
| `01.pdf` … | Az előadásdiák, alkalmanként |
| `betuk/` | A kurzus betűtípusai, helyben (vetítés nem függ hálózattól) |

Új dia kirakása:

```sh
cp ../prezi/prezi-02.pdf 02.pdf
git add 02.pdf && git commit -m "2. előadás diái" && git push
```

Utána az `index.html`-ben az „aktuális" kártyát és az óralista sorát kell átlinkelni.
