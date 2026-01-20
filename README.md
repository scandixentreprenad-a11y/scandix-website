# Scandix Entreprenad AB - Webbplats

## 📁 Projektstruktur

```
scandix-website/
│
├── index.html                      # Hemsida
├── tjanster.html                   # Tjänster-sida
├── badrumsrenovering.html          # Badrumsrenovering-sida
├── omoss.html                      # Om oss-sida
├── referenser.html                 # Referenser-sida
├── kontakt.html                    # Kontakt-sida
├── styles.css                      # Huvudsaklig CSS-fil
│
└── images/                         # Bildmapp
    │
    ├── logo/                       # Logotyper
    │   ├── logo-scandix.png
    │   └── logo-scandix-white.png
    │
    ├── hero/                       # Hero-bilder
    │   ├── hero-home.jpg
    │   ├── hero-services.jpg
    │   ├── hero-bathroom.jpg
    │   └── hero-about.jpg
    │
    ├── services/                   # Tjänstebilder
    │   ├── roofing/
    │   │   ├── service-roofing-main.jpg
    │   │   ├── service-roofing-1.jpg
    │   │   ├── service-roofing-2.jpg
    │   │   └── service-roofing-3.jpg
    │   │
    │   ├── facade/
    │   │   ├── service-facade-1.jpg
    │   │   ├── service-facade-2.jpg
    │   │   └── service-facade-3.jpg
    │   │
    │   ├── drainage/
    │   │   ├── service-drainage-main.jpg
    │   │   ├── service-drainage-1.jpg
    │   │   ├── service-drainage-2.jpg
    │   │   └── service-drainage-3.jpg
    │   │
    │   ├── foundation/
    │   │   ├── service-foundation-1.jpg
    │   │   ├── service-foundation-2.jpg
    │   │   └── service-foundation-3.jpg
    │   │
    │   └── bathroom/
    │       └── service-bathroom-main.jpg
    │
    ├── bathroom/                   # Badrumsbilder
    │   ├── gallery/
    │   │   ├── bathroom-gallery-1.jpg
    │   │   ├── bathroom-gallery-2.jpg
    │   │   └── bathroom-gallery-3.jpg
    │   │
    │   └── process/
    │       ├── bathroom-process-consultation.jpg
    │       ├── bathroom-process-design.jpg
    │       ├── bathroom-process-demolition.jpg
    │       ├── bathroom-process-plumbing.jpg
    │       ├── bathroom-process-tiling.jpg
    │       └── bathroom-process-final.jpg
    │
    ├── about/                      # Om oss-bilder
    │   ├── about-history.jpg
    │   ├── team-anders-svensson.jpg
    │   ├── team-maria-lindqvist.jpg
    │   └── team-johan-karlsson.jpg
    │
    └── partners/                   # Partner-logotyper
        ├── partner-benders.png
        ├── partner-ramirent.png
        ├── partner-lantz.png
        ├── partner-lindab.png
        ├── partner-5.png
        └── partner-6.png
```

## 🚀 Installation

1. **Skapa mappstrukturen:**
   ```bash
   mkdir -p scandix-website/images/{logo,hero,services/{roofing,facade,drainage,foundation,bathroom},bathroom/{gallery,process},about,partners}
   ```

2. **Kopiera HTML-filerna:**
   - Spara `index.html` i rotmappen
   - Spara `tjanster.html` i rotmappen
   - Spara `badrumsrenovering.html` i rotmappen
   - Spara `omoss.html` i rotmappen
   - Spara `referenser.html` i rotmappen
   - Spara `kontakt.html` i rotmappen

3. **Kopiera CSS-filen:**
   - Spara `styles.css` i rotmappen

4. **Lägg till bilder:**
   - Placera era bilder enligt mappstrukturen ovan
   - Döp bilderna exakt enligt filnamnen i strukturen

## 📸 Bildkrav

### Storlekar
- **Hero-bilder:** 1920x600px (eller liknande 16:9 format)
- **Tjänstebilder:** 400x250px (eller liknande 16:10 format)
- **Badrumsprocess:** 500x350px
- **Team-bilder:** 300x300px (kvadratiska)
- **Logotyper:** Transparent PNG, ca 200-300px bredd
- **Partner-logotyper:** Transparent PNG, max 120px bredd

### Format
- **Fotografier:** `.jpg` (komprimerade för webben)
- **Logotyper:** `.png` (transparent bakgrund)
- **Ikoner:** `.svg` eller `.png`

## 🎨 Färgschema

- **Primär röd:** `#c62828`
- **Mörkgrå:** `#3a3a3a`
- **Mellangrå:** `#666666`
- **Ljusgrå:** `#f5f5f5`
- **Vit:** `#ffffff`

## 📱 Responsiv Design

Webbplatsen är fullt responsiv med brytpunkter på:
- **Desktop:** > 968px
- **Tablet:** 768px - 968px
- **Mobil:** < 768px

## 🔗 Sidor och Navigation

1. **Hem** (`index.html`) - Översikt med hero, tjänster, badrum, testimonials
2. **Tjänster** (`tjanster.html`) - Detaljerad info om alla tjänster
3. **Badrumsrenovering** (`badrumsrenovering.html`) - Dedikerad badrumsida
4. **Om oss** (`omoss.html`) - Företagshistoria och team
5. **Referenser** (`referenser.html`) - Kundomdömen
6. **Kontakt** (`kontakt.html`) - Kontaktformulär och info

## 📞 Kontaktinformation

- **Adress:** Hammarby fabriksväg 23, 120 30 Stockholm, Sweden
- **Telefon:** 073-775 78 77
- **E-post:** info@scandixentreprenad.se

## 🛠️ Teknisk Stack

- **HTML5** - Semantisk markup
- **CSS3** - Grid, Flexbox, Responsive Design
- **Font Awesome 6.0** - Ikoner
- **Google Maps** - Kartor på kontaktsidan

## 📝 Licensinformation

© 2026 Scandix Entreprenad AB. Alla rättigheter förbehållna.

## 💡 Tips för GitHub

När du pushar till GitHub:
```bash
git init
git add .
git commit -m "Initial commit - Scandix Entreprenad AB website"
git branch -M main
git remote add origin https://github.com/dittanvändarnamn/scandix-website.git
git push -u origin main
```

För GitHub Pages:
1. Gå till Settings > Pages
2. Välj "Deploy from branch"
3. Välj "main" branch och "/ (root)"
4. Din webbplats kommer vara live på: `https://dittanvändarnamn.github.io/scandix-website/`
