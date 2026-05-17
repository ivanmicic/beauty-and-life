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

Projekat je u aktivnom razvoju. Vizuelni deo sajta je znacajno unapredjen u sesiji 2026-05-17.

Postojeci fajlovi:

- `beauty-and-life.html` - ceo sajt
- `assets/beauty-and-life-studio.png` - fotografija salona (zamena za placeholder)
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

- Nabaviti i dodati fotografije za galerije po uslugama (manikir, masaza, sminka, solarijum, nega koze, obuke).
- Implementirati lightbox galeriju za svaku uslugu kada fotografije budu dostupne.
- Dodati jos fotografija salona i vlasnice u sekciju "O salonu".
- Dodati favicon.
- Dodati Open Graph meta tagove za lep prikaz pri deljenju linka.
- Proveriti tekstove, cene, kontakt podatke i Instagram profil.
- Proveriti prikaz na mobilnom uredjaju nakon izmena layout-a.

### Prioritet 2

- Povezati formu za zakazivanje sa stvarnim servisom:
  - Formspree
  - Web3Forms
  - WhatsApp link
  - email servis
- Testirati slanje forme na desktopu i telefonu.
- Proveriti mapu i adresu.

### Prioritet 3

- Postaviti projekat na GitHub.
- Deploy sajta online.
- Testirati prikaz na mobilnom, tabletu i desktopu.
- Proveriti SEO osnovu: title, description, headings, alt tekstovi.

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

- Forma trenutno nema pravi backend (Formspree, Web3Forms ili WhatsApp link).
- U "O salonu" je jedna fotografija salona - dodati jos slika kada budu dostupne.
- Treba proveriti da li su svi podaci tacni pre objave: cene, radno vreme, Instagram link, Facebook link.
- Treba odluciti gde ce sajt biti hostovan.
- Footer SVG logo jos uvek ima stari B&L text unutar SVG - moze se uskladiti sa novim logom ako bude potrebno.

## Dnevnik rada

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
