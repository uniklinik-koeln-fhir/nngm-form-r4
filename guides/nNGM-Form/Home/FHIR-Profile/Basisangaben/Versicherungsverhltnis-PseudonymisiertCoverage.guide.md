## {{page-title}}

Dieses Profil beschreibt ein pseudonymisiertes Versicherungsverhältnis eines Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Coverage_VersicherungsverhaeltnisPseudonymisiert" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Coverage/nNGM/pseudonymisiert, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Coverage.payor.display|Krankenkasse|Krankenkasse|
|Coverage.type|Krankenkasse|Versicherungsart|

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
