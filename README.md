# SG Gwint — výsledky LLM sampionátů

Statický web s výsledky LLM sampionátů karetní hry **SG Gwint v2.2**
(komunitní hra spolku Společenstvo Gwintu, z.s. — projekt ukončen 2025).

## Co tu je

- `index.html` — šampioni frakcí, kompletní žebříčky, vzájemné zápasy
- `balicky.html` — všechny balíčky s kompletními výpisy karet
- `balicek-*.html` — detail každého balíčku (velitel, síla, zlaté karty, speciálky, řady, vzájemné zápasy)
- `o-projektu.html` — metodika, modely, interpretace

Web je generovaný (generátor `tools/build_web.py` žije v soukromém repu
`balhar-jakub/sgwint` společně s enginem, databází karet a kompletními herní logy
všech partií). Po dokončení každého sampionátu se přegeneruje a pushne sem.

Data: turnaje LLM agentů (deepseek-v4.1-flash, mistral-medium-latest,
ministral-8b-latest), každý balíček proti každému, 4 partie na pár, strany střídány.

## GitHub Pages

<https://balhar-jakub.github.io/sgwint-vysledky/>

## Autorská práva

Pravidla a karty SG Gwintu jsou dílem spolku Společenstvo Gwintu, z.s.
Repo neobsahuje artworky ani skeny karet — jen textová herní data a výsledky AI partií.
