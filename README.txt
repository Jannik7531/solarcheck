SolarCheck – iPhone-Web-App (PWA)

INHALT
index.html, manifest.webmanifest, sw.js, icon.svg

INSTALLATION
1. Lade alle Dateien unverändert auf einen HTTPS-Webspace (z.B. GitHub Pages, Netlify oder einen eigenen Webserver mit HTTPS).
2. Öffne die HTTPS-Adresse im Safari auf deinem iPhone.
3. Wähle Teilen > Zum Home-Bildschirm.
4. Starte SolarCheck über das Symbol. Nach dem ersten Laden ist die Oberfläche offline verfügbar.

WICHTIGE EINSCHRÄNKUNGEN
- iOS stellt Webseiten keinen regulären Umgebungslichtsensor zur Verfügung. Der Kamera-Index basiert auf Pixelhelligkeit und wird durch automatische Belichtung beeinflusst. Er ist NICHT in Lux oder W/m² kalibriert.
- Der Kompass kann auf metallischen PV-Gestellen stark abweichen; Neigungsberechnung ist ein Näherungswert und hängt von der Gerätehaltung ab.
- Eine Spannung allein sagt wenig über die Leistung oder den Zustand eines Solarmoduls aus. Es wird ausdrücklich KEIN vermeintlicher Prozent-Wirkungsgrad berechnet.
- Standort, Kamera und Bewegungssensoren benötigen Freigaben. Ein sicherer Kontext (HTTPS) ist nötig.
- Die Leerlaufspannung eines PV-Moduls kann höher als die Nennbetriebsspannung sein. Nur mit geeignetem Multimeter und sicheren Leitungen messen.
- Standard-Koordinaten 47.66 N, 9.31 E (Bodenseeregion) sind keine automatische Standorterkennung.

Diese Version ist ein erster funktionaler Prototyp. Keine native iOS-App und keine automatische Messung elektrischer Spannung.
