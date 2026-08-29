## {{page-title}}

Systemische Therapie(Therapielinie) Profil für das nNGM-Projekt, basierend auf der MII. Systemische Therapie.

**Name**: "Profile_nNGM_Procedure_Systemische_Therapie" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Procedure-Systemische-Therapie}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Procedure-Systemische-Therapie```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Procedure-Systemische-Therapie, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Procedure.code.coding.code|Systemische Therapie|Therapiefreie Zeit / Best Supportive Care|
|Procedure.performed.start|Systemische Therapie|Therapiefreie Zeit / Best Supportive Care - Start|
|Procedure.performed.end|Systemische Therapie|Therapiefreie Zeit / Best Supportive Care - Ende|
|Procedure.note.text|Systemische Therapie|Weitere Angaben (Therapieempfehlung)|
|Procedure.effectiveDateTime|Systemische Therapie|Datum (Therapieempfehlung)|
|Procedure.performed.start|Systemische Therapie|Beginn der Therapielinie|
|Procedure.performed.end|Systemische Therapie|Ende der Therapielinie|
|Procedure.extension.value.coding.code|Systemische Therapie|Therapeutische Intention|
|Procedure.extension.value.coding.code|Systemische Therapie|Stellung zu operativer Therapie|
|Procedure.extension:Therapyline.value[x]|Systemische Therapie|Line|
|Procedure.extension.value|Systemische Therapie|Therapiedokumentation bis|
|Procedure.partOf|Systemische Therapie|Therapie innerhalb einer klinischen Studie|
|Procedure.title|Systemische Therapie|Studienname / Kurztitel|
|Procedure.identifier.value|Systemische Therapie|Studien-ID|
|Procedure.identifier.value|Systemische Therapie|Studien-Register|
|Procedure.keyword.text|Systemische Therapie|Einschlusskriterium<br>genetische Variante(n)|
|Procedure.extension.value|Systemische Therapie|Off-Label-Use|
|Procedure.outcome.coding.code|Systemische Therapie|Grund für Therapieende/Therapiewechsel|
|Procedure.effective.start|Systemische Therapie|Therapiebeginn|
|Procedure.effective.end|Systemische Therapie|Therapieende|
|Procedure.extension.value|Systemische Therapie|Anzahl der Zyklen|
|Procedure.extension.value|Systemische Therapie|Ist Erhaltungstherapie|
|Procedure.value.coding.code|Systemische Therapie||
|Procedure.effective|Systemische Therapie|Bestes Ansprechen Datum|
|Procedure.method.coding.code|Systemische Therapie||
|Procedure.effective|Systemische Therapie|Datum des Progresses|
|Procedure.bodySite|Systemische Therapie|Metastasenlokalisationen|
|Procedure.note.text|Systemische Therapie|Bemerkungen|
|Procedure.performer.actor|Systemische Therapie|Durchführende Einrichtung|
|Procedure.medication.coding.code|Systemische Therapie|Therapieschema|
|Procedure.medication.coding.code|Systemische Therapie|Wirkstoff|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-systemischetherapie-basedonrecommendation}}|
|Procedure.extension:BasedOnRecommendation.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-systemischetherapie-basedonrecommendation}}|
|Procedure.extension:BasedOnRecommendation.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-systemischetherapie-basedonrecommendation}}|
|Procedure.code.coding:systemische_therapie_art|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-vs-systemischetherapie-therapieart}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Procedure.extension:Therapyline|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/nngm-ex-systemischetherapie-therapyline}}|
|Procedure.extension:BasedOnRecommendation|{{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/nngm-ex-systemischetherapie-basedonrecommendation}}|
|Procedure.extension:TherapyDate|{{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/nngm-ex-systemischetherapie-therapydate}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Procedure-Systemische-Therapie, snapshot}}
