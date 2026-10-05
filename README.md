# Winterdienst – Plattform für den Flughafen-Winterdienst

Winterdienst ist eine webbasierte Plattform für Unternehmen, die den Winterdienst an Flughäfen leisten. Sie bündelt Personal, Qualifikationen, Führerscheine, Schulungen und – optional – die Schichtplanung an einem Ort. Mehrere Unternehmen können die Plattform nutzen; jedes arbeitet in einem eigenen, getrennten Bereich. Die Oberfläche ist deutschsprachig und auch auf dem Smartphone gut bedienbar.

> Dieses Repository enthält ausschließlich das öffentliche Änderungsprotokoll. Der Quellcode der Anwendung ist nicht öffentlich.

**Aktuelle Version: v0.2.16**

## Funktionen im Überblick

### Personal & Qualifikationen
- Mitarbeiterverwaltung mit Stammdaten, optionaler Adresse und Eintrittsdatum
- Qualifikationen je Mitarbeiter, auf Wunsch mit Ablaufdatum
- Import von Mitarbeitenden aus Excel oder CSV mit Vorschau

### Führerscheine & Nachweise
- Eine Führerscheinkarte pro Person mit beliebig vielen Klassen, jeweils mit Erteilungs- und optionalem Ablaufdatum
- Nachweis-Fotos für Führerschein und Qualifikationen – direkt per Kamera oder aus der Galerie

### Schulungen
- Schulungsvorlagen mit Wiederholungsintervall und Standarddauer
- Schulungskalender, Anmeldung, Anwesenheit und Teilnahmebestätigung
- Anmelde-Links für externe Teilnehmende
- Bearbeiten von Schulungen bis zur Veröffentlichung

### Schichtplanung (optionales Modul)
- Schichtvorlagen, Schichtkalender und benötigte Qualifikationen je Schicht
- Abdeckungsanzeige und Zuweisung durch Manager
- Mitarbeitende fragen Schichten selbst an

### Berichte
- Compliance-Übersicht: wer ist konform, bald fällig oder überfällig
- PDF-Bericht zum Herunterladen

### Benutzer & Rollen
- Rollen Administrator, Manager, Trainer, Mitarbeiter und Betrachter
- Fein abgestufte Rechte, z. B. für Manager in der Personalverwaltung
- Unternehmensweite Einstellungen und Standardwerte

### Self-Service
- „Meine Daten": eigene Stammdaten und Adresse einsehen und korrigieren
- „Meine Nachweise": eigene Führerschein- und Qualifikationsfotos hochladen
- Passwort selbst ändern, eigene Schulungen und Schichtanfragen im Dashboard

### Sicherheit & Datenschutz
- Strikte Trennung der Daten zwischen Unternehmen
- Rollenbasierte Zugriffsrechte; sensible Angaben nur für berechtigte Personen sichtbar
- Datensparsamkeit, z. B. Entfernen von Standortdaten aus Fotos
- Kontinuierliche Sicherheitsprüfungen und Härtung

## Änderungen

- [CHANGELOG.md](CHANGELOG.md) – alle Versionen im Überblick
- [Releases](https://github.com/reldorkamori/winterdienst-public/releases) – Versionshinweise je Release
