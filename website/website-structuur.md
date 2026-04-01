# 💻 Website Structuur & Teksten

De website is het commandocentrum van het spel. Kinderen voeren hier codes in en krijgen instructies.

## Technische info
- Statische HTML/CSS/JS (geen backend nodig)
- Werkt op elke telefoon, tablet of laptop
- Kan lokaal gedraaid worden (open index.html) of online gezet worden

---

## Pagina 1 — Startpagina

**URL:** `/` of `index.html`

### Bovenkant
```
🔮 DE GEHEIME CODE VAN PROFESSOR KWARTS
```

### Introverhaal (scrollbaar)
> Professor Kwarts is verdwenen.
> Ze heeft 10 geheime codes achtergelaten.
> Jullie taak: ontcijfer elke code en vind de Kwartssteen.
>
> In elke envelop zit een puzzel.
> Los de puzzel op en voer de code hieronder in.
>
> Zijn jullie klaar? Dan beginnen we.

### Code-invoerveld
```
┌─────────────────────────────┐
│  Voer je code in...         │
│  [________________________] │
│        [ CONTROLEER ]       │
└─────────────────────────────┘
```

### Bij juiste code (KWARTS-01)
```
✅ WELKOM, SPEURNUZEN!
Professor Kwarts heeft jullie verwacht.

Jullie eerste opdracht:
Ga naar de KEUKEN. Daar ligt iets bijzonders
onder de rode theedoek. Zoek ENVELOP 2.

Succes! 🔍
```

### Bij foute code
```
❌ Die code klopt niet.
Controleer of je het goed hebt geschreven.
Hint: hoofdletters en streepjes doen ertoe.
```

---

## Pagina 2 — Spelvoortgang

**URL:** `/spel.html`

### Header
```
🔮 SPELVOORTGANG
Stap [X] van 10
```

### Voortgangsbalk
```
[████████░░] 8/10 codes gekraakt
```

### Huidige instructie
> Gebaseerd op de laatst ingevoerde juiste code

### Code-invoerveld (zelfde als startpagina)

---

## Code-feedback per stap

### Code: HELP (Stap 2)
```
✅ GOED GEDAAN!
Professor Kwarts vroeg om hulp!
Maar ze heeft meer achtergelaten...

GA NAAR: WOONKAMER
ZOEK: Achter het grootste kussen
VIND: ENVELOP 3

🔍 Tip: In deze envelop zit iets dat je in
een spiegel kunt lezen...
```

### Code: SLEUTEL (Stap 3)
```
✅ UITSTEKEND!
De sleutel zit onder de trap — letterlijk!

GA NAAR: ONDER DE TRAP
ZOEK: Een kleine envelop
VIND: ENVELOP 4

🔍 Tip: Deze envelop bevat een heel nieuw alfabet...
```

### Code: BOOM (Stap 4)
```
✅ BRILJANT!
Professor Kwarts hield van de natuur.

GA NAAR: TUIN (of BALKON)
ZOEK: Iets dat aan iets groens hangt
VIND: ENVELOP 5

🔍 Tip: Plaatjes kunnen ook woorden zijn...
```

### Code: STERREN (Stap 5)
```
✅ PERFECT!
De sterren wijzen altijd de weg.

GA NAAR: ZOLDER (of bovenste verdieping)
❗ HET CIJFERSLOT: 7-3-9-1
OPEN: Het slotje
VIND: ENVELOP 6

🔍 Tip: In deze envelop zit een raadsel...
```

### Code: RITS (Stap 6)
```
✅ SLIM GEDAAN!
Een rits — tanden die niet bijten!

GA NAAR: BADKAMER
ZOEK: In een potje of doosje
VIND: ENVELOP 7

🔍 Tip: Op deze plattegrond staan 3 X-markeringen...
```

### Code: DEUR (Stap 7)
```
✅ ECHTE DETECTIVES!
Jullie hebben de deur gevonden!

GA NAAR: GANG (bij de voordeur)
ZOEK: Ergens laag bij de grond
VIND: ENVELOP 8

🔍 Tip: Deze brief komt uit het verleden —
er zit een rebus in verstopt...
```

### Code: KRISTAL (Stap 8)
```
✅ HET KRISTAL!
Jullie hebben het gevonden!
Nog 2 stappen te gaan.

GA NAAR: TV-HOEK (of zithoek)
ZOEK: Ergens tussen de kussens
VIND: ENVELOP 9

🔍 Tip: Een kruiswoordraadsel —
de gele letters zijn het belangrijkst...
```

### Code: BEGIN (Stap 9)
```
✅ WAAR HET BEGON!
Jullie zijn er bijna!

GA TERUG NAAR: DE STARTTABEL
(ja, waar het allemaal begon!)
ZOEK: Iets dat verstopt zit
VIND: ENVELOP 10

🔮 Dit is de laatste stap...
```

### Code: KWARTS (Stap 10)
```
🎉🎉🎉 GEFELICITEERD! 🎉🎉🎉

JULLIE HEBBEN DE KWARTSSTEEN GEVONDEN!

Professor Kwarts is trots op jullie!
Jullie zijn de slimste speurneuzen
die er bestaan!

🔮 De Kwartssteen is nu van jullie. 🔮

Bedankt voor het spelen!
```

_(Confetti animatie op het scherm)_

---

## Hint Systeem

**Knop:** "Ik wil een hint" (altijd zichtbaar)

### Hints per stap:

**Stap 1:**
> "De code staat in de brief van Professor Kwarts. Zoek de dikke gedrukte tekst."

**Stap 2:**
> "Elk cijfer staat voor een letter. 8 is de 8e letter van het alfabet."

**Stap 3:**
> "Sommige teksten kun je alleen lezen in een spiegel. Waar vind je een spiegel?"

**Stap 4:**
> "Gebruik de decoderkaart. Begin met het symbool dat het vaakst voorkomt."

**Stap 5:**
> "Lees de plaatjes van links naar rechts. Ze vormen samen woorden."

**Stap 6:**
> "Dit is een raadsel. Wat in je kledingkast heeft tanden maar kan niet bijten?"

**Stap 7:**
> "De X-en op de plattegrond komen overeen met echte plekken in het huis."

**Stap 8:**
> "Lees elk plaatje als letter(s). KR + oog + staart + elleboog?"

**Stap 9:**
> "Los eerst alle woorden op. De gemarkeerde letters vormen de oplossing."

**Stap 10:**
> "Waar zijn jullie begonnen? Het antwoord ligt waar alles startte."

---

## Eindpagina

**URL:** `/einde.html` (automatisch na laatste code)

### Content
```
🔮 DE KWARTSSTEEN 🔮

Gefeliciteerd, [speurneuzen]!

Jullie hebben alle 10 codes gekraakt.
Professor Kwarts is trots op jullie!

Jullie zijn nu officieel lid van:
DE GEHEIME ORGANISATIE VAN DE KWARTSSTEEN

┌──────────────────────────────┐
│  🏆 EINDCIJFER: 10/10 🏆    │
│  Rang: Meester-Speurneus     │
└──────────────────────────────┘

Deel je avontuur met vrienden:
[Ik heb de Kwartssteen gevonden! 🔮]

— Professor Mira Kwarts
```

---

## Design Tokens

- **Primaire kleur:** #1a1a2e (donkerblauw)
- **Secundaire kleur:** #e94560 (rood-roze)
- **Accent kleur:** #f5c518 (goud)
- **Achtergrond:** #0f0f23 (donkerder blauw)
- **Lettertype:** 'Courier New', monospace (mysterieus/technisch)
- **Knoppen:** Goudkleurig met donkerblauwe tekst
- **Success berichten:** Groene rand + ✅
- **Fout berichten:** Rode rand + ❌
