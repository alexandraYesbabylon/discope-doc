## Identité
La classe Identity est utilisée comme interface pour représenter des entités telles que des organisations (personnes morales) et des partenaires (personnes physiques). Une Identity peut être une personne légale (organisation, entreprise) ou une personne physique (utilisateurs, employés, contacts).

Elle définit un ensemble de champs qui permettent de stocker et gérer les informations essentielles d'une identité comme le nom, le type, les informations bancaires, l'adresse et les relations avec d'autres entités (clients, employés, contacts, etc.)

Par défaut, une Identity est créée et est automatiquement associée à l'organisation qui est également créée par défaut.

### Type d'Identité 
La classe IdentityType est utilisée pour définir et gérer les types d'identités pouvant être attribués à une entité dans le système. Cela signifie qu'elle permet de classer les identités (personnes physiques ou organisations) en différentes catégories prédéfinies selon leur nature juridique ou fonctionnelle.

La configuration inclut les options prédéfinies suivantes :

| **ID** | **Code** | **Description**                              |
|-------|----------|---------------------------------------------|
| 1  | **I**    | Particulier (personne physique)             |
| 2 | **SE**   | Indépendant                                 |
| 3 | **C**    | Société                                     |
| 4 | **NP**   | Groupes, Associations et Écoles (ASBL)      |
| 5 | **PA**   | Administration publique                     |


## Center

Le Center représente un établissement d'hébergement fournissant des logements locatifs. Le Center permet notamment de gérer :

- L'identifiant unique du centre.
- Les groupes de prix et remises.
- Les catégories et unités locatives associées.
- Les informations de gestion comme le responsable, les modèles de communication et les compteurs de consommation.

## Équipe de gestion

Équipe de gestion permet la gestion des différents centres. Cette classe offre des fonctionnalités avancées telles que :  

- La gestion des contacts et des utilisateurs associés.  
- La configuration des signatures pour les communications.  
- La définition des modes d'impression pour les tickets de point de vente (PoS).  
- L'attribution manuelle des unités locatives.  
- La gestion des journaux comptables.  
- L'intégration avec des sections analytiques pour la comptabilité.  

L'Équipe de gestion des informations détaillées:

- Nom de l'équipe de gestion  
- Identifiant numérique de l'équipe de gestion  
- Liste des centres rattachés à l'équipe de gestion  
- Liste des contacts associés à l'équipe de gestion  
- Liste des utilisateurs liés à l'équipe de gestion  
- Mode par défaut pour la génération des documents officiels  
- Format d'impression pour les tickets de point de vente (PoS)  
- Liste des journaux comptables associés à l'équipe de gestion  
- Liste des produits favoris de l'équipe de gestion  
- Adresse e-mail pour l'envoi des copies des messages envoyés  


## Cliente

Le client est un partenaire dont l'activité principale est de réaliser une ou plusieurs réservations. 

Le client contient des informations détaillées:

- Nom complet
- L'organisation à laquelle appartient le client
- L'identité du client
- La catégorie tarifaire applicable au client.
- Le type de client (en relation avec les classes tarifaires).
- La nature du client, qui permet d'attribuer une catégorie tarifaire.
- Adresse principale du client.
- Numéro de compte IBAN arbitraire associé au client.

Cette classe est essentielle pour gérer les informations des clients et leurs réservations, facilitant l'attribution des tarifs et le suivi de leur activité dans le système.

## Contact
Le Contact représente une personne liée à une réservation avec des responsabilités spécifiques. Le partenariat reste toujours de type 'contact'. Les types de contact possibles incluent : 'booking' pour gérer les détails de la réservation, 'invoice' pour recevoir la facture, 'contract' pour recevoir les contrats et 'sojourn' pour identifier la personne présente durant le séjour .

## Address
L'Address est utilisée pour définir et gérer les adresses associées aux identités dans le système. Une adresse représente une localisation physique permettant de contacter une identité. Elle comprend diverses colonnes qui stockent les informations détaillées de l'adresse, y compris son rôle, sa relation avec une identité, et ses éléments géographiques


