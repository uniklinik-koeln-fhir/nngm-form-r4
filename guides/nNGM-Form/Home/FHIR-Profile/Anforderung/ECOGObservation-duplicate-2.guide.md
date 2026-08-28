## {{page-title}}

Dieses Profil beschreibt den ECOG-Status des Patienten zum Zeitpunkt der Diagnostik-Anforderung innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Observation_Ecog" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/ecog}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/ecog```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/ecog, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.value[x]|ECOG|ECOG|
|Observation.value[x]|Systemische Therapie|ECOG Performance Status bei Therapiebeginn|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/ecog}}|




<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/ecog, snapshot}}
