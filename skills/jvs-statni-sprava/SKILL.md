---
name: "jvs-statni-sprava"
description: "Jednotný vizuální styl (JVS) české státní správy pro ministerstva, ústřední správní úřady a jejich organizace. Použij vždy, když má vzniknout prezentace, dokument, tisková zpráva, dopis, grafika pro sociální sítě, tiskovina, e-mailový podpis, logo nebo jiný materiál pro kterýkoli úřad státní správy v JVS, i když uživatel řekne jen \"šablona JVS\", \"logo úřadu\", \"lev\", \"Czechia Sans\", \"BrandCloud\", \"úřad s členem vlády v čele\" nebo \"úřad bez člena vlády v čele\". Platí pro všechny ÚOSS od 30. 4. 2026."
---

# JVS státní správy: dokumenty, prezentace, grafiky pro kterýkoli úřad

Rámec: grafický manuál JVS na BrandCloudu státní správy (https://statni-sprava.brandcloud.pro, veřejný přístup přes sdílený odkaz https://statni-sprava.brandcloud.pro/link/EZBgcxNY, úplný obsah po přihlášení) a oficiální šablony z něj. Odkazy ve tvaru `BC …` níže vedou na stránky manuálu. Autor stylu Studio Najbrt, koordinátor JVS Karel Drašnar, MMR (karel.drasnar@mmr.gov.cz). Pro weby platí Design systém gov.cz (designsystem.gov.cz), manuál řeší jen logo v záhlaví.

Závaznost (BC Úvod / Pravidla pro implementaci JVS schválená vládou; usnesení vlády č. 551 ze 16. 7. 2025 a č. 963 ze 3. 12. 2025):
- Všechny ústřední orgány státní správy zavádějí JVS v plném rozsahu. Podřízené organizace dobrovolně, povinně na pokyn zřizovatele. JVS nezahrnuje kraje, obce, IZS, ozbrojené složky ani kulturní instituce.
- Od 30. 4. 2026 vznikají všechny nové materiály a prezentace podle JVS. Souběžné užívání starého a nového loga je zakázáno; vyrobené zásoby lze dospotřebovat, dotisky se starým logem ne. Soutěže na nová loga úřadů jsou zakázány.
- Státní znak má přednost: tam, kde je státní znak a název úřadu textem, logo nepřidávej. Produktová a projektová loga jsou možná; kombinované značení (logo JVS vedle starého loga úřadu) ne.

Pořadí autorit: 1. oficiální šablona nebo zdrojový soubor z BrandCloudu, 2. manuál na BrandCloudu, 3. tento skill. Co podklady neřeší, nedomýšlej: napiš „Nemám dost informací“ a zeptej se. Čísla, citace a legislativu ber jen z podkladů.

## 1. Postup

1. Zjisti úřad a jeho úroveň (část 2); od ní se odvíjí logo, šablona i odkazy.
2. Urči výstup a formát podle tabulky.
3. Zajisti podklady (část 3): logo úřadu, písmo, šablonu. Nic nepřekresluj.
4. Obsah jen z dodaných podkladů; chybějící údaj nech viditelně jako `[DOPLNIT: co]`.
5. Postav výstup podle části 5, 6 nebo 7 a dodrž část 8.
6. Zkontroluj podle části 9 (vždy přes vyrenderovaný náhled) a předej podle části 10.

| Výstup | Formát | Základ |
|---|---|---|
| Prezentace | .pptx | šablona PowerPoint JVS Sts26 (část 5) |
| Tisková zpráva | .docx | hlavičkový papír Tisková zpráva (6.1) |
| Dopis, interní sdělení, rozhodnutí, dopis ministra, premiéra, náměstka či ředitele | .docx | příslušný hlavičkový papír (6.1) |
| Textový podklad: briefing, argumentář, Q&A | .docx | základní hlavičkový papír bez identifikačního bloku (6.1) |
| Přehledový podklad na 1–2 strany, factsheet | PDF | HTML sazba s Czechia Sans (6.3) |
| Příspěvek na sítě, tiskovina, infografika, drobný formát | PNG pro obrazovku, PDF pro tisk | HTML sazba (část 7) a odkaz na Canva šablonu |
| Web, HTML blok do CMS | mimo tento skill | Design systém gov.cz |

Výstupy vznikají v oficiálních šablonách, proto prezentace .pptx a dokument .docx; Claude Docs ani artefakt Slides nepoužívej, pokud o ně uživatel výslovně nepožádá.

## 2. Dvě úrovně log

JVS definuje dvě úrovně (BC Pravidla užívání / Systém tvorby loga). Rozdíl je závazný a prochází všemi šablonami:

| | Úřad s členem vlády v čele | Úřad bez člena vlády v čele |
|---|---|---|
| Symbol | červený štít s bílým lvem a modrým svislým pruhem vpravo | červený štít s bílým lvem, bez pruhu |
| Poměry symbolu (výška loga = 1) | štít 0,45, pruh 0,05, celkem 0,5 široký | štít 0,45 široký |
| Název úřadu v barevném pozitivu | tmavě šedá #545860 | modrá #00469B |
| Začátek názvu od levé hrany loga | 0,61 × výška loga | 0,565 × výška loga |
| Kdo | Úřad vlády ČR a ministerstva | ČSÚ, ČÚZK, ČBÚ, ÚPV, ÚOHS, SSHR, SÚJB, NBÚ, ERÚ, ČTÚ, ÚOOÚ, RRTV, ÚDHPSH, NÚKIB, NSA, DIA a připojené organizace (Finanční správa, CRR, FAÚ, ÚZSVM, SÚKL, TA ČR, SFPI, KHS, ÚCL, SPS a další) |
| Šablony, Canva, favicon, avatar, vizitky | varianta „s členem“ (`urady-s-clenem…`) | varianta „bez člena“ (`urady-bez-clena…`) |

Názvy (BC Úvod / Názvy ministerstev a úřadů): česky přesně podle kompetenčního zákona č. 2/1969 Sb., bez dodatků „ČR“ nebo „České republiky“, pokud je zákon neuvádí. Anglicky buď se slovem Czech na začátku (Czech Statistical Office, Czech Mining Authority, Czech Telecommunication Office), nebo s dovětkem „of the Czech Republic“ na konci (Ministry of the Interior of the Czech Republic, National Cyber and Information Security Agency of the Czech Republic); přesná znění jsou v tabulce manuálu, u anglických log se dovětek neopakuje. „Česká republika“ se nikdy nepřekládá jako Czechia a „Česko“ nikdy jako Czech Republic; státní loga existují v obou podobách (Česká republika / Česko, Czech Republic / Czechia, BC Loga / Státní logo). Cizojazyčné verze loga vznikají jen ze šablon manuálu (BC Pravidla užívání / Cizojazyčné & nelatinkové verze loga); pro řečtinu, cyrilici, čínštinu, arabštinu a hebrejštinu je písmo Noto Sans a u sazby zprava doleva se kompozice zrcadlí, lev nikdy.

## 3. Podklady

Kde co na BrandCloudu je (sekce → dokument):
- Loga: `Loga / Úřady s členem vlády v čele / <úřad> / České provedení, Anglické provedení` a stejně `Úřady bez člena vlády v čele`; samostatný symbol obou úrovní (`Loga / … / Samostatný symbol`), státní logo, logo „Spolufinancováno státním rozpočtem ČR“, logolinky EU (u MMR). Každé logo má 6 provedení a soubory `logo_<zkratka>_<provedení>_rgb.svg|.png`, `_cmyk.pdf` nebo `.eps`, `_pantone.eps`, u jednobarevných `_tisk.pdf|.eps`. SVG je oříznuté na logo (výška 62,363 jednotek), PNG (průhledné, cca 2400 × 1770 px) má kolem loga ochrannou zónu o šířce x, proto ho před vložením do šablon ořízni (část 5). Šablony pro kontrolu loga (PNG s průhledným pozadím) jsou v BC Pravidla užívání / Systém tvorby loga.
- Styl: Základní barvy, Státní barvy, Piktogramy (Illustrator), Vzory (Illustrator), 3D lev (PSD), Písmo (Základní, Systémové, Nelatinková), Zdrojové soubory / Czechia Sans™ (`czechia-sans.zip`).
- Šablony: Prezentace PowerPoint (4 soubory `powerpoint_urady-se-clenem|bez-clena[_EN]_sablona-Sts26.potx`), Hlavičkové papíry (`JVS_hlavickovy-papir_urady-s-clenem-vlady|bez-clena-vlady_zakladni.dotx`, `_TLP.dotx`, `_tiskova-zprava.dotx`, `_interni-sdeleni.dotx`, `_dopis-namestku-a-reditelu`, dále `JVS_hlavickovy-papir_ministr.dotx`, `_premier.dotx`, `5_JVS_hlavickovy-papir_rozhodnuti.dotx`), Obálka publikace (Word), Mailový podpis (`sts_podpis-do-mailu.docx`), Digitální podpis (PDF podklady).
- Tiskoviny: Obálky (InDesign), Záštita & osvědčení (InDesign, Canva, Word `Záštita VZOR.docx`), Pozvánky (Canva, InDesign), Prezentační tiskoviny, Roll-up (Canva, InDesign), Vizitky (Canva, InDesign).
- Multimedia: Pozadí pro videohovory, Avatar, Příspěvky (sítě), LinkedIn Cover, Pozadí pro sociální sítě, Animace (Canva, Premiere MOGRT), Webové stránky (Záhlaví, Favicon, Webová barevná paleta, Ikony pro identitu občana), Ikony mobilních aplikací.
- Aplikace: Stánky a veletrhy, Razítko, Navigační systém, Reklamní předměty, Vstupní karty.
- Aktuálně probíhá: FAQ, RGB hodnoty barev pro tisk, Jednořádková varianta loga (stánky), Oprava číslovaných nadpisů (nástroj pro Word), Formulář, Podlicenční ujednání, Překlad názvů organizačních jednotek a pozic do AJ (xlsx).

Co potřebuješ od uživatele, když nemáš přístup: SVG loga ve správném provedení, `czechia-sans.zip` a šablonu. Písmo Czechia Sans™ je licencované: úřad ho získá žádostí přes formulář na BC Styl / Základní písmo, nesmí ho šířit dál a po skončení užití ho maže. Nepřikládej soubory písma k výstupům a nedávej je třetím stranám; v PDF vložené písmo je v pořádku. Písmo „Czechia Sans Logo“ z animací slouží jen pro animaci loga.

Čtení BrandCloudu v prohlížeči (když je sdílený odkaz otevřený, sezení platí pro celou doménu): `/api/v2/folder/shared?rootId=<id>` vrací podsložky, `/api/v2/document/shared?rootId=<id>` všechny dokumenty podstromu, `/api/v2/document/shared/<docId>` obsah dokumentu jako strom `children` (typy page, header, text s HTML, color, table, files/image/preview s uzly `file`, v nich `file.download_url.original`). Stahuj `fetch(url, {credentials: "same-origin"})` (s `include` selže na přesměrování do úložiště) a binární soubory přenášej jako base64 po částech do 250 000 znaků.

Kde pracovat: stavbu dělej tam, kde je LibreOffice, Chromium s Playwright a python-pptx/python-docx; přenes jen potřebné soubory. Bez Czechia Sans finální grafiku nedělej, nanejvýš náhled s Arialem s příponou `_NAHLED-nahradni-pismo`.

## 4. Pravidla z manuálu

### Logo (BC Pravidla užívání)
- Logo = lev, štít a písmo, nedělitelný celek; kompozice, tvar a barevnost se nemění, text se k symbolu neumisťuje jinak, než stanoví manuál. Vždy oficiální soubor; nová loga jen z definice manuálu s OpenType Stylistic Set 1 (Logo alternates).
- Provedení: barevné pozitivní je výchozí (světlé pozadí); barevné negativní na velmi tmavé pozadí; černobílé pozitivní a negativní, když to vyžaduje technologie nebo záměr; černé a bílé pro jednobarevné aplikace. V černobílém provedení je lev vždy v opačné barvě než zbytek loga; na jednobarevné kontrastní ploše může zůstat v barvě podkladu.
- Logo s názvem úřadu smí být jen na tmavě modré (nebo jiné velmi tmavé) ploše, na bílé ploše nebo na vhodné fotografii. Na ostatních barevných plochách používej samostatný symbol v barvě, která vůči červené (a modrému pruhu) dostatečně kontrastuje. Symbol smí nahradit logo jen tam, kde souvislost s JVS vyplývá z kontextu. Samostatný lev (bez štítu) jen ve speciálních aplikacích (dárkové předměty, raster, velké plochy), vždy jednobarevný bílý nebo šedý, případně v materiálu.
- Zakázáno: lev mimo štít, změna písma, řezu, prokladu, prostrkání či zalomení názvu, pozitiv na tmavém a negativ na světlém podkladu, rušivá fotografie, efekty (záře, stíny), podkládání loga obdélníkem, podkladová barva kolidující s logem.
- Ochranná zóna: jednotka x = šířka červeného pruhu v symbolu (0,45 × výška loga); nesmí do ní zasahovat text, jiné logo ani grafika. V digitálních šablonách (sítě) může být logo dotažené k levé hraně formátu.
- Minimální výška loga i symbolu 10 mm nebo 55 px; výchozí (100 %) 22 mm na A4. Doporučené výšky (BC Rozměrová řada loga): hlavičkový papír A4 22 mm, vizitka 85 × 55 mm 16 mm, záhlaví webu 64 px (mobil 56 px), podpis e-mailu 68 px, obálky C4 30 mm, C5 a DL 22 mm, C6 20 mm, pozvánka A5 22 mm, A6 20 mm, blok A4 a A5 22 mm, inzerce A4 30 mm, leták DL 30 mm, plakát B1 10 cm, roll-up 85 × 200 cm 20 cm, billboard 6 × 3 m 78 cm, banner 1080 × 1080 px a post 1080 × 1440 px 240 px. Formát mimo tabulku odvoď od nejbližšího a velikost uveď v odpovědi.
- Zarovnání textu (BC Zarovnání textu s logem): k levé hraně symbolu (úzké a svislé formáty); k názvu úřadu v logu, charakteristický prvek JVS (hodnoty v části 2); k pravé hraně symbolu, když je použit jen symbol; u vodorovných formátů lze text posunout k pravému okraji.
- Více log (BC Používání více log zároveň): loga státní správy obou úrovní vedle sebe mají stejnou výšku, mezery aspoň x; platí i svisle. Externí loga opticky vyrovnat, nejvýš 80 % výšky loga státní správy, mezery aspoň x. S logem EU: nejvýš výška loga EU, mezera aspoň 40 % šířky vlajky; povinnou publicitu fondů EU určuje manuál JVS fondů EU a generátor publicita.dotaceEU.cz. Při čtyřech úřadech jeden symbol a názvy vypsané v řádcích; pět s prioritizací: jeden úřad s vlastním logem před seznamem; pět a více: názvy ve dvou sloupcích s mezerou x; při kombinaci úrovní se názvy řadí k symbolu své úrovně; v angličtině se „of the Czech Republic“ uvádí jen jednou na konci seznamu.
- Logo v materiálu: lev, štít a případný pruh se oddělují úrovní materiálu nebo barvou; u barevného provedení lze přidat jemnou konturu.

### Barvy (BC Styl / Základní barvy)
Primárně národní barvy (bílá, červená, modrá) s odstíny; další barvy pro témata. CMYK je ručně laděný pro tisk, ber ho z tabulky a nepřepočítávej. Barevnost šablon lze měnit v rámci palety; nesmí utrpět čitelnost loga ani textu.

| Barva | HEX | CMYK | Pantone | RAL |
|---|---|---|---|---|
| Tmavě červená | #680526 | 0 100 48 56 | 209 C | 3004 |
| Červená | #D70C0F | 0 100 100 0 | 2035 C | 3020 |
| Světle červená | #F8C2B9 | 0 30 20 0 | 2337 C | 3015 |
| Tmavě modrá | #0C1838 | 100 87 0 58 | 2766 C | 5022 |
| Modrá | #00469B | 100 70 0 0 | 2145 C | 5005 |
| Světle modrá | #9EC8E9 | 40 10 0 0 | 2141 C | 5024 |
| Tmavě zelená | #00321D | 92 26 74 62 | 7729 C | |
| Zelená | #006538 | 78 7 80 43 | 7733 C | |
| Světle zelená | #B7E5B7 | 33 0 40 0 | 2254 C | |
| Tmavě tyrkysová | #002A2D | 96 26 35 76 | 2217 C | |
| Tyrkysová | #00998F | 80 8 47 0 | 6138 C | |
| Světle tyrkysová | #A1E5E0 | 42 0 18 0 | 6134 C | |
| Tmavě fialová | #271940 | 84 90 21 59 | 2765 C | |
| Fialová | #462E73 | 80 87 8 19 | 3566 C | |
| Světle fialová | #B1A3CB | 29 32 0 0 | 2099 C | |
| Hnědá | #471E0A | 28 89 60 77 | 2449 C | |
| Oranžová | #FFAA00 | 0 37 100 0 | 130 C | |
| Světle oranžová | #FFCF8C | 0 20 56 0 | 2005 C | |
| Žlutá | #FFDB4C | 0 5 80 0 | 106 C | |
| Světle žlutá | #F7E599 | 0 6 47 0 | 2001 C | |
| Tmavě šedá | #545860 | 0 0 0 80 | Cool Gray 11 C | 7043 |
| Středně šedá | #888B95 | 0 0 0 60 | Cool Gray 8 C | 7037 |
| Šedá | #A7A9B4 | 0 0 0 45 | Cool Gray 6 C | 7040 |
| Světle šedá | #D9DAE4 | 0 0 0 20 | Cool Gray 1 C | |
| Bílá | #FFFFFF | 0 0 0 0 | | 9003 |
| Imitace zlaté | #CBAC28 | 19 23 70 19 | 871 C | |

Fólie a nitě jsou v téže tabulce na BrandCloudu. Státní barvy (BC Styl / Státní barvy) pro státní symboly: bílá, červená #D70C0F, modrá #00469B, zlatá #FFDB00 (Pantone 871 C), stříbrná #AAAAAA (877 C).

RGB hodnoty barev pro tisk (BC Aktuálně probíhá, 20. 10. 2026) jsou RGB ekvivalenty tiskového CMYK; použij je, když tisková data musí být v RGB (PDF z prohlížeče, Office), na obrazovce zůstávají hodnoty z tabulky: tmavě červená #800026, červená #E7000E, světle červená #F9C2B9, tmavě modrá #0F194E, modrá #004E9E, světle modrá #9EC8EA, tmavě zelená #00432C, zelená #006C39, světle zelená #B3D8AA, tmavě tyrkysová #003038, tyrkysová #00A094, světle tyrkysová #98D3D2, tmavě fialová #27173F, fialová #462F73, světle fialová #BAADD2, hnědá #440E0B, oranžová #F8A800, světle oranžová #FDCF7D, žlutá #FFE73B, světle žlutá #FFEB9A, tmavě šedá #555756, středně šedá #878988, šedá #A7A9A9, světle šedá #D8DADA.

Web (BC Multimedia / Webová barevná paleta, aktualizace 28. 8. 2026): Design systém gov.cz rozšiřuje červenou a modrou o škály `color/primary/50–1050` a `color/error/50–1000` (primary/600 = #00469B, primary/900 = #0C1838, error/600 = #D70C0F, error/900 = #680526); hodnoty ber z BrandCloudu nebo z design systému.

Barva písma a pozadí (BC Pravidla užívání / Barva písma a pozadí): základní kombinace v jednom odstínu: tmavý tón písma na světlém tónu, bílá na středním tónu, světlý tón na tmavém; bílá jde na většinu tmavých a středních tónů. Běžný text aspoň 4,5 : 1 (WCAG AA), velký text aspoň 3 : 1; kombinace pod 3 : 1 jsou zakázané (bílá na oranžové nebo na světle modré, tyrkysová na světle tyrkysové). Office šablony mají barvy motivu mírně zaokrouhlené, v PPT a Wordu používej barvy motivu.

### Písmo (BC Styl / Písmo)
- Czechia Sans™: Regular, Italic, Medium, Bold; CE sada. Pro grafiky, tiskoviny, sítě, PDF podklady, vstupní karty a nápisy na předmětech.
- Stylistický set 01 (CSS `font-feature-settings: "ss01"`) jen v logu a u názvu úřadu sázeného odděleně od symbolu (propisky, lanyardy). V běžné sazbě a nadpisech vypnutý.
- Kancelářské aplikace a e-mail: Arial (případně Aptos nebo Helvetica), řezy Regular, Italic, Bold, Bold Italic. Šablony JVS mají Arial ve stylech.
- Řecká abeceda, cyrilice, čínština, arabština a další: Noto Sans (Google Fonts).

### Sazba (BC Pravidla užívání / Pravidla sazby)
- Proklad: běžný text cca 120 % velikosti písma, nadpisy 105–110 %.
- Prostrkání: výchozí 0; jen u velmi malých textů 6–7 b lze +10, 5 b a menší až +25. Kerning Metrics, nikdy Optical.
- Typografická pravidla: spojovník (-) bez mezer; pomlčka (–) s mezerami ve větě, bez mezer u rozsahů jednoslovných výrazů (15–20, 11.00–11.30, úterý–čtvrtek), s mezerami u víceslovných; uvozovky „“ a vnitřní ‚‘; datum 15. 10. 2026 s mezerami, rozsah pomlčkou; čas 10.30 (tečka, lze dvojtečka), doby trvání dvojtečkami; procento a jednotka s mezerou (75 %, 10 km), bez mezery ve významu přídavného jména (75% sleva); × a další matematické znaky s mezerami, počet opakování bez mezery (3×); 20 °C s mezerou, úhlový stupeň bez; jednopísmenné předložky a spojky a, i, k, o, s, u, v, z nekončí řádek (nezlomitelná mezera, v HTML `&nbsp;`).
- Tisíce oddělené mezerou (247 517), desetinná čárka. Formát času a data jednotně v celém výstupu.

### Fotografie (BC Pravidla užívání / Úprava fotografie)
Fotka nesmí narušit čitelnost loga ani textu. Když text leží na fotce, ztmav ji přechodem v tmavě modré (manuál ukazuje dva přes formát natažené gradienty #0C1838); barevnost podložení i přechodů jen z palety. Fotku bez ověřené licence nepoužívej; když ji uživatel nedodá, nech viditelný placeholder a řekni to.

### Vzory, piktogramy, doplňky (BC Styl)
- Vzory (fotostěny, průkazy): cihlový vzor, posun řad 0,5, žádné logo oříznuté. Z log s názvem: vodorovná mezera 75 % šířky a svislá 75 % výšky loga (pro logo 43,84 × 22 mm je to 32,88 a 16,5 mm). Ze symbolů: 600 % šířky a 50 % výšky symbolu (pro 11 × 22 mm: 66 a 11 mm). Ze lvů: 300 % šířky a 40 % výšky lva (pro 7,824 × 10 mm: 23,472 a 4 mm). Zdroj: `sts_urady-s-clenem|bez-clena-vlady-v-cele_vzory.ai`.
- Piktogramy JVS (BC Styl / Piktogramy): liniové, tvořené jen tahem, síla linky upravitelná; soubor `Piktogramy JVS_v15.ai` a jednotlivé PDF (dům, auto, dokument, schody, výtah, WC apod.) pro orientační systémy a tiskoviny. Vlastní piktogram ve stejném charakteru.
- 3D lev (PSD, CMYK i RGB, tmavě modrá) je volný doplňkový prvek pro roll-upy, prezentace a podobné výstupy.

## 5. Prezentace

Šablona `powerpoint_urady-se-clenem_sablona-Sts26.potx` nebo `…bez-clena…` (plus `_EN`), BC Šablony / Prezentace PowerPoint. 16 : 9 (33,867 × 19,05 cm), 40 ukázkových snímků, dvě předlohy se stejnými názvy rozvržení:
- **JVS PPT Dark** (první předloha): pozadí #0C1838, text bílý, akcenty světle modrá a světle červená. Ukázky na snímcích 1–12, 21 a 38–40.
- **JVS PPS Light**: bílé pozadí, nadpisy modrá #00469B, text tmavě šedá, zvýraznění červené. Ukázky 13–20 a 22–37.
Barvy motivu: accent1 #00469B, accent2 #D70C0F, accent3 #F8C2B9, accent4 #680526, accent5 #9EC8E9, accent6 #545860; tmavá předloha dk1 bílá, lt1 #0C1838, dk2 #A7A9B3, lt2 #545860; světlá dk1 #545860, lt1 bílá, dk2 #0C1838, lt2 #A7A9B3. Písmo motivu Arial.

Variantu, kterou uživatel nezadá, zvol podle účelu: světlá pro tisk, PDF a zasedačky, tmavá pro pódium a velké projekce; volbu zdůvodni jednou větou.

Co dává předloha: symbol úřadu vpravo nahoře dotažený k hornímu okraji (obrázek 1,29 × 2,82 cm na x 30,65 cm), zápatí s názvem úřadu (zástupný symbol zápatí, výchozí text „Úřad … vlády v čele (upravte přes Vložení / Záhlaví a zápatí)“), datum a číslo snímku. Na titulním a závěrečném snímku je logo s názvem vložené jako obrázek „Obrázek 10“ (x 1,9 cm, y 1,78 cm, výška 4,37 cm) se zástupným logem úrovně: nahraď ho logem úřadu ve správném provedení (negativní na tmavé, pozitivní na světlé) se stejným umístěním a výškou.

Rozvržení (stejná v obou předlohách; idx zástupných symbolů podle české šablony bez člena, u ostatních souborů ověř výpisem): „Úvodní snímek“, „Úvodní snímek s delším textem“, „Úvodní snímek s fotkou“ (idx 0 nadpis a barevný druhý řádek, 1 jméno a funkce, 10 datum, u fotky 10 obrázek a 11 datum); „Osnova 1 sloupec“, „Osnova 2 sloupce“ (obsah prezentace, idx 2 a 17); „Nadpis a obsah - velké písmo“, „Nadpis a obsah - malé písmo“ (idx 2 tmavá, 15 světlá); „Předělový snímek s nadpisem“ (světle modrá plocha, nadpis „01<tab>Název kapitoly“); „Dva sloupce“ (20, 21); „Tři sloupce“ (17, 18, 19), „Tři sloupce s pozadím“ (modré boxy, 17, 23, 24), „Tři sloupce s pozadím a šipky“ (postup); „Čtyři sloupce s obrázky“ a „… a popisy“ (obrázky 13, 19, 17, 15, texty 29–32); „Text a graf“ (text 21, graf 13); „Text a tabulka“ (text 22, tabulka 21); „Text a obrázek“ (text 21, obrázek 10); „Pouze nadpis“; „Prázdný snímek“; „Porovnání“ (nadpisy sloupců a obsah); „Závěr a shrnutí“; „Závěr a poděkování“ (idx 0 „Děkuji za pozornost“, 1 jméno a e-mail). Většina rozvržení má pod nadpisem zástupný symbol podnadpisu (idx 14, 16 nebo 20 na y 3,46 cm); nevyužitý smaž. Nadpis začíná na 1,72 cm, obsah na 6,33 cm. Sloupce a obrázky přiřazuj podle polohy (`ph.left`).

Zásady pro snímky: co nejméně textu, jedna myšlenka na snímek; odrážky ze šablony (čtverečky); text v barevných blocích vycentruj; čísla zpracuj jednotně (všechna v boxech, všechna bez pozadí, nebo tabulka); chybějící čísla jako viditelný placeholder na snímku; zdroje do poznámek pod snímkem; grafy nativní (upravitelné), barvy motivu, Arial.

Barvy podle ukázkových snímků: sloupcový graf řady accent1, accent2, accent3; spojnicový accent5, accent2, accent3 (čáry 4 pt); výsečový body accent3, accent2, accent4, accent5, accent1; legenda nahoře, u výseče vpravo. Tabulky Arial 15 pt, linky 1 pt: šedá (záhlaví tx1 s bílým textem, linky tx1), modrá (záhlaví accent1, linky accent1), bílá (bez výplně, linky bg2).

Postup v python-pptx:

```python
import copy, zipfile
from pptx import Presentation
from pptx.chart.data import CategoryChartData
from pptx.enum.chart import XL_CHART_TYPE
from pptx.enum.dml import MSO_THEME_COLOR as T
from pptx.enum.shapes import PP_PLACEHOLDER, MSO_SHAPE_TYPE
from pptx.enum.text import PP_ALIGN, MSO_ANCHOR
from pptx.util import Pt, Cm
from pptx.oxml.ns import qn
from lxml import etree

def potx_do_pptx(potx, pptx):  # python-pptx .potx neotevře; stačí změnit typ obsahu
    with zipfile.ZipFile(potx) as zin, zipfile.ZipFile(pptx, "w", zipfile.ZIP_DEFLATED) as zout:
        for it in zin.infolist():
            data = zin.read(it.filename)
            if it.filename == "[Content_Types].xml":
                data = data.replace(b"presentationml.template.main+xml", b"presentationml.presentation.main+xml")
            zout.writestr(it, data)

prs = Presentation("sablona.pptx")

def predloha(nazev):  # "JVS PPS Light" nebo "JVS PPT Dark"
    rel = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/theme"
    return next(m for m in prs.slide_masters if nazev.encode() in m.part.part_related_by(rel).blob)

def rozvrzeni(predl, nazev):
    return next(l for l in predl.slide_layouts if l.name == nazev)

def ph(snimek, idx):
    return next(p for p in snimek.placeholders if p.placeholder_format.idx == idx)

def ponechat(cisla):  # čísla ukázkových snímků (1–40), které zůstanou; ostatní pryč
    lst = prs.slides._sldIdLst
    for i, s in reversed(list(enumerate(list(lst), 1))):
        if i not in cisla:
            prs.part.drop_rel(s.rId); lst.remove(s)

def presunout(z, na):  # indexy od 0
    lst = prs.slides._sldIdLst; s = list(lst)[z]; lst.remove(s); lst.insert(na, s)

def cislo_a_zapati(snimek, urad):  # add_slide zápatí ani číslo nepřenese, zkopíruj je z rozvržení
    for p in snimek.slide_layout.placeholders:
        if p.placeholder_format.type in (PP_PLACEHOLDER.SLIDE_NUMBER, PP_PLACEHOLDER.FOOTER):
            snimek.shapes._spTree.append(copy.deepcopy(p._element))
    for p in snimek.placeholders:
        if p.placeholder_format.type == PP_PLACEHOLDER.FOOTER:
            p.text_frame.paragraphs[0].runs[0].text = urad

def logo_orez(png_in, png_out):  # oficiální PNG z BrandCloudu má kolem loga průhlednou ochrannou zónu; šablony počítají s logem bez ní
    from PIL import Image
    im = Image.open(png_in).convert("RGBA"); im.crop(im.getchannel("A").getbbox()).save(png_out)

def vymenit_logo(snimek, png):  # titulní a závěrečný snímek: zástupné logo úrovně za oříznuté logo úřadu; snímek z rozvržení logo nemá, přidá se na stejné místo
    for sh in list(snimek.shapes):
        if sh.shape_type == MSO_SHAPE_TYPE.PICTURE and not sh.is_placeholder:
            sh._element.getparent().remove(sh._element)
    snimek.shapes.add_picture(png, Cm(1.9), Cm(1.78), height=Cm(4.37))

def smazat_prazdne(snimek):
    for p in list(snimek.placeholders):
        if p.has_text_frame and not p.text_frame.text.strip() and p.placeholder_format.type not in (PP_PLACEHOLDER.SLIDE_NUMBER, PP_PLACEHOLDER.FOOTER):
            p._element.getparent().remove(p._element)

def tabulka_jvs(tab, varianta="modra", pt=15):  # jako ukázky: modra, seda, bila
    for el in tab._tbl.tblPr.findall(qn("a:tableStyleId")):
        tab._tbl.tblPr.remove(el)
    zahlavi = {"modra": T.ACCENT_1, "seda": T.TEXT_1, "bila": None}[varianta]
    linka = {"modra": "accent1", "seda": "tx1", "bila": "bg2"}[varianta]
    for r, radek in enumerate(tab.rows):
        for bunka in radek.cells:
            if r == 0 and zahlavi is not None:
                bunka.fill.solid(); bunka.fill.fore_color.theme_color = zahlavi
            else:
                bunka.fill.background()
            bunka.vertical_anchor = MSO_ANCHOR.MIDDLE
            tcPr = bunka._tc.get_or_add_tcPr()
            for tag in ("a:lnL", "a:lnR", "a:lnT", "a:lnB"):
                for old in tcPr.findall(qn(tag)): tcPr.remove(old)
                ln = etree.SubElement(tcPr, qn(tag), w="12700")
                etree.SubElement(etree.SubElement(ln, qn("a:solidFill")), qn("a:schemeClr"), val=linka)
            for fill in tcPr.findall(qn("a:solidFill")) + tcPr.findall(qn("a:noFill")):
                tcPr.remove(fill); tcPr.append(fill)
            for p in bunka.text_frame.paragraphs:
                p.alignment = PP_ALIGN.CENTER
                for run in p.runs:
                    run.font.name = "Arial"; run.font.size = Pt(pt); run.font.bold = False
                    run.font.color.theme_color = T.BACKGROUND_1 if (r == 0 and zahlavi is not None) else T.TEXT_1

SLOUPCE = (T.ACCENT_1, T.ACCENT_2, T.ACCENT_3)
CARY = (T.ACCENT_5, T.ACCENT_2, T.ACCENT_3)
KOLAC = (T.ACCENT_3, T.ACCENT_2, T.ACCENT_4, T.ACCENT_5, T.ACCENT_1)

def graf_jvs(graf, barvy, tmave=False, pt=12, cisla="#,##0"):
    graf.font.name = "Arial"; graf.font.size = Pt(pt)
    if tmave:
        graf.font.color.theme_color = T.BACKGROUND_1
    typ, plot = graf.chart_type, graf.plots[0]
    if typ in (XL_CHART_TYPE.PIE, XL_CHART_TYPE.DOUGHNUT):
        for bod, b in zip(plot.series[0].points, barvy):
            bod.format.fill.solid(); bod.format.fill.fore_color.theme_color = b
        return
    graf.value_axis.tick_labels.number_format = cisla
    graf.value_axis.tick_labels.number_format_is_linked = False
    for rada, b in zip(plot.series, barvy):
        if typ in (XL_CHART_TYPE.LINE, XL_CHART_TYPE.LINE_MARKERS):
            rada.format.line.color.theme_color = b; rada.format.line.width = Pt(4)
        else:
            rada.format.fill.solid(); rada.format.fill.fore_color.theme_color = b
```

Titulní snímek: ponech ukázkový snímek 1 (tmavá) nebo přidej „Úvodní snímek“ ze světlé předlohy a vlož logo přes `vymenit_logo` (negativní PNG na tmavou, pozitivní na světlou; oficiální `logo_<zkratka>_…_rgb.png`); nadpis a barevný druhý řádek jsou dva běhy jednoho zástupného symbolu oddělené zalomením, měň text běhů, formát nech; pole Datum (idx 10) vyplň nebo smaž, jinak zůstane návod ze šablony. Další snímky: `s = prs.slides.add_slide(rozvrzeni(predloha("JVS PPS Light"), "Nadpis a obsah - malé písmo"))`, `cislo_a_zapati(s, "Název úřadu")`, `ph(s, 0).text = …`, poznámky `s.notes_slide.notes_text_frame.text = "Zdroj: …"`, graf `ph(s, 13).insert_chart(XL_CHART_TYPE.COLUMN_CLUSTERED, data).chart` a `graf_jvs(…)`, tabulka `ph(s, 21).insert_table(r, c).table` a `tabulka_jvs(…)`, fotka `ph(s, 10).insert_picture(cesta)`, nakonec `smazat_prazdne(s)`. Závěr z rozvržení „Závěr a poděkování“ s logem přes `vymenit_logo` (rozvržení logo neobsahuje, je jen na ukázkovém snímku 40); pořadí přes `presunout`.

Pozor: nové textové pole, graf a tabulka dostanou písmo motivu Calibri, nastav Arial (funkce výše to dělají). Formát čísel kódem `#,##0` nebo `#,##0.0`, PowerPoint ho zobrazí podle místního nastavení. Náhled: LibreOffice → PDF → PNG, prohlédni každý snímek. Validace skriptem skillu pptx: `scripts/office/validate.py deck.pptx --original <šablona>`.

## 6. Dokumenty

### 6.1 Word (.docx)

| Dokument | Šablona (BC Šablony / Hlavičkové papíry) |
|---|---|
| Dopis, obecný dokument | `JVS_hlavickovy-papir_<úroveň>_zakladni.dotx` (záhlaví Sekce, Odbor, Oddělení; identifikační blok JID, Č. j., Sp. zn., Vyřizuje, Datum, místo, Adresát, ID DS; v těle ukázka všech stylů); `_TLP.dotx` s označením TLP v záhlaví a zápatí |
| Tisková zpráva | `…_tiskova-zprava.dotx` (záhlaví „Tisková zpráva“, zápatí s kontaktem pro média) |
| Interní sdělení | `…_interni-sdeleni.dotx` (blok Č. j., Vyřizuje, Linka, Datum, Jméno a Příjmení / Funkce; „Věc (nepovinné):“ stylem Nadpis 6) |
| Dopis předsedy, náměstka, ředitele | `…_dopis-namestku-a-reditelu` (styly „Ministr - jméno“ 14 pt tučně a „Ministr - funkce“ 12 pt, blok „V Praze, / Číslo jednací:“; první strana s jiným záhlavím a zápatím) |
| Dopis ministra, vedoucího ÚSÚ | `JVS_hlavickovy-papir_ministr.dotx` (jméno a funkce v hlavě dopisu) |
| Dopis premiéra | `JVS_hlavickovy-papir_premier.dotx` (velký státní znak) |
| Rozhodnutí | `5_JVS_hlavickovy-papir_rozhodnuti.dotx` (malý státní znak, „ROZHODNUTÍ“ stylem Rozhodnutí, blok Č. j., Sp. zn., Vyřizuje, Kontakt, Datum, Adresát, ID DS) |
| Obálka publikace | BC Šablony / Obálka publikace (.docx s fotkou nebo bez, pozitiv a negativ) |

Textový podklad (briefing, argumentář, Q&A) stav na základní šabloně: smaž ukázkové tělo včetně identifikačního bloku, záhlaví vyplň podle odesílatele (nepoužité řádky smaž), na začátek název stylem Název nebo Nadpis 1 a datum.

Co šablony nastavují (neměň): A4, okraje 40 / 24 / 27 / 26 mm (nahoře, vpravo, dole, vlevo), Arial, text do bloku, nadpisy tučně #545860 (Název 28 pt, Nadpis 1 20 pt, Nadpis 2 16 pt, Nadpis 3 14 pt, Nadpis 4 12 pt, Nadpis 5 11 pt), logo v záhlaví 22 mm, zápatí 8 pt #888B95 (název úřadu a číslo strany, adresa, IČ, T, ID DS, web). Styly: Perex (tučně #545860), Odrážka 1–6 (čtverečky), Seznam číslovaný 1–6, Nadpis 1–6 číslovaný, Citát (celý odstavec kurzívou), Popisek fotografie (8 pt); tabulky „Tabulka JVS 1 - šedá“ (výchozí), „Tabulka JVS 2 - modrá“, „Tabulka JVS 3 - bílá“, „Tabulka JVS 4 - bez ohraničení“, „Tabulka JVS 5 - na úvodní údaje“. Přímé formátování nepřidávej, s výjimkou kurzívy v citaci.

Známá chyba (BC Aktuálně probíhá / Oprava číslovaných nadpisů): ve starších distribuovaných šablonách mají styly „Nadpis 1–9 číslovaný“ úroveň osnovy „Základní text“, takže nejsou v navigaci ani v obsahu. Šablony z BrandCloudu ze srpna 2026 ji mají správně; u jiných ji doplň funkcí `opravit_osnovu` níže (nebo uživatel použije nástroj OpravaCislovanychNadpisu pro macOS a Windows z téže stránky).

```python
import zipfile
from docx import Document
from docx.oxml.ns import qn
from docx.oxml import OxmlElement

def sablona_do_docx(dotx, docx):  # python-docx neotevře .dotx; stačí změnit typ obsahu
    with zipfile.ZipFile(dotx) as zin, zipfile.ZipFile(docx, "w", zipfile.ZIP_DEFLATED) as zout:
        for it in zin.infolist():
            data = zin.read(it.filename)
            if it.filename == "[Content_Types].xml":
                data = data.replace(b"wordprocessingml.template.main+xml", b"wordprocessingml.document.main+xml")
            zout.writestr(it, data)

def opravit_osnovu(doc):  # Nadpis N číslovaný → úroveň osnovy N-1
    for st in doc.styles:
        if st.name.startswith("Nadpis ") and st.name.endswith(" číslovaný"):
            pPr = st.element.get_or_add_pPr()
            if pPr.find(qn("w:outlineLvl")) is None:
                ol = OxmlElement("w:outlineLvl"); ol.set(qn("w:val"), str(int(st.name.split()[1]) - 1)); pPr.append(ol)

def vycistit_telo(doc, od=None):  # bez od smaže celé tělo; s od maže od prvku, jehož text tak začíná
    mazat = od is None
    for el in list(doc.element.body):
        if el.tag.endswith("}sectPr"):
            continue
        if not mazat and "".join(t.text or "" for t in el.iter(qn("w:t"))).strip().startswith(od):
            mazat = True
        if mazat:
            doc.element.body.remove(el)

def nahradit(el, mapa):  # záhlaví, zápatí i tělo; klíč i rozdělený do více běhů, tabulátory a pole zůstanou; nezlomitelné mezery v klíči netřeba; vyprázdněný odstavec smaže
    for p in list(el.iter(qn("w:p"))):
        ts = list(p.iter(qn("w:t")))
        if not ts:
            continue
        pred = "".join(t.text or "" for t in ts)
        pole = p.find(".//" + qn("w:fldChar")) is not None or p.find(".//" + qn("w:fldSimple")) is not None
        for stare, nove in mapa.items():
            klic, start = stare.replace("\xa0", " "), 0
            while True:
                texty = [t.text or "" for t in ts]
                i = "".join(texty).replace("\xa0", " ").find(klic, start)
                if i < 0:
                    break
                j, pos, vlozeno = i + len(klic), 0, False
                for t, txt in zip(ts, texty):
                    a, b = pos, pos + len(txt); pos = b
                    if b <= i or a >= j:
                        continue
                    zac, kon = max(i - a, 0), min(j - a, len(txt))
                    t.text = txt[:zac] + ("" if vlozeno else nove) + txt[kon:]
                    t.set(qn("xml:space"), "preserve"); vlozeno = True
                start = i + len(nove)
        if pred.strip() and not "".join(t.text or "" for t in ts).strip() and not pole and p.getparent().tag != qn("w:tc"):
            p.getparent().remove(p)

def bunka_text(bunka, text):  # přepíše text buňky a zachová formát prvního běhu
    p = bunka.paragraphs[0]
    if p.runs:
        p.runs[0].text = text
        for r in p.runs[1:]: r.text = ""
    else:
        p.add_run(text)

def vymenit_logo_docx(doc, svg, png):  # logo úřadu do záhlaví: nahradí SVG i PNG náhled zástupného loga, výška 22 mm zůstane, šířka podle poměru stran; png bez ochranné zóny (viz logo_orez v části 5)
    from PIL import Image
    w, h = Image.open(png).size
    for sec in doc.sections:
        casti = [sec.header.part] + ([sec.first_page_header.part] if sec.different_first_page_header_footer else [])
        for part in casti:
            obrazky = [r.target_part for r in part.rels.values() if r.reltype.endswith("/image")]
            if not any(o.partname.ext == "svg" for o in obrazky):
                continue  # záhlaví bez loga JVS (státní znak u rozhodnutí a premiéra)
            for o in obrazky:
                o._blob = open(svg if o.partname.ext == "svg" else png, "rb").read()
            for ext in list(part.element.iter(qn("wp:extent"))) + list(part.element.iter(qn("a:ext"))):
                if ext.get("cy"):
                    ext.set("cx", str(round(int(ext.get("cy")) * w / h)))
```

Použití: `sablona_do_docx(…)`, `doc = Document(…)`, `opravit_osnovu(doc)`, `vymenit_logo_docx(doc, "logo_<zkratka>_barevne-pozitivni_rgb.svg", "logo_orez.png")` (PNG oříznuté funkcí `logo_orez` z části 5; šablony mají v záhlaví jen zástupné logo úrovně „Úřady … vlády v čele“), potom `vycistit_telo(doc)` pro TZ a textové podklady, u dopisu `vycistit_telo(doc, od="Poskytnuté osobní údaje")` (identifikační blok zůstane), u interního sdělení `od="Věc"`. Identifikační blok je první tabulka těla (`doc.tables[0]`): hodnotu zapiš do buňky vpravo od popisku přes `bunka_text`; Adresát je sloučená buňka s odstavci pod popiskem. Odstavce: `doc.add_paragraph(text, style="Perex")`; vestavěné styly mají v python-docx anglická jména („Heading 1“, „Title“, „Quote“), vlastní česká („Perex“, „Odrážka 1“, „Seznam číslovaný 1“, „Nadpis 1 číslovaný“, „Popisek fotografie“). Záhlaví a zápatí: pro každou `sec` v `doc.sections` volej `nahradit(sec.header._element, mapa_zahlavi)` a `nahradit(sec.footer._element, mapa_zapati)`, mapy zvlášť (klíč „Odbor“ by jinak zasáhl „Odbor – oddělení“); první stránku řeš jen při `sec.different_first_page_header_footer` (ministr, premiér, náměstci). Placeholdery v šablonách: „Úřady s členem vlády v čele“ nebo „Úřady bez člena vlády v čele“ (název úřadu v zápatí), „Sekce“, „Odbor“, „Oddělení“, „Odbor – oddělení“, „Adresa, 110 00 Praha 1“, „IČ: 00000000“, „T: +420 000 000 000“ (mezery nezlomitelné, `nahradit` je při hledání klíče ignoruje), „ID DS: XXX“, „media@urad.gov.cz“, „urad.gov.cz“, „XXX“, „XX. XX. 2026“. Údaje úřadu (IČ, ID DS, adresa) ber jen od uživatele, nikdy odhadem.

### 6.2 Tisková zpráva
Základ: šablona Tisková zpráva příslušné úrovně, nebo poslední TZ úřadu v této šabloně, když ji uživatel dodá (zápatí má vyplněný kontakt). Struktura: titulek stylem Nadpis 1; datum ve tvaru 25. 9. 2026; perex stylem Perex (2–3 věty); mezititulky stylem nadpisu ze šablony; odrážky Odrážka 1, kroky Seznam číslovaný 1. Citaci sázej do běžného odstavce: kurzívou jen běh s textem citace v uvozovkách „…“, uvozovací věta („uvádí Jméno Příjmení, funkce“) normálním řezem. Zápatí: název úřadu, odbor, kontakt pro média (jméno, T, E), web. Příklady TZ z praxe jsou v BC Aktuálně probíhá / Tiskové zprávy – příklady z praxe.

### 6.3 PDF podklady
Factsheet nebo přehled čísel na 1–2 strany A4 na výšku: HTML sazba podle 7.1, výstup PDF. Logo barevné pozitivní vlevo nahoře, výška 22 mm, kolem volná ochranná zóna. Text zarovnaný s názvem v logu nebo s levou hranou symbolu; Czechia Sans; nadpisy Bold v #0C1838 nebo #00469B, text #0C1838 nebo #545860. Číselné dlaždice všechny stejně. V patičce zdroj dat, stav k datu a kontakt.

## 7. Grafiky

### 7.1 Sazba a render
Grafiku sázej jako HTML v přesném rozměru (px pro obrazovku, mm pro tisk) s oficiálním SVG logem vloženým přímo do stránky a renderuj v Chromiu. Písmo převeď z OTF na TTF, jinak Chromium vloží do PDF písmo jako Type 3, se kterým mají tiskárny potíže.

```python
# otf2ttf.py: python3 otf2ttf.py fonts/*.otf  (vedle vzniknou .ttf, OpenType funkce včetně ss01 zůstanou)
import sys
from fontTools.ttLib import TTFont, newTable
from fontTools.pens.cu2quPen import Cu2QuPen
from fontTools.pens.ttGlyphPen import TTGlyphPen
for src in sys.argv[1:]:
    f = TTFont(src); gs = f.getGlyphSet(); glyfy = {}
    for jm in f.getGlyphOrder():
        pen = TTGlyphPen(gs); gs[jm].draw(Cu2QuPen(pen, 1.0, reverse_direction=True)); glyfy[jm] = pen.glyph()
    f["loca"] = newTable("loca"); f["glyf"] = g = newTable("glyf"); g.glyphOrder = f.getGlyphOrder(); g.glyphs = glyfy
    del f["CFF "]
    f["maxp"] = m = newTable("maxp"); m.tableVersion = 0x00010000
    for k in ("maxZones", "maxTwilightPoints", "maxStorage", "maxFunctionDefs", "maxInstructionDefs",
              "maxStackElements", "maxSizeOfInstructions", "maxComponentElements"):
        setattr(m, k, 0)
    m.maxZones = 1
    f["head"].glyphDataFormat = 0; f.sfntVersion = "\x00\x01\x00\x00"
    f["post"].formatType = 2.0; f["post"].extraNames = []; f["post"].mapping = {}
    f.save(src.rsplit(".", 1)[0] + ".ttf")
```

```python
import re
def logo_svg(cesta):  # SVG loga z BrandCloudu jsou v kódování iso-8859-1
    s = open(cesta, encoding="iso-8859-1").read()
    return re.sub(r"<\?xml[^>]*>|<!--.*?-->", "", s, flags=re.S)  # vložit do <div class="logo">; CSS .logo svg{height:240px;width:auto;display:block}
```

Oficiální SVG mají výšku 62,363 jednotek; symbol bez pruhu má `viewBox="0 0 28.063 62.363"`, s pruhem `0 0 31.181 62.362`; potřebuješ-li jen symbol, použij oficiální soubor Samostatný symbol.

```css
@font-face{font-family:"Czechia Sans";src:url(fonts/CzechiaSans-Regular.ttf);font-weight:400}
@font-face{font-family:"Czechia Sans";src:url(fonts/CzechiaSans-Italic.ttf);font-weight:400;font-style:italic}
@font-face{font-family:"Czechia Sans";src:url(fonts/CzechiaSans-Medium.ttf);font-weight:500}
@font-face{font-family:"Czechia Sans";src:url(fonts/CzechiaSans-Bold.ttf);font-weight:700}
html,body{margin:0}
.p{position:relative;overflow:hidden;font-family:"Czechia Sans",sans-serif}  /* rozměr na .p, u tisku i @page{size:148mm 210mm;margin:0} */
```

```python
# render.py: PNG  python3 render.py in.html out.png 1080 1440 | PDF  python3 render.py in.html out.pdf 148mm 210mm
import asyncio, sys, os
from playwright.async_api import async_playwright
async def main(src, out, w, h):
    async with async_playwright() as p:
        b = await p.chromium.launch(); px = not w.endswith("mm")
        pg = await b.new_page(**({"viewport": {"width": int(w), "height": int(h)}} if px else {}))
        await pg.goto("file://" + os.path.abspath(src))
        await pg.evaluate("document.fonts.ready.then(() => true)")
        print("písma:", await pg.evaluate("[...document.fonts].filter(f => f.status == 'loaded').map(f => f.family + ' ' + f.weight)"))
        if px:
            await pg.screenshot(path=out, clip={"x": 0, "y": 0, "width": int(w), "height": int(h)})
        else:
            await pg.pdf(path=out, width=w, height=h, print_background=True, prefer_css_page_size=True)
        await b.close()
asyncio.run(main(*sys.argv[1:5]))
```

Výpis „písma“ musí obsahovat Czechia Sans ve všech použitých řezech, jinak grafiku nepředávej. U PDF ověř `pdffonts` (CID TrueType, embedded). Pro tisk použij RGB hodnoty pro tisk z části 4. Zdrojové HTML předávej s písmem v base64.

### 7.2 Sociální sítě (BC Multimedia / Sociální sítě)
Šablony v Canvě a InDesignu pro post 1080 × 1440 a stories 1080 × 1920 zvlášť pro obě úrovně; rozvržení v manuálu: text s fotografií a CTA, textové bloky s fotografií, dělená plocha, textové sdělení, grafy. Geometrie změřená v resortní kopii šablony (řiď se Canva šablonou, když se liší): logo s názvem od levého okraje formátu, shora 80 px (stories 250), výška 240 px; text zarovnaný s názvem v logu; jen symbol vlevo nahoře navazuje na horní okraj, text od jeho pravé hrany; okraje 80 px, text končí na x 1000; spodní pruh červený #D70C0F výšky 156 px s textem Medium 72; hlavní sdělení Bold nebo Medium 90–185, doplňkový text Medium 50–95, proklad 110 %. Čtverec 1080 × 1080 šablonu nemá: okraje 80, logo 240.
Kombinace ze šablon: fotka ztmavená na #0C1838 s negativním logem a bílým textem; plocha #0C1838 s bílým textem, doplňky #9EC8E9 a akcent #F8C2B9; barevná plocha z palety (fialová, zelená, tyrkysová) jen se symbolem; plocha #D70C0F bez loga (červené pole by splynulo); bílá s nadpisem #0C1838, zvýraznění #D70C0F, graf v odstínech červené, jen symbol; velké číslo na dvou plochách (modrá a tmavě modrá, nebo červená a tmavě červená); citace Medium 90 s předsazenými uvozovkami.
Avatar: jednotný soubor `sts_socialni-site_avatar_<úroveň>.png` (800 × 800, kruhový výřez), nijak neupravovat. LinkedIn cover osobního profilu, pozadí pro Facebook, YouTube, X a LinkedIn: hotové soubory a Canva zdroje v BC Multimedia / Sociální sítě.

### 7.3 Tiskoviny (BC Tiskoviny)
- Pozvánky A5 (148 × 210 mm), A6 (105 × 148), DL (105 × 210): vlevo nahoře logo v definované velikosti; uprostřed (při fotce dole) nadpis a doprovodný text na levý prapor podle principů zarovnání; v podvalu místo, RSVP a web menším písmem zarovnané s logem nebo s textem v logu. Formát, barvy z palety, fotku i velikost písma lze upravit s ohledem na čitelnost a hierarchii. Canva šablony pro obě úrovně a InDesign zdroje na BC Tiskoviny / Pozvánky.
- Obálky: logo a adresa (Czechia Sans Regular, u ministra jméno Bold) odsazená od konce textu loga o x. C4 (324 × 229): logo 30 mm, 18 mm zleva, 15 mm shora, adresa 9/10,8 b; C5 (229 × 162): 22 mm, 15, 12, 6,5/7,5 b; DL (220 × 110): 22 mm, 11, 8, 6,5/7,5 b; C6 (162 × 114): 20 mm, 10, 8, 6/7 b. Zdroje InDesign pro obě úrovně.
- Vizitky 85 × 55 mm (dvoujazyčné, speciální pro ministry a státní tajemníky se zadní stranou v tmavě modré se symbolem, nelatinkové zrcadlené): logo 16 mm vlevo nahoře, u úřadu s členem 3,0 mm a bez člena 3,8 mm od levého okraje, aby název v logu seděl stejně; QR kód vpravo nahoře jen ze čtvercových modulů bez log a zaoblení, jen základní kontakt (při více datech až do výšky loga); osobní údaje v levém sloupci, adresa úřadu vpravo dole; web bez „www.“; „T:“ pevná linka, „M:“ mobil; pořadí údajů závazné; papír 300–400 g matná křída. Claude připraví texty, sazba v Canva nebo InDesign šabloně.
- Záštity, osvědčení, doklady zvláštní odborné způsobilosti: šablony InDesign pro obě úrovně, Canva a Word (`Záštita VZOR.docx`); tisk na papír vyšší gramáže.
- Prezentační tiskoviny, billboard, plakát: všechny prvky v bezpečné viditelné ploše, ochranná zóna loga a okrajové rezervy, text čitelný z pozorovací vzdálenosti (billboard 10–30 m), stručnost a hierarchie. Roll-up 85 × 200 cm: logo 20 cm v horní viditelné části, hierarchie titulek, doplňující text, detail; Canva zdroj a InDesign v BC Tiskoviny / Roll-up. Černobílé provedení jen z oficiálních jednobarevných variant, nikdy převodem do šedi.
- Tisk: PDF z Chromia je RGB s vloženým písmem, vhodné pro kancelářský a digitální tisk. Pro ofset a velkoformát přidej spadávku (obvykle 3 mm, ověř u tiskárny) a uveď, že tiskárna potřebuje CMYK hodnoty z manuálu; případně sazbu převezme grafik v InDesign šabloně.
- QR kód: `pip install segno`, `segno.make(url, error="m").save("qr.svg", dark="#0C1838", light=None, border=4)`; na vizitce `dark="#545860"`. Po vyrenderování ověř, že kód vede na správnou adresu.

### 7.4 Infografiky a grafy
Jedno sdělení na graf, titulek říká závěr. Klíčovou hodnotu zvýrazni červenou #D70C0F nebo tmavě červenou, ostatní světle modrou #9EC8E9 nebo šedou #A7A9B4; pořadí barev řad může kopírovat šablonu PPT. Tenká mřížka #D9DAE4, popisky os #545860, bez 3D, stínů a přechodů. Čísla česky. V grafice Czechia Sans, v Office Arial. Jednoduchý graf kresli jako SVG v HTML; složitější v matplotlib s registrovaným písmem (`matplotlib.font_manager.fontManager.addfont(cesta_ttf)`, `rcParams["font.family"] = "Czechia Sans"`). Zdroj dat pod grafem (v PPT v poznámkách).

### 7.5 Drobné formáty a digitál
- E-mailový podpis (BC Šablony / Mailový podpis): Arial, jméno tučně #545860, pozice a odbor #888B95, název úřadu tučně #545860, adresa, „T: +420 …“, „M: +420 …“, e-mail a web bez „www.“ #888B95 (pořadí jako na vizitce); logo výšky 68 px pod údaji v ochranné vzdálenosti; banner 68 px vpravo od loga, nebo vodorovný pod logem. Šablona `sts_podpis-do-mailu.docx`.
- Digitální podpis (BC Šablony / Digitální podpis): podpisové pole v poměru cca 4 : 1, grafický podklad PDF (samotný lev pro dokumenty, které už logo mají, nebo symbol příslušné úrovně), v Acrobatu písmo Arial, odebrat logo Adobe.
- Pozadí pro videohovory: 1920 × 1080 px, logo výšky 200 px odsazené 100 px zleva i shora; 10 hotových fotopozadí se symbolem pro každou úroveň, Canva a InDesign šablona pro variantu s názvem úřadu.
- Záhlaví webu (BC Multimedia / Webové stránky): logo 64 px na výšku s 16 px nad i pod (u vyššího záhlaví 80 px), mobil 56 px s 16 px nad a 12 px pod; v tmavém režimu negativní varianta (`@media (prefers-color-scheme: dark)`); název odboru vedle názvu úřadu oddělený linkou 0,5 px (při logu 64 px) odsazenou o polovinu šířky červeného pruhu, název odboru od linky o stejnou mezeru jako symbol od názvu úřadu. Favicon jen dodaný soubor (ico, svg, 96, 180, 192, 512 px) pro příslušnou úroveň, nezaměňovat s avatarem ani ikonou aplikace. Ikony mobilních aplikací: bílý lev na barevném poli z palety, 1024 px. Ikona pro identitu občana 64 × 64 px. Čtvercová loga do záhlaví produktových webů: BC Aktuálně probíhá.
- Animace loga: Canva šablony 16 : 9 a 9 : 16 pro obě úrovně a MOGRT pro Premiere Pro (BC Multimedia / Animace).
- Stánky a veletrhy: logo Czech Pavilion pro zahraniční veletrhy (nekombinovat se státní vlajkou), státní logo v horní části stánku, loga na logolištách jednobarevná (ideálně bílá), programy v Czechia Sans zarovnané vlevo s časy 10.30 a rozsahy pomlčkou; jednořádková varianta loga jen pro stánky (InDesign zdroj v BC Aktuálně probíhá).
- Razítko 47 × 18 nebo 58 × 22 mm: symbol na celou výšku, adresa nejvýš v pěti řádcích, kroužek s číslem jen když je vyžadován (InDesign šablony).
- Reklamní předměty (BC Aplikace): nápisy úřadu Czechia Sans Medium se ss01 (propisky 11/12,5 b, tužky a lanyardy 13/14,5 b, prostrkání −10), zalomení jako v logu; tašky bílá nebo tmavě modrá s logem 60 mm vpředu a symbolem 125 mm vzadu; tužky bílá, tmavě modrá, červená; odznaky barevné nebo stříbrné; bloky A4 a A5; samolepky 45 × 90, 30 × 60 a kruh 55 mm; textil s tkanou etiketou. Vstupní karty jen ze šablon, údaje v Czechia Sans (Arial jen když to systém neumí), text na průkazu tmavě modrý.

## 8. Text a typografie
Pravidla sazby z části 4 platí pro každý výstup: nezlomitelná mezera po jednopísmenných předložkách a spojkách, mezi číslem a jednotkou nebo %, uvnitř data a mezi titulem a jménem; tisíce mezerou, desetinná čárka, uvozovky „…“, rozsahy krátkou pomlčkou bez mezer; dlouhá pomlčka (—) se v české sazbě nepoužívá. Bez ozdobné typografie, kterou šablona nemá (prostrkané verzálky, nezvyklé řezy, tečky jako oddělovače, tlusté akcentní linky). Tón věcný a srozumitelný, bez marketingových klišé.

## 9. Kontrola před předáním
- Vyrenderuj a prohlédni každou stranu, snímek i grafiku.
- Správná úroveň loga a správné provedení k pozadí; oficiální soubor; výška aspoň minimum a podle tabulky; ochranná zóna volná; logo s názvem jen na tmavě modré, bílé nebo fotce.
- Písmo: Czechia Sans ve všech použitých řezech, v Office Arial, žádné Calibri v grafech, tabulkách a textových polích; ss01 jen v logu.
- Barvy jen z palety nebo motivu šablony; kontrast podle části 4; pro tisk RGB hodnoty pro tisk nebo CMYK.
- Zarovnání podle principů JVS; nic nepřetéká ani nezasahuje pod logo.
- Typografie podle části 8; fakta jen z podkladů, chybějící údaje jako `[DOPLNIT: …]`.
- PPT: logo úřadu na titulním a závěrečném snímku, název úřadu v zápatí, žádné ukázkové snímky ani prázdné zástupné symboly, čísla snímků, validace prošla.
- Word: záhlaví, zápatí a identifikační blok bez placeholderů, jen styly šablony, číslované nadpisy s úrovní osnovy.
- Grafiky: přesný rozměr; PDF s vloženým písmem (CID TrueType).

## 10. Předání
- Název `<ZKRATKA_URADU>_<tema>_<format>.<přípona>` bez diakritiky a mezer; existující soubor nepřepisuj, přidej `_v2`.
- U grafiky předej PNG nebo PDF, zdrojové HTML a odkaz na odpovídající Canva šablonu z BrandCloudu.
- V odpovědi 1–2 věty: co vzniklo a kde, u prezentace volba varianty, výčet míst `[DOPLNIT]` a každá odchylka od šablony nebo manuálu.