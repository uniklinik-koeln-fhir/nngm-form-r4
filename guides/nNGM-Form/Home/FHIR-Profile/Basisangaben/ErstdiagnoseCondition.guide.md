## {{page-title}}

Diese Profile beschreibt Erstdiagnose einer spezfischen Tumorerkrankung innerhalb des nNGM-Projektes, um diese für andere Fälle wiedererkennen zu können.

**Name**: "Profile_nNGM_Condition_FirstDiagnosis" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis, diff}}

<br>

**Erläuterungen**

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




<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Condition/nNGM/FirstDiagnosis, snapshot}}
