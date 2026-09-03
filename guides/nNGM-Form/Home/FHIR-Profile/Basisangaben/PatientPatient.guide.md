## {{page-title}}

Dieses Profil beschreibt einen Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Patient_Patient" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient, diff}}

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/izt}}|
|Patient.name:Name.prefix.extension:prefix-qualifier.value[x]|Fixed Value - AC|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Patient.deceased[x]:deceasedDateTime.extension:informationsquelleTod|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/izt}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient, snapshot}}
