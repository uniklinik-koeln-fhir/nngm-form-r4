## {{page-title}}

Diese Profile beschreibt Erstdiagnose einer spezfischen Tumorerkrankung innerhalb des nNGM-Projektes, um diese für andere Fälle wiedererkennen zu können.

**Name**: "Profile_nNGM_Condition_FirstDiagnosis" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Condition.onset[x]|Diagnosen|Diagnosedatum|
|Condition.bodySite|Diagnosen|Lokalisation|
|Condition.code|Diagnosen|Klassifikation|
|Condition.stage.summary|Diagnosen|genutzte UICC Version|
|Condition.stage.summary|Diagnosen|Stadium der Diagnose|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Condition.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/histologie-klassifikation}}|
|Condition.bodySite|{{link:http://uk-koeln.de/fhir/ValueSet/icd-o-3-topologie}}|
|Condition.stage.summary:uicc7|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/uicc-stage-v7}}|
|Condition.stage.summary:uicc8|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/uicc-stage-v8}}|
|Condition.stage.summary:uicc9|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/uicc-stage-v9}}|
|Condition.stage.summary:uiccU|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/uicc-stage-vU}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis, snapshot}}
