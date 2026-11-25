# DMS One design system: backlog

Első gyűjtés: 2026-11-19, a `dmsreg/dmsx-modszertan` repó munkaanyagaiból (csak olvasva). Gazda: Apáti József. A leltár: [LELTAR.md](LELTAR.md).

**Állapotok:** Nyitott (nálam) · Folyamatban · Vár: <kire/mire> · Kész · Elvetve.

**Szerep:** a design system és a design-megvalósítások gazdája és felelőse Apáti József (designer). Ami „Nyitott”, az nála van; ami „Vár”, ott más dönt vagy szállít, és tőle csak a követés kell.

**Forrás-rövidítések** (a `dmsx-modszertan` repóban; `F/` = `feltaras/felulet-design-ux-copy/`, `DS/` = `F/ds-export/`):
DSR = `DS/README.md` · FA = `DS/figma-atvezetes.md` · VN = `DS/VALTOZASNAPLO.md` · MJ = `DS/mintak.md` · FR = `F/README.md` · DR = `F/…-design-review-2026-11-03.md` · FE = `F/…-fe-epithetoseg-2026-11-09.md` · DF = `F/…-design-felmeres-2026-11-06.md` · MV = `F/…-meeting-visszajelzesek-2026-11-10.md` · KC = `F/…-kerdescsomag-2026-11-09.md` · KND = `F/…-kerdessor-nagy-daniel-2026-11-05.md` · GI = `F/…-gombige-javaslat-2026-11-17.md` · BL = `F/…-betumeret-lapozas-2026-11-03.md` · UX = `kimenet/felulet-design-ux-copy/` · D04 = `docs/04-dontesi-naplo.md`

## Nálam: javasolt sorrend

| # | Tételek | Miért most |
|---|---|---|
| 1 | **DS-063** biztonsági jelzés | Nyílt belépési adat, sürgős |
| 2 | **DS-065**, **DS-066** kérdéscsomag és Nagy Dániel kérdéssora, frissítve és elküldve | Ezen áll a 12 integrációs tétel (DS-021–032) és több „Vár” döntés |
| 3 | **DS-012** a saját döntésemen álló UX-DoR-ok | 14 jegy gyorsan DoR-t kaphat |
| 4 | **DS-006**, **DS-007**, **DS-008**, **DS-009**, **DS-011** saját DS-döntések | Rövidek, és a csomag szabályait zárják le |
| 5 | **DS-042**, **DS-044**, **DS-045** Figma: méretarány, export, átvezetési lista | Enélkül a következő generálás felülírja a döntéseket |
| 6 | **DS-047**, **DS-049**–**DS-052**, **DS-054**–**DS-056** DS-csomag | A csomag ügynök-oldali hiányai |
| 7 | **DS-033**–**DS-041**, **DS-043**, **DS-046** Figma-átvezetés | Nagy tömeg, folyamatosan |
| 8 | **DS-060**–**DS-062**, **DS-064** próba | – |
| 9 | **DS-069**–**DS-071** dokumentáció | DS-070: a README-k verziói elavultak |
| – | Közös döntések, ahol én is benne vagyok: **DS-001**, **DS-003**, **DS-010**, **DS-017**, **DS-019**; kommunikáció: **DS-067** | A másik féllel egyeztetve |

**Másra vár (27 tétel):** a táblákban „Vár: …” állapottal. Nagy Dánielnél 10, Kovács Tamásnál 8, Horváth Bencénél 7, Polyák Ádámnál 4, Négyes Jánosnál 4, Ollári Ákosnál 3 (egy tétel több embernél is lehet); 3 tétel másik backlogtételre vár.

## Összesítő

| Kategória | Darab |
|---|---|
| Döntés | 20 |
| Integráció | 12 |
| Figma-átvezetés | 14 |
| DS-csomag | 13 |
| Próba | 33 |
| Kommunikáció | 5 |
| Dokumentáció | 4 |
| **Összesen** | **101** |

> ⚠️ **Sürgős:** DS-063: a Confluence MVP23 „Bejelentkezés” oldalán (127569636) nyílt belépési adat van. Nincs nyoma annak, hogy valaki jelezte volna.

## Döntés

| ID | Tétel | Ki dönt / felelős | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|---|
| DS-001 | Feladataim kontra DK-143 ellentmondás lezárása | Kovács Tamás + Apáti József | D04 (DK-143); MV 1; KC T2 | A DK-143 szerint a szakmenük a Feladataim szűrt nézetei; a 11-10-i döntés és a `lista` minta szerint saját menük, számláló nélkül | Nyitott |
| DS-002 | „Teendőd: …” sáv és „Teendőid” jelzés szava | Kovács Tamás | KC T1; VN (11-09) | Az SZ-89 maradéka | Vár: Kovács Tamás |
| DS-003 | Feladataim részletei: számláló a nézetfüleken, „Mit kell csinálni” widget, Piszkozatok, kitűzhető és csoportosított nézet, összevonható menük | Apáti (+Horváth Bence, Ollári Ákos, Csányi Anikó) | MV 1–2 | A 11-10-i megbeszélés nyitott pontjai | Nyitott |
| DS-004 | Belépés: kezdőoldal (D13), kétlépcsős kötelezősége, egység belépéskor, belépési napló | Kovács Tamás / Horváth Bence / Ollári Ákos | DF 3.; VN (1.5); KC B3 | Rajzolás és bérlőcímzés: DS-026 | Vár: Kovács Tamás, Horváth Bence, Ollári Ákos |
| DS-005 | Kell-e Classic megjelenés a pilotnál | Kovács Tamás | DSR; D04 (11-02) | Ma a felületen nem kínáljuk | Vár: Kovács Tamás |
| DS-006 | „Döntök” gomb a listasoron (javaslat) | Apáti | DSR; VN (1.9); MJ | Jóváhagyásra vár | Nyitott |
| DS-007 | Nézetváltó minta (VDK-108) jóváhagyása | Apáti; Kovács Tamás (T5) | MJ (`nezetvalto`); KC T5 | „Javaslat, jóváhagyásra vár” | Nyitott |
| DS-008 | `--spacing-xs` és `--spacing-sm` egyaránt 4 px a 0,8-es skálán | Apáti | VN (11-18) | Kell-e két külön lépés | Nyitott |
| DS-009 | Külön méret mobilon (600 px alatt); DS-szabály legyen-e a kompakt nézet | Apáti | VN (11-18) | A kompakt nézet ma bemutató-kapcsoló | Nyitott |
| DS-010 | Tömeges továbbadás a Feladataimból; csoportos lezárás (WF-021) | Apáti + Kovács Tamás | VN (1.3); MJ (`reszletoldal`); KC T4 | Az összevont lista óta nincs a próbában | Nyitott |
| DS-011 | Szövegmező világos kerete (WCAG 1.4.11) és a 4,5:1 alatti linkszín | Apáti | DSR; UX/UX-058.md | A keret tudatos, nyitva tartott eltérés | Nyitott |
| DS-012 | Apáti-döntésen álló UX-DoR-ok: UX-016, -017, -024-a, -031-a, -032, -035, -040, -052, -057, -058, -062, -063-a/b; -008-a és -047-a bontása | Apáti (UX-062: + Kovács Tamás) | UX/UX-*.md | Gyorsan DoR-t kaphatnak | Nyitott |
| DS-013 | Design review nyitott B-i: B6 előnézet, B12 jobb gombos menü, B14 ÉS/VAGY szűrés, B16 saját oszlop, B17 nézetek a főkeresőben, B18 P2P menü | Polyák Ádám / PO-k / Horváth Bence / Apáti | DR | – | Vár: Polyák Ádám, PO-k, Horváth Bence |
| DS-014 | Bemutató D1 (elintézés válaszirat nélkül), D3 (csatolmányverziók, CSAT-001), D5 (toast szövege) | Kovács Tamás / Ollári Ákos / ToV-gazda | DR; KC B8 | – | Vár: Kovács Tamás, Ollári Ákos |
| DS-015 | Gombige-javaslat (D02-a–d) jóváhagyása, 3 nyitott ige | Kovács Tamás, Polyák Ádám; „Határidőbe teszem”: Ollári Ákos | GI | Apáti 11-17-én döntött | Vár: Kovács Tamás, Polyák Ádám |
| DS-016 | Betű- és oldalméret (25/50/100, „idei év” szűrő, címméret, tömeges felső határ) | Kovács Tamás, Horváth Bence | BL C) | A 0,8-es skála után a px-értékeket újra kell nézni | Vár: Kovács Tamás, Horváth Bence |
| DS-017 | Alapdöntések nyitottjai: „Később” gomb, nyilatkozatmondat, termékhang-pontok, ellentmondás az ügynökszabályokkal | Ollári Ákos, Apáti | F/…-alapdontesek-2026-10-30.md | – | Nyitott |
| DS-018 | A 404-es és felesleges menüpontok listájának gazdája | Horváth Bence / Négyes János | MV 8 | Ákos kérése: 404 helyett üres állapot | Vár: Horváth Bence, Négyes János |
| DS-019 | Dashboard-felmérés döntései | DK-130: adat Kovács Tamás, megjelenés Apáti | F/…-dashboard-felmeres-2026-11-05.md | – | Nyitott |
| DS-020 | Állapotmodell-rések a felületen (PART, JOG, AI, VDK, WF), aláírási folyamat képernyői | Kovács Tamás, Horváth Bence | FE 4; KC T13, B7 | Enélkül nem ellenőrizhető gépileg | Vár: Kovács Tamás, Horváth Bence |

## Integráció

| ID | Tétel | Ki dönt / felelős | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|---|
| DS-021 | DS-csomag helye a fejlesztői repóban, generálás módja (UX-072) | Nagy Dániel | DSR; KC N1; KND 1; UX/UX-072.md | Az UX-072 fájllistája elavult | Vár: Nagy Dániel |
| DS-022 | Angular-komponenskönyvtár, a katalógus „Kód” oszlopa, self-hosted Material Symbols | Nagy Dániel, utána Apáti | DSR; KC N2; DF 1.; UX/UX-073-a…d, UX-001 | – | Vár: Nagy Dániel |
| DS-023 | `ellenor.py` és `gen_mintak.py` a CI-ben, axe (UX-053) | Nagy Dániel, Négyes János | DSR; KC N4; KND 3; UX/UX-053.md | Az axe-nak nincs gazdajegye | Vár: Nagy Dániel, Négyes János |
| DS-024 | A Platform építi-e a közös felületi csomagot (AD1 #1) | Nagy Dániel | UX/README.md; UX-001, UX-031-a/b/c | Ezen áll a „mag” jegyeinek sorrendje | Vár: Nagy Dániel |
| DS-025 | Felirat-szótár formátuma és nyelv (UX-013-a/b, UX-063, UX-008-b) | Nagy Dániel (formátum), Kovács Tamás (nyelv) | KC N3; FE 2 | – | Vár: Nagy Dániel, Kovács Tamás |
| DS-026 | Keret-DoR-ok (UX-074-a/b/c), részletoldalak URL-sémája | Horváth Bence (+Nagy Dániel) | KC B1, N9; FE 2 | – | Vár: Horváth Bence |
| DS-027 | Belépőoldal: Keycloak-téma, bérlő címzése, címtár/SSO az M1-ben | Nagy Dániel, Horváth Bence | DF 3.; KC N5, B2 | A JOG-010-nek nincs DoR-ja | Vár: Nagy Dániel, Horváth Bence |
| DS-028 | A `ds-atallas` ág fő ágra kerülése (DS ráhúzása a K4-re) | Négyes János (teszt-átírás: Nagy Dániel) | VN (11-10); DS/atallas-egy-futasban.md | Az eredmény nem látszik a repóban | Vár: Négyes János |
| DS-029 | AGENTS.md felületi szakasz jóváhagyása | Négyes János, Nagy Dániel | DS/agents-md-szakasz.md | Javaslat, 11-10 | Vár: Négyes János, Nagy Dániel |
| DS-030 | Dokumentum-megjelenítő (PDF.js / Adobe / fizetős) | Nagy Dániel | KND 4 | Csak a KND-ben szerepel | Vár: Nagy Dániel |
| DS-031 | Egyéb architektúra: mobil, bérlő-arculat, élő frissítés, e-mail beégetett értékei, Szekuricsi felületi ellenőrzése, modulkulcs | Nagy Dániel (+Kovács Tamás, Négyes János) | KC N6–N12; FE 2; docs/05 8. | – | Vár: Nagy Dániel |
| DS-032 | Lapozás: oldalszámos vagy kurzoros, pontos vagy becsült darabszám, teljes kijelölés küldése | Nagy Dániel | BL C) | – | Vár: Nagy Dániel |

## Figma-átvezetés

Az FA szerint még nyitva van a 4. pont 45 sora és az 5–8. pont. Felelős mindegyiknél: Apáti.

| ID | Tétel | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|
| DS-033 | Shell: Rail, Top bar és brand, Nav panel, logó, 81 menüpont-ikon | FA 4 | – | Nyitott |
| DS-034 | Lista: Grid row, Row header, Filter bar Modern + View tabs, Column picker, Checkboxes, 7 listaoldal, Empty state | FA 4, 7 | – | Nyitott |
| DS-035 | Részletoldal: Case page változatai, Tabs badge, Summary card, Task bar, Section rail, térkép, Print preview, Partner | FA 4 | – | Nyitott |
| DS-036 | Csatolmány: Attachment list/panel/viewer, Uploader négy változata | FA 4, 7 | A „Tallózom” felirat cserélendő (+Horváth Bence) | Nyitott |
| DS-037 | Ablakok és űrlapok: Action form dialog, Toast, Select/Autocomplete/Date picker, Segmented button, „Új” menü, Menu item | FA 4, 7 | – | Nyitott |
| DS-038 | Új komponensek: Notification panel, Command bar, Focus view + gyorsiktató, súgómenü és -panel, Profile page, Checkbox tree | FA 4, 7 | – | Nyitott |
| DS-039 | Gombhierarchia és vezető ikon; a Global search régi szövege | FA 4 | – | Nyitott |
| DS-040 | Az Irányelvek oldal szövegei | FA 5 | – | Nyitott |
| DS-041 | Az export 7 hibája (Text field fókusz/hiba, Button size, sortáv, magyar leírások, Highlight, Overlay footer, „Rendben”) | FA 6; DSR | – | Nyitott |
| DS-042 | 0,8-es méretarány a Figma-változókban, utána a generátor `--skala` nélkül fut | FA 8; VN (11-18) | Különben kétszer kicsinyít | Nyitott |
| DS-043 | Dark mód kitöltése, a sötét paletta kontrasztmérése. **2026-11-19:** a fejlesztett felület sötétben szinte fekete, mert a `tokens.css` a panelt, a mezőt és az ablakot is `surface-container-lowest`-re köti (sötétben #0c0e13), így az ablak beleolvad. A próba saját palettája (ablak #22262c) jó. Teendő: sötétben külön szerep-tokenek (háttér, kártya, ablak, mező), a próbához igazítva; a mezőkeret sötétben `outline` (a mostani 2,08:1) | FA 2; DSR; FE 3.11; `ellenorzes/sotet-tema-osszevetes-2026-11-19.png` | A tokenekben megoldva (dmsx-modszertan main, 45e2461, `dontesek-2026-11-19.tsv`): háttér #111318, keret #191c20, kártya #1d2024, ablak #282a2f, mező átlátszó Outline kerettel, fátyol 40%; képek: `ellenorzes/sotet-tema-elotte-utana-2026-11-19.png`. Hátra: Figma (FA 11.), a fejlesztett felület átállítása a szerep-tokenekre | Folyamatban |
| DS-044 | Figma TSV-export frissítése, utána a `dontesek-*.tsv` sorainak törlése | FA; DSR | Frissítés nélkül a törlés visszahozza a régi értékeket | Nyitott |
| DS-045 | A 11-16–18-i változások felvétele az FA-ba: szakaszfejléc, egységes modálok × nélkül, „Továbbiak”, környezetjelző, eredménykártya | VN (11-16…18) | Ellenőrizendő, hogy hiányoznak-e | Nyitott |
| DS-046 | Claude Design DS (brand book) szinkronja egy forrásból | DSR | A magyar Figma-leírások a mérvadók | Nyitott |

## DS-csomag

| ID | Tétel | Felelős | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|---|
| DS-047 | Egységválasztás kivétele a `belepes` mintából | Apáti | MV (Joci 4.); MJ | – | Nyitott |
| DS-048 | `lista`: „Feladat” oszlop és a Feladataim helye; `app-shell`: a sín az összesítő oldalt nyitja, nincs számláló | Apáti | MV 1 | Függ: DS-001 | Vár: DS-001 |
| DS-049 | A minták px-számainak átírása a 0,8-es skálára | Apáti | VN (11-18) | – | Nyitott |
| DS-050 | Szakaszfejléc átvezetése a sablonszerkesztőbe, a mezőtervezőbe és a próba többi részébe | Apáti | VN (11-17) | – | Nyitott |
| DS-051 | Referenciakép a „Továbbiak” panelről és a kikapcsolt menüpontról | Apáti | VN (11-16) | – | Nyitott |
| DS-052 | Hiányzó ikonok a szótárban (UX-017 négy igéje, „Eltávolítom”), a tárgyas nyitógomb szabálya | Apáti | UX-017, UX-024-a; FE 3.9 | Ettől lesz DoR a két jegy | Nyitott |
| DS-053 | Gombige átvezetése: dms-ux-writing, `ellenor.py` (GYENGEIGE, NEZETIGE), ToV-csv | Apáti | GI 7. | Függ: DS-015 | Vár: DS-015 |
| DS-054 | „Irat képe”, „aláírandó”, „kézbesítendő” jelölés megjelenése (DK-018) | Apáti | D04 (11-05) | – | Nyitott |
| DS-055 | Közös mintaadat-készlet / API-mock | Apáti | DF 11.; FE 3.10 | 50 elfogadási kritérium a próba adataira hivatkozik | Nyitott |
| DS-056 | `verzio.json`, átadási menet, a menüpont-ikonok gépi exportja | Apáti | DF 10., 12.; FE 3.12–13; UX-072 | – | Nyitott |
| DS-057 | Komponenshiány-felmérés a GitHub-specekből | Apáti | MV 8 | Polyák Ádám anyagára vár | Vár: Polyák Ádám |
| DS-058 | A ToV és a szövegkönyvtár egy példánya a csomagba | Apáti | DF 4. | Függ: DS-025 | Vár: DS-025 |
| DS-059 | Polyák Ádám P2P-állapotainak felvétele a szójegyzékbe | Polyák Ádám → Apáti | MV (Joci 5.) | Az anyag még nem jött meg | Vár: Polyák Ádám |

## Próba

| ID | Tétel | Felelős | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|---|
| DS-060 | Egységes iktatófelület: Ollári Ákos kérdései, utána bemutatás Zsoltnak | Apáti + Ollári Ákos | MV 3 | Az alapok már a próbában vannak | Nyitott |
| DS-061 | Dashboard: „Teendőim típus szerint” widget | Apáti | MV 2 | – | Nyitott |
| DS-062 | 11-10-i javaslatok: értesítés-beállítás helye, cégnyilvántartás-kereső, tömeges sztornó megerősítése és korlátja, WF + ügykezelés egy sorban | Apáti; szabály: Ollári Ákos, Horváth Bence | MV 5–7 | Állapota a próbában ellenőrizendő | Nyitott |
| DS-064 | Design-átnézés eltérései: Partner és Dosszié, oldalcím-méret, Profil, szűrő-helyőrző, helykitöltő, Postázás összesítője | Apáti | F/…-design-atnezes-2026-11-05.md | Állapota ellenőrizendő | Nyitott |
| DS-073 | Dátumválasztó fejléce nem egyforma (2026-11-23): a minta (`urlapmezok`, 11-19) kattintható „2026. november” fejlécet ír hónapválasztóval (3 × 4) és jobbra a két nyilat; a próba naptára (11-04-i kód) két oldalt nyíl, nem kattintható cím, nincs hónap- és évváltó, üres szomszédnapok, 5 sor, nincs Holnap / 1 hét múlva; a Figmában négy naptárcsalád (Modal, Input, Docked, Classic window) eltérő fejléccel; a bemutató oldal a 11-18-i szöveget mutatja (jobbra ikon). Az évváltás a mintában nincs leírva | Apáti | MJ (`urlapmezok`); próba `dsRenderDate`; `komponensek.md` Date & Time Pickers | 2026-11-23: a próbában és a mintában kész (DS 1.26, `32bb8b9`), 5 elfogadási teszt átmegy; hátra: SKY dmsX (évváltó, DS-095), Figma, bemutató oldal | Folyamatban |

### Próba-felmérés (2026-11-23): a rögzített DS-döntések, amelyek a próbából hiányoznak
A próba a referencia-megvalósítás (Apáti József, 2026-11-23). A változásnapló 11-04 és 11-19 közötti 119 UI-döntéséből 83 megvan, 18 részben, 7 hiányzik, 9-et későbbi döntés felülírt, 2 nem ellenőrizhető (gépi felmérés: kódkeresés és böngészős mérés). Itt a hiányzók és a részlegesek; mindegyik a próbába megy, a mintát nem kell módosítani. Felelős: Apáti.

| ID | Tétel (DS-döntés) | Mi van ma a próbában | Minta | Állapot |
|---|---|---|---|---|
| DS-074 | Visszalépés a listára (1.25): nincs animáció, a görgetés és a szűrők megmaradnak, a fókusz a kiinduló sorra kerül 1,5 s + 400 ms kiemeléssel, eltűnt sornál a lista címére | 2026-11-25: kész a próbában, teszttel (`mozgas` AK5); a „sor eltűnt” ág kódban ellenőrizve | `lista, mozgas` | Kész |
| DS-075 | Ablakok bezárása egységesen 160 ms (1.24) | 2026-11-25: kész (műveleti és jogosultsági ablak a fátyollal, súgópanel), teszttel; a menük 120–140 ms-a marad | `muveleti-urlapablak, fokusznezet` | Kész |
| DS-076 | Új elem kiemelése: 1,5 s áll, 400 ms alatt elhalványul (1.24) | Részben: az új megjegyzés kiemelése nem halványul el | `megjegyzes-szal, elo-frissites` | Nyitott |
| DS-077 | Második menüszint zárása 160 ms elhalványulással, a nyíl visszafordul (1.24) | Részben: a nyitás megvan, a zárás animáció nélküli | `app-shell` | Nyitott |
| DS-078 | Szakasz az ablakban: cím a blokk fölött, keret nélküli frame-blokk; szakaszhiba 1 px Error kerettel (1.21) | Hiányzik (csak a SKY dmsX-ben van): a jogosultsági ablakok szakaszai sima címke + keretes doboz | `szakaszfejlec, muveleti-urlapablak` | Nyitott |
| DS-079 | Részletpanel-változat: fejléc Featured iconnal, szakaszok frame-blokkban, címke–érték egymás alatt (1.20) | Hiányzik: a próbában nincs részletpanel | `szakaszfejlec` | Nyitott |
| DS-080 | Szakaszcím a kártya fölött, darabszám nélkül mindenhol (1.18, 1.14) | 2026-11-25: kész a próbában (minden kártyás szakasz, 4 darabszámos cím), teszttel; a „Megjegyzések (n)” és „Fájlok (n)” ellentmondás: DS-101 | `szakaszfejlec` | Kész |
| DS-081 | Rádió és jelölőnégyzet: a vezérlő a felirat első sorához igazodik (1.22) | Részben: a jogosultsági ablakokban jó, az általános `.check` középre igazít | `urlapmezok` | Nyitott |
| DS-082 | Tervezői jegyzetek a próbában: „Keret a bemutató után” hiányzik; a Mozgás jegyzet még 120–200 ms-os kilépést ír; a Továbbiak rácsban .5 px betűköz és levágott nevek | Hiányzik / részben | `app-shell, mozgas` | Nyitott |
| DS-083 | „Felhasználónév” a „Bejelentkezési név” helyett (1.5) | 2026-11-25: kész (lista és adatlap) | `belepes, adminterulet` | Kész |
| DS-084 | Helyettesítés indítható legyen a próbában: toast, jelvény az avataron, „Kilépek…” a profilmenüben (1.7) | Részben: a kód kész, de az egyetlen indító gomb hibatoastot ad („nem érhető el a próbában”) | `profil` | Nyitott |
| DS-085 | Irat Adatok fül: címke balra, érték jobbra (1.4) | Részben: az ügyiratoldal irat-oszlopában a címke az érték fölött | `reszletoldal` | Nyitott |
| DS-086 | Döntés listából döntési nézetben, ha a dokumentumot látni kell (1.9) | Részben: a Jóváhagyás/Véleményezés „Véleményt adok” gombja dokumentum nélküli ablakot nyit | `dontesi-nezet` | Nyitott |
| DS-087 | Import: hosszú betöltésnél bezárható, értesítés a végén; a bemutató szövege „teljes képernyős ablakot” ír (11-09) | Részben: 3 lépés és 4 számláló megvan, bezárás és értesítés nincs | `fajlfeltolto` | Nyitott |
| DS-088 | Címtár: Csapatok oldal „Címtárból” csoportokkal, „Címtár: <csoport>” forrás (1.8) | Részben: Kapcsolatok és a „Címtár” forrás lakattal megvan | `adminterulet` | Nyitott |
| DS-089 | Menüpont kiemelése a menü teljes szélességében (1.9) | Részben: a ⋯ menüben 5 px-es behúzással emelődik ki | `interakcios-allapotok` | Nyitott |
| DS-090 | Folyamatoldal összesítő csempéi (1.2) | Részben: a Hol tart sáv és az idővonal megvan, a csempék nincsenek | `folyamatoldal` | Nyitott |
| DS-091 | Súgó visszajelzése: „Hasznos” / „Nem segített” (1.4) | Részben: a chip felirata „Igen, hasznos” | `sugo` | Nyitott |
| DS-092 | Jogosultság-ellenőrzés: „Jogforrások” szakaszcím (11-09) | Részben: „Amit az alkalmazásgazda adott” áll helyette | `adminterulet` | Nyitott |
| DS-093 | Sötét téma szerep-tokenjei a próbában is: mezőkeret sötétben `outline` (11-19) | Részben: a próba saját palettája jó, de a mezőkeret sötétben #444a53 (kb. 2:1) | `urlapmezok, tema` | Nyitott |
| DS-094 | Kevés mezős jogosultsági ablak (Új szerepkör, Megtartás) 560 px (1.17) | Nem ellenőrizhető: az ablak mindig 512 px (640 × 0,8), a két ablak nem található | `muveleti-urlapablak` | Nyitott |
| DS-095 | SKY dmsX: naptár évváltóval (hónaprács ‹ év ›, évrács) a DS 1.26 szerint | Átvezetés SKY ☐ (a próba és a minta kész) | `urlapmezok` | Nyitott |
| DS-096 | A 11-25-i próbaváltozások a mintába: jogosultsági képernyők v2 (utoljára használt egység és váltó a fejlécben, váltás-ajánlat, háromblokkos felhasználói adatlap, iktatókönyv Ki látja listával, beágyazott szerepkör, új alegység, AD-belépési pont, a Munkakörnyezet szűrő kikerült), hozzáférési szint új nevei, „Ezt látja” sor, egység + fokozat olvasási jog | 2026-11-25: a mintában javaslatként (DS 1.28, `e2a90ce`; `[JAVASLAT …]` jelölés, az ügynök a 11-30-i döntésig nem építi); a tesztek a döntés után. A v2 vitaanyag fájlja nincs a repóban | `app-shell, adminterulet` | Kész |
| DS-097 | Beállítások a fejlécben (DS 1.27, 2026-11-25) a SKY dmsX-ben és a fejlesztett dmsX-ben | A próba és a minta kész (`e05f659`); SKY ☐, fejlesztett dmsX ☐, Figma ☐, bemutató ☐ | `app-shell, adminterulet` | Nyitott |
| DS-098 | Műveleti ablak leírósora info-ikon mögött (próba `c25ee62`, 2026-11-25) és a delegált jogkezelő kivezetése | Csak a próbában; a `muveleti-urlapablak` minta (fejléc: „alatta egy mondat leírás”, 2 elfogadási kritérium) és az `adminterulet` ellentmond neki. 2026-11-25: eldöntve, tartalom szerint (következmény és tárgysor látható, magyarázat info-ikon mögött, a címet ismétlő mondat kimarad), minden műveleti ablakra; minta, próba (42 ablak) és teszt kész (DS 1.29) | `muveleti-urlapablak, adminterulet` | Kész |
| DS-099 | Képernyőtérképek: „Látható műveletek” oszlop minden domain térképébe (`eszkoztar`, DS 1.30): oldalanként a fő művelet és legfeljebb két gyakori; ami nincs benne, a ⋯ mögé kerül | A szabály kész (minta, próba, teszt, ellenőrző); a 13 térkép oszlopa hiányzik | `kimenet/felulet-design-ux-copy/kepernyoterkep/` | Nyitott |
| DS-100 | Az „Új” gomb tartalma (`uj-menu`, `app-shell`; DS-kérés 2026-11-25): bárhonnan, előzmény nélkül indított fő munka (feladat kiadása, folyamat indítása, dokumentum feltöltése, köteg szkennelése és feltöltése, iktatás); beállítás, sablon, szabály, törzsadat nem; csak jogosult elem, a keresett, de nem jogosult tiltva okkal; legfeljebb 5–6 elem domainenként csoportosítva, a fő munka felül; egy elemnél menü nélkül nyit („Új: <mi>”); kikapcsolt domain eleme nem jelenik meg; (Ollári Ákos) az iktatás egy pont, az irány és a változat az ablakban, iktatónál mellette Csoportos iktatás | Vár: döntőpult-kártya (Kovács Tamás dönt, a domaingazdák szavaznak); a mintába és a próbába csak utána kerül, addig a mostani nyolcpontos iktatási menü marad. A döntés után módosul: az `uj-menu` anatómiája (3 csoport → domaincsoportok), a 2 elfogadási kritérium (az első „Bejövő gyorsiktató” helyett „Bejövő iktatás”, ha a 6. pontot Ollári Ákos elfogadja; az N billentyű sora a 6. ponttól függ), +1 kritérium (Kovács Anna: legfeljebb hat elem, első a Feladat kiadása), UX-074-a (a domainek regisztrálják az elemeket). A felmérés fájlja (`feltaras/felulet-design-ux-copy/felulet-design-ux-copy-uj-gomb-felmeres-2026-11-25.md`) még nincs a fő ágon | `uj-menu, app-shell` | Vár: döntőpult |
| DS-101 | Ellentmondás: darabszám a szakaszcímben. A `szakaszfejlec` tiltja („Tagok (3)” helyett „Tagok”), a `megjegyzes-szal` („Megjegyzések (26)”) és a `csatolmanyok-resz` („Fájlok (4)”) előírja, elfogadási kritériummal | Döntés kell: kivétel ez a két minta (a darabszám a tartalomról szól, nem a szakaszról), vagy a szám a fül jelvényére / a tartalomba kerül | `szakaszfejlec, megjegyzes-szal, csatolmanyok-resz` | Nyitott |

## Kommunikáció

| ID | Tétel | Felelős | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|---|
| DS-063 | **Biztonsági jelzés:** nyílt belépési adat a Confluence MVP23 „Bejelentkezés” oldalán (127569636) | Apáti → az oldal gazdája | DF 3. | Sürgős | Nyitott |
| DS-065 | Kérdéscsomag a gazdáknak (N, T, B, A, P blokkok) frissítése és küldése | Apáti → Nagy Dániel, Kovács Tamás, Horváth Bence, Ollári Ákos, Polyák Ádám | KC; FR | Előtte ki kell venni, ami azóta eldőlt | Nyitott |
| DS-066 | Kérdéssor Nagy Dánielnek (4 kérdés + Slack-változat) | Apáti jóváhagyása | KND; FR | Átfed a DS-065 N-blokkjával | Nyitott |
| DS-067 | Belépőoldal háttérrajzának megerősítése a márka gazdájával | Apáti | VN (1.5) | – | Nyitott |
| DS-068 | Megjelenjenek-e az érkeztetés és a bontás tételei a Feladataimban név szerinti kiosztásnál | Ollári Ákos | MV 1 | – | Vár: Ollári Ákos |

## Dokumentáció

| ID | Tétel | Felelős | Forrás | Megjegyzés | Állapot |
|---|---|---|---|---|---|
| DS-069 | Az egyeztetés menete (spec → design → DS) egy oldalban | Apáti | MV (Joci 6.) | – | Nyitott |
| DS-070 | A DSR és az FR státuszainak frissítése | Apáti | DSR; FR | A DSR fejléce v1.9, a `mintak.json` már 1.19; a ×-kérdés eldőlt; az FR `ds-export` sora v1.3 | Nyitott |
| DS-071 | Saját anyagok igazítása: WF-térkép K01, UX-031-b AC12 | Apáti | FE 3.1 | – | Nyitott |
| DS-072 | A bemutató oldal hatóköre: a DS a DMS One minden felületére szól, nem csak a dmsX-re. A nyitócím és a név („DMS One design system”: cím, leírás, márkajel, kereső) javítva a közzétett oldalon (2026-11-19, Apáti József döntése); a `gen_oldal.py` generátorban is át kell írni, különben a következő generálás visszahozza. A generátor nincs fent a `dmsx-modszertan` repóban | Apáti | `oldal/index.html`; `ds-export/forras/gen_oldal.py` | Utána: a `ds-export` README-k és a `dmsx-design` skill hatókör-leírása is a DMS One-ra. 2026-11-23: a „Tartalom” menüpont nem nyílt meg, mert az útválasztó a `#/tartalom` címet az „Ugrás a tartalomra” ugrólinknek (`#tartalom`) vette; a közzétett oldalon javítva (`location.hash === '#tartalom'`), a generátorban is át kell írni | Nyitott |

## UX-igények (DoR) állapota

A `kimenet/felulet-design-ux-copy/` 65 UX-fájljából:
- 14 duplikátum;
- 43 más ok miatt nem DoR: 29 Nagy Dániel döntésére vár, 14 Apátiéra, a többi Horváth Bence, Ollári Ákos vagy Kovács Tamás döntésére;
- 8 valószínűleg DoR: UX-008-a, -030, -034, -039, -047-a, -059, -075-a, -075-b.

## Valószínűleg lezárt (nem került a backlogba)
- A műveleti ablak × gombja: 11-17 óta egyikben sincs (VN).
- A design review B1–B5, B7, B11 és B19 tétele kész. A B9, B10 és B20 nem kell, de a B9 kérdése a kompakt nézettel újranyílt (DS-009). A B8 helyett az egységes iktatófelület lett az irány.
- Az FE 3.2–3.8 és a DF csomaghibái javítva vannak a `mintak.json` 1.4–1.8-ban.
- AI-szavak és a lista neve (SZ-87, -89, -90, -91, -99): 11-09-én eldőlt, csak a DS-002 maradt.
- A jogosultsági anyag és a 11-11-i bemutató lezajlott.
- `atallas-felmeres-valaszok-2026-11-09.md`: felváltotta az `atallas-dontesek.md`.
- Az UX-072–077 tervezetekből DoR-dokumentumok lettek.
- Kikapcsolt modul menüpontja (app-shell, 11-16); csatolmány törlése (CSAT-030); belépés hangneme.
