## {{page-title}}

Dieses Profil beschreibt einen pseudonymisierten Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Patient_PatientPseudonymisiert" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Patient.birthDate|||
|Patient.gender|||

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/izt}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Patient.deceased[x]:deceasedDateTime.extension:informationsquelleTodesdatum|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/izt}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert, snapshot}}
