## {{page-title}}

Dieses Profil beschreibt einen Patienten innerhalb des nNGM-Projektes.

**Name**: "Profile_nNGM_Patient_Patient" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient, diff}}

<br>

**Erläuterungen**

| FHIR-Element-Id | EDC-Label | Beschreibung |
|-----------------|-----------|--------------|
|Patient.name|||
|Patient.name:Name|||
|Patient.name:Name.use|||
|Patient.name:Name.family|Name|Nur der aktuelle Name ist gefordert. Die Erfassung und Übermittelung des Geburtsnamen ist optional. Teil des Patienten-Matching der nNGM-Patientenliste.|
|Patient.name:Name.family.extension:namenszusatz|||
|Patient.name:Name.family.extension:nachname|||
|Patient.name:Name.family.extension:vorsatzwort|||
|Patient.name:Name.given|Vorname||
|Patient.name:Name.prefix|||
|Patient.name:Name.prefix.extension:prefix-qualifier|||
|Patient.name:Geburtsname|||
|Patient.gender|Geschlecht|Die Extension 'other-amtlich' und der Constraint pat-nngm-1 ist bei der Erfassung eines administrativen Geschlechts mit der Ausprägung 'divers' zu beachten.|
|Patient.gender.extension:other-amtlich.value[x]|Anderes Geschlecht|Gibt an ob das Geschlecht des Patienten divers oder unbestimmt ist|
|Patient.birthDate|Geburtsdatum|Teil des Patienten-Matching der nNGM-Patientenliste.|
|Patient.deceased[x]:deceasedBoolean|Verstorben|Ob der Patient verstorben ist|
|Patient.deceased[x]:deceasedDateTime|Todesdatum|Kodierung des Todeszeitpunkts. Optional kann auch die Informationsquelle zum Todesdatum angeben werden. deceasedBoolean ist wo möglich durch deceasedDateTime zu ersetzen, wenn PatientIn verstorben ist.|
|Patient.deceased[x]:deceasedDateTime.extension:informationsquelleTod.value[x]|Informationsquelle des Todes|Informationsquelle des Todes des Patienten|
|Patient.address|Adresse|Teil des Patienten-Matching der nNGM-Patientenliste.|
|Patient.address:Strassenanschrift|||
|Patient.address:Strassenanschrift.extension:Stadtteil|||
|Patient.address:Strassenanschrift.type|||
|Patient.address:Strassenanschrift.line|||
|Patient.address:Strassenanschrift.line.extension:Strasse|||
|Patient.address:Strassenanschrift.line.extension:Hausnummer|||
|Patient.address:Strassenanschrift.line.extension:Adresszusatz|||
|Patient.address:Strassenanschrift.city|||
|Patient.address:Strassenanschrift.postalCode|||
|Patient.address:Strassenanschrift.country|||


<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Extension.value[x]|([http://fhir.de/ValueSet/gender-other-de](http://fhir.de/ValueSet/gender-other-de))|
|Extension.value[x]:valueCodeableConcept|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/izt}}|
|Patient.name:Name.prefix.extension:prefix-qualifier.value[x]|Fixed Value - AC|


<br>

**Extensions**

| FHIR-Element-Id | Extension|
|-----------------|----------|
|Patient.gender.extension:other-amtlich|{{link:http://fhir.de/StructureDefinition/gender-amtlich-de}}|
|Patient.deceased[x]:deceasedDateTime.extension:informationsquelleTod|{{link:http://uk-koeln.de/fhir/StructureDefinition/Extension/nNGM/izt}}|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Patient/nNGM/patient, snapshot}}
