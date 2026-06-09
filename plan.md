# Plan rada - Beauty and Life

## Svrha fajla

Ovaj fajl sluzi kao radni dnevnik i plan za nastavak razvoja projekta.
Koristi se da agent brzo razume trenutno stanje projekta, sta je vec uradjeno, sta je sledece i koje odluke su vazne.

## Kratak opis projekta

Jednostranicni website za kozmeticki salon Beauty and Life Danijele Stojanovic.

Sajt je napravljen kao jedan samostalan HTML fajl:

- `beauty-and-life.html`

Glavne karakteristike:

- srpski / engleski jezik
- svetla / tamna tema
- responsive dizajn
- forma za zakazivanje
- interaktivna mapa
- sekcije: hero, o salonu, usluge, cenovnik, utisci, Instagram, kontakt

## Trenutno stanje

Projekat je spreman za susret sa vlasnicom i deploy. UI/UX korekcije (P0–P2), favicon, Open Graph i README azurirani u sesiji 2026-06-09.

Postojeci fajlovi:

- `beauty-and-life.html` - ceo sajt
- `assets/beauty-and-life-studio.png` - fotografija salona
- `assets/favicon.svg` - favicon (kapljica)
- `README.md` - opis projekta i uputstvo za pokretanje
- `.gitignore` - ignorisani fajlovi
- `Beauty and life PROMT.docx` - originalni prompt/specifikacija

## Uradjeno

- Napravljen single-page HTML sajt.
- Dodata dvojezicnost: srpski i engleski.
- Dodata svetla i tamna tema.
- Dodata navigacija kroz sekcije.
- Dodate sekcije za usluge, cenovnik, utiske i kontakt.
- Dodata forma za zakazivanje sa osnovnom validacijom.
- Dodata interaktivna mapa preko Leaflet.js i OpenStreetMap.
- Dodata osnovna responsive podrska.
- Napravljen `README.md`.
- Napravljen `plan.md` kao radni dokument za pracenje razvoja.
- Implementirane lightbox galerije za svih 5 usluga sa fotografijama (nokti, masaza, sminka, solarijum, obuke).
- Svaki hero tag i svaka kartica usluge vodi na odgovarajucu galeriju.
- Dodat CTA "Zakazi termin" unutar galerije koji vodi do forme za zakazivanje.
- Dodat `assets/ig/` folder za Instagram fotografije; prvi tile povezan sa pravom fotografijom i linkom.
- Instagram profil identifikovan: @danijela_beauty_and_life.

### Vizuelne izmene (2026-05-17)

- Promenjen font na `Inter` (moderan sans-serif) za ceo sajt.
- Dodata fotografija salona u sekciju "O salonu" (`assets/beauty-and-life-studio.png`).
- Logo u navigaciji: samo kapljica ikonica + tekst `B&L` u jednoj liniji, bez punog naziva.
- Kapljica ikonica povecana i uocljivija (tighter viewBox, veci opacity).
- Hero sekcija centrirana (naslov, tagovi, dugmad po sredini).
- Hero eyebrow tekst: `Kozmeticki salon "Beauty and Life" Požarevac` (navodnici umesto tacki, jedan red).
- Sekcija usluga: svih 6 kartica je jednake velicine (uklonjen asimetricni grid).
- Sekcija "O salonu": naslov premesten iznad grida (puna sirina), statistike premestene ispod grida.
- Statistike (10+, 1000+, 6) uokvirene u zasebna polja sa borderom i zaobljenim uglovima.
- Glow hover efekat dodat uniformno na sva polja: stat polja, servisne kartice, cenovnik, utisci, kontakt stavke.
- Hero tagovi postali klikabilni linkovi koji vode ka odgovarajucim servisnim karticama.
- Nazivi hero tagova uskladjeni sa nazivima servisnih kartica (Manikir & Nokti, Masaza, Sminka, Solarijum, Nega koze, Obuke).
- Servisne kartice dobile ID-jeve za direktno linkovanje (usluga-manikir, usluga-masaza, itd.).

## Sledeci koraci

### Prioritet 1

- Dodati jos fotografija salona i vlasnice u sekciju "O salonu" (nakon susreta sa Danijelom).
- Popuniti galeriju za "Nega koze" kada fotografije budu dostupne.
- Dopuniti Instagram sekciju sa preostalih 5 fotografija po izboru vlasnice.
- Proveriti tekstove, cene, kontakt podatke (nakon susreta sa Danijelom).
- Opciono: custom domen na Vercel-u umesto beauty-and-life.vercel.app.

### Prioritet 2

- Implementirati WhatsApp resenje za zakazivanje termina (dogovoreno kao sledeci korak).
- Testirati slanje forme / WhatsApp link na desktopu i telefonu.
- Proveriti mapu i adresu.

### Prioritet 3

- Testirati prikaz na mobilnom, tabletu i desktopu (produkcija: beauty-and-life.vercel.app).
- Proveriti SEO osnovu: title, description, headings, alt tekstovi.
- Opciono: custom domen.

## Vazne odluke

- Projekat ostaje jednostavan: HTML, CSS i vanilla JavaScript.
- Za sada nema framework-a, build sistema ni kompleksnog backend-a.
- Sajt treba da bude lak za odrzavanje i pokretanje.
- `README.md` sluzi kao javni opis projekta.
- `plan.md` sluzi kao interni radni plan i dnevnik razvoja.

## Pravila za buduci rad sa agentom

Kada se nastavlja rad na projektu, agent prvo treba da procita:

1. `README.md`
2. `plan.md`
3. `beauty-and-life.html`

Agent treba da proveri trenutno stanje pre izmena i da nakon znacajne izmene azurira sekcije:

- `Uradjeno`
- `Sledeci koraci`
- `Napomene / problemi`

## Napomene / problemi

- Forma trenutno nema pravi backend (Formspree, Web3Forms ili WhatsApp link) - odluka odlozena.
- U "O salonu" je jedna fotografija salona - dodati jos slika kada budu dostupne.
- Treba proveriti da li su svi podaci tacni pre objave: cene, radno vreme, Instagram link, Facebook link.
- Treba odluciti gde ce sajt biti hostovan.
- Footer SVG logo jos uvek ima stari B&L text unutar SVG - moze se uskladiti sa novim logom ako bude potrebno.
- Sve galerije imaju hardkodovane putanje u GALLERIES objektu u HTML-u. Dodavanje novih slika zahteva azuriranje tog niza. Folder i fajl nazivi moraju biti tacni (ukljucujuci dijakritike i velikaslovnost).
- Instagram linkovi u footeru i kontakt sekciji vode na pravi profil @danijela_beauty_and_life (reseno).
- Galerija za "Nega koze" je prazna - ceka fotografije.
- Instagram sekcija ima samo 1 od 6 fotografija (ig-1.jpg). Preostalih 5 ceka izbor vlasnice.

## Dnevnik rada

### 2026-06-09

- UI/UX audit i korekcije P0: hero eyebrow prelom na mobilnom, kontrast --color-text-faint.
- UI/UX korekcije P1: hero naslov tezina/senka, uskladjeni logoi, :active feedback, tap targeti 44px, hijerarhija naslova, IG placeholder ikonice.
- UI/UX korekcije P2: section--alt klasa, stat-suffix klasa, uklonjen mrtav CSS, ujednacene SVG ikone, Nega koze CTA "Zakazi termin", hero-sub font-weight 400.
- Dodat favicon (assets/favicon.svg) i Open Graph / Twitter Card meta tagovi.
- Azuriran README.md.
- Azuriran plan.md.
- GitHub repo kreiran: github.com/ivanmicic/beauty-and-life
- Deploy na Vercel: beauty-and-life.vercel.app
- OG meta tagovi azurirani sa produkcijskom adresom.

### 2026-06-06

- Naslovi (h1-h6) prebaceni na font-weight 400 (bez bolda).
- Hero eyebrow povecan i bez bolda.
- Logo promenjen sa B&L na Beauty&Life sa stilizovanim ampersandom.
- Obrisan nekorišćeni assets/dark-bg.svg.

### 2026-05-27

- Hero eyebrow tekst ("Kozmetički salon...") - uklonjen text-transform uppercase, prikazuje se malo/veliko slovo.
- Hero eyebrow tekst - povećan font (clamp 1.2–1.8rem), smanjen letter-spacing (0.1em), uklonjen italic.
- Hero naslov - promenjen font na Tangerine (Google Fonts), uklonjen italic, povećan (clamp 4–8rem).
- Hero naslov (engleski) - smanjen font da "Beauty is your calling" stane u jedan red.
- Hover efekat na karticama usluga - pojačan: vece podizanje (-8px), jaci glow i border, siri radial-gradient u uglu.
- Logo kapljica - dodata CSS animacija stalnog okretanja 360° (6s linear infinite).
- Azuriran plan.md.
- Kod poslat na GitHub.

### 2026-05-23

- Implementirane galerije za Masazu (8 slika), Sminku (7 slika), Solarijum (11 slika) i Obuke (9 slika).
- Svaki hero tag i kartica usluge sada otvaraju odgovarajucu galeriju fotografija.
- Resavan problem sa Unicode imenima foldera i fajlova (dijakritike, velicina slova) - proveravati uvek UTF8 ispis.
- Dodat CTA "Zakazi termin" unutar lightbox galerije, vodi na formu za zakazivanje.
- Kreiran folder `assets/ig/`; dodata prva Instagram fotografija (ig-1.jpg) sa linkom na pravi post.
- Razmotren izbor resenja za zakazivanje termina - odluka odlozena do dogovora sa Danijelom.
- Testirana promena fontova (Peace Sans + Open Sauce One) - odlika vracena na Inter.
- Azuriran `plan.md`.
- Kod poslat na GitHub.

### 2026-05-19

- Implementirana lightbox galerija za uslugu "Manikir & Nokti".
- Dodato 6 fotografija u `Galerija nokti/` (Nokti 1-6).
- Hero tag "Manikir & Nokti" i link "Saznaj vise" u kartici usluge sada otvaraju galeriju umesto da vode na zakazivanje.
- Galerija podrZava: navigacija strelicama, tastatura (←→ Escape), swipe na mobilnom, brojaC slika, animacija pri otvaranju.
- Dodat folder `Galerija obuka/` (3 slike), `Galerija soal/` (1 slika), `Galerija sminka/` (4 slike) - galerije za te usluge ce biti implementirane kada se odluci pristup hostovanju slika.
- Razgovarano o strategiji hostovanja slika - odluka odlozena.
- Azuriran `plan.md`.
- Kod poslat na GitHub.

### 2026-05-17

- Dogovoreno da se uvede `plan.md` kao radni dokument za pracenje napretka projekta.
- Promenjen font sajta sa Cormorant Garamond + Jost na Inter.
- Dodata fotografija salona u sekciju "O salonu".
- Vizuelno unapredjen logo (kapljica + B&L u jednoj liniji).
- Hero sekcija centrirana, eyebrow tekst unapredjen.
- Sekcija usluga poravnata na 6 jednakih kartica.
- Layout "O salonu" restrukturiran: naslov puna sirina, statistike u uokvirenim poljima ispod.
- Dodat uniformni glow hover efekat na sva polja i kartice sajta.
- Azuriran `plan.md`.
- Hero tagovi postali klikabilni, uskladjeni sa servisnim karticama.
- Plan za galerije: fotografije se nabavljaju, implementacija sledi.
- Kod poslat na GitHub (inicijalni commit + sve izmene iz sesije).
