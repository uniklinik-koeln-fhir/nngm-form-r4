## {{page-title}}

**Name**: "Profile_nNGM_Observation_Tumorstadium" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tumorstadium}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tumorstadium```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tumorstadium, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.effective[x]|Tumorstadium|Datum|
|Observation.extension:ErstDiagnose.value[x]|Tumorstadium|Erstdiagnose|
|Observation.extension:kurativ-operabel.value[x]|Tumorstadium|Kurativ-operabel|
|Observation.extension:uicc-version.value[x]|Tumorstadium|Genutzte UICC Version|
|Observation.component:TNM-prefix.value[x]|Tumorstadium|Präfix|
|Observation.component:T.value[x]|Tumorstadium|Größe und Ausdehnung des Tumors|
|Observation.component:T.extension:praefix.value[x]|Tumorstadium|Präfix|
|Observation.component:T.extension:suffix.value[x]|Tumorstadium|Suffix|
|Observation.component:N.value[x]|Tumorstadium|Zahl und Lage der befallenen Lymphknoten|
|Observation.component:N.extension:praefix.value[x]|Tumorstadium|Präfix|
|Observation.component:M.value[x]|Tumorstadium|Abwesenheit oder Vorhandensein von Metastasen|
|Observation.component:M.extension:praefix.value[x]|Tumorstadium|Präfix|
|Observation.bodySite|Tumorstadium|Lokalisation|
|Observation.value[x]|Tumorstadium|UICC-Stadium|
|Observation.value[x]|Tumorstadium|Stadium der Diagnose|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/uiccVersion}}|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-suffix-t}}|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-cpu-praefix}}|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-cpu-praefix}}|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-cpu-praefix}}|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/uicc-stage}}|
|Observation.component:T.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-t}}|
|Observation.component:N.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-n}}|
|Observation.component:M.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-m}}|
|Observation.component:TNM-prefix.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tnm-ry-praefix}}|
|Observation.bodySite|{{link:http://uk-koeln.de/fhir/ValueSet/icd-o-3-topologie}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Observation.extension:kurativ-operabel|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tnm-kurativ-operabel}}|
|Observation.extension:ErstDiagnose|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tnm-erstdiagnose}}|
|Observation.extension:uicc-version|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/uiccVersion}}|
|Observation.component:T.extension:suffix|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tnm-suffix-t}}|
|Observation.component:T.extension:praefix|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tnm-cpu-praefix}}|
|Observation.component:N.extension:praefix|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tnm-cpu-praefix}}|
|Observation.component:M.extension:praefix|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tnm-cpu-praefix}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tumorstadium, snapshot}}
