# OBSIDEO — Kompletní grafický brief

Tady je **všechna grafika**, kterou web a značka potřebují, sepsaná jako hotové zadání. U každého assetu máš: účel, rozměry, formát, barvy, styl a **hotový PROMPT**, který stačí zkopírovat do ChatGPT (generování obrázků), Midjourney nebo poslat grafikovi. Prompty pro generátory obrázků jsou v angličtině (modely tak dávají lepší výsledky), popisky česky.

> Web je plně funkční i bez těchto obrázků — používá vlastní SVG logo, SVG ikony a CSS pozadí. Grafika níže ho jen **pozvedne na maximum** a doplní social/tisk.

## 🎨 Značka — závazné mantinely (vlož do KAŽDÉHO promptu)
- **Barvy:** deep ink `#0B0C10` (tmavé pozadí), bone / teplá béžová `#ECE6D7` (světlé sekce), **electric indigo `#4736FF`** (signature akcent — kruhová tlačítka, CTA, hover), slonovinová `#F2EFE6` (text na tmavé), ink `#14140F` (text na světlé).
- **Písma:** nadpisy **Inter Tight** (těžký stažený grotesk), akcentní „ručně psaná" slova **Caveat** (script), text **Inter**.
- **Styl:** bold creative studio — odvážný, editorial, vysoký kontrast (ink × bone), full-bleed barevné plochy, gigantická typografie, jeden výrazný electric indigo akcent, hodně prostoru, heavy-motion energie. Sebevědomý, ne korporátní.
- **NE:** generický „tech startup" vzhled, stock fotky s úsměvem do kamery, clip-art, přesycené duhové barvy, jemné pastely, AI-slop.
- Anglický „style suffix" do promptů: *"bold editorial creative-studio aesthetic, deep ink #0B0C10 background and warm bone #ECE6D7, single electric indigo #4736FF accent (NOT gold), oversized confident typography, high contrast, generous negative space, sharp and modern, no clutter, no rainbow, photorealistic where relevant, 8k"*.

> Pozn.: V promptech níže nahraď zmínky o „champagne gold / zlatém" akcentu za **electric indigo `#4736FF`** — paleta značky se posunula na bold electric směr.

---

## 1) Logo — finální vektor (priorita 1)
**Účel:** hlavní logo značky pro web, social, fakturu, tisk. (Na webu už běží jednoduchá SVG verze — tohle je její profi dotažení.)
**Co potřebuju:** wordmark "Obsideo" ve Fraunces + symbol broušeného obsidiánového krystalu (fasetový pětiúhelníkový drahokam) vlevo od názvu.
**Varianty (dodej všechny):**
- horizontální (symbol + text), vertikální (symbol nad textem), jen symbol (ikona), jednobarevná (zlatá na černé), inverzní (černá na světlé), čistě bílá a čistě černá verze.
**Formát:** SVG + PNG (transparentní, 2000 px delší strana) + zdroj (AI/Figma).
**Barvy:** symbol zlatý gradient `#F4D9A6 → #E8B873 → #C9A227`, text slonovinová `#F4F1EA` (na tmavé) / obsidiánová (na světlé).

**PROMPT (ChatGPT / Midjourney):**
```
Design a premium logo for a digital agency called "Obsideo".
Symbol: a faceted obsidian gem / crystal shard (pentagon-cut, sharp geometric facets) rendered in a champagne-gold gradient (#F4D9A6 to #E8B873 to #C9A227).
Wordmark: "Obsideo" in a high-contrast editorial serif (Fraunces style), letters in warm ivory #F4F1EA.
Layout: horizontal lockup, gem to the left of the wordmark, balanced.
Background: obsidian black #0B0E14.
Style: luxury, minimal, auction-house elegance, crisp vector, lots of negative space, no gradients besides the gem, no purple, no rainbow.
Deliver clean, scalable, centered.
```

## 2) Favicon / app ikona
**Účel:** ikona v záložce prohlížeče a na ploše. **Rozměry:** 512×512 px (master), exporty 16, 32, 180 (apple-touch), 192, 512. **Formát:** PNG + ICO + SVG.
**Obsah:** jen symbol obsidiánového krystalu (bez textu) na obsidiánové čerň `#0B0E14`, zlatý krystal `#E8B873`, lehce zaoblené rohy (squircle).
**PROMPT:**
```
App icon: a single faceted obsidian gold gem (#E8B873 with #C9A227 facets) centered on a near-black #0B0E14 rounded-square background, premium, minimal, crisp edges, 512x512, no text.
```

## 3) Open Graph / náhled na sociálních sítích (priorita 1)
**Účel:** obrázek, který se ukáže při sdílení webu na FB/LinkedIn/Messenger/WhatsApp. **Rozměry:** **1200×630 px**. **Formát:** PNG/JPG. Ulož jako `/assets/img/og-default.jpg` a v `<head>` přidej `<meta property="og:image" content="/assets/img/og-default.jpg">`.
**Obsah:** vlevo nadpis "Vypadáte na milion. Platíte zlomek." (Fraunces, "Platíte zlomek." ve zlatě), pod tím malý claim "Digitální agentura · od 6 000 Kč" a logo; vpravo abstraktní obsidiánový krystal se zlatým odleskem.
**PROMPT:**
```
Social share banner, 1200x630px. Left side: headline "Vypadáte na milion. Platíte zlomek." in a high-contrast serif (Fraunces), with "Platíte zlomek." in champagne gold #E8B873, the rest ivory #F4F1EA; small tagline "Digitální agentura · od 6 000 Kč" and an "Obsideo" gold gem logo below. Right side: a large faceted obsidian crystal with champagne-gold light reflections, floating on obsidian black #0B0E14 with a subtle gold radial glow. Premium dark editorial aesthetic, generous negative space, no purple, no clutter.
```

## 4) Hero pozadí / atmosféra (volitelné, ale efektní)
**Účel:** decentní obrazové pozadí pod hero sekci homepage (přes CSS overlay). **Rozměry:** 2880×1620 px (kvůli retina), tmavé, ať text zůstane čitelný. **Formát:** JPG (optimalizovaný < 300 kB) nebo WebP.
**Obsah:** abstraktní makro broušeného obsidiánu / vulkanického skla s jemnými zlatými žilkami a hloubkou; spodní polovina velmi tmavá pro čitelnost.
**PROMPT:**
```
Abstract macro of polished black obsidian volcanic glass with subtle champagne-gold veins and soft depth-of-field highlights, very dark, cinematic, premium, on #0B0E14, gold accents #E8B873, bottom half fades to near-black for text legibility, no text, 2880x1620, photorealistic, elegant.
```

## 5) Ikony služeb (8 ks, volitelné — web už má SVG)
**Účel:** na webu běží liniové SVG ikony. Pokud chceš custom sadu, zadej jednotně. **Rozměry:** 64×64 px viewbox, stroke 1.8, zlatá `#E8B873`. **Formát:** SVG, jednotný liniový styl.
**Služby:** Webové stránky, Social Bot, Získat zakázky (marketing), SEO, GEO (AI), Automatizace, Systémy na míru, Grafika.
**PROMPT:**
```
A cohesive set of 8 line icons, single 1.8px stroke, champagne gold #E8B873 on transparent, 64x64, rounded joins, minimal premium style: (1) browser window = websites, (2) chat bubble with spark = AI social bot, (3) megaphone/rising chart = marketing, (4) magnifier = SEO, (5) sparkle/AI star = generative AI visibility, (6) lightning bolt + gear = automation, (7) code brackets = custom systems, (8) palette = graphic design. Consistent weight and corner radius, no fills.
```

## 6) Mockupy referencí / případových studií (9 ks)
**Účel:** na stránce `/reference/` a v sekci referencí nahradit textové karty náhledy webů. **Rozměry:** 800×600 px (poměr 4:3), zaoblené rohy. **Formát:** PNG/JPG.
**Obsah:** realistické náhledy webů v oborech: řeznictví, kadeřnictví, e-shop s nářadím, instalatér, kavárna, autoservis, fitness, květinářství, advokát. Tmavé/prémiové weby v duchu Obsideo.
**PROMPT (uprav obor):**
```
Realistic website mockup screenshot for a [ŘEZNICTVÍ] business, modern premium dark web design, champagne-gold accents, clean layout with hero and product section, shown as a browser frame, 800x600, on a soft dark background, high quality, no lorem-ipsum gibberish, Czech-feeling brand.
```

## 7) Vizuál Social Bota (vlajková služba)
**Účel:** na `/sluzby/social-bot/` hero — silný vizuál. **Rozměry:** 1200×1000 px. **Formát:** PNG (transparentní) nebo JPG na tmavém.
**Obsah:** abstraktní "AI správce" — chatové bubliny vyletující z telefonu/krystalu, zlatá a oranžová, pocit "běží 24/7". Bez tváří.
**PROMPT:**
```
Abstract illustration of an AI social-media assistant: floating chat bubbles, comment and DM icons, notification dots, flowing out of a glowing obsidian-gold crystal, champagne gold #E8B873 and a few warm orange #F2552C accents on obsidian black #0B0E14, sense of 24/7 motion, premium, minimal, no human faces, no text inside bubbles, 1200x1000.
```

## 8) Obrázky k blogu (6 ks)
**Účel:** cover obrázky článků na `/blog/`. **Rozměry:** 1200×675 px (16:9). **Formát:** JPG.
**Témata:** cena webu, GEO/AI, návratnost reklamy, Social Bot vs. správce, web který neprodává, SEO pro malé firmy.
**PROMPT (uprav téma):**
```
Editorial blog cover, 1200x675, theme "[KOLIK STOJÍ WEB]", abstract premium concept art on obsidian black #0B0E14 with champagne-gold #E8B873 elements, minimal, sophisticated, no stock-photo people, single subtle orange accent, lots of negative space.
```

---

## 🖨️ TISK & BRAND (pro vlastní propagaci agentury i jako ukázky služby Grafika)

## 9) Vizitka
**Rozměry:** 90×50 mm + 3 mm spadávka (96×56 mm), CMYK, 300 DPI. **Formát:** PDF k tisku + náhled.
**Přední:** černá obsidiánová, zlatý krystal + "Obsideo", jméno a pozice. **Zadní:** zlatý claim "Vypadáte na milion. Platíte zlomek." + kontakt.
**PROMPT:**
```
Premium business card design, 90x50mm with bleed, front: matte obsidian black #0B0E14, embossed-look gold #E8B873 Obsideo gem logo and wordmark, name and role in Inter; back: champagne-gold tagline "Vypadáte na milion. Platíte zlomek." centered, contact details small. Luxury, minimal, lots of space, gold-foil feel, CMYK print-ready.
```

## 10) Polep firemního vozu (ukázka služby)
**Rozměry:** šablona dodávky (např. VW Caddy) ve vektoru, měřítko 1:10. **Formát:** vektor.
**Obsah:** tmavý polep, velký zlatý claim, logo, web, telefon; čisté, drahé, čitelné z dálky.
**PROMPT:**
```
Vehicle wrap design mockup for a small delivery van, dark obsidian wrap with large champagne-gold "Obsideo" logo, tagline "Vypadáte na milion. Platíte zlomek.", website obsideo.cz and phone, premium minimal layout, readable from distance, side and rear views.
```

## 11) Šablony pro sociální sítě
**Rozměry:** příspěvek 1080×1080 px, story/reel 1080×1920 px. **Formát:** sada 5–8 šablon (Canva/Figma).
**Obsah:** jednotný systém — obsidiánové pozadí, zlaté nadpisy Fraunces, oranžové CTA, místo na claim/cenu ("od X Kč").
**PROMPT:**
```
A set of 6 Instagram templates (1080x1080 and 1080x1920) for a premium digital agency: obsidian black #0B0E14 background, champagne-gold #E8B873 Fraunces headlines, ivory body text, one orange #F2552C CTA button per template, consistent grid, space for a price tag "od X Kč" and the gold gem logo, luxury minimal, cohesive system.
```

---

## ✅ Po vygenerování — kam soubory dát
- Logo → `/assets/img/` (např. `logo.svg`, `logo-white.png`) a nahraď inline SVG v hlavičce/patičce, pokud chceš profi verzi.
- Favicon → `/assets/img/favicon.png` + přidej `<link rel="apple-touch-icon" ...>` do `<head>`.
- OG obrázek → `/assets/img/og-default.jpg` + přidej `<meta property="og:image">` (ideálně na každou stránku).
- Reference/blog obrázky → `/assets/img/reference/` a `/assets/img/blog/`, doplň do `<img>` na příslušných stránkách.

> **Tip:** všechny fotorealistické obrázky před nasazením zkomprimuj (TinyPNG / Squoosh) a ulož jako WebP — web pak zůstane bleskově rychlý.
