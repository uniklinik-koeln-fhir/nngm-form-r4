## {{page-title}}

None

**Name**: "Profile_nNGM_Observation_TkiResistenzRos1" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-ros1}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-ros1```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-ros1, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.effective[x]|Rezidiv/Progress + Resistenztestung|Datum|
|Observation.component:fusionPartner.value[x]|Rezidiv/Progress + Resistenztestung|Fusionspartner|
|Observation.component:tkiTherapie.value[x]|Rezidiv/Progress + Resistenztestung|Therapie|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tki-resistenz}}|
|Observation.component:tkiTherapie.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/SystemischeTherapieMedikament}}|
|Observation.code.coding.code|Fixed Value - C131071 - ([http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl](http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl))|




<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz-ros1, snapshot}}
