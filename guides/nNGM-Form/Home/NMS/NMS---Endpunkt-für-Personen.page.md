## NMS - Endpunkt zum Abruf von allen registrierten Personen

**GET** https://nngm-nms.medicalsyn.com/api/v1.0/Public/Person

**Content-Type:** application/json

### Schema

    [
        {
            "internalSequenceIdentifier": string,
            "title": string|null,
            "firstName": string,
            "lastName": string,
            "organizationAssignments" [
                string
            ]
        }
    ]

### Properties

- `internalSequenceIdentifier`: **Personen-Id**
- `title`: Titel der Person
- `firstName`: Vorname der Person
- `lastName`: Nachnahme der Person
- `organizationAssignments`: Eine Liste von `networkPartnerIdentifier` der Organisationen, dem die Person zugeordnet ist 

Bei der Übertragung der Behandlerrolle sollte man darauf achten, dass die gewählte Person 
der zusätzlich angegebenen Organisation zugeordnet ist. Dies kann  man durch
die Auflistung der Netzwerkpartnernummer (`networkPartnerIdentifier`) der Organisation im Property 
`organizationAssignments` der Person überprüfen.