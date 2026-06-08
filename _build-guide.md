# OBSIDEO — Build guide v3 (bold creative studio)

Závazné. Cíl: každá stránka = stejně odvážná jako homepage. **Heavy motion, atypický layout, crazy kompozice.**

## 0. Jak postavit stránku
1. Vezmi **přesně** kostru z `obsideo/_template.html` (nav, mobilní menu, footer, floating bar, cookie, scripty — kopíruj 1:1, NEMĚŇ).
2. Nahraď `{{TITLE}}`, `{{DESC}}` (česky, prodejně) a obsah `<main>`.
3. **První sekce v `<main>` musí být `<section class="section subhero panel--ink">`** (nebo `panel--bone`) — má odsazení pod fixed nav. H1 je jen tady, jednou.
4. Zapiš do `obsideo/<cesta>/index.html`. Needituj `assets/css/obsideo.css` ani `assets/js/obsideo.js`.
5. Inspirace kvality: přečti si `obsideo/index.html` (homepage — etalon stejných tříd a stylu).

## 1. Tvrdá pravidla
- Čeština s diakritikou, klientovi **vykáme**. Root-absolutní cesty (`/sluzby/...`, `/assets/...`).
- Jen existující CSS třídy (cheatsheet níže). Drobné doladění inline `style=""` OK (jako homepage). Žádné nové CSS/JS, žádné externí knihovny.
- **Sekce = `<section class="section panel--ink|--bone|--volt">` > `<div class="container">`.** STŘÍDEJ panely pro rytmus (ink → bone → ink → volt …). `panel--volt` (electric, full-bleed) použij 1–2× na stránku pro důraz (flagship blok / silné CTA).
- Prvky, co najedou při scrollu → `class="reveal"`? NE — používej **`data-reveal`** (motion engine sám udělá fade-up se staggerem). Dej ho na hlavní bloky/karty.
- Tlačítka s magnetem: přidej `data-magnetic` (hlavní CTA, kruhová, pen-btn).
- H1 jen jednou (v subhero). Validní sémantické HTML, alt u obrázků.
- Placeholdery ponech beze změny: telefon `+420 000 000 000`, `ahoj@obsideo.cz`, IČO `00000000`.
- Obrázky (kde se hodí): `https://picsum.photos/seed/<unikatni-slovo>/900/700?grayscale` (placeholder, šedotón). Vždy `loading="lazy"` + `alt`.

## 2. INTEGRITA
Reference, jména, čísla (+212 %, −14 000 Kč…) a obrázky jsou **ilustrativní placeholdery** — drž realistické a konzistentní s homepage, ale nevymýšlej certifikáty/ocenění/loga značek. Urgenci používej **jen u GEO** (okno AI). Žádné detektivní motivy, žádné jméno zakladatele — mluv za „studio Obsideo / my".

## 3. Hlas (voice)
Sebevědomé bold studio, ostrý ale poctivý prodej. Krátké úderné věty. Konkrétní čísla místo přídavných jmen. **Cenové kotvení** (naše cena vedle ceny velkých agentur: „Jinde 80 000. U nás od 6 000."). **Risk-reversal** otevřeně („Nelíbí se? Neplatíte."). Útoč na status quo (drahé agentury, šablony), nikdy na čtenáře (neříkej „okrádají" → „platíte zbytečně víc"). Poctivá očekávání (SEO/GEO 3–6 měsíců). CTA jedním slovesem v 1. osobě klienta: „Chci audit zdarma", „Spočítejte mi to", „Ukažte mi ceny", „Pošlete poptávku".

## 4. Fakta o službách
- **Webové stránky**: weby od 6 000 Kč, e-shopy 8 000–20 000 Kč. V ceně: unikátní design bez šablon, SEO-ready, responzivní, vizuální editor (klient si edituje sám), analytika (Plausible/GA4), školení 30 min, web vlastníte, hotovo do 14 dnů. Kotvení: agentury 60–120 tis.
- **Social Bot** (VLAJKA): od 5 000 Kč/měs. AI správce sítí 24/7 — komentuje pod cizí příspěvky, odpovídá pod vaše posty i v DM, mluví vaším tónem, vy schvalujete. Nahradí správce za ~15 000 Kč/měs. Instagram, Facebook/Messenger. Balíčky: Start 5 000 (1 síť), Plus 8 000 featured (2 sítě + DM + reporting), Pro 12 000 (+ aktivní komentování cizích).
- **Získat zakázky / Marketing**: PPC (Google Ads, Sklik), Meta Ads, e-mailing, sítě. Specializace na malé rozpočty. Postup: audit → strategie → realizace → měsíční optimalizace. Cena na míru.
- **SEO**: 4 000–8 000 Kč/měs, poctivě bez black-hat, bez „zaručených pozic", výsledky 3–6 měsíců, bez vázací smlouvy. Zahrnuje techniku, keyword research, obsah, link building, reporting, průběžnou optimalizaci.
- **GEO — AI viditelnost**: ChatGPT, Perplexity, Gemini, Google AI Overviews, Claude, Copilot. Balíčky (POUŽÍJ TYTO NÁZVY): **Start** 3 500/měs (nastavení 7 000), **Růst** 6 000/měs (nastavení 10 000, featured), **Lídr** 8 000/měs (nastavení 15 000). + jednorázový **AI audit 2 500 Kč**. Statistiky (lze): 800 M+ uživatelů ChatGPT týdně, 4,4× vyšší konverze z AI, ~25 % dotazů končí AI odpovědí. Poctivá urgence: first-mover okno se zavírá.
- **Automatizace firem**: od ~10 000 Kč nastavení + 1 000–4 000 Kč/měs. Ušetří hodiny týdně. Příklady: reklamy→CRM, automatické e-maily, reporting, správa poptávek. Příklad ROI: požadavek z 65 min na 3 min, úspora ~15 000 Kč/měs.
- **Systémy na míru**: web aplikace, SaaS, CRM, rezervační systémy, klientské zóny, API. Postup: audit → specifikace → vývoj → launch → podpora. Cena na míru, vstup konzultace zdarma.
- **Grafika**: od 600 Kč/banner. Logo (od 2 500), identita/brand manuál (od 6 000), vizitky (od 600), tiskoviny, polepy vozů (od 4 000), reklamní kreativa, social šablony, brand strategie. „Nejlevnější ceny na trhu." Kotvení: logo jinde 25 000 → od 2 500.
- **Audit zdarma** (lead magnet): hodinová analýza zdarma — za 60 min na číslech ukážeme, kde utíkají zakázky a co by to stálo jinde. Pokrývá měření, SEO, rychlost, CTA, nabídku, reklamu, bezpečnost, GDPR. Report do 5 dnů + 30 min konzultace. Nezavazuje, nelíbí = neplatíte.

## 5. CSS cheatsheet (v3)
**Panely/layout**: `.panel--ink` / `.panel--bone` / `.panel--volt`, `.section` (+`.tight`), `.container` (+`.wide`), `.split` (+`.lean`), `.grid` + `.cols-2/3/4`, `.rule`, `.section-head`, `.eybrow-row` (řádek eyebrow + meta).
**Typo**: `h1`/`h2` (gigant Inter Tight), `.h-xl`/`.h-lg`/`.h-md`, `h3`, `.script` (Caveat — pro „crazy" akcentní slova), `.eyebrow` (+`.nm` bez čárky), `.lead`, `.body-lg`, `.accent`, `.muted`, `.outline` (obrysový text).
**Crazy kompozice**: `.statement` > `.big` + `.scr`; `.overlap-script` (rodič) se `.giant-word` + `.scr` uvnitř (script přes obří slovo, jako na homepage „PRÁCE / co prodává" a „ZAČNĚME / auditem zdarma").
**Tlačítka**: `.btn` + `.btn-volt`/`.btn-bone`/`.btn-ink`/`.btn-outline` (u outline dej text do `<span>`), `.btn-lg`/`.btn-block`; `.pen-btn` (CTA s perem); `.circle-btn`; `.text-link` (podtržení); `.pill` (+`.dot`). Hlavní CTA = `data-magnetic`.
**Big list (služby)**: `.big-list` > `a.big-row` (`<span class="fill"></span>` + `.br-num` + `.br-name` + `.br-desc` + `.br-price` + `.br-arrow`(šipka ↗)).
**Case dlaždice**: `.tiles` > `a.tile` (+`.off` pro posun) > `.tile-media`(`img` + `.badge` + `.tagrow`) + `.tile-foot`(`.tile-title`/`.tile-client` + `.tile-metric`).
**Ceník**: `.price-rows` > `.price-row` (`.pr-name`>`small` + `.pr-market` přeškrtnuto + `.pr-ours`). Balíčky: `.plans` > `.plan`(+`.featured`) > `.pt`/`.pp`(>`small`)/`.pf`(>li se svg).
**Statistiky**: `.stats` > `.stat` > `.n` (číslo, count-up přes `<span data-count="212" data-suf=" %">212 %</span>`, volitelně `data-pre`/`data-dec`) + `.l`.
**Citace**: `.quote` (uvnitř `.stars`, `blockquote`, `.metric`, `.who`>`.av`+`.nm`/`.rl`). Do karty: `<div class="card hov" data-reveal><div class="quote">…</div></div>`.
**Karta/feat/kroky/garance**: `.card`(+`.hov`, `.ic`, `.pr`), `.feat`>li(svg+`.h`/`.p`), `.steps`>`.step`(`.sn`+h3+p), `.guarantee`(`.gi`+text, `strong`).
**FAQ**: `.faq` > `.faq-item` > `button.faq-q`(`.qt` text + `<span class="qi"></span>`) + `.faq-a`>`.faq-a-in`.
**Formulář**: `<form data-form>` > `.field`(label+`.input`/`.textarea`/`.select`), `.field-row` (2 sl.), honeypot `<div class="honeypot"><input name="website" tabindex="-1"></div>`, `.form-note`. JS sám zobrazí poděkování.
**Marquee**: `<div class="marquee"><div class="marquee__track auto"><div>…<span class="st">✳</span>…</div><div aria-hidden="true">…(duplikát)…</div></div></div>` (uvnitř `panel--volt`/`--ink`/`--bone`).
**Prose** (legal/blog text): `.prose` v `.container` (max ~70ch).

## 6. Hotové bloky (kopíruj a uprav)

### Ikony
Fajfka: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20 6L9 17l-5-5"/></svg>`
Šipka →: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M13 6l6 6-6 6"/></svg>`
Šipka ↗ (big-row): `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M7 17L17 7M7 7h10v10"/></svg>`

### A) SUBHERO (vždy první sekce)
```html
<section class="section subhero panel--ink">
  <div class="subhero-glow"></div>
  <div class="container">
    <span class="eyebrow" data-reveal>Eyebrow / sekce</span>
    <h1 data-reveal>Úderný nadpis<br><span class="accent">s akcentem</span></h1>
    <p class="lead muted" data-reveal style="max-width:46ch">Podnadpis na 1–2 věty.</p>
    <div class="actions mt-8" data-reveal>
      <a href="/audit-zdarma/" class="pen-btn" data-magnetic><span class="pen">{šipka}</span> Chci audit zdarma</a>
      <a href="/cenik/" class="btn btn-outline"><span>Ceník</span></a>
    </div>
  </div>
</section>
```
Pro „crazy" hero můžeš místo prostého h1 použít `.overlap-script` (giant-word + script) — viz blok H.

### B) SPLIT obsah (text + vizuál/feat)
```html
<section class="section panel--bone">
  <div class="container">
    <div class="split"><div data-reveal>…text, feat…</div><div data-reveal>…karta / obrázek / chat…</div></div>
  </div>
</section>
```

### C) Feature list
```html
<ul class="feat">
  <li>{fajfka}<div><div class="h">Nadpis přínosu</div><div class="p">Krátký popis.</div></div></li>
</ul>
```
### D) Kroky
```html
<div class="steps">
  <div class="step" data-reveal><div class="sn">01</div><div><h3>Krok</h3><p>Popis.</p></div></div>
</div>
```
### E) Ceník naruby
```html
<div class="price-rows" data-reveal>
  <div class="price-row"><div class="pr-name">Web na míru<small>Prezentační web</small></div><div class="pr-market">80 000 Kč</div><div class="pr-ours">od 6 000 Kč</div></div>
</div>
```
### F) Balíčky
```html
<div class="plans">
  <div class="plan" data-reveal><div class="pt">Start</div><div class="pp">3 500 Kč<small>/měs · nastavení 7 000 Kč</small></div><ul class="pf"><li>{fajfka} Funkce</li></ul><a href="/kontakt/" class="btn btn-outline btn-block"><span>Mám zájem</span></a></div>
  <div class="plan featured" data-reveal>…(uprostřed, btn-bone)…</div>
  <div class="plan" data-reveal>…</div>
</div>
```
### G) FAQ
```html
<div class="faq">
  <div class="faq-item"><button class="faq-q" aria-expanded="false"><span class="qt">Otázka?</span><span class="qi"></span></button><div class="faq-a"><div class="faq-a-in">Odpověď.</div></div></div>
</div>
```
### H) CRAZY kompozice (giant + script) — použij aspoň 1× na stránku
```html
<div class="overlap-script" style="display:inline-block">
  <div class="giant-word">PRÁCE</div>
  <span class="scr" style="left:50%;top:58%;transform:translateX(-50%) rotate(-5deg)">co prodává</span>
</div>
```
Nebo statement: `<h2>Vzhled za statisíce. <span class="script">cena za pár tisíc.</span></h2>`
### I) Formulář
```html
<form data-form>
  <div class="field-row"><div class="field"><label>Jméno <span class="req">*</span></label><input class="input" name="jmeno" required></div><div class="field"><label>Telefon <span class="req">*</span></label><input class="input" name="telefon" required></div></div>
  <div class="field"><label>E-mail <span class="req">*</span></label><input class="input" type="email" name="email" required></div>
  <div class="field"><label>Typ poptávky</label><select class="select" name="typ"><option>Web</option><option>Social Bot</option><option>Marketing</option><option>SEO</option><option>GEO</option><option>Automatizace</option><option>Systém na míru</option><option>Grafika</option><option>Audit zdarma</option><option>Jiné</option></select></div>
  <div class="field"><label>Zpráva</label><textarea class="textarea" name="zprava"></textarea></div>
  <div class="honeypot"><input name="website" tabindex="-1" autocomplete="off"></div>
  <button type="submit" class="pen-btn" style="width:100%;justify-content:center" data-magnetic><span class="pen">{šipka}</span> Pošlete poptávku</button>
  <p class="form-note mt-4">Odesláním souhlasíte se <a href="/ochrana-osobnich-udaju/">zpracováním osobních údajů</a>. Odpovídáme do 24 hodin.</p>
</form>
```
### J) Závěrečné CTA (dej skoro na každou stránku, předposlední sekce)
```html
<section class="section panel--volt grain text-center">
  <div class="container">
    <span class="pill" data-reveal style="border-color:rgba(255,255,255,.4)"><span class="dot"></span> Bez rizika</span>
    <h2 class="mt-8" data-reveal>ZAČNĚME.</h2>
    <p class="body-lg mx-auto mt-6" data-reveal style="max-width:44ch;color:rgba(255,255,255,.92)">1–2 věty.</p>
    <div class="actions mt-12" style="justify-content:center" data-reveal>
      <a href="/audit-zdarma/" class="btn btn-bone btn-lg" data-magnetic>Chci audit zdarma {šipka}</a>
      <a href="/kontakt/" class="btn btn-outline btn-lg"><span>Napište nám</span></a>
    </div>
  </div>
</section>
```
### K) Prose (legal/blog)
`<section class="section subhero panel--bone"><div class="container"><h1>Titulek</h1><p class="muted mt-4">Účinné od: [doplňte]</p></div></section>` pak `<section class="section panel--bone"><div class="container"><div class="prose">…h2/p/ul/table…</div></div></section>`. Na konci `.form-note`: „Vzorový dokument — před spuštěním ověřte právníkem."

## 7. Rytmus stránek
- **Detail služby**: subhero(ink, s cenovým kotvením v textu/feat) → „co dostanete" feat (bone, split) → jak to funguje steps (ink) → ceny/balíčky (bone) → flagship/`panel--volt` blok nebo guarantee → FAQ (bone) → CTA (volt). Aspoň 1× `.script`/`.overlap-script`.
- **Ceník**: subhero → `.price-rows` po kategoriích (bone) → „proč jsme levní" (ink) → guarantee → FAQ o cenách → CTA.
- **Audit**: subhero(volt nebo ink) → co projdeme feat → co dostanete → steps → guarantee → formulář (split: form + co dostanete/sociální důkaz). Formulář = hlavní CTA.
- **Reference**: subhero(„PRÁCE" overlap-script) → `.tiles` (6–9, střídej `.off`) s picsum obrázky → stats → CTA.
- **O nás**: subhero → „proč jsme levní" statement+feat → hodnoty (cols karty) → steps → guarantee → CTA.
- **Blog**: subhero → grid `.card` článků (6, s pill kategorií, h3, perex, datum, odkaz `#`) → CTA.
- **Kontakt**: subhero → split (formulář + kontaktní panel `.card`) → CTA volitelně.
- **FAQ**: subhero → `.faq` (2 skupiny po ~6) → CTA.
- **Legal**: subhero(bone) + prose. Bez CTA banneru (jen footer).
