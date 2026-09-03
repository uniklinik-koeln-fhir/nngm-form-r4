## {{page-title}}

**Name**: "Profile_nNGM_Observation_TkiResistenzBraf" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-braf}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-braf```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-braf, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.effective[x]|Rezidiv/Progress + Resistenztestung|Datum|
|Observation.component:C13231|Rezidiv/Progress + Resistenztestung|Exon|
|Observation.component:48004-6|Rezidiv/Progress + Resistenztestung|c. (nach HGVS -Human Genome Variation Society)|
|Observation.component:48005-3|Rezidiv/Progress + Resistenztestung|p. (nach HGVS -Human Genome Variation Society)|
|Observation.component:tkiTherapie.value[x]|Rezidiv/Progress + Resistenztestung|Therapie|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tki-resistenz}}|
|Observation.component:tkiTherapie.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/SystemischeTherapieMedikament}}|
|Observation.code.coding.code|Fixed Value - C147077 - ([http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl](http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl))|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-braf, snapshot}}
