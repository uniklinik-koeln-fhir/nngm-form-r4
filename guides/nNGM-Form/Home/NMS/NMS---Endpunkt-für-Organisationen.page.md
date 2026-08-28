## NMS - Endpunkt zum Abruf von allen registrierten Organisiationen

**GET** https://nngm-nms.medicalsyn.com/api/v1.0/Public/Organization

**Content-Type:** application/json

### Schema:

    [
        {
            "internalSequenceIdentifier": string
            "displayName": string
            "isActive": boolean
            "isDigiNet": boolean
            "networkPartnerIdentifier": string
        }
    ]

### Properties

- `internalSequenceIdentifier`: **Organistations-Id**
- `displayName`: Anzeigename der Organistation
- `isActive`: Ob die Organisation aktiv geschalten ist
- `isDigiNet`: Ob die Organisation an DigiNet teilnimmt
- `networkPartnerIdentifier`: Netzwerkpartnernummer

### Codierung des `internalSequenceIdentifier` :

Die Organisationen haben zur Unterscheidung in Netzwerkzentren, Krankenhäuser, 
Praxen und Pathologien jeweils ein Präfix an ihren `internalSequenceIdentifier` 
vorangestellt.

#### Bedeutung der Präfixe
- **SZ**  - Netzwerkzentrum
- **SK** - Krankenhaus
- **SP** - Praxis
- **SPa** - Pathologie