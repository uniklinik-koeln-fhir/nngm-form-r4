## {{page-title}}

Dieses Profil beschreibt den Vitalstatus eines Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Observation_Vitalstatus" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Vitalstatus}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Vitalstatus```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Vitalstatus, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.value[x]|Vitalstatus|Ist Verstorben|
|Observation.value[x].extension:datumLetzterKontakt|Vitalstatus|Datum letzter Kontakt|
|Observation.value[x].extension:informationsquelleLetzterKontakt|Vitalstatus|Informationsquelle zum letzten Kontakt|
|Observation.value[x].extension:todesdatum|Vitalstatus|Todesdatum|
|Observation.value[x].extension:informationsquelleTodesdatum|Vitalstatus|Informationsquelle zum Tod|
|Observation.value[x].extension:lostToFollowUp|Vitalstatus|lost to follow up|
|Observation.effective[x]|Vitalstatus|Erhebungsdatum|
|Observation.value[x]|Vitalstatus|Vitalstatus|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/izt}}|
|Extension.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/izt}}|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/Vitalstatus}}|

<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Observation.value[x].extension:todesdatum|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/todesdatum}}|
|Observation.value[x].extension:informationsquelleTodesdatum|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/iqt}}|
|Observation.value[x].extension:datumLetzterKontakt|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/datumLetzterKontakt}}|
|Observation.value[x].extension:informationsquelleLetzterKontakt|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/iqlk}}|
|Observation.value[x].extension:lostToFollowUp|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/lostToFollowUp}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Vitalstatus, snapshot}}
