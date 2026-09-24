# MedOS

MedOS ist eine Desktop-Lern-App für Medizinstudierende. Dieses Repository enthält Downloads und Nutzerhilfe. Der Quellcode liegt in einem separaten privaten Repository.

## Downloads

Installationsdateien erscheinen unter [Releases](../../releases). Solange dort kein Release steht, gibt es noch keinen öffentlichen Download. Frühe Alpha-Versionen enthalten noch Beispieldaten und sind für Tests gedacht; die vollständigen Lernfunktionen werden schrittweise angeschlossen.

| System | Download |
|---|---|
| macOS 13 oder neuer, Apple Silicon | DMG mit `darwin-aarch64` im Namen |
| macOS 13 oder neuer, Intel | DMG mit `darwin-x86_64` im Namen |
| Windows 10/11, 64 Bit | EXE-Installer mit `windows-x86_64` im Namen |

**Unsignierte Alpha-Builds:** Gatekeeper bzw. SmartScreen kann eine Warnung anzeigen. Prüfe Herkunft und SHA-256-Prüfsumme vor dem Start. Hinweise stehen in der [Installation](docs/installation.md). Betriebssystem-Signierung und die immer erforderliche kryptografische Updater-Signatur sind unterschiedliche Prüfungen.

## Hilfe

- [Installation und Updates](docs/installation.md)
- [Erste Schritte](docs/erste-schritte.md)
- [MedOS für Anki installieren und koppeln](docs/anki-addon.md)
- [Datenschutz](docs/datenschutz.md)
- [FAQ](docs/faq.md)

Kein Anki-Add-on in einem Release bedeutet: Die Anki-Anbindung ist in dieser Version noch nicht verfügbar. Verbindlich ist der Funktionsumfang in den jeweiligen Release-Notizen.
