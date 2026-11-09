# jvs-statni-sprava

Skill pro Claude, který vytváří materiály v **jednotném vizuálním stylu (JVS) české státní správy**: prezentace, tiskové zprávy, dopisy a další dokumenty, grafiky pro sociální sítě, tiskoviny, e-mailové podpisy a další.

Platí pro ministerstva, ústřední správní úřady a jejich organizace, které od 30. 4. 2026 vytvářejí nové materiály podle JVS. Skill rozlišuje obě úrovně log (úřad s členem vlády v čele a bez něj) a pracuje s oficiálními šablonami z BrandCloudu státní správy.

## Co skill umí

- **Prezentace** (.pptx) v oficiální šabloně PowerPoint JVS, světlá i tmavá varianta, grafy a tabulky v barvách motivu
- **Dokumenty** (.docx) v hlavičkových papírech: dopis, tisková zpráva, interní sdělení, rozhodnutí, dopis ministra a další
- **PDF podklady** a factsheety sázené písmem Czechia Sans
- **Grafiky** pro sociální sítě, pozvánky, obálky, vizitky, infografiky
- Pravidla manuálu: logo a ochranná zóna, barevná paleta (HEX, CMYK, Pantone, RAL), typografie, kontrast podle WCAG

## Instalace

### Claude Code

```
/plugin marketplace add cernykafe/jvs-statni-sprava
/plugin install jvs-statni-sprava@cernykafe
```

Nebo ručně zkopírujte složku `skills/jvs-statni-sprava` do `~/.claude/skills/`.

### Claude.ai a aplikace Claude

1. Stáhněte `jvs-statni-sprava.zip` z [Releases](https://github.com/cernykafe/jvs-statni-sprava/releases).
2. V Claude otevřete **Nastavení → Možnosti (Capabilities) → Skills** a soubor nahrajte.

## Co skill nepotřebuje a co ano

Skill sám neobsahuje loga, písmo ani šablony. Ty stahuje úřad z [BrandCloudu státní správy](https://statni-sprava.brandcloud.pro). Pro finální výstupy je potřeba:

- logo úřadu ve správném provedení (SVG a PNG),
- písmo **Czechia Sans™**, které je licencované a úřad ho získá žádostí přes BrandCloud; nešiřte ho dál,
- příslušná šablona (.potx, .dotx).

Pro práci s Office soubory skill počítá s prostředím, kde je LibreOffice, Python s `python-pptx` a `python-docx` a Chromium s Playwright.

## Upozornění

Neoficiální pomůcka. Závazný je vždy grafický manuál JVS na BrandCloudu státní správy a oficiální šablony z něj; autorem stylu je Studio Najbrt, JVS koordinuje Ministerstvo pro místní rozvoj. Výstupy vždy zkontrolujte proti manuálu.

## Licence

MIT, viz [LICENSE](LICENSE). Licence se týká textu skillu, ne loga, písma ani šablon JVS.
