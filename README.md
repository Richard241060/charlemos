# Charlemos

Kleine Web-App zum Spanischüben mit Claude: sprechen, hören, schreiben.

- Spracheingabe über das Mikrofon (Spracherkennung des Browsers, Spanisch oder Deutsch)
- Antworten von Claude auf Spanisch, mit deutscher Übersetzung und Korrektur
- Vorlesen mit spanischer Stimme des Geräts, einstellbares Tempo
- Gesprächsmodus: nach jeder Antwort hört die App wieder zu
- Lehrerin im Gespräch: plaudern, Kennenlernen (Profil), Lektionen aus einem Kurspaket,
  Erklären aus sieben Blickwinkeln, Vokabeln abfragen, Lückentexte – der Lernende bestimmt,
  Claude macht Vorschläge
- Wiederholungsplanung nach FSRS-4.5 (Übertragung von Poe V11 `fsrs.py`)
- Deutsche und spanische Stimme je nach Satzteil; Sprachanteil richtet sich nach dem Niveau

## Nutzung

1. Seite im Handybrowser öffnen (Chrome auf Android, Safari auf dem iPhone).
2. Über das Zahnrad den Anthropic-API-Schlüssel eintragen. Er wird nur im Browser
   dieses Geräts gespeichert (localStorage) und steht nirgends im Code.
3. Über „Zum Startbildschirm hinzufügen" als App ablegen.

Die App ruft die Claude-API direkt aus dem Browser auf
(`anthropic-dangerous-direct-browser-access`). Abgerechnet wird über die
Console-Organisation, zu der der Schlüssel gehört.

Gehostet über GitHub Pages, keine Build-Schritte: `index.html`,
`manifest.webmanifest` und die Icons.
