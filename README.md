# CAPA-Untersuchung - Medizintechnik

**Sprache: Deutsch | [English](README_EN.md)**

## Projektübersicht

Dieses Projekt dokumentiert eine simulierte CAPA-Untersuchung (Corrective and Preventive Action), die auf realen FDA-Rückrufdaten basiert. 

Im Mittelpunkt steht eine Nichtkonformität bei einem sterilen Inline-Filzer mit Entlüftungsfunktion, der als Bestandteil eines Infusionssystems eingesetzt wird. 

Anhand dieses Fallbeispiels wird ein strukturierter CAPA-Prozess dargestellt - von der Erfassung und Bewertung der Nichtkonformität über die systematische Ursachenanalyse bis zur Festlegung, Umsetzung und Wirksamkeitsprüfung geeigneter Korrektur- und Vorbeugungsmaßnahmen.

Ziel des Projekts ist es, theoretische Kenntnisse im Qualitätsmanagement und in der regulatorischen DOkumentation anhand eines praxisnahen Fallbeispiels anzuwenden. DEr Schwerpunkt liegt dabei auf der systematischen Fehleruntersuchung, der Entwicklung geeigneter Maßnahmen und der Überprüfung ihrer Wirksamkeit.

Die Untersuchung orientiert sich an den Anforderungen der **ISO 13485:2017**, **ISO 14971** und der **EU-Medizinprodukteverordnung (EU MDR 2017/745)**.

## Beschreibung des Szenarios

Das Szenario bezieht sich auf ein fiktives Medizintechnikunternehmen namens MedFluss GmbH. 

Die Untersuchung beginnt mit Kundenreklamationen über Flüssigkeitsaustritt an der Entlüftungsöffnung eines Inline-filters, der in Infusionssets verwendet wird. 

Im Rahmen der Fehleruntersuchung wird ein kleiner Fremdpartikel an der Sonotrode einer Ultraschallschweißanlage festgestellt. Dieser verursacht mikroskopisch kleine Beschädigungen an der hydrophoben Filtermembran, wodurch die Dichtheit des Filters beeinträchtigt wird. 

Die bestehenden Prüfverfahren können den Fehler nicht zuverlässig erkennen, da der Fremdpartikel mit bloßem Auge nicht sichtbar ist. Darüber hinaus lässt sich der festsitzende Partikel durch die regulären Reinigungsmaßnahmen nicht vollständig entfernen.

Die anschließende Ursachenanalyse ergibt, dass das festgelegte Prüfintervall nicht mehr an die aktuelle Produktionsmenge angepasst ist. Obwohl die Produktionszahlen seit der Produktionseinführung gestiegen sind, wurde das ursprüngliche Prüfkonzept nicht entsprechend überarbeitet. 

Auf Grundlage dieser Erkenntnisse werden gezielte Korrektur- und Vorbeugungsmaßnahmen definiert, umgesetzt und hinsichtlich ihrer Wirksamkeit überprüft. 


## Aufbau des CAPA-Berichts

Der CAPA-Bericht umfasst die wesentlichen Phasen einer systematischen Fehleruntersuchung und Maßnahmenbearbeitung. 

| Abschnitt | Beschreibung |
|---|---|
|1. CAPA-Identifikation|Erfassung der Nichtkonformität und Dokumentation der Ausgangssituation|
|2. Risikobewertung|Analyse möglicher Auswirkungen auf Produktqualität und Patientensicherheit|
|3. Sofortmaßnahmen|Festlegung kurzfristiger Maßnahmen zur Risikogrenzung|
|4. Ursachenanalyse|Systematische Untersuchung der Fehlerursachen mithilfe der 5-Why-Methode|
|5. Maßnahmenplanung|Definition und Umsetzung geeigneter Korrektur- und Vorbeugungsmaßnahmen|
|6. Verifizierung und Validierung|Überprüfung der Maßnahmen sowie erneute Prozessqualifizierung (IQ/OQ/PQ)|
|7. Wirksamkeitsprüfung|Überwachung der Maßnahmen über einen Zeitraum von 90 Tagen|
|8. CAPA-Abschluss|Bewertung der Ergebnisse, Dokumentation und formaler ABschluss|

## Eingesetzte Methoden und QM-Werkzeuge

Im Rahmen der simulierten Untersuchung werden verschiedene Methoden und Werkzeuge des Qualitätsmanagements angewendet: 
- **CAPA**: Strukturierte Bearbeitung von Nichtkonformität sowie Planung und Nachverfolgung von Korrektur- und Vorbeugungsmaßnahmen
- **5-Why.Methode**: Systematische Identifikation der zugrunde liegenden Fehlerursachen
- **Risikobewertung**: Einschätzung möglicher Auswirkungen auf die Produktsicherheit und Festlegung erforderlicher Maßnahmen
- **IQ/OQ/PQ** Qualifizierung und Validierung von Produktionsanlage und -prozessen
- **Wirksamkeitsprüfung**: Bewertung der langfristigen Wirksamkeit umgesetzter Maßnahmen anhand definierter Kriterien
- **Technische Dokumentation** Strukturierte und nachvollziehbare Dokumentation qualitätsrelevanter Informationen

## Normen und regulatorische Grundlagen

Die Untersuchung orientiert sich an folgenden Normen und regulatorischen Anforderungen_
- **ISO 13485:2016**: Qualitätsmanagement für Medizinprodukte
- **ISO 14971**: Anwendung des Risikomanagements auf Medizinprodukte
- **EU MDR 2017/745**: Europäische Medizinprodukteverordnung

Die genannten Anforderungen dienen als fachliche Grundlage für die Bewertung der Nichtkonformität, die Maßnahmenplanung sowie die Dokumentation des CAPA-Prozesses.

## CAPA-Berishte

Der vollständige CAPA-Untersuchungsbericht steht in deutscher und englischer Sprache zur Verfügung.

**Deutsch:**
[CAPA-Untersuchungsbericht – Deutsche Version](capa-bericht/CAPA-MF-1529-MFG-air-vent-leakage.md)

**English:**
[CAPA Investigation Report – English Version](capa-report/CAPA-MF-1529-MFG-air-vent-leakage.md)

## Repository-Struktur

```text
capa-investigation/
│
├── README.md
├── README_EN.md
│
├── capa-report/
│   └── CAPA-MF-1529-MFG-air-vent-leakage.md
│
└── capa-bericht/
    └── CAPA-MF-1529-MFG-air-vent-leakage.md
```

## Hinweis zum Projekt

Bei diesem Projekt handelt es sich um eine simulierte CAPA-Untersuchung zu Lern- und Demonstrationszwecken

Das dargestellte Unternehmen, die beteiligten Personen, Chargennummern, internen Verfahren sowie die unterstützenden Dokumente sind fiktiv.

Das zugrunde liegende Fehlerszenario orientiert sich an öffentlich zugänglichen FDA-Rückrufdaten. Die beschriebenen Untersuchungen und Maßnahmen stellen jedoch keine tatsächlichen Aktivitäten eines bestimmten Medizinprodukteherstellers dar.

Das Projekt dient dazu, theoretische Kenntnisse im Qualitätsmanagement, in der systematischen Ursachenanalyse sowie in der regulatorischen Dokumentation anhand eines praxisnahen Beispiels anzuwenden.

## Autorin

Jetal Bhanarkar

(Master: Biomedizintechnik, Bachelor: Maschinenbau)
