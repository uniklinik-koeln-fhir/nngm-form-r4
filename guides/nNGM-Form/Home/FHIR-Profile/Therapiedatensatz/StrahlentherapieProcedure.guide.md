## {{page-title}}

Strahlentherapie-Profil für das nNGM-Projekt, basierend auf MII_PR_Onko_Strahlentherapie. Mapping zu nNGM-Schema radioTherapy.

**Name**: "Profile_nNGM_Procedure_Strahlentherapie" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Strahlentherapie}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Strahlentherapie```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Strahlentherapie, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Procedure.performed.start|Strahlentherapie|Therapiebeginn|
|Procedure.performed.end|Strahlentherapie|Therapieende|
|Procedure.bodySite.coding.code|Strahlentherapie|Zielgebiet|
|Procedure.bodySite:http://fhir.de/StructureDefinition/seitenlokalisation|Strahlentherapie|Seite Zielgebiet|
|Procedure.extension.value.coding.code|Strahlentherapie|Intention der Strahlentherapie|
|Procedure.extension.value.text|Strahlentherapie|Sonstiges|
|Procedure.extension.value.coding.code|Strahlentherapie|Stellung zu operativer Therapie|
|Procedure.extension.value.value|Strahlentherapie|Einzeldosis pro Tag|
|Procedure.extension.value.value|Strahlentherapie|Gesamtdosis|
|Procedure.extension.value.coding.code|Strahlentherapie|Boost durchgeführt|
|Procedure.outcome.coding.code|Strahlentherapie|Ende der Bestrahlung|
|Procedure.note.text|Strahlentherapie|Bemerkungen|
|Procedure.performer.actor|Strahlentherapie|Durchführende Einrichtung|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Procedure.outcome.coding.code|([https://www.medizininformatik-initiative.de/fhir/ext/modul-onko/ValueSet/mii-vs-strahlentherapie-ende-grund](https://www.medizininformatik-initiative.de/fhir/ext/modul-onko/ValueSet/mii-vs-strahlentherapie-ende-grund))|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Profile-nNGM-Procedure-Strahlentherapie, snapshot}}
