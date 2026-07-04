# TeamCom — Releases

Public download + auto-update feed for **TeamCom** (film-set intercom).
This repo holds **only compiled binaries and the Sparkle appcast** — the app
source is private.

## Download

Grab the latest DMGs from **[Releases](../../releases/latest)**:

- **TeamCom.dmg** — the crew client
- **TeamCom-Server.dmg** — the menu-bar server

Universal (Apple Silicon + Intel), macOS 14+. First launch (unsigned):
right-click the app in Applications → **Open**.

## Auto-update

Both apps check these Sparkle feeds and prompt when a new version ships:

- Client: `appcast.xml`
- Server: `appcast-server.xml`

Updates are EdDSA-signed — only the holder of the private key can publish one.
