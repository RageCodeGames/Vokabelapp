# VokabelMaster Installation 🚀

## Schritt 1: Icons generieren

1. Öffne `icon-generator.html` im Browser
2. Klicke auf "⬇️ icon-192.png" und speichere die Datei
3. Klicke auf "⬇️ icon-512.png" und speichere die Datei

## Schritt 2: Dateien zu GitHub hochladen

Lade alle **5 Dateien** ins Repository hoch:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png` (generiert aus Schritt 1)
- `icon-512.png` (generiert aus Schritt 1)

## Schritt 3: GitHub Pages aktivieren

1. Gehe zu **Settings** → **Pages**
2. Wähle **Branch: main** → **/ (root)**
3. Klicke **Save**
4. Warte 1-2 Minuten

Die App ist dann erreichbar unter:
`https://dein-name.github.io/repository-name`

## Schritt 4: Als App installieren

### iOS (Safari):
1. Öffne die URL in Safari
2. Tippe auf das **Teilen-Icon** (Quadrat mit Pfeil)
3. Scrolle runter zu **"Zum Home-Bildschirm"**
4. Tippe **Hinzufügen**
5. ✅ VokabelMaster erscheint als App auf deinem Homescreen!

### Android (Chrome):
1. Öffne die URL in Chrome
2. Tippe auf das **⋮ Menü** (drei Punkte)
3. Wähle **"App installieren"** oder **"Zum Startbildschirm hinzufügen"**
4. ✅ VokabelMaster ist jetzt als App installiert!

### Desktop (Chrome/Edge):
1. Öffne die URL im Browser
2. Klicke auf das **⊕ Icon** in der Adressleiste
3. Oder: **⋮ Menü** → **App installieren**
4. ✅ VokabelMaster läuft jetzt als Desktop-App!

---

## Troubleshooting

**"App installieren" wird nicht angezeigt:**
- Stelle sicher dass alle 5 Dateien hochgeladen sind
- Prüfe ob GitHub Pages aktiv ist (grüner Haken bei Settings → Pages)
- Warte 2-3 Minuten nach dem Upload
- Leere den Browser-Cache (Strg+Shift+R / Cmd+Shift+R)
- iOS Safari braucht HTTPS (GitHub Pages nutzt automatisch HTTPS ✓)

**Icons werden nicht angezeigt:**
- Prüfe dass `icon-192.png` und `icon-512.png` im Root-Verzeichnis liegen
- Die Dateinamen müssen exakt so heißen (kleingeschrieben, mit Bindestrich)
- Nach Upload: Cache leeren und neu installieren

---

🎉 **Fertig!** Die App funktioniert jetzt offline und speichert alle Vokabeln lokal.
