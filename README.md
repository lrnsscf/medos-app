# MedOS

MedOS ist eine Desktop-Lern-App für Medizinstudierende. Dieses Repository enthält Downloads und Nutzerhilfe. Der Quellcode liegt in einem separaten privaten Repository.

## Downloads

Installationsdateien erscheinen unter [Releases](../../releases).

> **Erster Start auf dem Mac:** macOS kann MedOS blockieren, weil der Build nicht von Apple beglaubigt ist. Nach Prüfung des Downloads lässt sich MedOS gezielt freigeben. [Zur Anleitung mit Bildern →](docs/installation.md#macos)

> **Versionen 0.0.x sind Testbuilds vor v0.1.** MedOS arbeitet mit deinen echten Vorlesungen, Notizen und Anki-Karten und speichert sie lokal auf deinem Rechner. Noch sind nicht alle Funktionen abgenommen. Lege nichts nur in MedOS ab, das du nicht verlieren möchtest; Notizen lassen sich als Markdown exportieren.

| System | Download |
|---|---|
| macOS 13 oder neuer, Apple Silicon | DMG mit `darwin-aarch64` im Namen |
| macOS 13 oder neuer, Intel | DMG mit `darwin-x86_64` im Namen |
| Windows 10/11, 64 Bit | EXE-Installer mit `windows-x86_64` im Namen, sofern das Release einen enthält |

**Ohne Betriebssystem-Signierung:** MedOS ist kostenlos und wird ohne bezahlte Zertifikate von Apple oder Microsoft ausgeliefert. Gatekeeper bzw. SmartScreen zeigt deshalb beim ersten Start eine Warnung. Prüfe Herkunft und SHA-256-Prüfsumme vor dem Start; wie du MedOS dann öffnest, steht in der [Installation](docs/installation.md). Die kryptografische Signatur der Updates ist davon unabhängig und immer vorhanden.

## Hilfe

- [Installation und Updates](docs/installation.md)
- [Erste Schritte](docs/erste-schritte.md)
- [MedOS für Anki installieren und koppeln](docs/anki-addon.md)
- [Datenschutz](docs/datenschutz.md)
- [FAQ](docs/faq.md)

Verbindlich ist der Funktionsumfang in den jeweiligen Release-Notizen.
