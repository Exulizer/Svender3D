<div align="center">
  <img src="assets/images/logo_svender3d.png" alt="Svender3D Logo" width="200" height="auto" />
  <h1>Svender3D - 3D Printing Tools & Generators</h1>

  <p>
    <strong>Eine umfangreiche Web-Plattform mit professionellen Werkzeugen, Kalkulatoren und Generatoren für die 3D-Druck Community.</strong>
  </p>

  <p>
    <a href="https://www.svender3d.de">Live-Version ansehen</a> •
    <a href="https://layerspy.de/">LayerSpy</a> •
    <a href="https://meshdoc.svender3d.de/">MeshDoc</a>
  </p>
</div>

---

## 🌟 Übersicht & Features

Svender3D ist darauf ausgelegt, Enthusiasten und Profis dabei zu helfen, ihre 3D-Druck-Workflows zu optimieren, Firmware (Klipper/Marlin) exakt abzustimmen und Ressourcen wie Filament effizient zu verwalten.

### 🛠️ Kern-Werkzeuge
*   **Filament-Manager:** Ein intelligentes, hybrides Bestands-Tracking-Tool. 
    *   *Lokal & Schnell:* Komplett ohne Registrierung lokal im Browser (via `localStorage`) nutzbar.
    *   *Cloud-Sync:* Mit kostenlosem Account nahtlose Synchronisation über alle Geräte hinweg. Behalte Gewichte, Kosten und Spulenfarben zentral im Blick.
*   **LayerSpy:** Ein externes, spezialisiertes Analyse-Tool für detaillierte 3D-Druck-Parameter (https://layerspy.de/).
*   **MeshDoc:** Die ultimative Dokumentations-Suite für 3D-Modelle und Druck-Meshes (https://meshdoc.svender3d.de/).

### 🖨️ Generatoren & Kalkulatoren
*   **PID-Tuning Generator:** Schnelle Code-Generierung für Temperatur-Kalibrierung.
*   **Flow-Rate / Extrusions-Kalkulatoren:** Inklusive Sweetspot-Generator für den perfekten Materialfluss.
*   **Kostenrechner:** Exakte Kalkulation von Druckkosten basierend auf Filament-Verbrauch und Druckzeit.

### 📖 Blog & Tipps
Eine integrierte Wissensdatenbank mit detaillierten Anleitungen, Hardware-Tipps und Software-Updates rund um das Thema Klipper und 3D-Druck.

---

## 💻 Tech-Stack

Das Projekt ist als leichtgewichtige, hochperformante **Vanilla-Frontend-Architektur** (Single Page Application Ansatz) aufgebaut, die rasend schnell lädt und Suchmaschinen-optimiert (SEO) ist:

*   **Frontend:** HTML5, CSS3 (mit CSS Variables, Flexbox/Grid), Vanilla JavaScript (ES6+).
*   **Routing & SEO:** Eigenes Vanilla-JS basiertes Routing (`simple-router.js`) für blitzschnelle Seitenwechsel, kombiniert mit serverseitigen Fallbacks und dynamisch injiziertem `Schema.org` JSON-LD für optimales Google-Crawling.
*   **Backend / Auth / Database:** [Supabase](https://supabase.com/) (PostgreSQL, Row Level Security, JWT Authentication).
*   **UI / UX:** Moderne Design-Patterns, flüssige CSS-Swipe-Animationen (z.B. im Auth-Bereich), komplett responsiv gestaltet für Desktop, Tablet und Smartphone.

---

## 🚀 Lokale Installation & Entwicklung

Das Frontend benötigt keine komplizierten Build-Prozesse (wie Webpack oder Node.js) und kann in Sekunden lokal ausgeführt werden:

1.  **Repository klonen:**
    ```bash
    git clone https://github.com/DEIN-GITHUB-NAME/svender3d.de.git
    cd svender3d.de
    ```

2.  **Entwicklungsserver starten:**
    Da die App Vanilla JS Fetch-Requests nutzt, wird ein simpler lokaler Webserver benötigt, um CORS-Fehler (bei `file://` Aufrufen) zu vermeiden.
    *   *Mit Python:* `python -m http.server 8000`
    *   *Mit VS Code:* Nutze die Extension "Live Server" und klicke auf "Go Live"
    *   *Mit PHP:* `php -S localhost:8000`

3.  **App öffnen:** 
    Navigiere im Browser zu `http://localhost:8000`

> **Hinweis:** Für die vollständige Cloud-Funktionalität des Filament-Managers und das Login/Registrierungs-System wird eine aktive Supabase-Anbindung (`assets/js/supabase-client.min.js` & `api/`) vorausgesetzt. Ohne Datenbank-Verbindung läuft die App reibungslos im lokalen Fallback-Modus (`json/`-Ordner & `localStorage`)!

---

## 🤝 Kontakt & Community

Tritt der Community bei oder melde Fehler und Feature-Wünsche direkt über GitHub!

*   **Discord Server:** [Svender3D Community](https://discord.gg/3NGGNwAb5h)
*   **Impressum & Kontakt:** [www.svender3d.de/impressum.html](https://www.svender3d.de/impressum.html)

---
<div align="center">
  <em>Entwickelt mit Leidenschaft für die 3D-Druck Community.</em>
</div>
