Höhenmesser – GPS Altitude Tracker

Eine einfache, mobile Progressive Web App (PWA) zur Echtzeiterfassung deiner absoluten Höhe via GPS.

## Features

- **Absolute Höhe in Metern** – GPS-Altitude (WGS84) mit Echtzeit-Updates
- **Trendanzeige** – Visueller Pfeil zeigt, ob du steigst oder fällst
- **Min / Max** – Extremwerte der aktuellen Messsitzung
- **Höhendelta** – Änderung zum ersten Messpunkt
- **GPS-Genauigkeit** – Angabe des Höhenfehlers in Metern (±)
- **Sparkline-Verlauf** – Grafisches Diagramm der letzten 60 Messpunkte
- **Koordinaten & Uhrzeit** – Aktuelle Position und Zeitstempel
- **Offline fähig** – Funktioniert auch ohne Internet (nur GPS erforderlich)
- **Installierbar** – Als App auf dem Homescreen speicherbar

## Installation auf Android

1. `hoehenmesser.html` herunterladen
2. In Chrome öffnen
3. Chrome-Menü (⋮) → „Zum Startbildschirm hinzufügen"
4. App startet fullscreen auf deinem Homescreen

## Bedienung

App startet, fordert GPS-Berechtigung an. Nach Erlaubnis läuft die Messung live. Button unten resettet die aktuelle Sitzung.

## GPS-Genauigkeit

Typisch ±5–30 Meter – gut für Bergwanderungen, weniger für Präzisionsmessungen.

## Lizenz

Frei – kein Copyright.

**Autor:** Alois Auer, Mai 2026
Kopiere das jetzt in eine neue Datei README

Die Datei hoehenmesser_v2.html ist bereit zum Download.
So auf Android installieren:

Datei auf das Gerät übertragen (USB, Google Drive, o.ä.)
In Chrome öffnen → Menü (⋮) → „Zum Startbildschirm hinzufügen"
Die App startet dann vollbild ohne Browser-Leiste

Neu in dieser Version:

Blauer FAB-Button unten rechts → wechselt zur runden Kompaktansicht
Rundes Overlay-Bubble zeigt nur die Höhe, ist frei verschiebbar per Drag
„Vollansicht"-Button unten links bringt die App zurück
Hintergrundsimulation zeigt wie es über Google Maps aussehen würde


Echtes „immer im Vordergrund" über anderen Apps (wie Google Maps) erfordert unter Android die Systemberechtigung SYSTEM_ALERT_WINDOW — das geht nur mit einer nativen APK, nicht mit einer HTML-Datei im Browser.
