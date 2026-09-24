# Installation und Updates

Lade Dateien ausschließlich aus den Releases dieses Repositorys. Die Datei `SHA256SUMS` enthält die Prüfsummen. Unter macOS: `shasum -a 256 DATEI`. Unter Windows PowerShell: `Get-FileHash DATEI -Algorithm SHA256`. Vergleiche die gesamte ausgegebene Prüfsumme mit dem zugehörigen Eintrag.

## macOS

Wähle die DMG für Apple Silicon oder Intel, öffne sie und ziehe MedOS nach Programme. Öffne MedOS dort.

Bei einem unsignierten Alpha-Build kann macOS den ersten Start blockieren. Prüfe zuerst Quelle und Prüfsumme. Falls du dem Download vertraust, nutze die gezielte Freigabe für MedOS in Systemeinstellungen → Datenschutz & Sicherheit → Dennoch öffnen. Verfügbarkeit und Wortlaut hängen von der macOS-Version ab. Deaktiviere Gatekeeper nicht global; melde abweichende Warnungen statt Schutzmechanismen pauschal abzuschalten.

## Windows

Starte den EXE-Installer und folge seinen Schritten. Bei einem unsignierten Alpha-Build kann SmartScreen eine Warnung zeigen. Nach Prüfung von Quelle und Prüfsumme kannst du, sofern Windows diese Option anbietet, über Weitere Informationen → Trotzdem ausführen fortfahren. Unternehmensrichtlinien können dies untersagen.

## Updates

Mit aktivierter automatischer Updateprüfung sucht MedOS beim Start im Kanal der installierten Version: alpha, beta oder stable. Die Installation startet erst nach deiner Auswahl von „Installieren und neu starten“ im Update-Hinweis. Speichere vorher deine Arbeit. Manuell suchst du unter Einstellungen → Über MedOS → Nach Updates suchen.

Fehlende Netzwerkverbindung, ein noch nicht veröffentlichter Kanal oder eine ungültige Signatur können ein Update verhindern. Eine fehlgeschlagene Prüfung ist keine Bestätigung, dass die installierte Version aktuell ist. Lade bei Problemen den passenden Installer aus den Releases. Ein Wechsel des Kanals erfolgt durch die bewusste Installation einer Version dieses Kanals.
