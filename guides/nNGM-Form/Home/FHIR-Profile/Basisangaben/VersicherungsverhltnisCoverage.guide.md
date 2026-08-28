## {{page-title}}

Dieses Profil beschreibt ein Versicherungsverhältnis eines Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Coverage_Versicherungsverhaeltnis" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Coverage}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Coverage```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Coverage, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | EDC-Label | Beschreibung |
|-----------------|-----------|--------------|
|Coverage.identifier:GKV-Identifier.type|GKV||
|Coverage.identifier:GKV-Identifier.value|KV-Nummer||
|Coverage.identifier:PKV-Identifier.type|PKV||
|Coverage.identifier:PKV-Identifier.value|KV-Nummer||
|Coverage.type|Versicherungsart|Ob es sich um eine GKV oder PKV Krankenversicherung handelt|
|Coverage.beneficiary|Patient|Eine Verknüpfung mit dem Patienten muss stets gegeben sein|
|Coverage.payor.display|Versicherer|Nur zugelassene Krankenkassen dürfen übermittelt werden. Die Liste kann auf Anfrage bei der nNGM Geschäfststelle erweitert werden|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Coverage.status|Fixed Value - active - ([http://hl7.org/fhir/ValueSet/fm-status](http://hl7.org/fhir/ValueSet/fm-status))|
|Coverage.type|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/krankenkassentypen}}|
|Coverage.payor.display|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/krankenkasse}}|




<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Coverage, snapshot}}
