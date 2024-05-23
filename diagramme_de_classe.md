class Hotel{
   -id : Integer
   -nom : String
   -adresse : String
   -classe : String
   -getHotels : List<Hotel>
   +getNom()
   +setNom()
   +getAdresse()
   +setAdresse()
   +getClasse()
   +setClasse()
   -Hotel()
   -Hotel(string Nom, string Adresse, string Classe)
   +void ajouterHotel()
   +void supprimerHotel(int id)
   +void modifierHotel(int id)
   +getHotels afficherHotels()
   +Hotel afficherHotel()
}


class Chambre{
   -id : Integer
   -capacite : Integer
   -degreConfort : Integer
   -prix : Double
   -surface : Double
   -getChambres : List<Chambre>
   +getCapacite()
   +setCapacite()
   +getDegreConfort()
   +setDegreConfort()
   +getPrix()
   +setPrix()
   +getSurface()
   +setSurface()
   -Chambre()
   -Chambre(int Capacite, int DegreConfort, double Prix, double Surface)
   +void AjouterChambre()
   +void ModifierChambre(int id)
   +void SupprimerChambre(int id)
   +getChambres afficherChambres()
   +Chambre afficherChambre()
}


class Client {
   -id : Integer
   -nom : String
   -adresse : String
   -tel : String
   -email : String
   -categorieChambre : String
   -dateDebut : Date
   -dateFin : Date
   -classeHotel : String
   -Client()
   -Client(string nom, string adresse, string tel, string email, string categorieChambre, date dateDebut, dateFin, string classeHotel)
   +void creerClient()
   +void modifierClient(int id)
   +void supprimerClient(int id)
}

class Reservation {
   -codeClient : Integer
   -numResa : Integer
   -dateResa : Date
   -hotel : Hotel
   -chambre : Chambre
   -periodeSejour : Integer
   -nombrePersonne : Integer
   -activate : Boolean
   -getReservations : List<Reservation>
   +void creerReservation()
   +void confirmerReservation(int id)
   +void annulerReservation(int id)
   +getReservations afficherReservations()
   +Reservation afficherReservation()
}


class Facture {
   -id : Integer
   -reservation : Reservation
   -prixTotal : double
   -prestations : List<Prestation>
   +Facture genererFacture()
}


class Prestation {
   -id : Integer
   -intutile : String
   -prix : double
   +void ajouterPrestation()
   +void modifierPrestation(int id)
}
@enduml

