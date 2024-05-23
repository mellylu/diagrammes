@startuml
"User" as User
"Systeme de gestion" as Gestion
"Admin" as Admin
"Employe" as Employe
User --> (Consulter les offres)
User --> (Faire une réservation)
Admin--> (Maintenance du parc hotelier)
Admin --> (Valider les réservations)
Employee --> (Enregistrer l'arrivée du client)
Employee --> (Enregistrer les consommations)
Employee --> (Etablir la facture)
Employee --> (Consulter les arrivées prévues)
Employee --> (Consulter l'état d'occupation)
Gestion --> (Maintenance du parc hotelier)
Gestion --> (Consulter disponibilités)
Gestion --> (Enregistrer réservations)
Gestion --> (Enregistrer Arrhes)
Gestion --> (Enregistrer arrivées)
Gestion --> (Enregistrer consommations)
Gestion --> (Etablir factures)
Gestion --> (Consulter les arrivées prévues)
Gestion --> (Consulter l'état d'occupation)
@enduml
