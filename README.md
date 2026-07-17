# StavCalc
Stavební kalkulačka pro řemeslníky — jednoduchá PWA pro každodenní práci na stavbě.

---

## Co aplikace umí

### 📐 Úhel z diagonály
Změří skutečný úhel rohu pomocí diagonály. Zadáš délku ramene (1, 2 nebo 3 m) a naměřenou diagonálu — aplikace spočítá úhel a odchylku od 90°. Výsledek zobrazí, zda je roh pravý, ostrý nebo tupý.

### 📍 Vytyčení bodu
Výpočet vzdálenosti bodu od osy pomocí tangenty. Zadáš délku ramene a požadovaný úhel — výsledkem je přesná vzdálenost pro vytyčení.

### 📏 Spády

#### Převýšení A → B
Znáš výšku bodu A (nejvyšší), výšku bodu B (nejnižší) a vzdálenost mezi nimi — aplikace spočítá převýšení v mm, spád v procentech a úhel spádu ve stupních. Výsledek lze jedním klepnutím přenést do spádové tabulky nebo přímo do kalkulačky terčů.

#### Spádová tabulka
Generuje tabulku převýšení pro zadanou délku a sklon. Sklon lze zadat v procentech nebo stupních. Krok tabulky: 50 cm, 1 m nebo 2 m.

Součástí je přehled normových doporučení spádů podle českých norem (ČSN), ze kterých lze hodnotu rovnou předvyplnit:

| Prvek | Min | Opt | Max | Norma |
|-------|-----|-----|-----|-------|
| Spád chodníku (příčný) | 1,0 % | 2,0 % | 2,0 % | ČSN 73 6110 / Bezbar. předpisy |
| Balkony a lodžie | 1,0 % | 2,0 % | 3,0 % | ČSN 73 1901-1 |
| Střešní terasy | 1,0 % | 1,5 % | 3,0 % | ČSN 73 1901 |
| Sprchový kout | 1,0 % | 2,0 % | 2,5 % | Doporučení výrobců žlabů |
| Vnější parapet (oplechování) | 5,2 % | 8,7 % | 15,0 % | ČSN 73 3610 / ČSN 74 6077 |
| Plochá střecha | 2,0 % | 3,0 % | 8,7 % | ČSN 73 1901 |
| Střešní žlab | 0,5 % | 0,5 % | 1,0 % | ČSN 73 3610 |
| Vnitřní ležaté svody | 1,0 % | 2,0 % | 5,0 % | ČSN EN 12056-2 |
| Venkovní přípojka | 1,0 % | 2,0 % | 15,0 % | ČSN 75 6101 |
| Rampa do podzemních garáží | 2,0 % | 12,0 % | 17,0 % | ČSN 73 6058 |
| Vnější nezastřešená rampa | 2,0 % | 10,0 % | 15,0 % | ČSN 73 6058 |
| Rampa pro vozíčkáře (vnější) | 2,0 % | 6,25 % | 8,33 % | Vyhl. o bezbariérovém užívání |
| Rampa pro vozíčkáře (vnitřní) | 2,0 % | 6,25 % | 8,33 % | Vyhl. o bezbariérovém užívání |

### 🪨 Terče na terase
Výpočet výšek terčů pro terasy s dlaždicemi na rektifikovatelných podložkách. Zadáš formát dlaždice, rozměry plochy, požadovaný spád a výchozí výšku terče — aplikace vygeneruje tabulku klesajících výšek, upozorní na řady pod minimem 20 mm a zobrazí vizuální profil spádu. Součástí je odhad celkového počtu dlaždic a terčů včetně korekce podle tvaru plochy (obdélník, tvar L, U, složitý tvar).

---

## Technické info
- Vanilla HTML / CSS / JS — žádné frameworky, žádné závislosti
- PWA — lze nainstalovat na Android i iOS
- Tmavý vzhled, optimalizováno pro použití v terénu
- Offline provoz přes Service Worker

---

*Součást ekosystému NeoStudio Analytics © 2026*
