## {{page-title}}

Dieses Profil beschreibt ein pseudonymisiertes Versicherungsverhältnis eines Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Coverage_VersicherungsverhaeltnisPseudonymisiert" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | EDC-Label | Beschreibung |
|-----------------|-----------|--------------|
|Coverage.type|Versicherungsart|Ob es sich um eine GKV oder PKV Krankenversicherung handelt|
|Coverage.beneficiary|Patient|Begünstigter Patient|
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
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert, snapshot}}
