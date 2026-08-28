### Kompatibilität zu anderen Initiativen

Aufgrund des Fokus auf die Erhebung, Verarbeitung und Analyse zum Zwecker der Forschung und Versorgung im nNGM-Projekt ist der Datensatz breit gefächert und basier in Teilen auf bereits bestehenden Projekten. Um eine Interoperabilität zu fördern erfolgt innerhalb dieses Leitfadens eine Abgleich der Kompabilität zu bereits bestehnden FHIR-Profilen. Inbesondere werden folgende Projekte betrachtet:

* [Deutsche Basisprofile - Onkologie](https://simplifier.net/basisprofileonkologie), herausgegeben durch [HL7 Deutschland](https://simplifier.net/organization/hl7deutschlandev)
* [Datenmodell des DKTK und der Onkologischen Spitzenzentren - Version 1.1.1](https://simplifier.net/oncology), herausgegeben durch das [Deutschen Konsortium für Translationale Krebsforschung](https://dktk.dkfz.de).
* [Einheitlicher onkologischer Basisdatensatz - Version 2021](https://basisdatensatz.de/datensatz.php), herausgegeben durch [die Arbeitsgemeinschaft Deutscher Tumorzentren e. V. (ADT) und die Gesellschaft der epidemiologischen Krebsregister in Deutschland (GEKID)](https://basisdatensatz.de)

Der Abgleich der Kompabilität kann auf Anfrage erweitert werden. Das nNGM-Projekt ist bemüht eine Interoperabilität zu weiteren Projekten zu erziehlen.

Es ist zu beachten, dass das Vorhandensein von unterschiedlichen Profilen nicht zwangsläufig mit einem Implementierungsmehraufwand oder Transformation von Daten einhergeht. Vielmehr werden somit projektspezfische Requirements (z.B. durch must-support Felder) ausgedrückt. Es besteht die Absicht, dass alle Projekte sich auf die gleichen grundlegenden Datenobjekte beziehen welche eine projektunabhänige Abbildung in FHIR besitzen. Bei der Betrachtung der Kompatibilität wird stets von Implementierungen ausgegangen, die exakt die Minimalanforderungen (Pflichtfelder, Must-Support-Felder) der nNGM-Spezifikation umsetzen.