## {{page-title}}

Response Beurteilung nach MTB/DNPM/nNGM

**Name**: "nNGM_PR_Response_Befund" ({{link:https://ngnm.de/fhir/StructureDefinition/nNGM-PR-Response-Befund}})

**Canonical**: ```https://ngnm.de/fhir/StructureDefinition/nNGM-PR-Response-Befund```

**Differential**

{{tree:https://ngnm.de/fhir/StructureDefinition/nNGM-PR-Response-Befund, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.value.coding.code|Systemische Therapie|Bestes Ansprechen|
|Observation.effective|Systemische Therapie|Bestes Ansprechen Datum|
|Observation.method.coding.code|Systemische Therapie|Beurteilung nach|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.method|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-response-befund-bestresponseassessmentby}}|
|Observation.method.coding.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-response-befund-bestresponseassessmentby}}|

<br>

**Snapshot**
{{tree:https://ngnm.de/fhir/StructureDefinition/nNGM-PR-Response-Befund, snapshot}}
