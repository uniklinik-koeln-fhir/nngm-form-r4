## {{page-title}}

Dieses Profil beschreibt einen pseudonymisierten Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Patient_PatientPseudonymisiert" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | EDC-Label | Beschreibung |
|-----------------|-----------|--------------|
|Patient.identifier:Patientenliste-Pseudonym|Pseudonym|Pseudonym vergeben durch die nNGM-Patientenliste|
|Patient.gender|Geschlecht|Die Extension 'other-amtlich' und der Constraint pat-nngm-1 ist bei der Erfassung eines administrativen Geschlechts mit der Ausprägung 'divers' zu beachten.|
|Patient.gender.extension:other-amtlich.value[x]|Anderes Geschlecht|Gibt an ob das Geschlecht des Patienten divers oder unbestimmt ist|
|Patient.birthDate|Geburtsdatum|Geburtsdatum des Patienten|
|Patient.deceased[x]:deceasedBoolean|Verstorben|Ob der Patient verstorben ist|
|Patient.deceased[x]:deceasedDateTime|Todesdatum|Todesdatum des Patienten|
|Patient.deceased[x]:deceasedDateTime.extension:informationsquelleTodesdatum.value[x]|Informationsquelle des Todes|Informationsquelle des Todes des Patienten|


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|([http://fhir.de/ValueSet/gender-other-de](http://fhir.de/ValueSet/gender-other-de))|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/izt}}|


<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Patient.name.family.extension:namenszusatz|{{link:http://fhir.de/StructureDefinition/humanname-namenszusatz}}|
|Patient.gender.extension:other-amtlich|{{link:http://fhir.de/StructureDefinition/gender-amtlich-de}}|
|Patient.deceased[x]:deceasedDateTime.extension:informationsquelleTodesdatum|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/izt}}|


<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/pseudonymisiert, snapshot}}
