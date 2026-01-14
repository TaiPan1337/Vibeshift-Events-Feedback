# Richtlinien für Issues

Eine gute Issue-Beschreibung spart Zeit und hilft dem Entwickler, das Problem schnell zu verstehen und zu beheben. Diese Anleitung zeigt, welche Informationen wichtig sind.

## Bug Reports

### Pflichtangaben

**Gerät & System**
- Gerät: z.B. iPhone 14 Pro, MacBook Air M2, iPad Pro 11"
- Betriebssystem: z.B. iOS 17.2, macOS 14.1
- App-Version: z.B. 1.2.3 (Build 456)

**Reproduktion**
1. Was hast du gemacht? (Schritt für Schritt)
2. Was hast du erwartet?
3. Was ist stattdessen passiert?

**Beispiel:**
```
1. Notiz mit Bild erstellt
2. Synchronisation gestartet
3. Erwartung: Bild wird auf allen Geräten angezeigt
4. Tatsächlich: Bild fehlt auf iPad
```

### Hilfreich

- **Screenshot/Video**: Zeigt das Problem oft klarer als Worte
- **Fehler-Log**: Falls eine Fehlermeldung erscheint, kompletten Text kopieren
- **Häufigkeit**: Tritt immer auf? Manchmal? Nach bestimmten Aktionen?
- **Seit wann**: Nach Update? Seit Installation? Plötzlich?

## Feature Requests

### Beschreibe dein Ziel

- **Problem**: Welches Problem willst du lösen?
- **Use Case**: Wann und wie würdest du das Feature nutzen?
- **Beispiel**: Konkrete Situation aus deinem Alltag

**Nicht so hilfreich:**
> "Brauche eine bessere Suche"

**Besser:**
> "Bei 500+ Notizen finde ich alte Meeting-Notes nicht mehr. Ich müsste nach Schlagworten UND Datum filtern können, z.B. alle Notizen mit #meeting aus Q3 2024."

### Optional

- **Mockup/Skizze**: Wie könnte es aussehen?
- **Alternative**: Andere Apps, die es gut lösen?
- **Priorität**: Nice-to-have oder blockiert dich das?

## Allgemeine Tipps

✅ **Mach es:**
- Eine Issue pro Problem/Feature
- Aussagekräftiger Titel: "iOS: Bilder fehlen nach Sync" statt "Bug"
- Deutsches Datum: 13.01.2026

❌ **Vermeide:**
- Mehrere Probleme in einer Issue
- Vage Beschreibungen: "geht nicht", "ist langsam"
- Persönliche Angriffe - wir sind alle Menschen

## Template

```markdown
**Gerät**: 
**OS**: 
**App-Version**: 

**Schritte zur Reproduktion**:
1. 
2. 
3. 

**Erwartet**: 

**Tatsächlich**: 

**Screenshot**: [falls vorhanden]

**Zusätzliche Info**: 
```

---

*Danke, dass du hilfst, LastNotes besser zu machen!*
