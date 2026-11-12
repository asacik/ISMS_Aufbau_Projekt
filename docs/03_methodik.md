## 1. Zweck und Zielsetzung 

Diese Methodik beschreibt das einheitliche Vorgehen zur Identifikation, Analyse, Bewertung und Behandlung von Informationssicherheitsrisiken innerhalb der fiktiven Noventis Group GmbH. 

Ziel dieses Dokuments ist esm Risiken nachhvollziehbar zu erfassen, nach einheitlichen Kriteriien zu bewerten und geeigneten Maßnahmmen zur Reduzierung der Risiken abzuleiten. Die Ergebnisse sollen als Grundlage für Entscheidungen des Managements sowie für die kontinuirliche Verbesserung des ISMS dienen. 

Die Methoden orientiert sich an den Grundsätzen der ISO/IEC 27001:2022, insbesondere an den Anforderungen zur Risikobeurteilung und Risikobehandlung. SIe ist auf den im Dokument [Scope](02_scope.md) beschriebenen Geltungsbereich abgestimmt. 

--- 

## 2. Methodische Grundlagen

Die Risikobeurteilung orientiert sich insbesondere an folgenden Regelwerken:

- **ISO/IEC 27001:2022:** Anforderungen an Informationssicherheitsmanagementsysteme, insbesondere Abschnitt 6.1.2 (Informationssicherheitsrisikobeurteilung) und 6.1.3 (Informationssicherheitsrisikobehandlung).
- **ISO/IEC 27005:2022:** Leitlinien zur Identifikation, Analyse, Bewertung und Behandlung von Informationssicherheitsrisiken.
- **DSGVO:** Berücksichtigung datenschutzrechtlicher Anforderungen, sofern personenbezogene Daten betroffen sind.

Die ISO/IEC 27001 gibt keine allgemeingültige numerische Risikomatrix oder feste Berechnungsformel vor. Die konkreten Bewertungskriterien und Akzeptanzgrenzen werden daher projektspezifisch festgelegt und in der Datei `04_bewertungsskalen.md` dokumentiert.

---

## 3. Grundsätze der Risikobeurteilung

Die Risikoanalyse erfolgt nach folgenden Grundsätzen:

- **Einheitlichkeit:** Alle Risiken werden anhand derselben Bewertungsregeln beurteilt.
- **Nachvollziehbarkeit:** Annahmen, Bewertungen und Entscheidungen werden dokumentiert und begründet.
- **Risikoorientierung:** Die Analyse berücksichtigt mögliche Auswirkungen auf Vertraulichkeit, Integrität und Verfügbarkeit von Informationen.
- **Verhältnismäßigkeit:** Sicherheitsmaßnahmen sollen zum jeweiligen Risiko und zum Schutzbedarf der betroffenen Informationswerte passen.
- **Verantwortlichkeit:** Für jedes identifizierte Risiko wird ein Risikoeigner festgelegt.
- **Reproduzierbarkeit:** Wiederholte Bewertungen sollen unter vergleichbaren Bedingungen zu nachvollziehbaren Ergebnissen führen.
- **Kontinuierliche Verbesserung:** Risiken und Maßnahmen werden regelmäßig sowie bei wesentlichen Veränderungen überprüft.

Die Risikobeurteilung berücksichtigt sowohl technische als auch organisatorische, personelle und externe Einflussfaktoren.

---

## 4. Anwendungsbereich und Abgrenzung

Die Methodik gilt für die im Dokument `02_scope.md` definierten Organisationseinheiten, Geschäftsprozesse, Informationswerte und IT-Systeme der Noventis Group GmbH.

Berücksichtigt werden insbesondere:

- Geschäftsprozesse und unterstützende Tätigkeiten.
- IT-Systeme, Anwendungen und Infrastrukturen.
- Personenbezogene und vertrauliche Informationen.
- Cloud-Dienste und externe Dienstleister.
- Organisatorische und technische Sicherheitsmaßnahmen.
- Schnittstellen zwischen internen und externen Systemen.

Die Bewertung erfolgt auf Grundlage der im Asset-Register dokumentierten Informationswerte und der beschriebenen Unternehmens- und Prozesslandschaft.

Da es sich um eine fiktive Fallstudie handelt, basiert die Analyse auf modellhaften Annahmen. Eine tatsächliche Prüfung der Infrastruktur oder der Wirksamkeit bestehender Sicherheitsmaßnahmen findet nicht statt.

---

## 5. Risikomanagementprozess

Die Risikobeurteilung wird in mehrere aufeinander aufbauende Schritte unterteilt.

| Schritt | Beschreibung |
|---|---|
| 1. Kontextanalyse | Betrachtung des Unternehmens, der Geschäftsprozesse und des Untersuchungsbereichs |
| 2. Risikoidentifikation | Ermittlung möglicher Bedrohungen, Schwachstellen und Risikoszenarien |
| 3. Risikoanalyse | Untersuchung der möglichen Auswirkungen und Eintrittswahrscheinlichkeiten |
| 4. Risikobewertung | Einordnung und Priorisierung anhand definierter Bewertungskriterien |
| 5. Risikobehandlung | Auswahl und Planung geeigneter Maßnahmen |
| 6. Restrisikobewertung | Neubewertung nach Umsetzung der geplanten Maßnahmen |
| 7. Überprüfung | Regelmäßige Überprüfung und Aktualisierung der Ergebnisse |

Die einzelnen Schritte werden dokumentiert und miteinander verknüpft, sodass die Entstehung einer Risikobewertung bis zur abgeleiteten Maßnahme nachvollzogen werden kann.

---

## 6. Risikoidentifikation

Im Rahmen der Risikoidentifikation werden mögliche Ereignisse und Umstände ermittelt, die die Informationssicherheit der Noventis Group GmbH beeinträchtigen können.

Als Grundlage dienen insbesondere:

- Das Asset-Register.
- Das Unternehmensprofil und die definierten Geschäftsprozesse.
- Die dokumentierte IT- und Cloud-Infrastruktur.
- Das Verzeichnis von Verarbeitungstätigkeiten (VVT).
- Bekannte organisatorische und technische Sicherheitsmaßnahmen.
- Abhängigkeiten von Lieferanten und externen Dienstleistern.

Die Identifikation erfolgt sowohl aus technischer als auch aus organisatorischer Sicht.

### 6.1 Bedrohungen und Schwachstellen

Bei der Identifikation werden mögliche Bedrohungen und ausnutzbare Schwachstellen betrachtet.

**Bedrohungen** beschreiben mögliche Ursachen oder Ereignisse, die einen Schaden verursachen können.

Beispiele:

- Phishing und Social Engineering.
- Ransomware und Schadsoftware.
- Unbefugter Zugriff auf IT-Systeme.
- Ausfall kritischer Infrastrukturen.
- Fehlkonfigurationen von Cloud-Diensten.
- Menschliche Fehler.
- Ausfall oder Kompromittierung externer Dienstleister.

**Schwachstellen** beschreiben technische oder organisatorische Mängel, die das Eintreten eines Schadens begünstigen können.

Beispiele:

- Fehlende oder unzureichende Mehr-Faktor-Authentifizierung.
- Unzureichende Berechtigungsvergabe.
- Fehlende Sicherheitsupdates.
- Unzureichende Netzwerksegmentierung.
- Fehlende Mitarbeitersensibilisierung.
- Unzureichende Überwachung von Systemzugriffen.

### 6.2 Formulierung von Risikoszenarien

Risiken werden als konkrete Szenarien formuliert, damit Ursache, mögliches Ereignis und Auswirkungen nachvollziehbar sind.

Dabei werden nach Möglichkeit folgende Bestandteile berücksichtigt:

1. **Informationswert / Asset:** Welcher Wert ist betroffen?
2. **Bedrohung:** Welche mögliche Ursache kann das Ereignis auslösen?
3. **Schwachstelle:** Welche technische oder organisatorische Schwäche begünstigt das Ereignis?
4. **Risikoereignis:** Was könnte konkret passieren?
5. **Auswirkung:** Welche Folgen könnten für das Unternehmen entstehen?

**Beispiel:**

Aufgrund fehlender Mehr-Faktor-Authentifizierung bei privilegierten Administratorkonten besteht das Risiko, dass Angreifer durch kompromittierte Zugangsdaten unbefugten Zugriff auf die Cloud-Infrastruktur erhalten und vertrauliche Kundeninformationen einsehen oder verändern können.

Die Risikoszenarien werden eindeutig identifiziert und im Risikoregister dokumentiert.

### 6.3 Zuordnung von Risikoeignern

Für jedes identifizierte Risiko wird ein verantwortlicher Risikoeigner (Risk Owner) festgelegt.

Der Risikoeigner ist für die Bewertung und Behandlung des jeweiligen Risikos sowie für die Entscheidung über die Akzeptanz des verbleibenden Risikos im Rahmen seiner festgelegten Befugnisse verantwortlich.

Die Zuordnung erfolgt anhand der organisatorischen Zuständigkeiten und der betroffenen Geschäftsprozesse.

---

## 7. Risikoanalyse

Nach der Identifikation werden die Risiken hinsichtlich ihrer möglichen Auswirkungen und ihrer realistischen Eintrittswahrscheinlichkeit untersucht.

Ziel ist es, das jeweilige Risikoniveau nachvollziehbar zu bestimmen.

### 7.1 Bewertung der Auswirkungen

Die Auswirkungen beschreiben die möglichen Folgen, falls ein identifiziertes Risikoszenario eintritt.

Berücksichtigt werden insbesondere:

- **Vertraulichkeit:** Unbefugte Offenlegung oder Zugriff auf Informationen.
- **Integrität:** Unbefugte Veränderung, Manipulation oder Zerstörung von Informationen.
- **Verfügbarkeit:** Einschränkung oder Ausfall von Informationen und IT-Systemen.

Darüber hinaus können weitere Auswirkungen berücksichtigt werden:

- Finanzielle Schäden.
- Betriebsunterbrechungen.
- Rechtliche und regulatorische Konsequenzen.
- Vertragliche Verpflichtungen.
- Reputationsschäden.
- Beeinträchtigungen betroffener Personen.

Die Bewertung erfolgt anhand der in `04_bewertungsskalen.md` definierten Kriterien.

### 7.2 Bewertung der Eintrittswahrscheinlichkeit

Die Eintrittswahrscheinlichkeit beschreibt, wie realistisch das Eintreten eines identifizierten Risikoszenarios unter Berücksichtigung der vorhandenen Rahmenbedingungen ist.

Bei der Einschätzung werden unter anderem folgende Faktoren berücksichtigt:

- Art und Häufigkeit der möglichen Bedrohung.
- Technische und organisatorische Rahmenbedingungen.
- Vorhandene Schwachstellen.
- Externe Abhängigkeiten und Angriffsflächen.
- Bereits implementierte Sicherheitsmaßnahmen.
- Bekannte Vorfälle und vergleichbare Erfahrungen, sofern entsprechende Informationen vorliegen.

Die Bewertung erfolgt anhand der festgelegten Wahrscheinlichkeitsskala in `04_bewertungsskalen.md`.

### 7.3 Bestimmung des Risikoniveaus

Aus der Bewertung der Eintrittswahrscheinlichkeit und der möglichen Auswirkungen wird das jeweilige Risikoniveau abgeleitet.

Die Kombination der Bewertungswerte erfolgt anhand der in `04_bewertungsskalen.md` definierten Bewertungsmatrix.

Dabei wird zwischen folgenden Risikozuständen unterschieden:

- **Ausgangsrisiko:** Einschätzung des Risikos vor Berücksichtigung bestehender Sicherheitsmaßnahmen.
- **Aktuelles Risiko:** Einschätzung unter Berücksichtigung bereits vorhandener Sicherheitsmaßnahmen, soweit deren Existenz und Wirksamkeit nachvollziehbar angenommen oder belegt werden können.
- **Restrisiko:** Verbleibendes Risiko nach Umsetzung und Wirksamkeit der geplanten Risikobehandlungsmaßnahmen.

Bei der Bewertung wird berücksichtigt, dass dokumentierte oder geplante Maßnahmen nicht automatisch als wirksam gelten. Ihre tatsächliche Umsetzung und Wirksamkeit muss gesondert betrachtet werden.

---

## 8. Risikobewertung

Im Rahmen der Risikobewertung werden die ermittelten Risikoniveaus mit den festgelegten Risikokriterien und Akzeptanzgrenzen verglichen.

Ziel ist es, zu entscheiden, welche Risiken behandelt werden müssen und welche unter bestimmten Voraussetzungen akzeptiert werden können.

Die Risikobewertung dient insbesondere:

- Der Priorisierung identifizierter Risiken.
- Der Ermittlung des erforderlichen Handlungsbedarfs.
- Der Vorbereitung von Managemententscheidungen.
- Der Festlegung geeigneter Maßnahmen zur Risikobehandlung.

Die Einteilung in Risikoklassen sowie die jeweiligen Akzeptanzgrenzen werden in `04_bewertungsskalen.md` festgelegt.

Risiken, die außerhalb der definierten Akzeptanzgrenzen liegen, müssen einer entsprechenden Risikobehandlung zugeführt werden.

Auch akzeptierbare Risiken werden dokumentiert und regelmäßig überprüft.

---

## 9. Risikobehandlung

Nach der Risikobewertung wird für jedes Risiko festgelegt, wie mit dem identifizierten Risikoniveau umgegangen werden soll.

Die Auswahl der Risikobehandlung richtet sich nach der Höhe des Risikos, den möglichen Auswirkungen, den betrieblichen Anforderungen und dem Aufwand geeigneter Maßnahmen.

Grundsätzlich werden folgende Behandlungsoptionen berücksichtigt:

| Option | Beschreibung |
|---|---|
| Risikovermeidung | Die risikobehaftete Tätigkeit wird beendet oder nicht aufgenommen. |
| Risikominderung | Geeignete technische oder organisatorische Maßnahmen reduzieren Wahrscheinlichkeit oder Auswirkungen. |
| Risikoteilung | Teile der finanziellen oder operativen Folgen werden beispielsweise durch Versicherungen oder vertragliche Vereinbarungen geteilt. |
| Risikoakzeptanz | Das verbleibende Risiko wird nach nachvollziehbarer Bewertung und Freigabe bewusst akzeptiert. |

Die gewählte Behandlungsoption wird für jedes Risiko dokumentiert und begründet.

### 9.1 Auswahl geeigneter Sicherheitsmaßnahmen

Bei der Ableitung geeigneter Maßnahmen werden insbesondere folgende Aspekte berücksichtigt:

- Bezug zum identifizierten Risikoszenario.
- Erwartete Reduzierung der Eintrittswahrscheinlichkeit oder der Auswirkungen.
- Technische und organisatorische Umsetzbarkeit.
- Wirtschaftlichkeit und Verhältnismäßigkeit.
- Gesetzliche, regulatorische und vertragliche Anforderungen.

Die Maßnahmen können sowohl technischer als auch organisatorischer Natur sein.

Beispiele:

- Einführung verpflichtender Mehr-Faktor-Authentifizierung.
- Regelmäßige Überprüfung privilegierter Zugriffsrechte.
- Verbesserung der Netzwerksegmentierung.
- Einführung verbindlicher Patch-Management-Prozesse.
- Durchführung regelmäßiger Awareness-Schulungen.
- Verbesserung der Datensicherungs- und Wiederherstellungsverfahren.

### 9.2 Berücksichtigung von ISO/IEC 27001 Annex A

Die ausgewählten Maßnahmen werden anhand ihrer Relevanz für die identifizierten Risiken und weiterer Anforderungen überprüft.

Hierbei werden die Referenzmaßnahmen aus Annex A der ISO/IEC 27001:2022 als Orientierung herangezogen.

Die Anwendbarkeit einzelner Maßnahmen wird anhand der jeweiligen Rahmenbedingungen und Anforderungen bewertet.

Die Ergebnisse werden in einer Erklärung zur Anwendbarkeit (Statement of Applicability, SoA) dokumentiert.

Diese enthält insbesondere:

- Die als notwendig identifizierten Maßnahmen.
- Die Begründung für ihre Aufnahme.
- Den jeweiligen Implementierungsstatus.
- Die Begründung für ausgeschlossene Annex-A-Maßnahmen.

Nicht jede Annex-A-Maßnahme ist automatisch für jedes Unternehmen anwendbar. Die Auswahl muss nachvollziehbar begründet werden.

### 9.3 Risikobehandlungsplan

Die ausgewählten Maßnahmen werden in einem Risikobehandlungsplan dokumentiert.

Dieser enthält mindestens:

- Zugehörige Risiko-ID.
- Beschreibung der geplanten Maßnahme.
- Verantwortliche Rolle.
- Geplanten Umsetzungstermin.
- Priorität der Maßnahme.
- Erwartete Risikoreduzierung.
- Umsetzungsstatus.

Der Plan dient als Grundlage für die weitere Umsetzung und Überwachung der Maßnahmen.

### 9.4 Bewertung des Restrisikos

Nach der geplanten Risikobehandlung wird das verbleibende Risiko erneut bewertet.

Dabei wird untersucht, in welchem Umfang die vorgesehenen Maßnahmen die Eintrittswahrscheinlichkeit oder die möglichen Auswirkungen reduzieren.

Das Restrisiko muss innerhalb der definierten Akzeptanzgrenzen liegen oder durch eine entsprechende Entscheidung des zuständigen Risikoeigners behandelt werden.

Die Akzeptanz von Restrisiken wird nachvollziehbar dokumentiert.

---

## 10. Rollen und Verantwortlichkeiten

Die Durchführung und Steuerung des Risikomanagementprozesses erfordert eine klare Zuordnung von Aufgaben und Verantwortlichkeiten.

Grundsätzlich werden folgende Rollen berücksichtigt:

| Rolle | Verantwortung |
|---|---|
| Geschäftsführung | Übergeordnete Verantwortung und Entscheidungen innerhalb der festgelegten Risikobefugnisse |
| CISO | Fachliche Steuerung und Überwachung des Informationssicherheitsrisikomanagements |
| Risikoeigner | Bewertung, Behandlung und Akzeptanz des zugeordneten Risikos |
| Asset Owner | Bereitstellung von Informationen und Verantwortung für den jeweiligen Informationswert |
| IT-Betrieb | Unterstützung bei der Bewertung und Umsetzung technischer Maßnahmen |
| Datenschutzbeauftragter | Beratung bei datenschutzrelevanten Fragestellungen |
| Bereichsleitungen | Unterstützung bei der Identifikation und Bewertung bereichsspezifischer Risiken |

Die konkreten Aufgaben, Zuständigkeiten und Entscheidungsbefugnisse werden in `06_rollen_und_verantwortlichkeiten.md` näher beschrieben.

---

## 11. Dokumentation und Kommunikation

Alle wesentlichen Ergebnisse der Risikobeurteilung und Risikobehandlung werden nachvollziehbar dokumentiert.

Hierzu gehören insbesondere:

- Identifizierte Informationssicherheitsrisiken.
- Zugehörige Informationswerte und Geschäftsprozesse.
- Bedrohungen und Schwachstellen.
- Begründungen der Risikobewertungen.
- Zugeordnete Risikoeigner.
- Festgelegte Behandlungsmaßnahmen.
- Entscheidungen zur Risikoakzeptanz.
- Ergebnisse der Restrisikobewertung.

Das Risikoregister bildet die zentrale Dokumentationsgrundlage für die identifizierten Risiken.

Die Maßnahmen werden mit den zugehörigen Risiko-IDs verknüpft, damit der Zusammenhang zwischen Risikoidentifikation, Risikobewertung und Risikobehandlung nachvollziehbar bleibt.

Wesentliche Risiken und erforderliche Entscheidungen werden den zuständigen Verantwortlichen und gegebenenfalls der Geschäftsführung zur Verfügung gestellt.

---

## 12. Überwachung und Überprüfung

Die Risikobewertungen und die Wirksamkeit der Risikobehandlungsmaßnahmen müssen regelmäßig überprüft werden.

Eine erneute Bewertung ist insbesondere erforderlich, wenn:

- Wesentliche Änderungen an der IT-Infrastruktur erfolgen.
- Neue Anwendungen oder Cloud-Dienste eingeführt werden.
- Geschäftsprozesse verändert oder erweitert werden.
- Neue Schwachstellen oder Bedrohungen bekannt werden.
- Sicherheitsvorfälle auftreten.
- Lieferanten oder externe Dienstleister ausgetauscht werden.
- Gesetzliche oder regulatorische Anforderungen verändert werden.

Für die Fallstudie wird eine regelmäßige Überprüfung der Risikobewertungen mindestens einmal jährlich als Planungsannahme vorgesehen.

Die Ergebnisse der Überprüfungen werden dokumentiert. Bei Bedarf werden Risikobewertungen und Maßnahmenpläne aktualisiert.

---

## 13. Berücksichtigung des Datenschutzes

Datenschutzbezogene Aspekte werden ergänzend in den Risikomanagementprozess integriert.

Als Informationsgrundlage dient insbesondere das Verzeichnis von Verarbeitungstätigkeiten (VVT) der Noventis Group GmbH.

Bei Verarbeitungstätigkeiten mit personenbezogenen Daten werden unter anderem folgende Aspekte berücksichtigt:

- Kategorien personenbezogener Daten.
- Betroffene Personengruppen.
- Verarbeitungszwecke.
- Zugriffs- und Berechtigungskonzepte.
- Speicherdauer und Löschprozesse.
- Externe Empfänger und Dienstleister.
- Technische und organisatorische Maßnahmen.

Neben den Auswirkungen auf die Informationssicherheit werden auch mögliche Folgen für die Rechte und Freiheiten betroffener Personen betrachtet.

Die ISMS-Risikoanalyse ersetzt keine eigenständige datenschutzrechtliche Prüfung. Insbesondere eine gegebenenfalls erforderliche Datenschutz-Folgenabschätzung nach Art. 35 DSGVO ist gesondert zu beurteilen.

---

## 14. Annahmen und Grenzen der Methodik

Die Methodik wird im Rahmen einer fiktiven Fallstudie entwickelt und angewendet.

Daraus ergeben sich folgende Einschränkungen:

- Unternehmensdaten, Geschäftsprozesse und IT-Systeme sind modellhafte Annahmen.
- Risikobewertungen beruhen auf den verfügbaren Projektinformationen.
- Eine technische Überprüfung der beschriebenen IT-Infrastruktur findet nicht statt.
- Die tatsächliche Wirksamkeit bestehender Sicherheitsmaßnahmen wird nicht durch technische Tests nachgewiesen.
- Nicht dokumentierte Sicherheitsmaßnahmen werden nicht automatisch als nicht vorhanden bewertet.
- Die Bewertungsergebnisse stellen keine verbindliche Aussage über die Sicherheit eines realen Unternehmens dar.

Alle wesentlichen Annahmen und methodischen Einschränkungen werden ergänzend in `05_annahmen_und_grenzen.md` dokumentiert.

