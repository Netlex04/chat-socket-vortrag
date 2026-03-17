# Präsentationsmodus (HTML-Slides)

Eine einfache HTML-basierte Präsentation, die direkt aus dem Browser läuft. Ideal für Live-Demos oder Vorträge ohne zusätzliche Tools.

## 🚀 Schnell starten (empfohlen)

### 1) Live Server (VS Code)

1. Öffne den Ordner `presentation` in VS Code.
2. Installiere die Erweiterung **Live Server** (falls noch nicht installiert).
3. Rechtsklicke auf `index.html` → **"Open with Live Server"**.

> ✅ Vorteil: Automatisches Neuladen bei Änderungen.

## 🖥️ Alternative: Browser direkt starten

Du kannst die Präsentation auch direkt im Browser starten (macht den Vollbildmodus leichter erreichbar).

### macOS

```bash
/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --app=http://127.0.0.1:5500/index.html
```

### Windows

```bash
chrome --app=http://127.0.0.1:5500/index.html
```

## 🧪 Alternative: Schneller Webserver (Python)

Falls du keinen Live-Server nutzen möchtest, kannst du einen minimalen HTTP-Server starten:

```bash
cd presentation
python3 -m http.server 5500
```

Dann im Browser öffnen:

`http://127.0.0.1:5500/index.html`

---

## 📝 Inhalt

- `index.html`: Präsentation (Scroll-Slider mit Keyboard-Navigation)
- `*.png`: Bilder für die Folien

Viel Erfolg bei der Präsentation! 🎉
