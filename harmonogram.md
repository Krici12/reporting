# Harmonogram prací 2025–2026

Harmonogram pokrývá pouze práci vykonanou pro projekt — meteorologický model **WRF** a výpočty na platformě **MetaCentrum**.

---

## 1. pololetí 2025 (leden–červen)

**Téma období:** ladění WRF na adagrifu, stáž na Cyprus Institute, přechod na MetaCentrum a první zprovoznění WRF.

### Leden–březen (ladění na adagrifu, příprava)
- **Práce na WRF** na školním serveru „adagrif“ (sebevzdělávání modelu, ladění a příprava běhů).
- **12. 3. 2025** – školení HPC Cluster (příprava na superpočítačové výpočty).
- **31. 3. 2025** – odlet na stáž.

### Duben (stáž na Cyprus Institute – zaměřená na WRF)
- Stáž na **Cyprus Institute** byla **zaměřena na práci s modelem WRF**; v kanceláři seděl s kolegou **Ioannisem Sofokleousem** ([profil](https://www.cyi.ac.cy/index.php/eewrc/about-the-center/eewrc-our-people/itemlist/user/1376-ioannis-sofokleous.html)), který je **expertem na WRF**.
- **Práce na WRF** v průběhu celé stáže (nastavení, ladění, příprava dat pro běhy).

### Květen (první kontakt s MetaCentrem)
- **8. a 9. 5.** – meetingy projektu.
- **16. a 19. 5.** – začátek **validace dat WRF ze serveru Adagrif**.
- **24. 5. 2025** – první pokus o **instalaci WRF na MetaCentrum** (problémy); pokračuje 30. a 31. 5.

### Červen (zprovoznění WRF na MetaCentru)
- **1.–2. 6.** – dokončení instalace WRF, **zkouška první simulace**.
- **4.–5. 6.** – řešení problému WRF; **9. 6.** – čištění starých dat, příprava nové instalace.
- **10.–11. 6.** – pokusy o novou instalaci (neúspěšné).
- **12.–15. 6.** – **reinstalace WRF na MetaCentru** (15. 6. přibližně úspěšná).
- **18.–20. 6.** – **testy WRF na MetaCentru**.
- **22.–24. 6.** – příprava dat, **první a druhá simulace**, opravy problémů.
- **25. 6.** – úprava job skriptu, stahování meteorologických dat.
- **26. 6.** – úprava domény pro efektivnější výpočet.
- **30. 6.** – řešení pádu všech jobů.

---

## 2. pololetí 2025 (červenec–prosinec)

**Téma období:** stabilizace a škálování WRF na MetaCentru, první reanalýzy a validace, finalizace domény.

### Červenec (škálování na více uzlů)
- **Pokusy o zlepšení workflow WRF** a opravy chyb z předchozích běhů.
- **Třetí kolo simulací (test01c)** – analýza chyby, příprava test01cc (9. 7.), úspěch (14. 7.).
- **test01d** – problémy, analýza, nakonec rozběhnut na méně uzlech (24. 7.).
- **27. 7.** – objevení sdíleného úložiště **scratch_shared**.
- **28. 7.** – test01d rozběhnut na **4 uzly / 128 CPU**.
- **29. 7.** – test01e na **8 uzlů / 256 CPU** (konzultace M. Vach, P. Máca).
- **30.–31. 7.** – problémy test01f se scratch_shared, kontaktování **podpory MetaCentra**.

### Srpen (finalizace výpočtů domény D01)
- **Komunikace s podporou MetaCentra**, rozjetí projektu na D01.
- **4. 8.** – vyřešení problému se scratch_shared, **úspěch test01f**.
- **5.–9. 8.** – příprava **restart souborů pro doménu D01**, fronta plná jobů,
  první výsledky, úprava skriptu a *time stepu*, čištění adresářů, instalace NCVIEW.
- **9. 8.** – doména **D01 téměř kompletně dokončena** pro první validace.
- **21. 8.** – konzultace s Martinem Vokounem ohledně validace D01.

### Září (stabilní build – OpenMPI, NetCDF, paralelizace, automatizace PBS)
- **17.–18. 9.** – debug starých výpočtů, příprava nového prostředí WRF.
- **19. 9.** – instalace **OpenMPI** pro paralelizaci mezi uzly a stabilitu.
- **20.–21. 9.** – test runy (test01h, x, z), oprava parcelizace, **reinstalace NetCDF**,
  oprava paralelizace, test01z/zz.
- **22. 9.** – **úspěšné runy test01zz**, prezentace projektu (RUR).
- **23. 9.** – příprava **automatizace PBS jobu**.
- **24. 9.** – úspěšný test01zz na 66 jader, **finalizace MM D01**.
- **25. 9.** – run zbytku měsíců MM D01, test01zz na 132 jader, test01z/y/g.
- **26. 9.** – test01g na 132 jader, debug testu.
- **27. 9.** – fronta výpočtů test01g, z, zx, zy.
- **29.–30. 9.** – schůzky na katedře (projekt).

### Říjen (WRF_AA a postprocessing)
- **7. 10.** – nastavení všech výpočtů **WRF_AA**.
- **20.–21., 24.–25. 10.** – **postprocessing dat WRF**, nastavení nových simulací.

### Listopad (validace, eddy covariance, R skripty)
- **3.–4. 11.** – **postprocessing dat WRF**.
- **5. 11.** – research k validaci meteo dat.
- **9. 11.** – research a postprocessing.
- **10.–11. 11.** – úprava dat **eddy covariance stanice Amálie** a dat POH (vstupy pro validaci).
- **16.–17. 11.** – **validace dat z WRF**.
- **18.–20. 11.** – příprava **R skriptu na bulk validaci**.
- **24.–25. 11.** – oprava problémů při bulk validaci WRF výstupů.
- **26.–30. 11.** – analýza validace, příprava nových výpočtů WRF.

### Prosinec (validace, EC stanice, bulk validace pro MetaCentrum)
- **1.–2. 12.** – analýza validace, příprava nových výpočtů, úprava výstupů.
- **4.–5. 12.** – úprava **bulk R skriptu na validaci**.
- **6.–8. 12.** – úprava R skriptu z teploty na srážky.
- **9.–13. 12.** – úprava dat z EC stanic Amálie, **přidání dat EC do validačních skriptů**.
- **15.–16. 12.** – příprava **validačního skriptu pro MetaCentrum (bulk validace)**.
- **17. 12.** – vizualizace validace a domény.
- **22.–23. 12.** – vyhodnocení validací.
- **27.–31. 12.** – řešení problému s daty v sadě AA, nové spuštění výpočetních skriptů.

---

## 1. pololetí 2026 (leden–červen)

**Téma období:** dokončení validací, prostorová verifikace (MERGE1h), příprava rozšíření reanalýzy (FNL, CFSv2), WRF bulk skript, **autonomní předpovědní pipeline (WRF Forecast)** a **klimatické scénáře CMIP6**; výstupy pro prezentace a Karlovarský kraj.

### Leden (reanalýzy, bulk validace, PBS a build)
- **1.–4. 1.** – oprava dat v sadě AA (missing values), nové spuštění výpočetních skriptů.
- **7., 9. 1.** – **validační skripty WRF**.
- **12.–13. 1.** – **bulk verze validačních skriptů R na MetaCentru** (finalizace, funkční skripty).
- **15. 1.** – oprava RST souborů (sada AA).
- **16. 1.** – komunikace s ČVUT (přístup „Farin“) pro běh skriptů.
- **18. 1.** – příprava **prostorové verifikace D01**.
- **19. 1.** – prostorová verifikace D01, schůzky na univerzitě.
- **20.–22. 1.** – komunikace podpory MetaCentra, **oprava nefunkčního PBS** (CPU využití).
- **23.–24. 1.** – **reinstalace buildu WRF**, test runy s podporou PBS (funkční build).
- **26.–27. 1.** – prostorové verifikace D01 (nefunkční skript), schůzky na univerzitě.
- **29.–30. 1.** – spouštění skriptu na **ČVUT Farin** (selhání a oprava), příprava skriptů pro Farin.

### Únor (prostorová verifikace, performance testy, ČHMI data, prezentace POH)
- **2. 2.** – vytvoření **performance testu „DAVID“** (CPU × čas × RAM).
- **3., 6., 11., 12. 2.** – **deep research prostorové verifikace** a alternativy dat.
- **4.–5. 2.** – pokusy o verifikaci D01, zapojení dat stanice **Amálie** (validace).
- **7. 2.** – údržba skriptů a úpravy.
- **9. 2.** – příprava RST skriptu a prostředí.
- **13. 2.** – oprava nefunkčního RST skriptu, příprava posledních restart simulací (sada AA).
- **16. 2.** – úprava vizualizace výsledků, příprava stránky **https://krici12.github.io/WRF_Domain/**.
- **17.–18. 2.** – **scrape ČHMÚ dat**, implementace pro verifikace,
  **run validace D01, D02 a D03** (vše funkční).
- **19.–20. 2.** – příprava a **prezentace POH (20. 2. 2026)**.
- **23. 2.** – komunikace s ČHMI, snaha o zisk dat Opera EUMETNET,
  zahájení stahování aktuálního **MERGE1h**.
- **24.–25. 2.** – úklid dat na MetaCentru, roztřídění skriptů, přesun dat do `real_data`.
- **26.–27. 2.** – rozšíření performance testů „DAVID“, **automatický synchronizační skript MERGE1h**.

### Březen (QGIS, ERA5 vyhodnocení, rozšíření reanalýzy FNL/CFSv2, WRF bulk)
- **2. 3.** – vizualizace výsledků reanalýzy.
- **3.–9. 3.** – nové nastavení podmínek pro verifikaci, **nastavení QGIS pro verifikaci**,
  finalizace verifikačního nastavení.
- **10. 3.** – vyhodnocení **ERA5 verifikace**.
- **11.–12. 3.** – **stahování FNL a CFS dat** na rozšíření reanalýzy.
- **16. 3.** – psaní skriptu na rozšíření reanalýzy (FNL, CFS).
- **17.–18. 3.** – implementace FNL a CFS do WRF (a oprava).
- **Poznámka:** rozšířená reanalýza **FNL / CFSv2** byla **připravena** (data stažena, skripty a implementace do WRF hotové), ale **zatím nebyla spuštěna a vypočtena modelem WRF** – spuštění je naplánováno do budoucna.
- **23. 3.** – WRF bulk skript.
- **24.–25. 3.** – WRF bulk skript, zkoumání možností komerčního prodeje meteorologických dat.
- **26. 3.** – WRF bulk skript, konzultace Jana Häuslera (využití WRF dat v jeho výzkumu).
- **30.–31. 3.** – WRF bulk skript, rozšíření o jednoduché přepínání mezi doménami a meteo daty.

### Duben (WRF bulk skript, WRF Forecast, klimatické scénáře)
- **1.–10. 4.** – **WRF bulk skript** – test runy, opravy, změna přístupu,
  **stažení kompletních meteodat pro WRF Bulk**, kompletace skriptu.
- **13.–14. 4.** – **příprava WRF Forecast**.
- **16.–17. 4.** – WRF Forecast – tvoření struktury, průzkum GFS dat.
- **20.–21. 4.** – WRF Forecast – robustní bulk přístup.
- **23.–24., 27.–28. 4.** – **klimatické scénáře**, možnosti využití ve WRF.
- **29.–30. 4.** – WRF Forecast – **reálný test** (29. 4. selhání, 30. 4. úspěch).

### Květen (spuštění WRF Forecast, CMIP6 preprocessing, WRF Scenario)
- **3. 5. 2026** – **běží WRF Forecast: GFS, domény D01 (9×9 km) a D02 (3×3 km)**; vizualizace.
- **4.–8. 5.** – WRF Forecast vizualizace a automatizace, **stahování CMIP6 dat**, preprocessing.
- **8. 5.** – redownload CMIP6 dat.
- **11. 5.** – WRF Forecast **plná automatizace**.
- **12.–13. 5.** – preprocessing CMIP6 dat.
- **15. 5.** – příprava CMIP6 pro WPS, psaní **WRF Scenario pipeline**.
- **16. 5.** – WRF Scenario pipeline.
- **17. 5.** – spuštění **WRF Scenario Testu** (na 5 let).
- **25. 5.** – oprava „WRF Scenario Test“.
- **26. 5.** – průzkum dat z WRF Scenario Testu.
- **27. 5.** – vizualizace dat pro prezentaci, údržba WRF Forecast webu.
- **28.–29. 5.** – příprava a **prezentace POH v Chomutově (29. 5. 2026)**.

### Červen (scénářové simulace, MPI-ESM1-2-HR, Karlovarský kraj)
- **1.–2. 6.** – úpravy WRF Forecastingu.
- **4. 6.** – rozšíření proměnných a vizualizací validace reanalýzy WRF (validace reanalýzy ERA5; rozšířená reanalýza FNL/CFSv2 připravena, ale zatím nespuštěna).
- **5., 8., 10., 14., 16.–17., 22.–24. 6.** – **bulk skript pro klimatické scénáře**
  (testy, opravy); řešení pádu při hromadném stahování dat.
- **9.–12., 18.–19. 6.** – stahování a **preprocessing meteo dat MPI-ESM1-2-HR pro WRF**.
- **24.–25. 6.** – fungující bulk skript, **záchrana starších dat z node**.
- **29. 6.** – **meeting Karlovarský kraj** a příprava dat do projektu.
- **30. 6.** – příprava dat a výpočetních skriptů pro MetaCentrum před dovolenou.

---

## Přehled klíčových čísel (k 07/2026)

| Míra | Hodnota |
|---|---|
| Odeslané výpočetní úlohy na MetaCentru | ≈ 1 420 |
| Strojový čas | ≈ 946 000 CPU-hodin (≈ 107 let + 329 dní) |
| Napočítaná data | ≈ 67 TB (48 TB scénáře · 14 TB předpovědi · 4,9 TB reanalýzy) |
| Rozlišení domén | scénáře 9 km · předpověď 3 km (možnost 1 km) · reanalýza 1 km |

**Meziroční nárůst aktivity:** 2025 → 202 úloh (39 let 280 dní strojového času); 2026 (k 22. 7.) → ≈ 1 220 úloh (68 let 48 dní).

**Online výstupy:**
- https://krici12.github.io/WRF_Domain/
- https://weather-forecast.fzp.czu.cz – **nová adresa**; vizualizace předpovědí byla v srpnu 2026 přesunuta z původního repozitáře **WRF_Forecast_Viewer** (https://krici12.github.io/WRF_Forecast/), který už nefunguje.
