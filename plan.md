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

Projekat je u aktivnom razvoju. Galerije i Instagram sekcija su znacajno unapredjene u sesiji 2026-05-23.

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

- Dodati jos fotografija salona i vlasnice u sekciju "O salonu".
- Popuniti galeriju za "Nega koze" kada fotografije budu dostupne.
- Dopuniti Instagram sekciju sa preostalih 5 fotografija po izboru vlasnice (imamo template, dodaje se brzo).
- Azurirati Instagram linkove na pravi profil u footeru i kontakt sekciji (trenutno vodi na instagram.com/). Pravi link: https://www.instagram.com/danijela_beauty_and_life/
- Dodati favicon.
- Dodati Open Graph meta tagove za lep prikaz pri deljenju linka.
- Proveriti tekstove, cene, kontakt podatke.
- Proveriti prikaz na mobilnom uredjaju.

### Prioritet 2

- Odluciti i implementirati resenje za zakazivanje termina:
  - WhatsApp link (najbrze, odmah)
  - Formspree / Web3Forms (forma salje email, 10 minuta podesavanja)
  - Calendly (automatska potvrda termina)
  - Booking sistem: Fresha, Treatwell, Booksy (profesionalno, placa se)
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

- Forma trenutno nema pravi backend (Formspree, Web3Forms ili WhatsApp link) - odluka odlozena.
- U "O salonu" je jedna fotografija salona - dodati jos slika kada budu dostupne.
- Treba proveriti da li su svi podaci tacni pre objave: cene, radno vreme, Instagram link, Facebook link.
- Treba odluciti gde ce sajt biti hostovan.
- Footer SVG logo jos uvek ima stari B&L text unutar SVG - moze se uskladiti sa novim logom ako bude potrebno.
- Sve galerije imaju hardkodovane putanje u GALLERIES objektu u HTML-u. Dodavanje novih slika zahteva azuriranje tog niza. Folder i fajl nazivi moraju biti tacni (ukljucujuci dijakritike i velikaslovnost).
- Instagram linkovi u footeru i kontakt sekciji jos vode na instagram.com/ umesto na pravi profil @danijela_beauty_and_life.
- Galerija za "Nega koze" je prazna - ceka fotografije.
- Instagram sekcija ima samo 1 od 6 fotografija (ig-1.jpg). Preostalih 5 ceka izbor vlasnice.

## Dnevnik rada

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
