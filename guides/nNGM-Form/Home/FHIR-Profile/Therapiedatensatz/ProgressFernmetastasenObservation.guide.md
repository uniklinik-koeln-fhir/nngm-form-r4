## {{page-title}}

Beschreibung vom Progress und Fernmetastasen (Lokalisation und Datum)

**Name**: "Profile_nNGM_Observation_Progress_Fernmetastasen" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Observation-Fernmetastasen}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Observation-Fernmetastasen```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Observation-Fernmetastasen, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.effective[x]|Systemische Therapie|Datum des Progresses|
|Observation.bodySite|Systemische Therapie|Metastasenlokalisationen|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.bodySite.coding:icd-o-3.code|{{link:https://www.medizininformatik-initiative.de/fhir/ext/modul-onko/ValueSet/mii-vs-onko-icdo3-topographie}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Profile-nNGM-Observation-Fernmetastasen, snapshot}}
