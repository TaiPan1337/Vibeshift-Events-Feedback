# Richtlinien für GitHub Issues

Eine gute Issue-Beschreibung spart Zeit und hilft dem Entwickler, das Problem schnell zu verstehen und zu beheben. Diese Anleitung zeigt, welche Informationen wichtig sind.

## Bevor du eine Issue erstellst

- **Suche erst**: Schau, ob jemand das Problem bereits gemeldet hat
- **Labels nutzen**: Wähle passende Labels (bug, enhancement, question)
- **Templates**: Falls vorhanden, nutze die Issue-Templates des Repos

## Bug Reports 🐛

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

- **Screenshot/Video**: Drag & Drop direkt in die Issue
- **Code-Snippets**: Nutze Syntax-Highlighting mit ` ```swift ` für Code
- **Fehler-Log**: In Code-Block packen für bessere Lesbarkeit
- **Häufigkeit**: Tritt immer auf? Manchmal? Nach bestimmten Aktionen?
- **Seit wann**: Nach Update? Seit Installation? Plötzlich?
- **Verwandte Issues**: Verlinke mit #123 (Issue-Nummer)

### GitHub-Features nutzen

**Screenshots einfügen:**
- Einfach per Drag & Drop in den Editor ziehen
- Oder Copy & Paste aus Zwischenablage

**Code formatieren:**
```swift
// So wird Code lesbar
func example() {
    print("Nutze ```swift für Syntax-Highlighting")
}
```

**Logs einfügen:**
```
[2026-01-14 10:23:45] ERROR: Sync failed
[2026-01-14 10:23:46] TRACE: Connection timeout
```

## Feature Requests 💡

### Beschreibe dein Ziel

- **Problem**: Welches Problem willst du lösen?
- **Use Case**: Wann und wie würdest du das Feature nutzen?
- **Beispiel**: Konkrete Situation aus deinem Alltag

**Nicht so hilfreich:**
> "Brauche eine bessere Suche"

**Besser:**
> "Bei 500+ Notizen finde ich alte Meeting-Notes nicht mehr. Ich müsste nach Schlagworten UND Datum filtern können, z.B. alle Notizen mit #meeting aus Q3 2024."

### Optional

- **Mockup/Skizze**: Einfach als Bild hochladen
- **Alternative**: Andere Apps, die es gut lösen?
- **Priorität**: Nice-to-have oder blockiert dich das?
- **Bereit zu helfen?**: Würdest du einen PR (Pull Request) erstellen?

## GitHub-spezifische Tipps

### Titel formatieren

✅ **Gut:**
- `[iOS] Bilder fehlen nach Sync auf iPad`
- `[Feature] Erweiterte Suche mit Datums-Filter`
- `[macOS] App-Absturz beim Öffnen von PDFs`

❌ **Vermeide:**
- `Bug`
- `Hilfe!!!`
- `geht nicht`

### Markdown nutzen

```markdown
# Überschrift 1
## Überschrift 2

**Fett** und *kursiv*

- Liste
- mit Punkten

1. Nummerierte
2. Liste

`inline code` für Befehle

> Zitat oder wichtiger Hinweis

[Link](https://example.com)

@username erwähnen
#123 Issue verlinken
```

### Checklisten

Für Tasks oder Reproduktionsschritte:

```markdown
- [ ] Schritt 1 durchgeführt
- [x] Schritt 2 durchgeführt
- [ ] Problem tritt auf
```

### Screenshots kommentieren

Nutze Markierungen/Pfeile in Screenshots, um das Problem zu zeigen. GitHub zeigt Bilder direkt inline an.

### Labels vorschlagen

Falls du keine Labels setzen kannst, erwähne sie im Text:
> "Labels: bug, iOS, high-priority"

## Allgemeine Tipps

✅ **Mach es:**
- Eine Issue pro Problem/Feature
- Aussagekräftiger Titel mit Kontext
- Beschreibung in Markdown formatieren
- Verwandte Issues verlinken (#123)
- Bei Duplikaten: Issue schließen und auf Original verweisen

❌ **Vermeide:**
- Mehrere Probleme in einer Issue
- Vage Beschreibungen ohne Details
- "+1" Kommentare (nutze stattdessen 👍 Reaction)
- Off-Topic Diskussionen
- Persönliche Angriffe

## Nach dem Erstellen

- **Benachrichtigungen**: Du bekommst Updates per E-Mail
- **Diskussion**: Beantworte Rückfragen vom Entwickler
- **Updates**: Wenn du mehr Infos hast, ergänze sie
- **Schließen**: Wenn das Problem gelöst ist, kannst du die Issue schließen

## Bug Report Template

```markdown
## Beschreibung
[Kurze Zusammenfassung des Problems]

## Umgebung
- **Gerät**: 
- **OS**: 
- **App-Version**: 

## Schritte zur Reproduktion
1. 
2. 
3. 

## Erwartetes Verhalten
[Was sollte passieren?]

## Tatsächliches Verhalten
[Was passiert stattdessen?]

## Screenshots/Videos
[Falls vorhanden]

## Logs/Fehler
```
[Relevante Logs hier einfügen]
```

## Zusätzliche Informationen
- Häufigkeit: 
- Seit wann: 
- Verwandte Issues: 
```

## Feature Request Template

```markdown
## Problem
[Welches Problem möchtest du lösen?]

## Gewünschte Lösung
[Wie sollte das Feature funktionieren?]

## Use Case
[Wann und wie würdest du es nutzen?]

## Beispiel
[Konkrete Situation]

## Alternativen
[Andere Lösungen, die du in Betracht gezogen hast]

## Mockups
[Falls vorhanden]

## Priorität
[ ] Blockiert mich
[ ] Wichtig
[ ] Nice-to-have
```

---

**Hilfreiche Links:**
- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Issues Guide](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)

*Danke, dass du hilfst, das Projekt besser zu machen!*
