# Posisjon og layout i HTML og CSS

## Oppgavebeskrivelse:

I denne oppgaven skal du utforske posisjonering og layout i HTML og CSS. Å forstå hvordan elementer er plassert og layout på en nettside er viktig for å lage visuelt tiltalende og responsive nettsteder. Du vil arbeide med praktiske øvelser for å anvende kunnskapen din om ulike CSS-posisjoneringsteknikker og layoutmodeller.

## Mål med oppgaven:

- Å forstå CSS-posisjoneringsegenskapene (static, relative, absolute og fixed) og deres effekter på elementer.
- Å forstå CSS-layoutmodellene, inkludert boksmodellen og CSS Grid.
- Å praktisere prinsippene for responsiv webdesign.

## Bakgrunnsinformasjon
- [Posisjonering (Aunivers.no)](https://innhold.aunivers.no/fagpakker/realfag/informasjonsteknologi-1-2/it-1/2-nettsider-med-html-og-css/2e-posisjonering-og-css-flexbox/posisjonering)
- [CSS Layout - The position Property (W3schools.com)](https://www.w3schools.com/css/css_positioning.asp)
- [Lage en rask og enkel CSS-layout med float (ndla.no)](https://ndla.no/subject:1:1352b19e-e706-4480-a728-c6b0a57ba8ae/topic:1:f7b88f8c-5f2f-4ea8-bdcf-1bd4811c37b3/topic:1:df9278b0-7252-4a62-a39c-3107d7f319f1/resource:c8e50788-7ef0-4a32-ba89-d882a8e25451)
- [CSS Flexbox (Aunivers.no)](https://innhold.aunivers.no/fagpakker/realfag/informasjonsteknologi-1-2/it-1/2-nettsider-med-html-og-css/2e-posisjonering-og-css-flexbox/css-flexbox)
- [CSS Flexbox (W3schools.com](https://www.w3schools.com/css/css3_flexbox.asp)




## Tema: Min favorittfilm

Nå skal du lage en nettside om din favorittfilm eller serie. Hele nettsiden skal være i ett html-dokument der man scroller nedover for å finne informasjonen. Du skal også ha en meny med interne lenker til de forskjellige delene av nettsiden.

## Del 1: CSS-posisjonering

### Opprett en mappe i Visual Studio Code, med en HTML-fil, `index.html`, som inkluderer følgende elementer:

- En `<header>` med navn på filmen og bakgrunnsbilde fra filmen.
- En navigasjonsmeny (`<nav>`) med minst tre lenker (`<a href="#">Lenke</a>`), f.eks. "Handling", "Skuespillere" og "Anmeldelse". Navigasjonsmeny lages som oftest ved å opprette en liste (`<ul>`) med lenkene inni.
- En faktaboks (`<div>` eller `<aside>`) med fakta om filmen (regissør, land, lengde, aldersgrense)
- En seksjon (`<section id="handling">`) med bilde av filmplakaten og en kort beskrivelse av hva filmen handler om.
- En seksjon (`<section id="skuespillere">`) med oversikt over skuespillere i filmen. Det skal være en overskrift med navnet på skuespilleren, og hvem de spiller i filmen, et bilde og en kort tekst om hver av skuespillerne.
- En seksjon (`<section id="anmeldelse">`) der du skriver din egen anmeldelse av filmen, og gir et terningkast.
- En bunntekst med dine kontaktopplysninger.

### Legg inn følgende CSS-stiler:

Bruk CSS-posisjonering (static, relative, absolute og fixed) for å plassere elementene på HTML-siden din.
- Headeren skal sitte fast øverst på siden, og skal ikke flytte seg når du scroller nedover på siden.
- Navigasjonsmenyen kan enten ligge rett under header og vise lenkene horisontalt, eller den kan ligge som en boks til venstre, under headeren. Navigasjonsmenyen skal heller ikke flytte på seg nåer man scroller nedover (evt kan den scrolle til den når toppen av nettleservinduet, og sitte fast der (`sticky`)).
- Faktaboksen skal ligge til høyre, ved siden av "handling"-seksjonen. Den skal ha en egen bakgrunnsfarge så den skiller seg litt ut fra resten.
- Handling-seksjonen skal være smalere enn nettleservinduet, og skal være midtstilt. Bildet i handling-seksjonen skal stå til venstre for teksten.
- Skuespillere-seksjonen skal ha hver skuespiller som et "kort" som står organisert i rader under hverandre, med to eller tre "kort" på hver rad.
- `footer` skal alltid ligge nederst på siden, uavhengig av scrolling. 


Eksperimenter med ulike kombinasjoner av posisjoneringsegenskaper og observer hvordan de påvirker oppsettet av nettsiden din.
Sørg for å legge til kommentarer i CSS-koden din for å forklare valgene dine for posisjonering.
