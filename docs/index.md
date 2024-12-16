# Configuration'une instance de Discope

## Sécurité 
Cette option permet d'établir les permissions et restrictions pour les utilisateurs assignés à un groupe. 

### Utilisateurs 
Il est nécessaire de compléter les informations suivantes : sélectionner une identité existante, remplir l'email et le mot de passe, et assigner un nom d'utilisateur tout en choisissant la langue de préférence. Après la création d'un nouvel utilisateur, celui-ci doit être validé par un administrateur.
### Groupes
La configuration des groupes permet de gérer les accès des utilisateurs aux différentes applications. Chaque application peut contenir plusieurs groupes. Pour chaque groupe, il est essentiel de définir les utilisateurs. Par défaut, certains groupes sont créés lors de l'initialisation de l'application, mais de nouveaux groupes peuvent être ajoutés en indiquant un nom et une description.
### Permissions 
Les permissions sont définies par l'identificateur du groupe et les droits qui lui sont attribués. Bien que les permissions soient généralement préétablies, l'administrateur a la possibilité de les ajuster si nécessaire.

## Organisation
### Organisation 
Par défaut, l'organisation est déjà créée avec l'identificateur 1. Il est nécessaire d'ajouter le nom, le type, l'email, le numéro de téléphone, le numéro d'entreprise, ainsi que l'adresse complète (pays, ville, rue, numéro et code postal).
### Équipes de gestion
L'équipe de gestion gère plusieurs centres et centralise la facturation ainsi que la comptabilité. Elle nécessite les informations suivantes : le libellé, qui correspond au nom du centre, le code de groupe, un identifiant unique du centre, et l'IBAN, soit le compte bancaire pour la facturation. Au moins une équipe de gestion doit être créée pour assurer la gestion financière.
### Centres
Le centre représente les lieux physiques où les réservations auront lieu. Il nécessite de compléter les informations suivantes : le nom du centre, l'abréviation du centre, l'équipe de gestion responsable, le type de séjour et l'organisation associée.

### Unités locatives
Cette configuration nécessite de compléter des informations précises pour chaque unité, telles que le libellé, le code unique, le statut (par exemple, "complètement occupé" ou "en ordre") et les actions requises (comme le nettoyage complet). D’autres détails incluent le type d'hébergement, le centre associé, la capacité d’accueil, ainsi que la possibilité de sous-louer ou non l’unité. Ces données garantissent une gestion optimale des ressources et de la logistique dans chaque centre.
###  Catégorie d'unité locative 
La catégorie classe les types d'unités disponibles, comme les salles de réunion, les chambres ou les bâtiments. Chaque catégorie a un nom et une description définissant son utilisation, facilitant ainsi la gestion des unités locatives pour chaque catégorie.


## Identités

### Identité
La classe Identity est utilisée comme interface pour représenter des entités telles que des organisations (personnes morales) et des partenaires (personnes physiques). Une Identity peut être une personne légale (organisation, entreprise) ou une personne physique (utilisateurs, employés, contacts).

Elle définit un ensemble de champs qui permettent de stocker et gérer les informations essentielles d'une identité comme le nom, le type, les informations bancaires, l'adresse et les relations avec d'autres entités (clients, employés, contacts, etc.)
### Type d'Identité 
La classe IdentityType est utilisée pour définir et gérer les types d'identités pouvant être attribués à une entité dans le système. Cela signifie qu'elle permet de classer les identités (personnes physiques ou organisations) en différentes catégories prédéfinies selon leur nature juridique ou fonctionnelle.

La configuration inclut les options prédéfinies suivantes :

| **ID** | **Code** | **Description**                              |
|--------|----------|---------------------------------------------|
| **1**  | **I**    | Particulier (personne physique)             |
| **2**  | **SE**   | Indépendant                                 |
| **3**  | **C**    | Société                                     |
| **4**  | **NP**   | Groupes, Associations et Écoles (ASBL)      |
| **5**  | **PA**   | Administration publique                     |


### Addresses
La classe Address est utilisée pour définir et gérer les adresses associées aux identités dans le système. Une adresse représente une localisation physique permettant de contacter une identité. Elle comprend diverses colonnes qui stockent les informations détaillées de l'adresse, y compris son rôle, sa relation avec une identité, et ses éléments géographiques

### Établissement

La classe Establishment représente une unité d'établissement au sein d'une organisation, permettant de gérer des informations telles que le nom, l'adresses et le lien avec l'organisation parent. Elle permet ainsi de suivre les différents établissements d'une organisation