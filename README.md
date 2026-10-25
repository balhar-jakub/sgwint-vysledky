# SG Gwint — sampionát v10 (výsledky)

Statický web s výsledky aktuálního **sampionátu v10** karetní hry **SG Gwint v2.2**
(komunitní hra spolku Společenstvo Gwintu, z.s. — projekt ukončen 2025).

## Co tu je

- `index.html` — šampioni frakcí, žebříčky, vzájemné zápasy, validace v10 hráče
- `balicky.html` — seznam všech 24 balíčků setu k4 s odkazy na detaily
- `karty.html` — kompletní databáze karet SG Gwintu v2.2 (velitelé, jednotky,
  speciálky, tokeny, po frakcích, s hledáním)
- `k4balicek-*.html` — detail každého ze 24 balíčků setu k4 (velitel, síla, zlaté
  karty, speciálky, řady, kompletní výpis karet se schopnostmi)
- `hry/` — přehrávače partií: každý matchup (36 párů × všechny odehrané partie)
  jako interaktivní replayer — deska tah po tahu, skóre, počasí, perspektivy
  (god/A/B), timeline; katalog na `hry/index.html`

Web obsahuje **pouze aktuální set k4** (4 balíčky na frakci, všech 6 frakcí,
každý 34 karet, s velitelem; legálnost ověřuje rozhodčí engine). Historické
sampionáty a ligy (před rulingy 17. 10. 2026) zůstávají v soukromém repu.

Web je generovaný (generátor `tools/build_web.py --v10-only` žije v soukromém repu
`balhar-jakub/sgwint` společně s enginem, databází karet a kompletními herní logy
všech partií). Po dokončení každého měření se přegeneruje a pushne sem.

## GitHub Pages

<https://balhar-jakub.github.io/sgwint-vysledky/>

## Autorská práva

Pravidla a karty SG Gwintu jsou dílem spolku Společenstvo Gwintu, z.s.
Repo neobsahuje artworky ani skeny karet — jen textová herní data a výsledky AI partií.
