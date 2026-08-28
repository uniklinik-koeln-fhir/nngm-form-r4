## {{page-title}}

Dieses Profil beschreibt den Einwilligungserklärung innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Consent_Einwilligungserklaerung" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | Type | Instrument | Label |
|-----------------|------|------------|-------|
|Consent.provision.type|1a|Zustimmungen nNGM|Unterschrieben|
|Consent.dateTime|1a|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|1b|Zustimmungen nNGM|Unterschrieben|
|Consent.dateTime|1b|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|2|Zustimmungen nNGM|Unterschrieben|
|Consent.dateTime|2|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|TE|Zustimmungen nNGM|Der Patient hat alle vorgesehenen Unterschriften hinterlegt.|
|Consent.dateTime|TE|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|DS|Zustimmungen nNGM||
|Consent.dateTime|DS|Zustimmungen nNGM||
|Consent.provision.type|MD|Zustimmungen nNGM||
|Consent.dateTime|MD|Zustimmungen nNGM||
|Consent.provision.type|ST|Zustimmungen nNGM||
|Consent.dateTime|ST|Zustimmungen nNGM||
|Consent.provision.type|WPI|Zustimmungen nNGM|Weitergabe pseudonymisierter krankheitsbezogener Daten (MDAT) innerhalb des nNGM und an kooperierende Partner - Unterschrieben|
|Consent.dateTime|WPI|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|WP|Zustimmungen nNGM|Weitergabe von MDAT und Resttumorproben innerhalb des nNGM und an kooperierende Partner - Unterschrieben|
|Consent.dateTime|WP|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|WD|Zustimmungen nNGM|Weitergabe pseudonymisierter krankheitsbezogener Daten (MDAT) in ein Drittland - Unterschrieben|
|Consent.dateTime|WD|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|WR|Zustimmungen nNGM|Weitergabe von MDAT und Resttumorproben in ein Drittland - Unterschrieben|
|Consent.dateTime|WR|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|WPK|Zustimmungen nNGM|Weitergabe pseudonymisierter krankheitsbezogener Daten (MDAT) zur kommerziellen Nutzung - Unterschrieben|
|Consent.dateTime|WPK|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|WK|Zustimmungen nNGM|Weitergabe von MDAT und Resttumorproben zur kommerziellen Nutzung - Unterschrieben|
|Consent.dateTime|WK|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|KW|Zustimmungen nNGM|Kontaktaufnahme des nNGM-Zentrums zu einem späteren Zeitpunkt zur Gewinnung weiterer Informationen über den Behandlungsverlauf - Unterschrieben|
|Consent.dateTime|KW|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|KE|Zustimmungen nNGM|Kontaktaufnahme des nNGM-Zentrums zum Zweck des Einschlusses in eine mögliche infrage kommende neue Studie - Unterschrieben|
|Consent.dateTime|KE|Zustimmungen nNGM|Datum der Patientenunterschrift|
|Consent.provision.type|RD|Zustimmungen nNGM|Rückmeldung wichtiger gesundheitsrelevanter Ergebnisse (Zufallsfunde) - Unterschrieben|
|Consent.dateTime|RD|Zustimmungen nNGM|Datum der Patientenunterschrift|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Consent.status|Fixed Value - active - ([http://hl7.org/fhir/ValueSet/consent-state-codes](http://hl7.org/fhir/ValueSet/consent-state-codes))|
|Consent.scope.coding.code|Fixed Value - patient-privacy - ([http://terminology.hl7.org/CodeSystem/consentscope](http://terminology.hl7.org/CodeSystem/consentscope))|
|Consent.category.coding.code|Fixed Value - 59284-0 - ([http://loinc.org](http://loinc.org))|
|Consent.policyRule|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-consent-policy}}|




<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/Consent, snapshot}}
