## {{page-title}}

Dieses Profil beschreibt die Einwilligungserklärung innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Consent_Einwilligungserklaerung_V4" ({{link:http://uk-koeln.de/fhir/StructureDefinition/nNGM/ConsentV4}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/nNGM/ConsentV4```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/ConsentV4, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Type | Instrument | Label |
|-----------------|------|------------|-------|
|Consent.provision.type|1|Zustimmungen nNGM|Pflichtangabe für Teil 1 der Einwilligungserklärung:<br>Ist der Patient mit den Inhalten gemäß den Ziffern 1 - 7 einverstanden?|
|Consent.provision.type|1|Zustimmungen nNGM|Patient / gesetzlicher Vertreter (Vorsorgebevollmächtigter) hat unterschrieben|
|Consent.dateTime|1|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|EVND|Zustimmungen nNGM|1.1 - 1.3  Der Patient willigt in die Erhebung, Verarbeitung, Speicherung und wissenschaftliche Nutzung seiner Patientendaten wie in Punkt 1.1 bis 1.3 der Einwilligungserklärung und im Teil 1 der Patienteninformation beschrieben, ein.|
|Consent.dateTime|EVND|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|ÜNKKD|Zustimmungen nNGM|2.1 Der Patient willigt rückwirkend für die Daten der vergangenen 10 Kalenderjahre, sowie in die Übermittlung seiner Versicherungsnummer an die nNGM-Geschäftsstelle bzw. eine beauftragte Treuhandstelle, ein.|
|Consent.dateTime|ÜNKKD|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|ÜVN|Zustimmungen nNGM|2.2 Der Patient willigt ab dem Datum seiner Unterschrift für die Daten über einen Zeitraum von 10 Kalenderjahren, sowie in die Übermittlung seiner Versicherungsnummer an die nNGM-Geschäftsstelle bzw. eine beauftragte Treuhandstelle, ein.|
|Consent.dateTime|ÜVN|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|GLNB|Zustimmungen nNGM|3.1 – 3.2 Der Patient willigt in die Gewinnung, Lagerung und wissenschaftliche Nutzung seiner Biomaterialien (Gewebe und Blut), wie in Punkt 3.1 bis 3.2 der Einwilligungserklärung und im Teil 2 der Patienteninformation beschrieben, ein.|
|Consent.dateTime|GLNB|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|WDL|Zustimmungen nNGM|Der Patient stimmt der Weitergabe seiner krankheitsbezogenen Daten (MDAT) und, bei Einwilligung zu Punkt 2 der Patienteninformation, Biomaterialien für Forschungszwecke in ein Drittland zu.|
|Consent.dateTime|WDL|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|KNBM|Zustimmungen nNGM|Der Patient stimmt der kommerziellen Nutzung seiner krankheitsbezogenen Daten (MDAT) und, bei Einwilligung zu Punkt 2 der Patienteninformation, Biomaterialien für Forschungszwecke zu.|
|Consent.dateTime|KNBM|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|EKAZI|Zustimmungen nNGM|4.1 Der Patient willigt ein, dass er von der behandelnden Einrichtung erneut kontaktiert werden darf, um gegebenenfalls zusätzliche für wissenschaftliche Fragen relevante Informationen [falls zutreffend: oder Biomaterialien] zur Verfügung zu stellen, um über neue Forschungsvorhaben/Studien informiert zu werden, und/oder um seine Einwilligung in die Verknüpfung seiner Patientendaten mit  medizinischen Informationen aus anderen  Datenbanken einzuholen (siehe Punkt 4.1 im Teil 2 der Patienteninformation).|
|Consent.dateTime|EKAZI|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|EKAZB|Zustimmungen nNGM|4.2 Der Patient willigt ein, dass er von der behandelnden Einrichtung wieder kontaktiert werden darf, um über medizinische Zusatzbefunde informiert zu werden (siehe Punkt 4.2 im Teil 2 der Patienteninformation).|
|Consent.dateTime|EKAZB|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|
|Consent.provision.type|GDWR|Zustimmungen nNGM|Ist der Patient mit den Inhalten gemäß den Ziffern 1 - 6 einverstanden?|
|Consent.provision.type|GDWR|Zustimmungen nNGM|Patient / gesetzlicher Vertreter (Vorsorgebevollmächtigter) hat unterschrieben|
|Consent.dateTime|GDWR|Zustimmungen nNGM|Datum der Patientenunterschrift / gesetzlicher Vertreter (Vorsorgebevollmächtigter)|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Consent.status|Fixed Value - active - ([http://hl7.org/fhir/ValueSet/consent-state-codes](http://hl7.org/fhir/ValueSet/consent-state-codes))|
|Consent.scope.coding.code|Fixed Value - patient-privacy - ([http://terminology.hl7.org/CodeSystem/consentscope](http://terminology.hl7.org/CodeSystem/consentscope))|
|Consent.category.coding.code|Fixed Value - 59284-0 - ([http://loinc.org](http://loinc.org))|
|Consent.policyRule|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/nngm-consent-policy-v4}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/nNGM/ConsentV4, snapshot}}
