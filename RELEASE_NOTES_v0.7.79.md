# STREAMVANCE Studio v0.7.79 — Open Beta Hotfix

Dieses Open-Beta-Update behebt die fehlende Erkennung von Twitch-Resub-Aktivitäten.

## Behoben

- Twitch-Resubs werden über `channel.subscription.message` empfangen.
- Resubs werden in die bestehende Event-History übernommen.
- Event Feed zeigt Resubs inklusive kumulierter Monate.
- Alert Widget erkennt Resubs und zeigt den Resub-Alert korrekt an.
- Tier, Monate und optionale Resub-Nachricht werden übernommen.
- Vorhandene Sub-Sounds und Sub-Automationen bleiben kompatibel.

## Unverändert

- Die Event-History bleibt streamübergreifend lokal erhalten.
- Twitch bleibt die unterstützte Plattform der aktuellen Open Beta.
- YouTube bleibt bis zur separaten OAuth-/Mehrkonto-Validierung in Vorbereitung.
