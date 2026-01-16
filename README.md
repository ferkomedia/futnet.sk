# 🏐 Futnet.sk - Slovenská asociácia nohejbalu

Moderná webová stránka pre Slovenskú asociáciu nohejbalu postavená na Astro frameworku.

## 📋 O projekte

Tento projekt je oficiálna webová stránka Slovenskej asociácie nohejbalu (SNA), ktorá obsahuje:

- 📰 Aktuality a novinky
- 🏆 Prehľad súťaží a výsledkov
- 🏟️ Zoznam klubov
- 🇸🇰 Informácie o reprezentácii
- 📸 Fotogalériu
- ℹ️ Dôležité dokumenty a informácie
- 📞 Kontaktné údaje

## 🚀 Inštalácia

```bash
# Nainštalujte závislosti
npm install

# Spustite vývojový server
npm run dev

# Build pre produkciu
npm run build

# Náhľad produkčného buildu
npm run preview
```

## 📁 Štruktúra projektu

```
futnet.sk/
├── public/              # Statické súbory
├── src/
│   ├── layouts/         # Layout komponenty
│   │   └── Layout.astro
│   ├── pages/           # Stránky (route-based)
│   │   ├── index.astro
│   │   ├── aktuality.astro
│   │   ├── kluby.astro
│   │   ├── reprezentacia.astro
│   │   ├── galeria.astro
│   │   ├── sutaze/
│   │   │   └── index.astro
│   │   ├── informacie/
│   │   │   └── index.astro
│   │   └── o-nas/
│   │       ├── index.astro
│   │       └── kontakt.astro
│   └── components/      # Reusable komponenty
├── astro.config.mjs
├── package.json
└── README.md
```

## 🛠️ Technológie

- **Astro** - Static Site Generator
- **HTML/CSS** - Markup a styling
- **TypeScript** - Type safety

## 🌐 Deployment

Projekt je nasadený na **Cloudflare Pages** s automatickým deploymentom z GitHub repozitára.

### Build nastavenia:
- **Build command:** `npm run build`
- **Build output:** `dist`
- **Framework preset:** Astro

## 📝 Pridávanie obsahu

### Nové aktuality
Pridajte nový článok do `/src/pages/aktuality/` alebo upravte existujúcu stránku.

### Nové stránky
Vytvorte nový `.astro` súbor v priečinku `/src/pages/`. Astro automaticky vytvorí route podľa štruktúry súborov.

### Upravenie navigácie
Navigácia sa nachádza v `/src/layouts/Layout.astro`.

## 🎨 Dizajn

Web používa vlastný CSS s nasledujúcimi hlavnými farbami:

- **Primary:** `#0066cc` (modrá)
- **Secondary:** `#003d7a` (tmavá modrá)
- **Accent:** `#ff6b35` (oranžová)

## 📧 Kontakt

**Slovenská asociácia nohejbalu**
- Email: nohejbal.sna@gmail.com
- Tel: +421 917 800 004
- Web: https://futnet.sk

## 📄 Licencia

© 2026 Slovenská asociácia nohejbalu. Všetky práva vyhradené.
