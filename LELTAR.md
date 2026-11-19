# dmsX design system: leltár

Állapot: 2026-11-19. Gazda: Apáti József (Felület, design, UX copy).

A design system jelenleg nem önálló repóban él. A forrás a `dmsreg/dmsx-modszertan` repó (privát), a bemutató és a próba claude.ai-artifactként, a tervezés forrása a Figma. Ez a repó a DS-feladatok kezelésére szolgál; a tartalom egyelőre a helyén marad, innen csak hivatkozunk rá.

## 1. Hol van mi

| Hely | Mi ez | Szerepe | Állapot |
|---|---|---|---|
| **Figma: dmsX könyvtár** (`ytRkVBTW4TfyiyAj4x9wdN`) | tokenek, 153 publikus komponens, leírások, Irányelvek, Changelog | a tervezés forrása, minden változás itt kezdődik | **nem teljes**: a döntési réteg tételei még nincsenek benne (lásd `figma-atvezetes.md`) |
| **Figma: App shell** (`9NSbL4THsQU10mA2WaOnbE`, node `45:8188`) | az alkalmazáskeret terve | a próba váza | – |
| **dmsx-modszertan › `feltaras/felulet-design-ux-copy/ds-export/`** | gépi csomag az ügynököknek | **a felülethez ez a mérvadó** (2026-11-10 óta), ütközésnél a próba | csomag v1.9, `mintak.json` 1.19 (2026-11-18), ügynökszabályok 2.2 |
| **dmsx-modszertan › `feltaras/felulet-design-ux-copy/prototipus/dmsx-alapvaz-proba.html`** | kattintható próba, a minták viselkedési referenciája | mintánként közvetlen link: `#m/<minta-id>` | élő, ~1,6 MB |
| **dmsx-modszertan › `.claude/skills/dmsx-design/`** | `dmsx-design` skill: képernyő tervezése a DS szerint, kezdőváz, ellenőrzés, gyors design-kérdések | más domaingazdáknak és ügynököknek | a `ds-export/`-ból olvas; `scripts/frissit.py csomag` készít claude.ai-ra csomagot |
| **dmsx-modszertan › `kimenet/felulet-design-ux-copy/`** | UX-felvetések DoR-dokumentumai (UX-001–UX-077, 66 fájl), képernyőtérkép domainenként (13), FE-iránymutatás | igények a fejlesztésnek | állapotuk a felvetésgyűjtő táblázat O oszlopában |
| **dmsx-modszertan › `feltaras/felulet-design-ux-copy/`** | feltárások, design review-k, felmérések, kérdéscsomagok (~20 munkaanyag) | munkaanyag, bizonyíték | részletek a mappa `README.md`-jében |
| **dmsx-modszertan › `alapvetesek/`** | felületi krédó, szövegírási alapvetések, hibaüzenetek | szövegírás és tervezés alapja | törzspéldány 2026-11-04 óta |
| **`dmsreg/dms-ToV`** (GitHub) | DMS One termékhang (ToV), 0.2.0 tervezet | felületi szövegek mérvadó forrása; skill: `dms-ux-writing` | ebből a sessionből nem érhető el |
| **dmsx fejlesztői repó** | az Angular-frontend, ahová a csomag véglegesen kerül | – | a csomag helyéről Nagy Dániel dönt; nem érhető el innen |

### A gépi csomag (`ds-export/`) tartalma

| Fájl | Tartalom |
|---|---|
| `tokens.css` / `.json` / `.md` | 234 CSS-változó; alap: Light + Modern; sötét téma, Classic, felületek, töréspontok (600/840/1200/1600), szövegstílusok, effektek. 2026-11-18 óta 0,8-es méretarány (`--skala 0.8`) |
| `komponensek.md` | 153 publikus komponens: mire való, mikor ne, variánsok, Figma-azonosító |
| `mintak.json` / `mintak.md` | **46 felületi minta** gépi szerződésként, elfogadási kritériumokkal (lista lent) |
| `valaszthato-mintak.md` | egyszerű nevű mintalista képpel a DoR „Felület” szakaszához |
| `ikonszotar.md` | ige → ikon (Material Symbols) |
| `ures-allapotok.md` | üres állapotok szövegtáblája, 74 lista |
| `ugynok-szabalyok.md` | szabályok a fejlesztői CLAUDE.md-be, agentic munkamenettel |
| `agents-md-szakasz.md` | rövid szakasz a dmsx repó `AGENTS.md`-jébe |
| `menetrend-mostani-dmsx.md`, `atallas-egy-futasban.md`, `atallas-dontesek.md` | a DS ráhúzása a mostani dmsX K4-rétegére (Négyes János botja) |
| `figma-atvezetes.md` | ami a döntési rétegben van, de a Figmában még nincs |
| `referencia/` | 139 referenciakép mintánként (világos/sötét 1440 px, világos 900 px) + `INDEX.md` |
| `forras/` | `gen_tokens.py`, `gen_mintak.py`, `ellenor.py` (felületi ellenőrző), `ref_kepek.py`, Figma-export TSV, döntési rétegek (`dontesek-2026-11-02.tsv`, `dontesek-2026-11-09.tsv`) |
| `VALTOZASNAPLO.md` | verziók és tartalmuk |

### A 46 minta

`app-shell`, `globalis-kereses`, `uj-menu`, `lista`, `lista-szuro`, `reszletoldal`, `fokusznezet`, `ablaksav`, `dontesi-nezet`, `ertesitesek`, `ai-munkatars`, `profil`, `megerosites-visszavonas`, `interakcios-allapotok`, `mozgas`, `tema`, `sugo`, `urlapmezok`, `muveleti-urlapablak`, `gombhierarchia`, `ures-allapot`, `folyamatoldal`, `kozos-reszletoldal`, `szakaszfejlec`, `attekintes`, `belepes`, `oldalallapotok`, `lathatosag`, `adminterulet`, `fajlfeltolto`, `osszeveto-nezet`, `megjegyzes-szal`, `elo-frissites`, `fa-es-favalaszto`, `nezetvalto`, `csatolmanyok-resz`, `szabalyszerkeszto`, `sablonszerkeszto`, `mezotervezo`, `mi-valasz`, `beszelgetesnezet`, `lapkep-ellenorzes`, `hivatkozasos-oldal`, `ertesito-email`, `tipp-es-vegigvezetes`, `tobbszalu-allapot`

## 2. Bemutató oldalak és artifactok (claude.ai)

| Artifact | Mi ez | Frissítve |
|---|---|---|
| [dmsX design system](https://claude.ai/artifact/8zUw5fV62Urua9RbJ8Poda) | DS bemutató oldal | 2026-11-18 |
| [dmsX (Claude Design DS)](https://claude.ai/artifact/663CdKkAfzGaotBwuXtfxJ) | brand book és élő referencia, React-csomag (`window.DmsX`), nem éles kód; privát | 2026-11-19 |
| [dmsX alapváz próba](https://claude.ai/artifact/J7Njya913tLiQjjCvRJLqY) | a kattintható próba közzétett példánya | 2026-11-18 |
| [dmsX design skill](https://claude.ai/artifact/7v1q6QhMPQQjgCqF1MaLN1) | a `dmsx-design` skill bemutatója | 2026-11-12 |
| [dmsX mozgáskatalógus](https://claude.ai/artifact/8n9AXoVVKbDCte25kev42S) | mozgás- és animációkatalógus | 2026-11-17 |
| [dmsX illusztrációk](https://claude.ai/artifact/EJ8wBDpBMKCxY5AMoNxGhm) | illusztrációk | 2026-11-17 |
| [dmsX iktatófelület](https://claude.ai/artifact/RXWqHNs6K1o6e47fhGZQkw) | iktatófelület-próba | 2026-11-18 |
| [dmsX feltöltő terület](https://claude.ai/artifact/969JdMVybAG6UbvCfo7PGG) | feltöltő terület próbája | 2026-11-16 |
| [SKY dmsX bemutató](https://claude.ai/artifact/5mKxZP8Ny5ht2awzGy2Yj6) | dmsX bemutató | 2026-11-19 |
| [SKY – Figma nélküli fejlesztési módszertan](https://claude.ai/artifact/Pk5dxDNNYYufHxrgBix5PG) | módszertan | 2026-11-19 |
| [DMS One – Alapváz (App shell) változatok](https://claude.ai/artifact/RrnFB9egXGoWpPLxhKxzN5) | App shell változatok | 2026-11-19 |
| [Felület a DoR-ban](https://claude.ai/artifact/B69ahyk4yapET2hXcJx1qY) | a DoR „Felület” szakasza | 2026-11-06 |
| [Design System (régi)](https://claude.ai/artifact/218AGh6URoJ1PTbtY1WzYT) | korábbi DS-oldal | 2026-10-30 |
| [Ulti DS – minimum leltár és építési sorrend](https://claude.ai/artifact/NmDSpwTP8fHpQmNQ1ULgiv) | korai DS-leltár | 2026-10-27 |
| [UX/UI státusz, közös pult](https://claude.ai/artifact/FEm15FzMoB3fs7FR1zYPin) | megosztott státuszpult (döntések, alkalmak); jelenleg üres, csak olvasható | – |
| [dmsX döntőpult](https://claude.ai/artifact/8aAjNLRysqabcuAb5JAqVq) | doménközi döntések kártyákon (`eszkozok/dontopult/`) | – |

## 3. Kapcsolódó források
- Felvetésgyűjtő táblázat (Google Sheet), „Felület, design, UX copy” fül, UX-előtag: a leütött felvetések helye a Jira-projektig.
- Döntési napló és nyitott kérdések: `dmsx-modszertan/docs/04-dontesi-naplo.md`, `docs/05-nyitott-kerdesek.md`.
- Közös szójegyzék: `dmsx-modszertan/docs/10-kozos-szojegyzek.md`.
