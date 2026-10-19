# DB Autodetailing — alternativní prémiový redesign webu

Moderní, responzivní návrh webových stránek pro detailingové studio **DB Autodetailing – David Baják**.

Tento projekt představuje druhou, vizuálně odlišnou variantu redesignu původního webu. Na rozdíl od první zelenošedé verze využívá tmavý automobilový styl, výraznou typografii, velkoformátové fotografie a asymetrické rozložení obsahu.

Cílem je vytvořit výraznější prezentaci studia, jeho služeb a skutečných realizací.

## Obsah webu

Web se skládá z pěti HTML podstránek:

- **Úvod (`index.html`)** – představení studia, výrazná úvodní fotografie, ukázky realizací, přehled služeb a fotogalerie.
- **Služby (`sluzby.html`)** – kompletní přehled 12 nabízených detailingových služeb.
- **Keramika a kůže (`keramika.html`)** – informace o keramických povlacích a renovaci kožených povrchů.
- **O nás (`o-nas.html`)** – představení studia a jeho přístupu k péči o vozidla.
- **Kontakt (`kontakt.html`)** – kontaktní údaje a Google Mapy.

## Design a funkce

- Tmavý automobilový design s kontrastními akcenty.
- Výrazná typografie a velkoformátové fotografie.
- Asymetrické rozložení galerie a prezentace realizací.
- Responzivní zobrazení pro počítače, tablety a mobilní telefony.
- Mobilní navigační menu.
- Fotogalerie s možností zvětšení fotografií pomocí lightboxu.
- Tematicky rozmístěné fotografie skutečných realizací.
- Interaktivní Google Mapy na kontaktní stránce.
- Telefonické a e-mailové kontaktní odkazy.

## Fotogalerie

Web využívá fotografie realizací DB Autodetailing, které jsou tematicky rozdělené podle jednotlivých služeb.

Fotografie zachycují například:

- Čištění a detailing interiéru.
- Leštění a renovaci laku.
- Ochranu povrchů vozidel.
- Renovaci kožených částí interiéru.
- Další detailingové práce a realizace.

Fotografie jsou uložené ve složce `fotografie/`.

Složka `galerie/` obsahuje původní ilustrační SVG podklady, které byly zachovány jako součást vývojových materiálů projektu.

**Autorská práva:** Fotografie byly dodány pro přípravu návrhu. Jejich veřejné použití vyžaduje odpovídající oprávnění od držitele práv.

## Google Mapy

Kontaktní stránka obsahuje vloženou mapu Google Maps, která pomáhá návštěvníkům najít provozovnu.

Návštěvníci mohou mapu přibližovat, oddalovat a otevřít si trasu v Google Mapách.

Před oficiálním předáním webu je nutné ověřit správnost adresy a umístění provozovny na mapě.

## Použité technologie

- **HTML5** – struktura jednotlivých podstránek.
- **CSS3** – design, responzivní rozložení a vizuální efekty.
- **JavaScript** – mobilní navigace a interaktivní fotogalerie.
- **Google Maps** – mapa na kontaktní stránce.
- **GitHub Pages** – hostování statického webu.

Web nevyžaduje databázi ani serverový backend.

## Struktura projektu

```text
db-autodetailing-redesign2/
├── index.html
├── sluzby.html
├── keramika.html
├── o-nas.html
├── kontakt.html
├── style.css
├── script.js
├── fotografie/
├── galerie/
├── README.md
└── LICENSE
```

## Spuštění webu

Projekt je vytvořený jako statický web. Pro lokální zobrazení stačí otevřít soubor `index.html` v internetovém prohlížeči.

### GitHub Pages

Pro zveřejnění prostřednictvím GitHub Pages:

1. Nahraj všechny HTML, CSS a JavaScript soubory do kořene repozitáře.
2. Nahraj také složky `fotografie/` a `galerie/`.
3. V nastavení repozitáře otevři **Settings → Pages**.
4. Vyber **Deploy from a branch**, větev `main` a složku `/ (root)`.
5. Po dokončení nasazení otevři zveřejněnou adresu webu.

**Ukázka druhého návrhu:**
https://simokostovcik-hash.github.io/db-autodetailing-redesign2/

## Porovnání návrhů

Pro DB Autodetailing byly připraveny dvě odlišné vizuální varianty.

**Varianta 1 – zelenošedý redesign**

Světlejší, elegantní a přehledný styl s důrazem na jednoduchou orientaci a prezentaci služeb.

https://simokostovcik-hash.github.io/db-autodetailing-redesign/

**Varianta 2 – tmavý automobilový redesign**

Výraznější vizuální styl s velkými fotografiemi, moderní typografií a důrazem na skutečné realizace.

https://simokostovcik-hash.github.io/db-autodetailing-redesign2/

Oba návrhy lze dále upravovat podle požadavků a představ majitele studia.

## Důležité upozornění

**Tento web je neoficiálním návrhem redesignu a není provozován ani oficiálně schválen společností DB Autodetailing.**

Projekt slouží k prezentaci možného vzhledu a funkčnosti nových webových stránek.

Před případným oficiálním spuštěním je nutné s majitelem ověřit kontaktní údaje, ceny, popisy služeb, adresu provozovny a oprávnění k použití fotografií.

## Autor

**Simon Kostovcik**  
Webdesign a frontend vývoj

Portfolio: https://simokostovcik-hash.github.io/portfolio/

GitHub: https://github.com/simokostovcik-hash
