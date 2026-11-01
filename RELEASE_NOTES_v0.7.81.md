# STREAMVANCE Studio v0.7.81 — Open Beta Updater Hotfix

Mit v0.7.81 wird die Übergabe an den Windows-Installer verbessert. In vorherigen Versionen konnte beim Start des Updates die Fehlermeldung `Error invoking remote method 'streamvance-update-install': reply was never sent` auftreten.

## Behoben und verbessert

- Installer-Start über ein einseitiges Electron-IPC-Ereignis statt eines auf Antwort wartenden Aufrufs.
- STREAMVANCE beendet sich erst, wenn der Installer erfolgreich gestartet wurde.
- Ein fehlgeschlagener Installer-Start wird als Fehler angezeigt; STREAMVANCE bleibt geöffnet.
- Schutz vor mehrfachem gleichzeitigen Installer-Start.

## Unverändert

- Vollständiger Installer-Download und SHA-256-Prüfung vor dem Start.
- Keine automatische Installation ohne Aktion des Nutzers.
- Prüfung auf ungespeicherte Projekte vor dem Update.
- Twitch-Datenlöschung und Live-Reconnect aus v0.7.80 bleiben erhalten.
- Twitch bleibt die unterstützte Open-Beta-Plattform; YouTube ist weiterhin „In Vorbereitung“.

## Wichtig für bestehende Installationen

Bereits installierte v0.7.79- und v0.7.80-Versionen enthalten noch den älteren Update-Aufruf. Wenn das Update darüber scheitert, die **v0.7.81-Installationsdatei nach Veröffentlichung einmal manuell von der offiziellen GitHub-Release-Seite starten**. Danach kann die verbesserte Update-Logik bei künftigen Versionswechseln genutzt und überprüft werden.

## Qualitätssicherung

- Gezielte IPC-Handoff- und relevante Regressionstests bestanden.
- Lokaler Windows-Funktionstest des v0.7.81-Candidates erfolgreich und freigegeben.
- Der tatsächliche automatische Versionswechsel über die korrigierte Update-Logik ist noch nicht end-to-end bestätigt.
