## {{page-title}}

Medikation der Systemische Therapie. Dieses Profil beschreibt die konkreten Medikationen/Schemata, die im Rahmen der systemischen Therapie dokumentiert wurden. Medikation der Systemische Therapie. Dieses Profil beschreibt die konkreten Medikationen/Schemata, die im Rahmen der systemischen Therapie dokumentiert wurden.

**Name**: "Profile_nNGM_MedicationStatement_Medication" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-MedicationStatement-Medication, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|MedicationStatement.extension:offLabelUse.value[x]|Systemische Therapie|Off-Label-Use|
|MedicationStatement.effective.start|Systemische Therapie|Therapiebeginn|
|MedicationStatement.effective.end|Systemische Therapie|Therapieende|
|MedicationStatement.extension:CyclesCount.value[x]|Systemische Therapie|Anzahl der Zyklen|
|MedicationStatement.extension:MaintainceTherapy.value[x]|Systemische Therapie|Ist Erhaltungstherapie|
|MedicationStatement.note.text|Systemische Therapie|Bemerkungen|
|MedicationStatement.medication.coding.code|Systemische Therapie|Therapieschema|
|MedicationStatement.medication.coding.code|Systemische Therapie|Wirkstoff|

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
