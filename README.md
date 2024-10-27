
RAPPORT : tp note JAVA POO





## Présentation de l'application

Cette application de gestion de parc automobile permet de gérer les véhicules et les clients d'une agence de location. Elle offre des fonctionnalités pour ajouter, supprimer des véhicules et des clients, ainsi que pour louer et retourner des véhicules.

## Fonctionnalités principales

1. Gestion des véhicules :
   - Ajouter un véhicule (camion ou voiture).
   - Supprimer un véhicule de la liste.
   - Lister tous les véhicules disponibles ou non disponibles.

2. Gestion des clients :
   - Ajouter un client .
   - Supprimer un client de la liste.
 - Lister tous les clients enregistrés.

3. Gestion des contrats de location :
   - Louer un véhicule à un client en vérifiant la disponibilité.
   - Retourner un véhicule après location.
   - Lister tous les contrats de location.

## Structure du projet

Le projet est organisé en plusieurs packages pour faciliter la gestion du code :

- Le package Clients : Contient la classe `Client` qui représente les clients de l'agence.

- Le package Vehicules :Contient les classes `Vehicule`, `Voiture`, et `Camion` qui représentent les différents types de véhicules.
- **Le package ContratLocation : Contient la classe `ContratLocation` qui gère les contrats de 

location entre les clients et les véhicules.
- **Exception :** Contient les classes d'exception personnalisées pour gérer les erreurs (par exemple : `VehiculeNonTrouveException`, `ClientNomAutoriseException`).

## Comment utiliser l'application

1. **Lancer l'application :** 
   - Ouvrez le projet dans votre IDE Java préféré 
   - Exécutez la classe principale pour démarrer l'application.

2. **Ajouter des véhicules et des clients :**
   - Utilisez les méthodes disponibles dans la classe `ParcAutomobile` pour ajouter des véhicules et des clients.

3. **Louer et retourner des véhicules :**

 - Louez un véhicule à un client en vous assurant que le véhicule et le client sont disponibles.
 - Retournez le véhicule.

4. **Gérer les exceptions :**
   - Les exceptions sont levées lorsque des actions invalides sont tentées (par exemple, louer un véhicule non disponible).
