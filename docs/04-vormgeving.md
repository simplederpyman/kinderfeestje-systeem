# 🎨 Vormgeving — De Geheime Code van Professor Kwarts

## Algemene Stijl
**Mysterieus Avontuur** — Donker, spannend, maar niet eng. Denk aan een geheim laboratorium vol kristallen en codes.

## Kleurenpalet

| Naam | Hex | Gebruik |
|------|-----|---------|
| Diepblauw | #1a1a2e | Achtergrond |
| Nachtblauw | #16213e | Secties, kaarten |
| Mysteriepaars | #0f3460 | Accenten, randen |
| Kristalrood | #e94560 | Foutmeldingen, waarschuwingen |
| Kwartsgoud | #f5c518 | Succes, codes, accent |
| Sneeuwwit | #eaeaea | Tekst |
| IJzigblauw | #94b3fd | Hints, subtiel accent |

## Lettertypes

| Gebruik | Lettertype | Stijl |
|---------|-----------|-------|
| Titels | 'Courier New', monospace | Vet, geheimzinnig |
| Lopende tekst | 'Segoe UI', Tahoma, sans-serif | Gewoon, leesbaar |
| Codes | 'Courier New', monospace | Goudkleurig, groot |
| Hintknop | 'Segoe UI' | Cursief, subtiel |

## Iconen & Symbolen

| Symbool | Gebruik |
|---------|---------|
| 🔮 | Logo, titels, certificaat |
| ✅ | Juiste code feedback |
| ❌ | Foutieve code feedback |
| 🔍 | Zoek-opdrachten |
| ⭐ | Beloningen, certificaten |
| 🔑 | Sleutelmomenten |
| 📜 | Brieven, documenten |
| 🗝️ | Sloten, deuren |
| 💎 | Kwartsteen |

## Printables Stijl

| Element | Stijl |
|---------|-------|
| Achtergrond | Crèmekleurig (#f5f0e1) |
| Randen | Goudkleurig, dubbele lijn |
| Koppen | Donkerblauw, schreeflettertype |
| Lichaamstekst | Zwart, schreefloos |
| Cijfercodes | Extra groot, goudkleurig |
| Hintkaarten | Lichtgeel achtergrond |
| Certificaten | Donkerblauw + goud |

## Website Design

### Achtergrond
- Donkerblauwe gradient (#1a1a2e → #0f0f23)
- Subtiel sterrenpatroon (CSS sterren of SVG)
- Vage kristalvormen als decoratie

### Knoppen
```css
.btn-primary {
  background: #f5c518;
  color: #1a1a2e;
  border: 2px solid #f5c518;
  font-family: 'Courier New', monospace;
  font-weight: bold;
  padding: 12px 24px;
  border-radius: 4px;
}

.btn-primary:hover {
  background: #ffd700;
  box-shadow: 0 0 15px rgba(245, 197, 24, 0.5);
}
```

### Code-invoerveld
```css
.code-input {
  background: #16213e;
  border: 2px solid #f5c518;
  color: #f5c518;
  font-family: 'Courier New', monospace;
  font-size: 24px;
  text-align: center;
  letter-spacing: 4px;
  padding: 15px;
  border-radius: 8px;
}
```

### Feedback-berichten
```css
.success {
  border-left: 4px solid #4ecca3;
  background: rgba(78, 204, 163, 0.1);
}

.error {
  border-left: 4px solid #e94560;
  background: rgba(233, 69, 96, 0.1);
}

.hint {
  border-left: 4px solid #94b3fd;
  background: rgba(148, 179, 253, 0.1);
}
```

### Animaties
- Confetti bij eindoverwinning (canvas confetti library)
- Subtiele gloed-effect op knoppen
- Glint-effect op Kwartsteen (CSS shimmer)
- Fade-in voor nieuwe berichten

## Consistentie

### Print ↔ Website
- Zelfde kleurenpalet
- Zelfde icoontjes/symbolen
- Zelfde lettertype voor codes
- Zelfde tone-of-voice

### Sfeer
- Spannend maar niet eng
- Avontuurlijk maar veilig
- Mysterieus maar duidelijk
- Feestelijk maar niet kinderachtig

---

_Thema: Mysterie & Avontuur — De Geheime Code van Professor Kwarts_
