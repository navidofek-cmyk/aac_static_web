# Chat history — vývoj aplikace

## Výchozí stav
- Existující soubor `cteni.html` — jednoduchá čtecí app
- `window.storage` (nefungovalo v prohlížeči), žádné PAS/ADHD úpravy

---

## Co bylo přidáno / opraveno

### Základ
- Přejmenováno na `index.html` (GitHub Pages)
- Opraveno `window.storage` → `localStorage`
- Pushnutý repozitář: https://github.com/navidofek-cmyk/aac_static_web
- GitHub Pages aktivovány: https://navidofek-cmyk.github.io/aac_static_web/

### Úpravy pro PAS + ADHD (7–8 let, žije s tátou)
- **Fokus mód** — slabiky jednu po druhé (méně rušivé)
- **Auto-čtení** — automaticky přečte při přechodu na další položku
- **Zopakovat** — velké oranžové tlačítko na každé obrazovce
- **Micro-odměna** — létající hvězdička každých 5 kroků
- **Přestávka** — připomínač po 5 nebo 10 krocích
- Odstraněno slovo **máma** (dítě žije s tátou)

### Obsah — Slabiky
- 12 → **22 skupin** souhlásky: M L S P T V B N D K J R **F G H CH Z Ž Š Č C Ř**
- Ke každé **slabice** pěkné české slovo (balón, beruška, medvěd, tulipán…)
- V **fokus módu**: velká slabika + obrázek ARASAAC/Mulberry + klikatelné slovo
- V **mřížce**: slabika + malý popis slova
- Pod každou skupinou ukázková slova s obrázkem

### Obsah — Slova
- Rozšířeno z ~25 na **~45 slov**
- Nová slova: hora, husa, záda, zima, žába, šála, fena, chata, šiška, čáp, zuby, cesta, řeka, guma, garáž, bubák, ryba, koza, duha, auto…
- Opraveny překlepy: `leto`→`léto`, `jidlo`→`jídlo`, `teletu`→`pero`, odstraněn duplikát `táta`
- Odstraněno `selo` (není slovo) → nahrazeno `ryba`
- Odstraněno `kosa` (obrázek velryby!) → nahrazeno `koza`

### Obrázky
- **ARASAAC** (CC BY-NC-SA) — hlavní zdroj, ~120 slov
- **Mulberry Symbols** (CC BY-SA) — záloha pro slova bez ARASAAC obrázku
  - Ema, Eva, mele, luna, hůl, fůra, šéf, bůh, seno, topinka, chůva
- Špatné obrázky opraveny (kosa→velryba→odstraněno, mele→chameleon→odstraněno…)

### Věty
- Přidány věty s autem: *Táta má auto.* / *Táta jede autem.* / *Táta je bez auta.*
- Odstraněny věty s **máma**

### Pohádky
- Odstraněna pohádka „Máma mele" → nahrazena „Na poli" (Eva, táta, vosa, kolo)

### Sekce 5 — Počítání (nové)
- Typy: **sčítání, odčítání, řady L1** (krok 1), **řady L2** (kroky 2–3), **rozklad**
- Max. číslo: `do 5` / `do 10` / `do 15` / `do 20`
- Vizuální symboly pod čísly: ● ★ ♥ ☺ (volitelné)
- 4 tlačítka s odpověďmi, zelená/červená zpětná vazba
- Hvězdičky za správné odpovědi v řadě
- Tlačítko „Nová sada příkladů"

### Nastavení
| Položka | Výchozí |
|---|---|
| Velikost písma | střední |
| Oddělovat slabiky | ano |
| Číst nahlas | zapnuto |
| Rychlost čtení | normálně |
| Auto-čtení | zapnuto |
| Fokus mód | zapnuto |
| Přestávka | po 5 |

### Technické
- GitHub odkaz v hlavičce aplikace
- README aktualizováno po každém commitu

---

## Chybějící obrázky (k doplnění)
Slova bez vhodného ARASAAC ani Mulberry obrázku:
`louka, lípa, datel, kaluž, vinice, vodník, záhada, čajník, síla, tíha, tůň, gitara, hiena`

### Slabiky bez slova (k doplnění)
`bé, ca, ché, chí, cá, ců, dé, fu, gí, gů, hé, hí, ju, jé, jů, ké, kí, mé, né, ní, pé, ri, rí, sé, té, vu, vé, zé, zů, ču, čé, čů, řo, řu, řé, řů, šů, žo, žé, žů`

---

## Zdroje symbolů
- ARASAAC: https://arasaac.org (CC BY-NC-SA)
- Mulberry Symbols: https://github.com/mulberrysymbols/mulberry-symbols (CC BY-SA)
- OpenSymbols: https://www.opensymbols.org (zatím bez tokenu)
