# Deep Playground

Deep Playground ist eine interaktive Visualisierung neuronaler Netzwerke, geschrieben in
TypeScript mit d3.js. Wir verwenden GitHub Issues für das Verfolgen neuer Anfragen und Fehler.
Ihr Feedback wird sehr geschätzt!

**Wenn Sie beitragen möchten, lesen Sie bitte die [Richtlinien für Beiträge](CONTRIBUTING.md).**

## Lokale Installation und Ausführung

Diese Anweisungen helfen Ihnen, die Anwendung auf Ihrem lokalen Computer zu installieren und auszuführen.

### Voraussetzungen

Bevor Sie beginnen, stellen Sie sicher, dass Sie Folgendes installiert haben:

1. **Node.js und npm**: Besuchen Sie [nodejs.org](https://nodejs.org/) und laden Sie die empfohlene Version herunter.
   - Um zu prüfen, ob Node.js installiert ist, öffnen Sie ein Terminal und geben Sie ein: `node -v`
   - Um zu prüfen, ob npm installiert ist, geben Sie ein: `npm -v`

2. **Git**: Besuchen Sie [git-scm.com](https://git-scm.com/downloads) und laden Sie die entsprechende Version für Ihr Betriebssystem herunter.
   - Um zu prüfen, ob Git installiert ist, öffnen Sie ein Terminal und geben Sie ein: `git --version`

### Installationsschritte

1. **Klonen Sie das Repository**:
   Öffnen Sie ein Terminal und führen Sie folgenden Befehl aus:
   ```
   git clone https://ngoldbla/tf-playground-de/playground.git tf-playground-de
   cd tf-playground-de

   ```

2. **Installieren Sie die Abhängigkeiten**:
   ```
   npm install
   ```

3. **Kompilieren Sie die Anwendung**:
   ```
   npm run build
   ```

4. **Starten Sie den lokalen Server**:
   ```
   npm run serve
   ```

   Nach diesem Befehl sollte sich automatisch ein Browser-Fenster öffnen, das die Anwendung anzeigt.
   Falls nicht, öffnen Sie einen Browser und gehen Sie zu: [http://localhost:8080/](http://localhost:8080/)

### Entwicklung mit Live-Aktualisierung

Wenn Sie an der Anwendung arbeiten und Änderungen vornehmen möchten, können Sie den Entwicklungsmodus mit automatischer Aktualisierung verwenden:

```
npm run serve-watch
```

Dieser Befehl startet einen HTTP-Server und kompiliert die TypeScript-, HTML- und CSS-Dateien automatisch neu, wann immer Sie Änderungen vornehmen.

### Fehlerbehebung

- **Problem**: "npm command not found" oder ähnliche Fehler
  **Lösung**: Stellen Sie sicher, dass Node.js und npm korrekt installiert sind und zur Umgebungsvariablen PATH hinzugefügt wurden.

- **Problem**: Kann das Repository nicht klonen
  **Lösung**: Stellen Sie sicher, dass Git korrekt installiert ist und Sie eine Internetverbindung haben.

- **Problem**: Fehler beim Kompilieren oder Starten des Servers
  **Lösung**: Überprüfen Sie die Node.js-Version (sollte 12.x oder höher sein) und stellen Sie sicher, dass alle Abhängigkeiten korrekt installiert wurden.

## Für Eigentümer
Um in die Produktion zu übertragen: `git subtree push --prefix dist origin gh-pages`.

## Deutsche Version

Diese deutsche Übersetzung wurde für "Die Entwicklung und Grundlagen der KI" (Dr. Dylan Goldblatt, Kennesaw State University) erstellt.

Dies ist kein offizielles Google-Produkt.
