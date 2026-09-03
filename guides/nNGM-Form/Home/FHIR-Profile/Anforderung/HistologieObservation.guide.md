## {{page-title}}

Dieses Profil beschreibt die Klassifikation (Morphologie), Topographie und die Histopathologische Differenzierung (Grading) der Tumorerkankung innerhalb des nNGM Projektes.

**Name**: "Profile_nNGM_Observation_Histologie" ({{link:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/histologie}})

**Canonical**: ```http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/histologie```

**Differential**

{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/histologie, diff}}

<br>

**Erläuterungen**

> Hinweis: Die folgende Tabelle listet ausschließlich die Felder auf, die vom
> Zielsystem tatsächlich eingelesen werden. Alle übrigen im Profil erlaubten
> Elemente werden beim Import ignoriert.

| FHIR-Element-Id | Instrument | Label |
|-----------------|------------|-------|
|Observation.specimen|Histologie|Tumormaterial|
|Observation.effective[x]|Histologie|Datum|
|Observation.value[x]|Histologie|Klassifikation|
|Observation.bodySite|Histologie|Lokalisation|
|Observation.component:grading.value[x]|Histologie|Grading|
|Observation.component:growthPatternInAdenocarcinomaLepidic.value[x]|Histologie|Wachstumsmuster bei Adenokarzinom lepidisch|
|Observation.component:growthPatternInAdenocarcinomaAcinar.value[x]|Histologie|Wachstumsmuster bei Adenokarzinom azinär|
|Observation.component:growthPatternInAdenocarcinomaPapillary.value[x]|Histologie|Wachstumsmuster bei Adenokarzinom papillär|
|Observation.component:growthPatternInAdenocarcinomaMicropapillary.value[x]|Histologie|Wachstumsmuster bei Adenokarzinom mikropapillär|
|Observation.component:growthPatternInAdenocarcinomaSolid.value[x]|Histologie|Wachstumsmuster bei Adenokarzinom solide|
|Observation.component:percentageOfSignetRingCellCarcinoma.value[x]|Histologie|Anteil an Siegelringzellkarzinomen|

<br>

**Bindings**

| FHIR-Element-Id | ValueSets|
|-----------------|----------|
|Observation.status|Fixed Value - final - ([http://hl7.org/fhir/ValueSet/observation-status](http://hl7.org/fhir/ValueSet/observation-status))|
|Observation.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/histologie-klassifikation}}|
|Observation.bodySite|{{link:http://uk-koeln.de/fhir/ValueSet/icd-o-3-topologie}}|
|Observation.component:grading.code.coding.code|Fixed Value - 59542-1 - ([http://loinc.org](http://loinc.org))|
|Observation.component:grading.value[x]|{{link:http://uk-koeln.de/fhir/ValueSet/nNGM/grading}}|
|Observation.component:growthPatternInAdenocarcinomaLepidic.code.coding.code|Fixed Value - 112677002 - ([http://snomed.info/sct](http://snomed.info/sct))|
|Observation.component:growthPatternInAdenocarcinomaAcinar.code.coding.code|Fixed Value - 128703004 - ([http://snomed.info/sct](http://snomed.info/sct))|
|Observation.component:growthPatternInAdenocarcinomaPapillary.code.coding.code|Fixed Value - 4797003 - ([http://snomed.info/sct](http://snomed.info/sct))|
|Observation.component:growthPatternInAdenocarcinomaMicropapillary.code.coding.code|Fixed Value - 450895005 - ([http://snomed.info/sct](http://snomed.info/sct))|
|Observation.component:growthPatternInAdenocarcinomaSolid.code.coding.code|Fixed Value - 81920005 - ([http://snomed.info/sct](http://snomed.info/sct))|
|Observation.component:percentageOfSignetRingCellCarcinoma.code.coding.code|Fixed Value - 87737001 - ([http://snomed.info/sct](http://snomed.info/sct))|

<br>

**Snapshot**
{{tree:http://uk-koeln.de/fhir/StructureDefinition/Observation/nNGM/histologie, snapshot}}
