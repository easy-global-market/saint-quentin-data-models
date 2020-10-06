#Reservation Entity

The table below details the NGSI-LD mapping process:

| Name in the CSV                          | NGSI-LD attribute Type | NGSI-LD attribute Name |
|------------------------------------------|------------------------|------------------------|
| Nom de l'équipement Père                 | Relationship           | refStadium             |
| Nom de l'équipement de la réservation    | Relationship           | refField               |
| Type de lieu                             | Property               | equipmentType          |
| Nom usager                               | Property               | booker                 |
| Date de début,Mois,Année,Heure de début  | Temporal Property      | startAt                |
| Date de début, Mois, Année, Heure de fin | Temporal Property      | endAt                  |
| Activité                                 | Property               | activity               |
| Type de résservation                     | Property               | reservationType        |
| ENTIER                                   | Property               | duration               |