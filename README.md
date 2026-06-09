# Beauty and Life — Kozmetički salon

Jednostraničan sajt za kozmetički salon **Beauty and Life**, vlasništvo **Danijele Stojanović**.
Lokacija: Stari Korzo 30, TC Evrocentar, I sprat lokal 08, Požarevac 12000.
Telefon: 065 2808026

## O projektu

Production-ready single-page website napravljen kao jedan samostalan HTML fajl.
Dvojezičan (srpski/engleski), svetla i tamna tema, lightbox galerije usluga, interaktivna mapa, forma za zakazivanje.

## Tehnologije

- HTML5 + CSS3 (custom properties, bez framework-a)
- Vanilla JavaScript (bez build alata)
- Google Fonts: Inter + Tangerine (hero naslov)
- Leaflet.js + OpenStreetMap (interaktivna mapa)

## Struktura

```
.
├── beauty-and-life.html          # ceo sajt u jednom fajlu
├── plan.md                       # interni radni plan i dnevnik razvoja
├── assets/
│   ├── favicon.svg               # ikonica sajta (kapljica)
│   ├── beauty-and-life-studio.png
│   └── ig/                       # Instagram fotografije
├── Galerija nokti/               # fotografije po uslugama
├── Galerija masaza/
├── Galerija sminka/
├── Galerija Solarijum/
├── Galerija Obuke/
├── Galerija Nega koze/
├── Beauty and life PROMT.docx
├── README.md
└── .gitignore
```

## Kako pokrenuti lokalno

### Najlakše: dvoklik

Dvoklikni `beauty-and-life.html` — otvoriće se u podrazumevanom browser-u.

### Preporučeno: lokalni server

Mapa, fontovi i favicon pouzdanije rade kad se sajt servira preko `http://`. Ako imaš Python:

```powershell
python -m http.server 8000
```

Pa otvori [http://localhost:8000/beauty-and-life.html](http://localhost:8000/beauty-and-life.html).

Ako imaš Node.js:

```powershell
npx serve .
```

### Live Server (Cursor/VS Code)

Instaliraj ekstenziju "Live Server" (autor: Ritwick Dey), pa desni klik na `beauty-and-life.html` → **Open with Live Server**.

## Funkcionalnosti

- Fiksni navbar sa SR|EN prebacivanjem jezika i svetla/tamna tema
- Hero sekcija sa Tangerine naslovom i klikabilnim tagovima usluga
- O salonu sa fotografijom studija i animiranim brojačima
- 6 usluga sa lightbox galerijama (osim Nega kože — čeka fotografije)
- Cenovnik sa 3 paketa (Basic, Premium, VIP)
- Utisci klijentkinja + Instagram feed
- Forma za zakazivanje sa inline validacijom
- Interaktivna mapa Požarevca (Leaflet + OpenStreetMap)
- Favicon i Open Graph meta tagovi za deljenje linka
- Potpuno responsive, mobile-first

## Pre deploy-a

U `beauty-and-life.html`, u `<head>` sekciji, zameniti `SITE_URL` punom produkcijskom adresom (npr. `https://vas-domen.rs`) u `og:image`, `og:url` i `twitter:image` meta tagovima.

## Sledeći koraci

- Povezati formu za zakazivanje (planirano: WhatsApp)
- Dodati preostale fotografije (O salonu, Instagram, galerija Nega kože) po izboru vlasnice
- Finalna provera cena, radnog vremena i tekstova sa Danijelom
- GitHub + deploy online

## Kontakt

**Kozmetički salon Beauty and Life**
Danijela Stojanović
Stari Korzo 30, TC Evrocentar, I sprat lokal 08
Požarevac 12000, Srbija
Telefon: [065 2808026](tel:+381652808026)
WhatsApp: [wa.me/381652808026](https://wa.me/381652808026)
Instagram: [@danijela_beauty_and_life](https://www.instagram.com/danijela_beauty_and_life/)
