# Datenschutzrichtlinie — Bâtonnage

*Stand: 12. Juni 2026*

Bâtonnage ist eine private iOS-App zur Lagerbewirtschaftung
von Weinkellern, Verkostungs-Notizen und Portfolio-Tracking.

## Welche Daten erfasst die App?

**Alle Daten bleiben ausschliesslich lokal auf deinem Gerät.**
Es findet keine Übertragung an unsere Server statt, weil
Bâtonnage keine eigenen Server betreibt.

Konkret:

- **Wein- und Flascheneinträge, Verkostungs-Notizen,
  Portfolio-Werte:** lokal auf dem Gerät via Apple SwiftData
  gespeichert.
- **Etikettenfotos:** werden nur lokal mit Apples Vision-
  Framework verarbeitet. Die Fotos verlassen das Gerät nicht
  und werden nach der Erkennung verworfen.
- **Lokale Benachrichtigungen:** werden ausschliesslich
  lokal vom iOS-System verwaltet.

## Optionale „Bring-Your-Own-Key"-Funktion (BYOK)

Wenn du in den Einstellungen einen eigenen API-Schlüssel
für einen externen KI-Dienst (z. B. OpenAI, Anthropic) oder
für einen Marktwert-Anbieter hinterlegst, werden bei
ausdrücklicher Verwendung dieser Funktionen Daten an den
jeweiligen Drittanbieter übertragen.

- Der API-Schlüssel wird **ausschliesslich in der iOS-Keychain
  auf deinem Gerät** gespeichert.
- Du entscheidest selbst, welche Anfragen du sendest.
- Es gelten die Datenschutzrichtlinien des jeweiligen
  Drittanbieters, dessen Schlüssel du nutzt.

## Berechtigungen

- **Kamera:** ausschliesslich zur Etiketten-Erkennung im
  Erkennen-Tab.
- **Mitteilungen:** ausschliesslich für lokale, optionale
  Reife-Erinnerungen.

Beide Berechtigungen sind optional und können jederzeit in
den iOS-Einstellungen widerrufen werden.

## Tracking, Analyse, Werbung

Bâtonnage verwendet **kein** Analyse-Tracking, **keine**
Werbedienste und **keine** Third-Party-SDKs zur
Datenerfassung.

## Kontakt

Bei Fragen zur Datenschutzrichtlinie:
**maurusfaessler89@gmail.com**
