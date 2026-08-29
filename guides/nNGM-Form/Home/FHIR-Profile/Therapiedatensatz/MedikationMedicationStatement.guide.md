## {{page-title}}

Medikation der Systemische Therapie. Dieses Profil beschreibt die konkreten Medikationen/Schemata, die im Rahmen der systemischen Therapie dokumentiert wurden. Medikation der Systemische Therapie. Dieses Profil beschreibt die konkreten Medikationen/Schemata, die im Rahmen der systemischen Therapie dokumentiert wurden.

**Name**: "Profile_nNGM_MedicationStatement_Medication" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication, diff}}

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|MedicationStatement.medication[x]:medicationCodeableConcept.coding:atcClassDe|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-atc-2026}}|
|MedicationStatement.medication[x]:medicationCodeableConcept.coding:atcClassDe.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-atc-2026}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|MedicationStatement.extension:CyclesCount|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/nngm-ex-systemischetherapie-cyclescount}}|
|MedicationStatement.extension:MaintainceTherapy|{{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/nngm-ex-systemischetherapie-ismaintaincetherapy}}|
|MedicationStatement.extension:offLabelUse|{{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/nngm-ex-systemischetherapie-offlabeluse}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication, snapshot}}
