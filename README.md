# Sprachnotiz – Downloads

Eine private macOS-App für lokale Audio-Transkription und Zusammenfassungen mit einer Liquid-Glass-Lesekarte.

**Dieses öffentliche Repository enthält ausschließlich fertige App-Downloads, Anleitung und Update-Informationen. Der Quellcode wird hier nicht veröffentlicht.** Die von GitHub automatisch angebotenen „Source code“-Archive enthalten nur die Dateien dieses Download-Repositories.

## Installation

1. Die [DMG für Version 0.8.0 herunterladen](https://github.com/Nichttobi12/sprachnotiz-releases/releases/download/v0.8.0/Sprachnotiz-0.8.0.dmg) und öffnen.
2. `Sprachnotiz.app` im Installationsfenster auf `Programme` ziehen und anschließend aus dem Programme-Ordner starten.
3. Bei der Ersteinrichtung den Audioordner auswählen und entscheiden, ob die App beim Anmelden starten soll. Beides kann auch später in den Einstellungen geändert werden.
4. Neue Audiodateien im ausgewählten Ordner werden automatisch erkannt. Bestehende Dateien werden beim Start übersprungen.

Bei Updates bleiben bestehende Ordner und Einstellungen erhalten; die Ersteinrichtung erscheint nur bei einer neuen Installation. Die zusätzliche ZIP in den Releases dient dem eingebauten Update-Kanal.

Voraussetzungen: Apple-Silicon-Mac und macOS 26 oder neuer. Getestet auf macOS 27.0.1. Lokale Zusammenfassungen erfordern ein verfügbares Apple-Intelligence-Sprachmodell. Die App führt keinen Cloud-Fallback durch.

Die App bleibt als private Version ad hoc signiert und ist nicht Apple-notarisiert. macOS kann den ersten Start nach dem Download blockieren. [Apples Hinweise zum Öffnen privater Apps](https://support.apple.com/de-de/102445).

## Kostenlose Beta und Datenschutz

Ab Version 0.8 ist eine erste Online-Freigabe erforderlich; danach kann die App bis zu sieben Tage offline genutzt werden. Spätestens nach sieben Tagen muss die Freigabe erfolgreich erneuert werden. Andernfalls pausieren neue Transkriptionen und Kurzfassungen. Vorhandene Texte bleiben lesbar und Dateien bleiben erhalten. Die Beta kann später geschlossen oder eine neuere Version erforderlich werden. Es gibt derzeit keine Begrenzung der Anzahl oder Länge von Audios durch die Beta-Lizenz.

Die App lädt nur die digital signierte öffentliche Freigabedatei von GitHub. Audios, Transkripte, Dateinamen und Gerätekennungen werden dabei nicht übertragen. GitHub sieht übliche Verbindungsdaten wie die IP-Adresse. Die Freigabe wird lokal im macOS-Schlüsselbund gespeichert. Spracherkennung und Zusammenfassungen laufen auf dem Mac; fehlende Modelle lädt macOS von Apple.

Der Feedback-Knopf öffnet ein öffentliches GitHub-Formular, für das ein GitHub-Konto erforderlich ist. Es werden keine Anhänge oder Diagnosedaten automatisch ergänzt und kein Beitrag automatisch abgeschickt. Bitte keine Audios, Transkripte oder persönlichen Daten einfügen.

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
