## {{page-title}}

Dieses Profil beschreibt eine Anforderung einer Diagnostik innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_ServiceRequest_AnforderungDerDiagnostik" ({{link:http://uk-koeln.de/fhir/StructureDefinition/ServiceRequest/nNGM/AnforderungDerDiagnostik}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/ServiceRequest/nNGM/AnforderungDerDiagnostik```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/ServiceRequest/nNGM/AnforderungDerDiagnostik, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|ServiceRequest.authoredOn|Eckdaten der Anforderung|Anforderungsdatum|
|ServiceRequest.extension:aufenthaltsart|Eckdaten der Anforderung|Patient war / ist zum Zeitpunkt dieser Anforderung|
|ServiceRequest.code|Eckdaten der Anforderung|Typ|
|ServiceRequest.orderDetail:diagnosticRequest|Eckdaten der Anforderung|Gewünschte Diagnostik|
|ServiceRequest.orderDetail:ngsPanel|Eckdaten der Anforderung|NGS Panel|
|ServiceRequest.orderDetail:fastTrack|Eckdaten der Anforderung|Fast Track|
|ServiceRequest.orderDetail|Eckdaten der Anforderung|Liquid Biopsy|
|ServiceRequest.orderDetail|Eckdaten der Anforderung|Immunhistochemie|
|ServiceRequest.orderDetail|Eckdaten der Anforderung|Histologische Abklärung|
|ServiceRequest.extension:GrundFehlendeBiopsie|Eckdaten der Anforderung|Grund für fehlende Biopsie|
|ServiceRequest.requester|Eckdaten der Anforderung|Anforderndes Netzwerkzentrum oder Netzwerkpartner|
|ServiceRequest.performer|Eckdaten der Anforderung|Durchführendes Netzwerkzentrum|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/aufenthaltsart}}|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/grundFehlendeBiopsie}}|
|ServiceRequest.intent|Fixed Value - proposal - ([http://hl7.org/fhir/ValueSet/request-intent](http://hl7.org/fhir/ValueSet/request-intent))|
|ServiceRequest.code|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-diagnostic-type}}|
|ServiceRequest.orderDetail:diagnosticRequest|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-diagnostic-request}}|
|ServiceRequest.orderDetail:histologischeAbklaerung|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-histologischeAbklaerung}}|
|ServiceRequest.orderDetail:molekularpathologie|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-molekularpathologie}}|
|ServiceRequest.orderDetail:ngsPanel|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-ngsPanel}}|
|ServiceRequest.orderDetail:fastTrack|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-fastTrack}}|
|ServiceRequest.orderDetail:liquidBiopsy|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/anforderung-liquidBiopsy}}|


<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|ServiceRequest.extension:aufenthaltsart|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/aufenthaltsart}}|
|ServiceRequest.extension:GrundFehlendeBiopsie|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/grundFehlendeBiopsy}}|


<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/ServiceRequest/nNGM/AnforderungDerDiagnostik, snapshot}}
