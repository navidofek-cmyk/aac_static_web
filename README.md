# Čtení – krok za krokem

Webová aplikace pro výuku čtení a počítání určená dětem s PAS (poruchou autistického spektra) a ADHD ve věku 6–9 let.

**Živá verze:** https://navidofek-cmyk.github.io/aac_static_web/

---

## Sekce

| # | Název | Obsah |
|---|---|---|
| 1 | **Slabiky** | Otevřené slabiky po skupinách (M, L, S, P, T, V, B, N, D, K, J, R) |
| 2 | **Slova** | ~27 slov s ARASAAC / Mulberry obrázky, klikací slabiky |
| 3 | **Věty** | 15 krátkých vět s klikacími slovy |
| 4 | **Krátké pohádky** | 3 příběhy složené z naučených slov |
| 5 | **Počítání** | Sčítání, odčítání, řady (L1/L2), rozklad — volitelné max. číslo (do 5/10/15/20), vizuální symboly |

---

## Přizpůsobení pro PAS a ADHD

| Funkce | Popis |
|---|---|
| **Fokus mód** | Slabiky zobrazuje jednu po druhé místo celé mřížky |
| **Auto-čtení** | Při přechodu na další položku ji automaticky přečte nahlas |
| **Tlačítko Zopakovat** | Velké, výrazné, vždy na stejném místě |
| **Vizuální symboly** | Pod příklady v počítání: ● ★ ♥ ☺ (volitelně) |
| **Micro-odměna** | Každých 5 kroků létající hvězdička |
| **Připomínač přestávky** | Volitelně po 5 nebo 10 krocích |
| **Hvězdičky** | Celkový progres viditelný v hlavičce |

---

## Obrázky ke slovům

- **ARASAAC** (https://arasaac.org) — většina slov, licence CC BY-NC-SA
- **Mulberry Symbols** (https://github.com/mulberrysymbols/mulberry-symbols) — Ema, Eva, mele, licence CC BY-SA

---

## Nastavení

Vše se ukládá v prohlížeči (localStorage).

- Velikost písma: malé / střední / velké
- Oddělovat slabiky: ano / ne
- Číst nahlas: zapnuto / vypnuto (Web Speech API, hledá hlas `cs-CZ`)
- Rychlost čtení: pomalu / normálně / rychle
- Auto-čtení: zapnuto / vypnuto
- Fokus mód: zapnuto / vypnuto
- Přestávka: vypnuto / po 5 / po 10

---

## Technické info

- Čistý HTML/CSS/JS — žádné závislosti, žádný build
- Jeden soubor: `index.html`
- Obrázky načítány z ARASAAC a Mulberry CDN (vyžaduje internet)
- Text a TTS fungují offline

---

## Lokální spuštění

```bash
git clone https://github.com/navidofek-cmyk/aac_static_web.git
cd aac_static_web
# otevři index.html v prohlížeči
```
