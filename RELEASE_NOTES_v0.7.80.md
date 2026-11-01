# STREAMVANCE Studio v0.7.80 — Open Beta Update

Dieses Update verbessert den Umgang mit Twitch-Kontodaten und behebt Probleme beim erneuten Verbinden nach einer Live-Trennung.

## Neu und verbessert

- **Twitch-Konto entfernen:** Nach Bestätigung werden die gespeicherte Twitch-Anmeldung und die von STREAMVANCE verwaltete lokale Twitch-Event-History bereinigt.
- **Live trennen ohne Datenverlust:** Die Live-Verbindung wird beendet, während das Twitch-Konto und seine Event-History für eine spätere Wiederverbindung erhalten bleiben.
- **Live erneut verbinden:** Eine gespeicherte, gültige Twitch-Autorisierung kann für die erneute Live-Verbindung genutzt werden, ohne das Konto vorher entfernen und neu autorisieren zu müssen.
- **Wiederherstellung des Verbindungsstatus:** Die Twitch-Oberfläche bleibt nach dem Trennen nicht länger im Zustand „Wird wiederhergestellt …“ hängen. Der Reconnect-Button wird wieder verfügbar.
- **Stabilität:** Verbesserter Schutz vor doppelten Verbindungsversuchen, sicherere Wiederherstellung der Kanalzuordnung und verbesserte Behandlung unterbrochener Löschvorgänge.

## Unverändert

- Projekte, Szenen, Widgets und Automationskonfigurationen bleiben beim Entfernen eines Twitch-Kontos erhalten.
- Andere Plattformdaten werden von der Twitch-Kontolöschung nicht erfasst.
- Twitch ist weiterhin die unterstützte Plattform der Open Beta; YouTube bleibt „In Vorbereitung“.

## Qualitätssicherung

- 31 gezielte Twitch-Tests erfolgreich.
- Vollständige Release-Testsuite und JavaScript-Syntaxprüfung erfolgreich.
- Lokaler Windows-/Twitch-Funktionstest durch den Entwickler bestätigt, einschließlich Live-Trennung, Wiederverbindung, Kontolöschung und erneuter Anmeldung.

**Hinweis:** Die Bereinigung betrifft die von STREAMVANCE verwalteten lokalen Daten. Eine sichere physische Überschreibung freier Festplattenbereiche, externer Backups oder eigenständiger Exporte ist damit nicht zugesichert.
