## NMS - nNGM Management System

Um eine einfache und verlässliche Art der Zuordnung von Organistationen und Personen 
im nNGM-System zu ermöglichen, wurde das nNGM Management System (NMS) geschaffen. 
Hier sind alle Organistationen (Netzwerkzentren, Krankenhäuser, Praxen und Pathologien) 
gespeichert, sowie alle Personen (Behandler), welche im Kontext des nNGM- und 
Diginet-Projekt benötigt werden.

Alle Organisationen und Personen haben im NMS einen eindeutigen Identifikationscode 
(`internalSequenceIdentifier`) welcher auch für die Übertragung an das nNGM-eCRF 
verwendet werden soll. Es ist damit nicht mehr notwendig die komplette Organisations
oder Behandlerdaten anzugeben. Der einfache Identifikationscode aus dem NMS reicht aus.

Um diese Daten verfügbar zu machen, wurden 2 öffentliche Schnittstellen geschaffen, an denen  
man die Daten im Json-Format abrufen kann.

In Falle dessen, dass eine Organisation oder Person im NMS fehlt, kann man sich gerne
an das nNGM wenden, damit die Daten ergänzt werden.

### Inhaltsverzeichnis

{{index:current}}