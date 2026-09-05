<div align="center">
  <img src="https://www.svender3d.de/assets/images/logo_svender3d.svg" alt="Svender3D Logo" width="200" />
  <h1>Svender3D - 3D Printing Tools & Generators</h1>

  <p>
    <strong>Eine umfangreiche Web-Plattform mit professionellen Werkzeugen, Kalkulatoren und Generatoren für die 3D-Druck Community.</strong>
  </p>

  <p>
    <a href="https://www.svender3d.de">Live-Version ansehen</a> •
    <a href="https://layerspy.de/">LayerSpy</a> •
    <a href="https://www.meshdoc.de/">MeshDoc</a>
  </p>
</div>

---

## 🌟 Übersicht & Features

Svender3D ist darauf ausgelegt, Enthusiasten und Profis dabei zu helfen, ihre 3D-Druck-Workflows zu optimieren, Firmware (Klipper/Marlin) exakt abzustimmen und Ressourcen wie Filament effizient zu verwalten.

### 🛠️ Kern-Werkzeuge
*   **Filament-Manager:** Ein intelligentes Bestands-Tracking-Tool. 
    *   *Lokal & Schnell:* Komplett ohne Registrierung lokal im Browser (via `localStorage`) nutzbar.
    *   *Cloud-Sync:* Mit kostenlosem Account nahtlose Synchronisation über alle Geräte hinweg. Behalte Gewichte, Kosten und Spulenfarben zentral im Blick.
*   **LayerSpy:** Ein externes, spezialisiertes Analyse-Tool für detaillierte 3D-Druck-Parameter (https://layerspy.de/).
*   **MeshDoc:** Die ultimative Dokumentations-Suite für 3D-Modelle und Druck-Meshes (https://www.meshdoc.de/).

### 🖨️ Generatoren & Kalkulatoren
*   **PID-Tuning Generator:** Schnelle Code-Generierung für präzise Temperatur-Kalibrierung von Hotend und Druckbett.
*   **Flow-Rate / Sweetspot-Generator:** Finde den perfekten Materialfluss und extrudiere exakt die richtige Menge Filament.
*   **Kostenrechner:** Berechne auf den Cent genau, was dein gedrucktes Bauteil inklusive Material, Strom und Verschleiß kostet.
*   **XYZ-Steps & Belt-Tension:** Spezifische Tools zur mechanischen Kalibrierung deiner Drucker-Achsen.

### 📖 Blog & Tipps
Eine integrierte Wissensdatenbank mit detaillierten Anleitungen, Hardware-Tipps und Software-Updates rund um das Thema Klipper und 3D-Druck. Alle Artikel sind eng mit den jeweiligen Generatoren verknüpft (Silo-Struktur).

---

## ⚡ Performance & Architektur (Tech-Stack)

Das Projekt zeichnet sich durch extreme Geschwindigkeit und eine **Vanilla-Frontend-Architektur** aus. Es wurde bewusst auf große Frameworks wie React oder Vue verzichtet, um maximale Performance und sofortige Ladezeiten zu garantieren:

*   **Frontend:** Pures HTML5, CSS3 (mit CSS Variables, Flexbox/Grid) und Vanilla JavaScript (ES6+).
*   **Custom Routing:** Ein komplett eigenentwickeltes Vanilla-JS Routing-System (`simple-router.js`) sorgt für blitzschnelle, unterbrechungsfreie Seitenwechsel ohne lästige Reloads.
*   **Modern UX:** Native CSS-Animationen (z.B. Swipe-Layouts beim Login), dynamische Content-Silos und ein Responsive Design, das auf dem Smartphone genauso gut funktioniert wie am Desktop.
*   **Backend / API:** Serverseitige Prozesse, Authentifizierung und Datenbank-Synchronisation werden über ein performantes Custom PHP-Backend abgewickelt.
*   **SEO:** Die Seite ist stark suchmaschinenoptimiert, unter anderem durch dynamisch injiziertes `Schema.org` JSON-LD und sauberes Tagging für Google-Crawling.

---

## 🎯 Die Vision (Warum Svender3D?)

Die Welt des 3D-Drucks (speziell mit Klipper) kann komplex und unübersichtlich sein. Svender3D wurde mit dem Ziel geschaffen, **alles an einem Ort zu bündeln**: Statt fünf verschiedene Excel-Tabellen für Druckkosten, Flow-Berechnung und Filament-Management nutzen zu müssen, bietet Svender3D eine saubere, moderne und zentralisierte Web-App. Es ist ein Projekt "von der Community, für die Community".

---

## 🤝 Support, Fehler & Feedback

Da dieses Tool ständig weiterentwickelt wird, ist Feedback extrem wertvoll! Wenn dir ein Fehler auffällt oder du eine Idee für einen neuen Generator hast:

*   **Fehler melden:** Erstelle hier auf GitHub ein Issue (über den Reiter "Issues" oben), um Fehler oder Ideen mitzuteilen.
*   **Discord Server:** Tritt der [Svender3D Community auf Discord](https://discord.gg/3NGGNwAb5h) bei, um dich direkt auszutauschen.
*   **Kontakt:** [www.svender3d.de/impressum.html](https://www.svender3d.de/impressum.html)

---

## ⚖️ Lizenz & Copyright

**Copyright © 2026 Svender3D (Sven Enders). Alle Rechte vorbehalten.**

Der Quellcode in diesem Repository dient ausschließlich zu Anschauungs- und Lernzwecken. Das Kopieren, Verändern, Verbreiten oder die Nutzung des Codes (auch in Teilen) für eigene private oder kommerzielle Projekte ist **ohne ausdrückliche schriftliche Genehmigung untersagt**. 

Weitere Details findest du in der [LICENSE](LICENSE) Datei.

---
<div align="center">
  <em>Entwickelt mit Leidenschaft für die 3D-Druck Community.</em>
</div>
