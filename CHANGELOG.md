# Changelog – Winterdienst

Öffentliches Änderungsprotokoll der Winterdienst-Plattform. Neueste Version zuerst.

## v1.0.0 — Winterdienst 1.0 – 2026-10-05

### Highlights
- Winterdienst 1.0 – die erste stabile Version.
- Die aktuelle Version wird jetzt unten in der Navigation angezeigt; ein Klick öffnet diese Versionshinweise.

## v0.2.16 — Benachrichtigungs-Mails – 2026-10-05

### Highlights
- Benachrichtigungs-Mails: Bestätigung von Schulungsanmeldungen, Erinnerung 24 Stunden vor einer Schulung und eine gebündelte Mail zu neu veröffentlichten Schulungen.
- Administratoren und Manager können Mitarbeitende gezielt über Schulungen informieren.
- Jede Person kann Benachrichtigungen in ihrem Konto oder direkt über den Link in der E-Mail abbestellen.

### Verbesserungen
- Benachrichtigungen lassen sich zentral und je Organisation ein- und ausschalten.

### Fehlerbehebungen
- Ein technischer Fehler bei bestimmten Formularanfragen wurde behoben.

## v0.2.15 — E-Mail-Vorlagen und Sicherheits-Mails – 2026-10-04

### Highlights
- Neue Einstellungsseite **E-Mail**: Vorlagen für automatische E-Mails lassen sich bequem im Editor gestalten, mit Vorschau und Testversand an die eigene Adresse.
- Eigenes Erscheinungsbild je Organisation: Akzentfarbe, Logo, Fußzeile und Antwortadresse.
- Sicherheits-Benachrichtigungen: Nutzer werden informiert, wenn ihr Passwort oder ihre E-Mail-Adresse geändert bzw. ihr Passwort von einem Administrator zurückgesetzt wurde.

### Verbesserungen
- Zuverlässiger E-Mail-Versand mit automatischen Wiederholungen und Statusübersicht für Administratoren.

### Sicherheit
- Strenge Prüfung aller E-Mail-Vorlagen und Uploads; E-Mails enthalten niemals Passwörter.

## v0.2.14 — Nachfrage vor dem Verwerfen von Eingaben – 2026-10-04

### Highlights
- Schutz vor versehentlich verlorenen Eingaben: Wer einen Dialog mit ungespeicherten Änderungen schließt, wird gefragt, ob die Eingaben wirklich verworfen werden sollen.
- Beim Anlegen und Bearbeiten von Schulungen gilt das auch beim Verlassen der Seite.

## v0.2.13 – 2026-10-04

### Highlights
- Anmeldungen sind besser gegen das Erraten von Passwörtern geschützt: Nach mehreren Fehlversuchen wird ein Konto vorübergehend gesperrt; Administratoren können die Sperre jederzeit aufheben.
- Zusätzlicher Schutz vor automatisierten Angriffen auf die Anmeldung.

### Verbesserungen
- Die Benutzerverwaltung zeigt vorübergehend gesperrte Konten an („Vorübergehend gesperrt").
- Verständliche Meldung auf der Anmeldeseite, wenn zu viele Fehlversuche erfolgt sind.

### Sicherheit
- Datensparsamere Protokollierung: E-Mail-Adressen erscheinen nicht mehr in technischen Protokollen.

## v0.2.12 – 2026-10-04

### Sicherheit
- Anmeldung gegen Missbrauch weiter abgesichert: Es sind nur noch die tatsächlich benötigten Anmeldefunktionen erreichbar.
- Zusätzliche Schutzmaßnahmen im Browser, unter anderem gegen das Einbetten der Anwendung in fremde Seiten; Links zu Schulungen werden nicht an andere Webseiten weitergegeben.
- Begrenzungen gegen zu viele Anfragen greifen zuverlässiger.

### Verbesserungen
- Technische Wartung und Härtung des Betriebs, keine sichtbaren Änderungen.

## v0.2.11 – 2026-10-04

### Highlights
- Stammdaten nachträglich ändern: Administratoren und Manager korrigieren Name, E-Mail, Mobiltelefon, Personalnummer und Eintrittsdatum über „Stammdaten bearbeiten"; in der Benutzerverwaltung gibt es dafür die Aktion „Bearbeiten".
- Self-Service „Meine Daten": Mitarbeitende korrigieren ihren Namen, ihr Mobiltelefon und ihre E-Mail-Adresse selbst.
- Letzte Anmeldung: sichtbar in der Benutzerliste und auf der Mitarbeiterseite („noch nie", falls bisher keine Anmeldung erfolgte).

### Neue Funktionen
- Eine geänderte E-Mail-Adresse gilt ab der nächsten Anmeldung als Login; laufende Sitzungen bleiben bestehen.
- Der Name im Benutzermenü aktualisiert sich sofort nach dem Speichern.
- Hilfe zu Mitarbeitern, Benutzern und „Meine Daten" erweitert, neue Einträge in „Fehlermeldungen A–Z".

### Sicherheit
- Zugriffsrechte für Manager präzisiert: Auch beim Bearbeiten von Mitarbeiter-Stammdaten bleiben Administratoren, andere Manager und das eigene Konto für Manager unveränderbar.
- Die Änderung der eigenen E-Mail-Adresse erfordert das aktuelle Passwort; wiederholte Fehleingaben werden vorübergehend begrenzt.
- E-Mail-Adressen bleiben eindeutig.
- „Letzte Anmeldung" berücksichtigt nur erfolgreiche Anmeldungen und ist nur für Administratoren und Manager sichtbar.

### Fehlerbehebungen
- Eine bereits vergebene Personalnummer führt zur Meldung „Personalnummer bereits vergeben".
- Namensänderungen werden durchgängig übernommen.

## v0.2.10 – 2026-10-03

### Highlights
- Schulungen bearbeiten, solange sie nicht veröffentlicht sind: Titel, Beschreibung, Datum und Uhrzeit, Ort, Kapazität, Trainer und Themenpunkte.
- Optionale Adresse für Mitarbeitende – pflegbar durch Administratoren und Manager, über den Import und selbst über die neue Seite „Meine Daten".
- Ein Führerschein mit mehreren Klassen: eine Führerscheinkarte pro Person mit beliebig vielen Klassen, jeweils mit eigenem Erteilungs- und optionalem Ablaufdatum.

### Neue Funktionen
- Gemeinsames Formular für Anlegen und Bearbeiten von Schulungen; Datum und Uhrzeit sind im Entwurf optional und erst beim Veröffentlichen Pflicht. Die Detailseite zeigt die Beschreibung.
- Führerschein-Reiter: Klassen hinzufügen (mehrere auf einmal), bearbeiten und entfernen, Karte bearbeiten, Führerschein löschen. „Meine Nachweise" zeigt die Karte mit allen Klassen.
- Adresse nach dem Prinzip „alles oder nichts" (Straße, Hausnummer, PLZ, Ort); „Adresse entfernen" löscht sie. Import-Vorlagen enthalten die Adressspalten; vierstellige Postleitzahlen aus Excel werden automatisch ergänzt (z. B. 4435 → 04435).
- „Meine Daten" im Benutzermenü: eigene Stammdaten einsehen und eigene Adresse pflegen.
- Hilfe erweitert: neuer Abschnitt „Meine Daten", aktualisierte Abschnitte zu Mitarbeitern, Benutzern, Schulungen und Fehlermeldungen.

### Sicherheit
- Bearbeiten und Veröffentlichen von Schulungen ist gegen gleichzeitige Änderungen abgesichert.
- Zugriffsrechte für Manager präzisiert: Adressen von Administratoren, anderen Managern und die eigene sind für Manager nicht über die Verwaltung änderbar (dafür gibt es „Meine Daten").
- „Meine Daten" wirkt ausschließlich auf das eigene Konto.

### Fehlerbehebungen
- Veröffentlichte Schulungen sind gesperrt und melden dies verständlich auf Deutsch.
- Ein Ablaufdatum vor dem Erteilungsdatum wird mit einer klaren Meldung abgelehnt.
- Verständliche Meldungen bei ungültigen Aufrufen.

## v0.2.9 – 2026-10-03

### Highlights
- Schulungsteilnehmer für alle sichtbar: Kalender und Schulungsdetails zeigen, wer angemeldet ist – mit Status Angefragt, Bestätigt oder Teilgenommen. Externe Teilnehmer erscheinen anonym als „Externer Teilnehmer".
- Nachweis-Fotos: Neue Seite „Meine Nachweise" für Fotos von Führerschein (Vorder- und Rückseite) und Qualifikationen – direkt mit der Kamera oder aus Galerie bzw. Datei.

### Neue Funktionen
- Teilnehmerliste im Kalender (auf dem Smartphone die ersten zehn plus „+N weitere") und auf der Schulungsseite; Direktlinks aus „Meine Schulungen" auf dem Dashboard.
- „Anmelden" wird ausgeblendet, wenn die eigene Anmeldung abgelehnt oder zurückgezogen wurde.
- Bis zu vier Fotos pro Qualifikation. Administratoren und Manager sehen und pflegen die Nachweise im Mitarbeiterprofil (Spalte „Nachweise").
- Fotos werden automatisch verkleinert und ausgerichtet; Metadaten wie Standortangaben werden vor dem Speichern entfernt.
- Neuer Hilfe-Abschnitt „Meine Nachweise".

### Sicherheit
- Mitarbeitende sehen bei Schulungen nur noch die für sie nötigen Angaben zu anderen Teilnehmenden.
- Schulungen im Entwurf bleiben für Mitarbeitende vollständig unsichtbar.
- Nachweis-Fotos sind nur für die eigene Person sowie Administratoren und Manager des Unternehmens sichtbar.
- Uploads werden auf Dateityp und Größe geprüft und gegen Missbrauch begrenzt.

### Fehlerbehebungen
- Teilnehmerzahl und Kapazität zählen nur noch aktive Anmeldungen.
- Verständliche Meldungen bei ungültigen Aufrufen und zu großen Import-Dateien.
- Sprünge zu einem Abschnitt der Hilfe funktionieren zuverlässig.

## v0.2.8 – 2026-10-03

### Highlights
- Passwort selbst ändern – und Pflicht zur Änderung des Startpassworts bei der ersten Anmeldung.
- Import von Mitarbeitenden aus Excel (XLSX/XLS) und CSV, inklusive Zugangsdaten und Vorschau.
- Schichtplanung als optionales Modul je Unternehmen.
- Schulungen können gelöscht werden.

### Neue Funktionen
- „Passwort ändern" im Benutzermenü. Neue Benutzer werden bei der ersten Anmeldung aufgefordert, ihr Startpasswort zu ändern; beim Zurücksetzen eines Passworts lässt sich diese Pflicht wählen.
- Mitarbeitende sind fest mit einem Benutzerkonto verknüpft; Personen ohne Zugang werden mit „Kein Login" gekennzeichnet.
- Mitarbeiter-Import mit Vorschau vor dem Übernehmen, Passwortspalte und Vorlagen zum Herunterladen (bis zu 500 Zeilen).
- Schichtplanung kann pro Unternehmen ein- oder ausgeschaltet werden; ist sie aus, entfallen Menüpunkte, Dashboard-Bereiche und Hilfe-Abschnitte zu Schichten.
- Administratoren und Manager können Schulungen löschen; vorher wird angezeigt, welche Anmeldungen betroffen sind und wie sich das auf die Compliance auswirkt.
- Hilfe zu Import und Passwortänderung ergänzt.

### Sicherheit
- Zugangsdaten für den E-Mail-Versand werden verschlüsselt gespeichert; Versandziele werden streng geprüft.
- Weitere Absicherung der Kontoverwaltung.

### Fehlerbehebungen
- Anmeldung direkt nach einer Passwortänderung funktioniert zuverlässig.
- Zu große Import-Dateien führen zu einer verständlichen deutschen Meldung.

## v0.2.7 – 2026-10-03

### Highlights
- Deutlich besser auf dem Smartphone nutzbar.

### Neue Funktionen
- Mobiles Layout: aufklappbares Menü statt fester Seitenleiste, umbrechende Kopfzeilen, seitlich scrollbare Tabellen und ein Kalender mit Tagesliste für kleine Bildschirme.
- Neue Schulung: Das Ende wird aus Startzeit und Standarddauer der Schulungsvorlage vorbelegt.

### Fehlerbehebungen
- Dashboard „Meine Schulungen" zeigt nur noch kommende, aktive Anmeldungen (bis zu fünf, mit „Alle anzeigen").
- Die Standarddauer von Schulungsvorlagen wird jetzt zuverlässig gespeichert.

## v0.2.6 – 2026-10-03

### Highlights
- Manager können genehmigte Schichtzuweisungen zurücknehmen.

### Neue Funktionen
- Aktion „Zurücknehmen" für genehmigte Zuweisungen; die Zuweisung erscheint danach als „Zurückgezogen", und die betroffene Person kann die Schicht erneut anfragen.
- Hilfe und Fehlermeldungs-Verzeichnis ergänzt.

### Verbesserungen
- Zuweisungsstatus werden einheitlich geführt und angezeigt.

### Fehlerbehebungen
- Korrekte Beschriftung zurückgezogener Zuweisungen.

## v0.2.5 – 2026-10-03

### Highlights
- Mitarbeitende können Schichten selbst anfragen und Anfragen wieder zurückziehen.

### Neue Funktionen
- Buttons „Schicht anfragen" und „Anfrage zurückziehen" in der Schichtansicht; angefragt werden können nur veröffentlichte Schichten, zeitliche Überschneidungen werden abgelehnt.
- Eigener Anfragestatus im Schichtkalender und auf dem Dashboard unter „Meine Anfragen".
- Für Manager: Filter „Offene Anfragen" und Spalte „Anfragen" in der Schichtliste.
- Neuer Hilfe-Abschnitt „Schichten anfragen".

### Fehlerbehebungen
- Einheitliche Meldung bei fehlender Qualifikation – bei Anfrage, Selbstanfrage und Genehmigung.

## v0.2.4 – 2026-10-03

### Highlights
- Qualifikationsanforderungen für Schichten: Für jede Schicht lässt sich festlegen, welche Qualifikationen in welcher Anzahl benötigt werden.

### Neue Funktionen
- Benötigte Qualifikationen können auf Schichtvorlagen, neuen Schichten und Entwürfen gepflegt werden.
- Die Schichtdetails zeigen die Abdeckung je Qualifikation (Benötigt, Abgedeckt, Überschrieben) und weisen darauf hin, wenn der Bedarf bereits gedeckt ist.
- Bei der Zuweisung von Mitarbeitenden ohne passende Qualifikation erscheint der Hinweis „Qualifikation fehlt". Administratoren und Manager können die Zuweisung bewusst trotzdem vornehmen; dies wird vermerkt.
- Hilfe zu Qualifikationsanforderungen, Abdeckung und Überschreiben.

### Verbesserungen
- Gleichzeitige Zuweisungen zur selben Schicht oder zur selben Person werden zuverlässig nacheinander verarbeitet.

### Fehlerbehebungen
- Beschreibung einer Schicht wird überall korrekt angezeigt.
- Doppelte Anfragen führen zur verständlichen Meldung „Bereits angefragt".
- Qualifikationsprüfung vergleicht Kalendertage zuverlässig, unabhängig von der Zeitzone.

## v0.2.3 – 2026-10-03

### Neue Funktionen
- Manager verwalten Schulungen jetzt im selben Umfang wie Trainer: Schulungen, Schulungsvorlagen und Anmelde-Links anlegen und pflegen.
- Hilfe entsprechend ergänzt.

## v0.2.2 – 2026-10-03

### Highlights
- Kontaktdaten auf der öffentlichen Anmeldeseite werden nur noch angezeigt, wenn das Unternehmen dies ausdrücklich einschaltet.

### Neue Funktionen
- Neue Einstellung „Kontaktdaten auf der öffentlichen Anmeldeseite anzeigen" (standardmäßig aus). Wer die Kontaktdaten wie bisher zeigen möchte, aktiviert den Schalter unter „Einstellungen".
- Hilfe zur neuen Einstellung ergänzt.

## v0.2.1 – 2026-10-03

### Highlights
- Neue Hilfe-Seite direkt in der Anwendung.
- Verständlichere öffentliche Anmeldeseite für Schulungen per Link.

### Neue Funktionen
- Menüpunkt „Hilfe" für alle Rollen: Erklärungen zu allen Bereichen, passend zur eigenen Rolle, mit Direktlinks und einem Verzeichnis „Fehlermeldungen A–Z".
- Anmelde-Links für Schulungen können gelöscht werden; die Übersicht zeigt nur noch aktive Links.
- Öffentliche Anmeldeseite: abgelaufene, ausgeschöpfte oder zurückgezogene Links erklären klar, warum keine Anmeldung mehr möglich ist. Bei veröffentlichten Schulungen werden Trainer und Ansprechpartner angezeigt.
- Telefonnummern werden bei der Anmeldung geprüft; das Formular bleibt bei Fehlern ausgefüllt, ein „Zurück"-Button erleichtert die Korrektur.
- Die Schulungsliste zeigt standardmäßig veröffentlichte Schulungen (Option „Alle"); neuer Button „Kalender".

### Fehlerbehebungen
- Schaltflächen zum Anlegen, Archivieren und Wiederherstellen erscheinen nur noch für Rollen, die die Aktion auch ausführen dürfen.
- „Neue Schicht" im Schichtkalender nur noch für Administratoren und Manager.
- Verständliche deutsche Meldungen bei fehlender Berechtigung, Ladefehlern und zu vielen Anmeldeversuchen auf der öffentlichen Seite.

## v0.2.0 – 2026-10-03

### Highlights
- Mandantenfähigkeit: Jedes Unternehmen arbeitet in einem eigenen, klar getrennten Bereich mit eigenen Mitarbeitenden, Schulungen und Einstellungen.
- Neue Seite „Einstellungen" für unternehmensweite Standardwerte.
- Erweiterte Rechte für Manager in der Personalverwaltung.

### Neue Funktionen
- Einstellungen pro Unternehmen: Anzeigename, Adresse, Kontaktdaten, Standard-Schichtzeiten und Vorlaufzeit für Schulungserinnerungen. Die Werte fließen in Dashboard, Compliance-Übersicht und den Kopf des PDF-Berichts ein.
- Manager können Mitarbeitende anlegen und dabei die Rollen Mitarbeiter, Trainer oder Betrachter vergeben; der Import von Mitarbeitenden steht ihnen ebenfalls zur Verfügung.
- Die Plattformverwaltung kann für ein neues Unternehmen den ersten Administrator anlegen und Passwörter zurücksetzen.
- Einheitliches Formular zum Anlegen und Bearbeiten von Benutzern.

### Sicherheit
- Zugriffsrechte für Manager präzisiert: Administratoren und andere Manager sowie das eigene Konto bleiben für Manager unveränderbar.
- Interne Verwaltungskonten sind in Benutzerlisten nicht sichtbar; Aktionen der Plattformverwaltung erscheinen neutral als „Systemverwaltung".
- Zusätzlicher Schutz gegen Anfragen, die von fremden Webseiten aus ausgelöst werden.

### Fehlerbehebungen
- Benutzerliste aktualisiert sich nach dem Zurücksetzen eines Passworts sofort.
- Die Vorlaufzeit für Schulungserinnerungen akzeptiert nur ganze Tage.
