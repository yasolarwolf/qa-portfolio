# qa-portfolio
QA : Fehler, Checklisten, Testfälle

 1 . Fehlerberichte (Bug Reports) 
|  ID   | Projektname  | Fehlbeschreibung  |          Priorität                                                      | Link    |     |
|------------------------------|-------|-------------|----------------------------------------------------------------------------------|-----------|--------------|
| #001                         | Reddit.com | Die Schaltfläche „Akzeptieren“ führt zu keiner sichtbaren Reaktion | High      | [REDDIT#001](https://example.com) |
| #002                         | Reddit.com | Der Gruppenavatar wird auf der Hauptseite im Abschnitt „Zuletzt verwendet“ nicht angezeigt. | Medium    | [REDDIT#002](https://example.com) |
| #003                         | Reddit.com | Die gelesene Nachricht ist immer noch als ungelesen markiert. | Low       | [REDDIT#003](https://example.com) |
| #004                         | Reddit.com | Es gibt kein separates Feld für das Passwort, das Feld zur Erstellung des Passworts ist mit dem E-Mail-Eingabefeld verknüpft | High      | [REDDIT#004](https://example.com) |
| #005                         | brigitte.de | Der Sicherheitsschlüssel des Formulares ist abgelaufen. | High      | [BRIGITTE#005](https://example.com) |
| #006                         | brigitte.de | Fehlerhafte Validierung für E-Mail-Adressen mit der Domäne gmail.com | High      | [BRIGITTE#006](https://example.com) |
| #007                         | brigitte.de | Fehlerhafte Validierung für E-Mail-Adressen mit der Domäne mail.ru | High      | [BRIGITTE#007](https://example.com) |
| #008                         | brigitte.de | Falsches Feedback zur E-Mail-Validierung | Low       | [BRIGITTE#008](https://example.com) |


2. Testfälle und Checklisten

  
  ### ✅ Zalando Test-Checkliste: Login und Registrierung 

| ID   | Kategorie          | Testfall-Beschreibung                                                              | Erwartetes Ergebnis                               |
|------|--------------------|-------------------------------------------------------------------------------------|---------------------------------------------------|
| 01   | Gültige Eingabe    | E-Mail eingeben (Copy/Paste)                                                       | E-Mail wird korrekt übernommen                    |
| 02   | Gültige Eingabe    | E-Mail-Adresse im gültigen Format eingeben                                        | Weiterleitung zur nächsten Seite                  |
| 03   | Social Login       | Login über Google mit gültigem Account                                            | Erfolgreicher Login                               |
| 04   | Social Login       | Login über Apple mit gültigem Account                                             | Erfolgreicher Login                               |
| 05   | Social Login       | Login über Facebook mit gültigem Account                                          | Erfolgreicher Login                               |
| 06   | Links              | Klick auf „Nutzungsbedingungen“ führt zur richtigen Seite                         | Nutzungsbedingungen-Seite wird geöffnet           |
| 07   | Links              | Klick auf „Datenschutzerklärung“ öffnet Datenschutzseite                          | Datenschutz-Seite wird geöffnet                   |
| 08   | Links              | Klick auf "Impressum" öffnet Impressumseite                                       | Impressum wird angezeigt                          |

### ❌ Ungültige Szenarien

| ID   | Kategorie          | Testfall-Beschreibung                                                              | Erwartetes Ergebnis                               |
|------|--------------------|-------------------------------------------------------------------------------------|---------------------------------------------------|
| 09   | Leere Eingabe      | Klick auf "Weiter" mit leerem E-Mail-Feld                                          | Fehlermeldung „Pflichtfeld“ erscheint             |
| 10   | Nicht registriert  | Klick auf „Weiter“ mit nicht registrierter E-Mail-Adresse                         | Meldung „E-Mail nicht gefunden“                   |
| 11   | Ungültiges Format  | Klick auf "Weiter" mit ungültigem E-Mail-Format                                   | Validierungsfehler erscheint                      |
| 12   | Gesperrter Account | Login über Facebook mit gesperrtem Account                                        | Zugriff verweigert / Fehlermeldung angezeigt      |
| 13   | Gesperrter Account | Login über Google mit gesperrtem Account                                          | Zugriff verweigert / Fehlermeldung angezeigt      |
| 14   | Gesperrter Account | Login über Apple mit gesperrtem Account  

