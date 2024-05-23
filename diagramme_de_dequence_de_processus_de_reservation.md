@startuml

autonumber

Client -> Gestion: Reserver chambre
Gestion -> Hotel: Vérifier la disponibilité
Hotel -> Hotel: Vérifier si chambre disponible
Hotel --> Gestion: Disponibilité confirmée
Gestion --> Client: Réservation confirmée
Client -> Gestion: Payer Arrhes
Gestion -> Hotel: Enregistrer Arrhes
Hotel --> Gestion: Confirmation paiement
Gestion --> Client: Confirmation réservation

@enduml
