## {{page-title}}

Diese Profile sind die Basis-Profile für die TKI-Resistenztestungen innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Observation_TkiResistenz" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | EDC-Label | Beschreibung |
|-----------------|-----------|--------------|
|Observation.effective[x]|Datum||
|Observation.component:tkiTherapie.value[x]|Therapie||


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/tki-resistenz}}|
|Observation.component:tkiTherapie.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/SystemischeTherapieMedikament}}|




<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/tki-resistenz, snapshot}}
