# ˚ʚ Meowly ₊✧ — Releases

Dieses Repository enthält **nur die veröffentlichten Windows-Installer** von Meowly, einem
persönlichen Anime-Tracker (Desktop-App). Es dient ausschließlich als Auto-Update-Quelle für
die App — hier liegt **kein Quellcode**.

## Was ist hier drin?

Jeder [Release](../../releases) enthält:

- `Meowly-Setup-X.X.X.exe` — der Windows-Installer
- `Meowly-Setup-X.X.X.exe.blockmap` — ermöglicht differenzielle Updates (nur geänderte Teile
  werden nachgeladen statt der ganzen Datei erneut)
- `latest.yml` — Metadaten, die die App nutzt, um automatisch auf neue Versionen zu prüfen

## Auto-Update

Die installierte App prüft beim Start automatisch gegen dieses Repository, ob eine neuere
Version verfügbar ist, lädt sie im Hintergrund herunter und installiert sie beim nächsten
Neustart der App.

---

<sub>˚ʚ Meowly ₊✧ — Anime Tracker · Deine persönliche Anime-Liste</sub>
