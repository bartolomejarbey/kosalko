# Martin Pečenka — kreativní balík pro 2 nové firmy

Klient dává volnou ruku na brand identity, logo, web, grafiku a video pro **dvě nové,
na sobě nezávislé firmy**. Tahle složka je **koncept k odsouhlasení** — to, co položíš
klientovi na stůl, aby řekl „ano / ne / jinak" a doplnil ceny. Smyčka je: *koncept → feedback → finál*.

> Dvě firmy = **dvě samostatné značky**, ne jeden společný brand. Cílovka, tón i nákupní
> situace se nepřekrývají (klidná noc v přírodě × adrenalin pro děti). Spojuje je jen majitel.

---

## 🏕️ Firma 1 — Tiny house u lomu
Pronájem **dvou tiny houses na noc**, sever/východ Čech, pod Libercem. **Lom ~10 m** od domků →
v létě koupání, celoročně vyhlášená příroda. Detail, naming a web v **[`tiny-house/`](./tiny-house/)**.

## 🏍️ Firma 2 — Pronájem dětských pitbike
Elektro (krátkodobě) i benzín (dlouhodobě). Model: **mobilní pop-up** — dodávka přiveze ~20 strojů
na lokalitu, ~14 dní okno, mini PPC rozpočet 2–3 tis. Kč + **stálý výdej v Praze**. Ceny: **100 Kč / 10 min**,
**1 000 Kč / den**, **kauce 5 000 Kč**. Detail, naming, web a PPC playbook v **[`pitbike/`](./pitbike/)**.

---

## 📁 Co je v balíku
```
martin-pecenka/
├── README.md                     # tenhle přehled
├── tiny-house/
│   ├── ZNACKA.md                 # naming, positioning, identita, copy, foto/video, ceny
│   └── index.html                # landing page – KONCEPT (otevři v prohlížeči)
└── pitbike/
    ├── ZNACKA.md                 # naming, positioning, identita, copy, podmínky
    ├── MARKETING-popup.md        # 14denní pop-up PPC playbook + checklist na každou zastávku
    └── index.html                # landing page – KONCEPT (otevři v prohlížeči)
```

## 👀 Jak si to prohlédnout
Landing pages jsou **samostatné HTML** (žádná instalace). Otevři dvojklikem, nebo pošli klientovi
soubor `index.html` — funguje i offline. Pro hezké náhledy v mobilu pošli přes hosting (Netlify drag&drop).

---

## ⚠️ Co ověřit u klienta (předpoklady, ze kterých jsem vyšel)
Pár věcí jsem **domyslel** — než půjde cokoli živě, potvrď:

**Obě firmy**
- [ ] **Mají firmy už názvy / IČO / s.r.o.?** Pokud ano, řekni — naming je návrh, finál překlopím za 5 min.
- [ ] **Domény a IG handly** — u doporučených názvů ověřit volnost (`.cz` + Instagram).
- [ ] **Plátce DPH?** (kvůli prezentaci cen — „včetně DPH" / „bez DPH").
- [ ] Logo, fotky, videa: máme přístup k focení na místě? Termín?

**Tiny house**
- [ ] **Přesná lokalita** (obec) — kvůli mapě, SEO a textu o okolí.
- [ ] **Je lom ke koupání?** Stavěl jsem hero na „koupání v lomu v létě" — pokud se nekoupe, přepíšu na výhled/atmosféru.
- [ ] **Ceny za noc** (víkend vs. všední, sezóna) + co je v ceně. Sauna / vířivka / snídaně / domácí mazlíček ano-ne?
- [ ] **Rezervační systém** — chceme napojit (Smoobu/Lodgify/Beds24), nebo zatím jen formulář + kalendář? Listing na Airbnb/Booking?

**Pitbike**
- [ ] Potvrdit **ceny a kauci** (mám 100/10 min, 1000/den, kauce 5000) + jestli chceme přidat mezistupně (hodina, půlden, víkend).
- [ ] **Věk/výška dětí**, na který stroje sedí (do textu o bezpečnosti a do cílení reklamy).
- [ ] Pojištění / odpovědnost za škodu / co když se stroj poškodí nad rámec kauce.
- [ ] Stálá pražská **výdejna** — adresa nebo „po domluvě"?

---

## ✅ Doporučené pořadí dalších kroků
1. **Klient vybere názvy** (u každé firmy 3 směry, mám doporučení) → zarezervovat domény + IG.
2. **Dotáhnout loga** (v `ZNACKA.md` máš hotové prompty na generátor i zadání pro grafika).
3. **Focení/video na místě** (shotlisty jsou v každé `ZNACKA.md` — levné, dají 80 % výsledku).
4. **Doplnit reálné ceny + texty** do landing pages, nasadit na doménu (Netlify/Vercel, zdarma).
5. **Pitbike: rozjet pop-up PPC** podle `pitbike/MARKETING-popup.md` na první lokalitě.

> Tón i barvy v landing pages jsou **návrh** — všechno je na jednom místě a snadno se mění.
> Až bude směr odsouhlasený, dotáhnu weby do plné verze (víc sekcí, motion, rezervace, SEO).
