# Sprachnotiz – Downloads

Eine private macOS-App für lokale Audio-Transkription und Zusammenfassungen mit einer Liquid-Glass-Lesekarte.

**Dieses öffentliche Repository enthält ausschließlich fertige App-Downloads, Anleitung und Update-Informationen. Der Quellcode wird hier nicht veröffentlicht.** Die von GitHub automatisch angebotenen „Source code“-Archive enthalten nur die Dateien dieses Download-Repositories.

## Installation

1. Die ZIP-Datei unter [Releases](https://github.com/Nichttobi12/sprachnotiz-releases/releases/latest) herunterladen und entpacken.
2. `Sprachnotiz.app` nach `Programme` ziehen und öffnen.
3. Oben in der Menüleiste das Wellenform-Symbol öffnen. Unter **Einstellungen → Audioquellen** den eigenen Downloads-Ordner oder weitere Audioordner hinzufügen.
4. Neue Audiodateien in diesen Ordnern werden automatisch erkannt. Bestehende Dateien werden beim Start übersprungen.

Voraussetzungen: Apple-Silicon-Mac und macOS 26 oder neuer. Getestet auf macOS 27.0.1. Lokale Zusammenfassungen erfordern ein verfügbares Apple-Intelligence-Sprachmodell. Die App führt keinen Cloud-Fallback durch.

Die App bleibt als private Version ad hoc signiert und ist nicht Apple-notarisiert. macOS kann den ersten Start nach dem Download blockieren. [Apples Hinweise zum Öffnen privater Apps](https://support.apple.com/de-de/102445).

## Bedienung

- Wellenform-Symbol: Pause, Audiodateien öffnen, letzte Karte, letzte Texte und Einstellungen.
- Lesekarte: Volltext/Kurzfassung, Funkeln-Taste zum Zusammenfassen, Vergrößern, Kopieren und Schließen.
- Einstellungen: mehrere Audioordner, Dateifilter, Kartenbreite, Schriftgröße, Position, Anmeldestart und optionales Aufräumen.
- Audios können auch manuell geöffnet oder in die Ablagefläche des Menüfensters bzw. in das Fenster „Letzte Texte“ gezogen werden.
- Beim optionalen Aufräumen wird nur die erfolgreich transkribierte, unveränderte Datei zur geschlossenen Karte aus einem überwachten Ordner in den Papierkorb verschoben. Manuell geöffnete oder abgelegte Dateien bleiben erhalten.

Transkripte und Kurzfassungen liegen nur bis zum Beenden der App im Arbeitsspeicher. Die Ordnerberechtigungen werden auf jedem Mac separat eingerichtet. Audioinhalte werden nicht an GitHub übermittelt. Fehlende Sprachmodelle lädt macOS von Apple.

## Updates

Ab Version 0.6 ist Sparkle integriert. Unter **Einstellungen → Updates** lassen sich automatische Prüfungen einstellen oder Updates manuell suchen. Update-Dateien und der Update-Feed werden kryptografisch signiert. Eine neue Version wird zur Installation angeboten.

Die frühere ZIP-Version ohne Update-Funktion muss einmal manuell durch die neue App ersetzt werden. Einstellungen und ausgewählte Ordner werden beim Update übernommen.

## Drittanbieter

Die Update-Funktion verwendet [Sparkle](https://sparkle-project.org/). Der zugehörige Lizenztext liegt in der App.
