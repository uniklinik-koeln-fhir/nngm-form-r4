## {{page-title}}

Diese Profile beschreiben das eingereichte Tumormaterial innerhalb des nNGM-Projektes. Dabei handelt es sich explizit nicht um einen Tumorblock, sondern die Gewebeprobe oder Liquid Biopsy

**Name**: "Profile_nNGM_Specimen_Tumormaterial" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Specimen}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Specimen```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Specimen, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Specimen.type|Tumormaterial|Materialtyp|
|Specimen.identifier|Tumormaterial|Biopsie-ID/Eingangsnummer|
|Specimen.collection.collected[x]|Tumormaterial|Entnahmedatum|
|Specimen.extension:entnahmeKontext.value[x]|Tumormaterial|Entnahmekontext|
|Specimen.extension:tumorzellgehalt|Tumormaterial|Tumorzellgehalt in %|
|Specimen.extension:tumormaterialLagertBei|Tumormaterial|Tumormaterial lagert bei|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/aufenthaltsart}}|
|Specimen.type.coding:ncit|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/MaterialTyp}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Specimen.extension:entnahmeKontext|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/aufenthaltsart}}|
|Specimen.extension:tumormaterialLagertBei|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/specimen-tumormaterial-lagert-bei}}|
|Specimen.extension:tumorzellgehalt|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/tumorzellgehalt}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Specimen, snapshot}}
