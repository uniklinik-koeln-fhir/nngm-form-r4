## {{page-title}}

**Name**: "Profile_nNGM_MII_PR_MolGen_MolekulargenetischerBefundbericht" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM_MII_PR_MolGen_MolekulargenetischerBefundbericht}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM_MII_PR_MolGen_MolekulargenetischerBefundbericht```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM_MII_PR_MolGen_MolekulargenetischerBefundbericht, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|DiagnosticReport.specimen.reference|NGS DNA Panel|Tumormaterial|
|DiagnosticReport.effective|NGS DNA Panel|Datum Untersuchungsergebnis|
|DiagnosticReport.extension:analysispossible|NGS DNA Panel|Analyse möglich|
|DiagnosticReport.extension:analysisimpossiblereason|NGS DNA Panel|Grund|
|DiagnosticReport.extension:otherAnalysisImpossibleReason|NGS DNA Panel|Bitte spezifizieren Sie "Anderes"|
|DiagnosticReport.conclusion|NGS DNA Panel|Kommentar|
|DiagnosticReport.extension:ngspanelversion|NGS DNA Panel|NGS Lung Panel Version|
|DiagnosticReport.extension:ngspanelversion|NGS DNA Panel|Bitte spezifizieren Sie "Anderes"|
|DiagnosticReport.deviceName.name|NGS DNA Panel|NGS Sequencer|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/analysisimpossiblereason}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|DiagnosticReport.extension:ngspanelversion|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/ngspanelversion}}|
|DiagnosticReport.extension:analysispossible|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/analysispossible}}|
|DiagnosticReport.extension:analysisimpossiblereason|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/analysisimpossiblereason}}|
|DiagnosticReport.extension:otherAnalysisImpossibleReason|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/otherAnalysisImpossibleReason}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM_MII_PR_MolGen_MolekulargenetischerBefundbericht, snapshot}}
