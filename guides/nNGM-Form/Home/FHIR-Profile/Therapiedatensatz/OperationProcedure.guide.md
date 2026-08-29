## {{page-title}}

Procedure-Profil OP für das nNGM-Projekt basierend auf MII-PR_Onko_Operation. Enthält alle Profile-nNGM-Procedure-Operation-Felder und erforderliche Erweiterungen.

**Name**: "Profile_nNGM_Procedure_Operation" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Operation}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Operation```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Operation, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Procedure.performed|Operation|Operationsdatum|
|Procedure.extension.value.coding.code|Operation|Operative Intention|
|Procedure.code.coding.code|Operation|Art der Resektion|
|Procedure.code.text|Operation|Bitte spezifizieren Sie "Sonstiges"|
|Procedure.outcome.coding.code|Operation|Resektionsstatus|
|Procedure.complication.coding.code|Operation|Ausgang mit Todesfolge|
|Procedure.bodySite|Operation|Lokalisation|
|Procedure.bodySite.text|Operation|Andere|
|Procedure.code.coding:http://fhir.de/StructureDefinition/seitenlokalisation|Operation|Seitenlokalisation|
|Procedure.extension:Lymphadenektomie.value[x]|Operation|Lymphadenektomie|
|Procedure.note.text|Operation|Bemerkungen|
|Procedure.performer.actor|Operation|Durchführende Einrichtung|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-jnu}}|
|Procedure.code.coding:resectionType|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-resectiontype}}|
|Procedure.bodySite.coding:oBDS-Lokalisation|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-lokalisation}}|
|Procedure.complication:outcomeDeath.coding|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-jnu}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Procedure.extension:Lymphadenektomie|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/nngm-ex-operation-lymphadenectomy}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Operation, snapshot}}
