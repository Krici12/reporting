# Reporting – přehled činnosti na univerzitě

Veřejný repozitář s přehledem mé práce na projektu meteorologického modelu **WRF (Weather Research and Forecasting)** – downscaling klimatických scénářů a autonomní pipeline krátkodobé předpovědi počasí, provozovaného na národní HPC platformě **MetaCentrum**.

Obsahuje pouze práci vykonanou pro projekt (WRF a MetaCentrum), ne výuku, IGA ani jiné aktivity.

## Obsah

- [harmonogram.md](harmonogram.md) – harmonogram prací rozdělený do tří období
  - 1. pololetí 2025 (leden–červen)
  - 2. pololetí 2025 (červenec–prosinec)
  - 1. pololetí 2026 (leden–červen)

## Kontext

- **Smlouva / projekt od univerzity:** duben 2025.
- **MetaCentrum:** od dubna/května 2025; do té doby ladění WRF na školním serveru „adagrif“.
- **Projekt „WRF nad povodím Ohře“:** ve spolupráci s Mgr. Markem Vachem a kolegy (Aleš Balvín, Michala Jakubcová, Daniel Černý, Marta Kuželková).
- **Stáž Cyprus Institute (04/2025):** zaměřená na WRF, konzultace s expertem na WRF **Ioannisem Sofokleousem** ([profil](https://www.cyi.ac.cy/index.php/eewrc/about-the-center/eewrc-our-people/itemlist/user/1376-ioannis-sofokleous.html)).

## Online výstupy

- https://krici12.github.io/WRF_Domain/ – interaktivní mapa domén
- https://weather-forecast.fzp.czu.cz – **nová adresa**; vizualizace předpovědí byla v srpnu 2026 přesunuta z původního repozitáře **WRF_Forecast_Viewer** (https://krici12.github.io/WRF_Forecast/), který už nefunguje.

## Klíčová čísla (zdroj: průběžná zpráva týmu WRF, stav k 07/2026)

- **≈ 1 420** odeslaných výpočetních úloh (jobs) na MetaCentru
- **≈ 946 000** CPU-hodin strojového času (≈ 107 let a 329 dní výpočtu na jednom jádru)
- **≈ 67 TB** napočítaných dat (48 TB klimatické scénáře · 14 TB předpovědi · 4,9 TB reanalýzy)
- Rozlišení domén: scénáře 9 km · předpověď 3 km (možnost 1 km) · reanalýza 1 km
- Meziročně: 2025 → 202 úloh, 2026 (k 22. 7.) → ≈ 1 220 úloh

## Zdroje

- Měsíční pracovní výkazy (WorkIS) za 01/2025–08/2026
- Průběžná zpráva týmu WRF „Downscaling scénářů a předpověď WRF“ (duben 2025 – červenec 2026)
- Prezentace „WRF nad povodím Ohře“ (20. 2. 2026 a 29. 5. 2026, Chomutov)
- Online vizualizace předpovědí: https://weather-forecast.fzp.czu.cz (dříve https://krici12.github.io/WRF_Forecast/, přesun 08/2026)
