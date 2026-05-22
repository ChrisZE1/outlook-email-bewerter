# E-Mail Bewerter – Outlook Add-in

KI-gestützter E-Mail-Bewerter direkt in Outlook 365.

---

## Schritt-für-Schritt Installation

### 1. GitHub-Konto erstellen (kostenlos)
→ https://github.com/signup (falls noch keins vorhanden)

### 2. Neues Repository anlegen
- Auf github.com oben rechts auf "+" klicken → "New repository"
- Name: `outlook-email-bewerter`
- Auf "Public" setzen (wichtig!)
- Auf "Create repository" klicken

### 3. Dateien hochladen
Alle 4 Dateien in das Repository hochladen:
- manifest.xml
- taskpane.html
- commands.html
- (Icon-Dateien, falls vorhanden)

Klicke auf "uploading an existing file" und ziehe die Dateien hinein.

### 4. GitHub Pages aktivieren
- Im Repository auf "Settings" klicken
- Links auf "Pages" klicken
- Unter "Branch" → "main" auswählen → "Save"
- Nach 1-2 Minuten ist die Seite live unter:
  `https://DEIN-USERNAME.github.io/outlook-email-bewerter/`

### 5. manifest.xml anpassen
Öffne manifest.xml und ersetze ALLE Vorkommen von:
  `DEIN-USERNAME`
mit deinem echten GitHub-Benutzernamen.

Dann die Datei wieder hochladen (bestehende überschreiben).

### 6. Add-in in Outlook installieren
**Outlook Web (outlook.com / Office 365 Web):**
1. Eine beliebige E-Mail öffnen
2. Oben rechts auf die drei Punkte "···" klicken
3. "Add-ins abrufen" oder "Get Add-ins" wählen
4. Links auf "Meine Add-ins" klicken
5. Ganz unten: "Benutzerdefiniertes Add-in hinzufügen" → "Aus Datei hinzufügen"
6. manifest.xml auswählen → Installieren

**Outlook Desktop (Windows):**
1. Auf "Datei" → "Add-Ins verwalten" klicken
2. Oder: In einer E-Mail auf "Add-Ins" in der Toolbar
3. "Meine Add-ins" → "Benutzerdefiniertes Add-in" → "Aus Datei"
4. manifest.xml auswählen

---

## Verwendung

1. Eine E-Mail in Outlook öffnen
2. In der Toolbar auf **"E-Mail bewerten"** klicken
3. Das Seitenpanel öffnet sich
4. Kriterien anpassen (einmalig, werden gespeichert)
5. Auf **"E-Mail jetzt bewerten"** klicken
6. KI gibt Bewertung 1-10 mit Begründung aus

---

## Tipps

- Kriterien werden lokal im Browser gespeichert und bleiben erhalten
- Der Verlauf zeigt die letzten 20 bewerteten E-Mails
- Beim Wechsel zur nächsten E-Mail einfach erneut auf "Bewerten" klicken
