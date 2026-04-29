# Čtení – krok za krokem

Jednoduchá webová aplikace pro výuku čtení určená dětem s PAS (poruchou autistického spektra) a ADHD ve věku 6–9 let.

**Živá verze:** https://navidofek-cmyk.github.io/aac_static_web/

---

## Co aplikace umí

Čtyři sekce seřazené od nejjednoduššího po složitější:

1. **Slabiky** – otevřené slabiky rozdělené do skupin podle počáteční hlásky (M, L, S, P, T…)
2. **Slova** – dvojslabičná a trojslabičná slova s vizuálním oddělením slabik
3. **Věty** – krátké věty s klikacími slovy
4. **Krátké pohádky** – tři příběhy složené z naučených slov

---

## Přizpůsobení pro PAS a ADHD

| Funkce | Popis |
|---|---|
| **Fokus mód** | Slabiky zobrazuje jednu po druhé místo celé mřížky — méně vizuálního rušení |
| **Auto-čtení** | Při přechodu na další položku ji automaticky přečte nahlas |
| **Tlačítko Zopakovat** | Velké, výrazné tlačítko vždy na stejném místě — okamžité opakování bez hledání |
| **Micro-odměna** | Každých 5 kroků se zobrazí létající hvězdička — okamžitá pozitivní zpětná vazba |
| **Připomínač přestávky** | Volitelně připomene pauzu po 5 nebo 10 krocích |
| **Hvězdičky** | Celkový počet splněných sekcí viditelný v hlavičce |

---

## Nastavení

Vše se ukládá do prohlížeče (localStorage), takže nastavení přetrvá i po zavření.

- Velikost písma: malé / střední / velké
- Oddělovat slabiky: ano / ne
- Číst nahlas: zapnuto / vypnuto
- Rychlost čtení: pomalu / normálně / rychle
- Auto-čtení: zapnuto / vypnuto
- Fokus mód: zapnuto / vypnuto
- Přestávka: vypnuto / po 5 / po 10

---

## Technické info

- Čistý HTML/CSS/JS — žádné závislosti, žádný build
- Funguje offline (po prvním načtení)
- Čtení nahlas přes Web Speech API (hledá český hlas `cs-CZ`)
- Jeden soubor: `index.html`

---

## Lokální spuštění

Stačí otevřít `index.html` v prohlížeči. Žádný server není potřeba.

```bash
git clone https://github.com/navidofek-cmyk/aac_static_web.git
cd aac_static_web
# otevři index.html v prohlížeči
```
