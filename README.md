# DB Autodetailing — prémiový automobilový redesign webu

Moderní, responzivní návrh webových stránek pro detailingové studio **DB Autodetailing – David Baják**.

Projekt představuje druhou, vizuálně odlišnou variantu redesignu původního webu. Na rozdíl od první zelenošedé verze využívá tmavý automobilový styl, výraznou typografii, velké obrazové plochy a asymetrické rozložení obsahu.

Cílem je vytvořit výraznější prezentaci studia, jeho služeb a realizací s důrazem na profesionální vzhled a přehlednost.

Jedná se o druhou ze dvou připravených designových variant.

## Obsah webu

Web se skládá z pěti HTML podstránek:

- **Úvod (`index.html`)** – představení studia, výrazná úvodní sekce, přehled služeb, ukázky realizací a fotogalerie.
- **Služby (`sluzby.html`)** – přehled 12 detailingových služeb.
- **Keramika a kůže (`keramika.html`)** – informace o keramických povlacích a renovaci kožených povrchů.
- **O nás (`o-nas.html`)** – představení studia a jeho přístupu k péči o vozidla.
- **Kontakt (`kontakt.html`)** – kontaktní údaje, Google Mapy a možnost otevření navigace do studia.

## Design a funkce

- Tmavý automobilový design s kontrastními barevnými akcenty.
- Výrazná typografie a velké obrazové plochy.
- Asymetrické rozložení galerie a prezentace realizací.
- Responzivní design pro počítače, tablety a mobilní telefony.
- Mobilní navigační menu.
- Fotogalerie s možností zvětšení obrázků pomocí lightboxu.
- Zástupné obrázky připravené pro doplnění skutečných fotografií.
- Interaktivní Google Mapy na kontaktní stránce.
- Telefonické a e-mailové kontaktní odkazy.

## Fotogalerie

Web obsahuje připravená místa pro fotografie skutečných realizací DB Autodetailing.

Fotografie mají být tematicky rozdělené podle jednotlivých služeb, například:

- Čištění a detailing interiéru.
- Leštění a renovace laku.
- Keramická ochrana a další ochrana povrchů.
- Renovace kožených částí interiéru.
- Další detailingové práce a realizace.

### Zástupné obrázky

V aktuální veřejné verzi jsou skutečné fotografie nahrazené jednotným zástupným obrázkem s označením **„MÍSTO PRO FOTOGRAFII“**.

Zástupný obrázek je uložený ve složce `fotografie/` jako `placeholder.svg`.

Toto řešení umožňuje představit rozložení webu bez veřejného zobrazování fotografií, k jejichž použití zatím nebylo potvrzeno oprávnění.

Po získání souhlasu držitele práv lze zástupné obrázky nahradit fotografiemi skutečných realizací.

Složka `galerie/` obsahuje původní ilustrační SVG podklady, které byly zachovány jako součást vývojových materiálů projektu.

**Autorská práva:** Skutečné fotografie realizací budou doplněny až po získání odpovídajícího oprávnění od držitele práv.

## Vizuální koncepce

Druhý design je navržený jako výraznější alternativa k první zelenošedé variantě.

Hlavními prvky jsou:

- Tmavé pozadí inspirované automobilovým prostředím.
- Kontrastní typografie a výrazné nadpisy.
- Velké plochy určené pro fotografie vozidel.
- Asymetrické rozložení obsahu.
- Důraz na vizuální prezentaci detailingových služeb.

Po doplnění fotografií skutečných realizací má design více vyniknout jako prezentace práce samotného studia.

## Google Mapy

Na stránce Kontakt je vložena interaktivní mapa Google Maps, která návštěvníkům usnadňuje nalezení provozovny.

Mapa umožňuje:

- Přiblížení a oddálení.
- Prohlížení okolí provozovny.
- Otevření navigace v Google Mapách.

Před oficiálním předáním webu je nutné ověřit přesnou adresu provozovny a správnost umístění na mapě.

## Použité technologie

- **HTML5** – struktura jednotlivých podstránek.
- **CSS3** – design, responzivní rozložení a vizuální efekty.
- **JavaScript** – mobilní navigace a interaktivní fotogalerie.
- **Google Maps** – vložená mapa na kontaktní stránce.
- **GitHub Pages** – publikování statického webu.

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
│   └── placeholder.svg
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
4. Jako zdroj publikování vyber **Deploy from a branch**, větev `main` a složku `/ (root)`.
5. Po dokončení nasazení otevři zveřejněnou adresu webu.

**Ukázka projektu:**

https://simokostovcik-hash.github.io/db-autodetailing-redesign2/

## Porovnání designových variant

Pro DB Autodetailing byly připraveny dvě odlišné varianty webových stránek.

### Design 1 – zelenošedý redesign

Elegantní a přehledný design s důrazem na jednoduchou orientaci, prezentaci služeb a interaktivní rychlou navigaci.

https://simokostovcik-hash.github.io/db-autodetailing-redesign/

### Design 2 – tmavý automobilový redesign

Výraznější automobilový styl s kontrastní typografií, asymetrickým rozložením a velkými plochami určenými pro fotografie realizací.

https://simokostovcik-hash.github.io/db-autodetailing-redesign2/

Obě varianty lze dále upravovat podle požadavků a představ majitele studia.

## Důležité upozornění

**Tento web je neoficiálním návrhem redesignu a není provozován ani oficiálně schválen společností DB Autodetailing.**

Projekt slouží k prezentaci možného vzhledu a funkčnosti nových webových stránek.

Před případným oficiálním spuštěním je nutné s majitelem studia ověřit kontaktní údaje, ceny, popisy služeb, adresu provozovny a oprávnění k použití fotografií.

Případné kontaktní formuláře nejsou připojené k serverovému backendu.

## Autor

**Simon Kostovcik**  
Webdesign a frontend vývoj

Portfolio: https://simokostovcik-hash.github.io/portfolio/

GitHub: https://github.com/simokostovcik-hash
