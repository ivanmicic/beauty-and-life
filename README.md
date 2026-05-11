# Beauty and Life — Kozmetički salon

Jednostraničan sajt za kozmetički salon **Beauty and Life**, vlasništvo **Danijele Stojanović**.
Lokacija: Stari Korzo 30, TC Evrocentar, I sprat lokal 08, Požarevac 12000.
Telefon: 065 2808026

## O projektu

Production-ready single-page website napravljen kao jedan samostalan HTML fajl.
Dvojezičan (srpski/engleski), svetla i tamna tema, interaktivna mapa, forma za zakazivanje.

## Tehnologije

- HTML5 + CSS3 (custom properties, bez framework-a)
- Vanilla JavaScript (bez build alata)
- Google Fonts: Cormorant Garamond + Jost
- Leaflet.js + OpenStreetMap (interaktivna mapa)

## Struktura

```
.
├── beauty-and-life.html       # ceo sajt u jednom fajlu
├── Beauty and life PROMT.docx # originalni prompt sa svim specifikacijama
├── README.md                  # ovaj fajl
└── .gitignore                 # fajlovi koje Git ignoriše
```

## Kako pokrenuti lokalno

### Najlakše: dvoklik

Dvoklikni `beauty-and-life.html` — otvoriće se u podrazumevanom browser-u.

### Preporučeno: lokalni server

Mapa i fontovi pouzdanije rade kad se sajt servira preko `http://`. Ako imaš Python:

```powershell
python -m http.server 8000
```

Pa otvori [http://localhost:8000/beauty-and-life.html](http://localhost:8000/beauty-and-life.html).

Ako imaš Node.js:

```powershell
npx serve .
```

### Live Server (Cursor/VS Code)

Instaliraj ekstenziju "Live Server" (autor: Ritwick Dey), pa desni klik na `beauty-and-life.html` → **Open with Live Server**. Bonus: automatski refreshuje stranicu kad sačuvaš izmene.

## Funkcionalnosti

- Fiksni navbar sa SR|EN prebacivanjem jezika i svetla/tamna tema
- Hero sekcija sa atmosferičnim gradient-om i animiranim elementima
- O salonu sa animiranim brojačima (godine iskustva, klijentkinje, usluge)
- Asimetričan grid usluga (6 usluga sa inline SVG ikonama)
- Cenovnik sa 3 paketa (Basic, Premium, VIP)
- Utisci klijentkinja u masonry layout-u + Instagram feed
- Forma za zakazivanje sa inline validacijom i porukom o uspehu
- Interaktivna mapa Požarevca (Leaflet + OpenStreetMap)
- Footer sa kontakt info i društvenim mrežama
- Potpuno responsive, mobile-first, pristupačno

## Sledeći koraci (ideje)

- Dodati prave fotografije salona (eksterijer, radovi, portret)
- Open Graph meta tagovi za lep izgled prilikom share-ovanja
- Povezati formu sa stvarnim backend-om (Formspree, Web3Forms, ili WhatsApp link)
- Favicon
- Push na GitHub za online backup

## Kontakt

**Kozmetički salon Beauty and Life**
Danijela Stojanović
Stari Korzo 30, TC Evrocentar, I sprat lokal 08
Požarevac 12000, Srbija
Telefon: [065 2808026](tel:+381652808026)
WhatsApp: [wa.me/381652808026](https://wa.me/381652808026)
Instagram: @danijela_beauty_and_life
