@startuml
start
fork
  :sur internet;
fork again
  :en agence;
end fork {and}
:le client remplit le formulaire de réservation sur le site;
:le disponibilité est vérifié;
if (disponible?) then (yes)
  :créer une réservation;
  :calcul du prix;
  :enregistrement des arrhes;
  :confirmer la réservation;
else (no)
  :le client est informé de la non disponibilité de sa réservation;
endif
stop
@enduml
