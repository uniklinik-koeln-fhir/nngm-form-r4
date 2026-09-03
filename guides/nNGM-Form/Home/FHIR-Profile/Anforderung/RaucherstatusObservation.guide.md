## {{page-title}}

Dieses Profil beschreibt den Raucherstatus des Patienten zum Zeitpunkt der Diagnostik-Anforderung innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Observation_Raucherstatus" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/raucherstatus}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/raucherstatus```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/raucherstatus, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.value[x]|Raucherstatus|Raucherstatus|
|Observation.component:nichtraucherSeit.value[x]|Raucherstatus|Nichtraucher seit|
|Observation.component:packYears.value[x]|Raucherstatus|Pack years|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/raucherstatus}}|
|Observation.component:packYears.value[x]:valueQuantity.code|Fixed Value - {PackYears} - ([http://unitsofmeasure.org](http://unitsofmeasure.org))|
|Observation.component:nichtraucherSeit.value[x]:valueQuantity.code|Fixed Value - a - ([http://unitsofmeasure.org](http://unitsofmeasure.org))|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/raucherstatus, snapshot}}
