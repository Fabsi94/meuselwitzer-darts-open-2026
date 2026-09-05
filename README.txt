MEUSELWITZER DARTS OPEN 2026 – ONLINE WEBSITE

Enthalten:
- index.html: öffentliche Anmeldung
- admin.html: geschützter Admin-Bereich
- config.js: Supabase URL + Publishable Key
- logo.jpeg: Turnierlogo
- style.css: Design

Die Webseite erwartet in Supabase die bereits angelegten Tabellen/Funktionen:
- participants
- registrations
- register_group(jsonb)
- get_player_count()
- organizers + RLS

WICHTIG:
Der Publishable Key darf im Browser verwendet werden. Secret/service_role Keys dürfen NICHT in diese Dateien.

Nächster Schritt:
Die Dateien auf GitHub hochladen und anschließend mit Cloudflare Pages veröffentlichen.
