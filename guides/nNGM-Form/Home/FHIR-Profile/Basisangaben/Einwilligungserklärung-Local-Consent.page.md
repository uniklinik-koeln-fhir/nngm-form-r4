## {{page-title}}

Dieses Profil beschreibt die Einwilligungserklärung innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Consent_Einwilligungserklaerung" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent-Local}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent-Local```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent-Local, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Consent.provision.type|Zustimmungen nNGM|Alle vorgesehenen Kreuze wurden mit "Ja" beantwortet.|
|Consent.dateTime|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.extension:revokeDate|Zustimmungen nNGM|Datum des Widerrufs|
|Consent.extension:localConsentName|Zustimmungen nNGM|Bezeichnung (+Version) der (lokalen) Einwilligungserklärung|
|Consent.extension:validityDuration|Zustimmungen nNGM|Geltungsdauer|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Consent.status|Fixed Value - active - ([http://hl7.org/fhir/ValueSet/consent-state-codes](http://hl7.org/fhir/ValueSet/consent-state-codes))|
|Consent.scope.coding.code|Fixed Value - patient-privacy - ([http://terminology.hl7.org/CodeSystem/consentscope](http://terminology.hl7.org/CodeSystem/consentscope))|
|Consent.category.coding.code|Fixed Value - 59284-0 - ([http://loinc.org](http://loinc.org))|


<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Consent.extension:validityDuration|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/ValidityDuration}}|
|Consent.extension:revokeDate|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/RevokeDate}}|
|Consent.extension:localConsentName|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/LocalConsentName}}|


<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent-Local, snapshot}}
