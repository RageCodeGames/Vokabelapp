# 🔄 App aktualisieren - So geht's

## Problem: App zeigt alte Version

PWAs (Progressive Web Apps) cachen aggressiv. Hier die Schritte:

---

## ✅ Methode 1: Komplette Neuinstallation (funktioniert immer)

### iOS:
1. **App vom Homescreen löschen:**
   - Lange auf App-Icon drücken → "App entfernen" → "Vom Home-Bildschirm entfernen"
2. **Safari öffnen:**
   - Einstellungen → Safari → "Verlauf und Website-Daten löschen"
3. **Neu installieren:**
   - Safari → deine-url.github.io öffnen
   - Teilen-Icon → "Zum Home-Bildschirm"

### Android:
1. **App deinstallieren:**
   - Lange auf App-Icon → "Deinstallieren"
2. **Chrome-Daten löschen:**
   - Chrome → ⋮ Menü → Verlauf → Browserdaten löschen
   - "Bilder und Dateien im Cache" ✓
   - "Gesamte Zeit" → Daten löschen
3. **Neu installieren:**
   - Chrome → deine-url.github.io öffnen
   - ⋮ Menü → "App installieren"

---

## 🚀 Methode 2: Force Reload (schneller, klappt manchmal)

### iOS Safari:
1. App öffnen
2. URL-Leiste antippen
3. Reload-Symbol **lange gedrückt halten** (2-3 Sekunden)
4. "Website ohne Inhaltsblocker neu laden" wählen

### Android Chrome:
1. App öffnen (oder in Chrome)
2. ⋮ Menü → Einstellungen
3. "Website-Einstellungen" → deine URL finden
4. "Speicher löschen" + "Cache leeren"
5. Zurück und Seite neu laden

---

## 📝 Nach Upload auf GitHub:

**Warte 2-3 Minuten** bevor du aktualisierst!
- GitHub Pages braucht Zeit zum Deployen
- Prüfe ob die Datei online ist: öffne `https://dein-name.github.io/repo/index.html` im **Desktop-Browser**
- Siehst du die neue Version im Code? (Rechtsklick → Seitenquelltext anzeigen)
- Dann erst auf Handy aktualisieren

---

## 🔧 Was ich gerade gefixt habe:

1. **sw.js** - Cache-Version auf `v3` erhöht → alter Cache wird gelöscht
2. **index.html** - Auto-Reload eingebaut → lädt automatisch neu wenn Update verfügbar

**Lade beide Dateien auf GitHub hoch:**
- `sw.js` (Cache v3)
- `index.html` (mit Auto-Update)

Dann Methode 1 oder 2 oben durchführen.

---

## ⚡ Für die Zukunft:

Jedes Mal wenn du `index.html` änderst:
1. Auch in `sw.js` die Version hochzählen: `v3` → `v4` → `v5` ...
2. Beide Dateien hochladen
3. 2-3 Minuten warten
4. Dann erst auf Handy testen

So erzwingst du dass der Cache aktualisiert wird!
