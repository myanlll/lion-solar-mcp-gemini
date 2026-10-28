# Lion Solar for Gemini CLI

Gemini CLI extension that connects to the public, read-only MCP server of Lion Solar Solutions OÜ. No account, no API key. / Gemini-CLI-Erweiterung für den öffentlichen, reinen Lese-MCP-Server der Lion Solar Solutions OÜ. Kein Konto, kein API-Schlüssel.

## English

Lion Solar plans PV projects for solar installers (PV*SOL plans and reports, K2 Systems mounting plans with statics, material lists, SLD and electrical plans, drone 3D building models).

Tools:
- `lion_solar_services`: what Lion Solar delivers, delivery times, how to get started.
- `drone_3d_requirements`: what is needed for a drone 3D model (80 to 600 GPS photos, flight advice, export formats, measured processing times).

Install:

```
gemini extensions install https://github.com/myanlll/lion-solar-mcp-gemini
```

Try: "What does Lion Solar deliver for a residential PV project?" or "What do I need to photograph a roof with a drone for a 3D model?"

Without the extension, add the server by hand in `~/.gemini/settings.json`:

```json
{ "mcpServers": { "lion-solar": { "httpUrl": "https://mcp.lion-solar.com/mcp" } } }
```

Privacy: https://mcp.lion-solar.com/privacy | Terms: https://mcp.lion-solar.com/terms | Support: info@lion-solar.com

## Deutsch

Lion Solar plant PV-Projekte für Solarinstallateure (PV*SOL-Pläne und -Berichte, K2-Systems-Montagepläne mit Statik, Materiallisten, Stromlauf- und Elektropläne, Drohnen-3D-Gebäudemodelle).

Werkzeuge:
- `lion_solar_services`: was Lion Solar liefert, Lieferzeiten, wie der Einstieg funktioniert.
- `drone_3d_requirements`: was für ein Drohnen-3D-Modell nötig ist (80 bis 600 Fotos mit GPS, Flugempfehlungen, Exportformate, gemessene Verarbeitungszeiten).

Installation:

```
gemini extensions install https://github.com/myanlll/lion-solar-mcp-gemini
```

Ausprobieren: "Was liefert Lion Solar für ein Einfamilienhaus-PV-Projekt?" oder "Was brauche ich, um ein Dach mit der Drohne für ein 3D-Modell zu fotografieren?"

Datenschutz: https://mcp.lion-solar.com/privacy | Nutzungsbedingungen: https://mcp.lion-solar.com/terms | Support: info@lion-solar.com

## License

MIT, see LICENSE. The extension contains only configuration; the server code is not part of this repository.
