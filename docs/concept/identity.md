## Identité
La classe Identity est utilisée comme interface pour représenter des entités telles que des organisations (personnes morales) et des partenaires (personnes physiques). Une Identity peut être une personne légale (organisation, entreprise) ou une personne physique (utilisateurs, employés, contacts).

Elle définit un ensemble de champs qui permettent de stocker et gérer les informations essentielles d'une identité comme le nom, le type, les informations bancaires, l'adresse et les relations avec d'autres entités (clients, employés, contacts, etc.)

Par défaut, une Identity est créée et est automatiquement associée à l'organisation qui est également créée par défaut.
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


## Addresses
La classe Address est utilisée pour définir et gérer les adresses associées aux identités dans le système. Une adresse représente une localisation physique permettant de contacter une identité. Elle comprend diverses colonnes qui stockent les informations détaillées de l'adresse, y compris son rôle, sa relation avec une identité, et ses éléments géographiques

## Établissement

La classe Establishment représente une unité d'établissement au sein d'une organisation, permettant de gérer des informations telles que le nom, l'adresses et le lien avec l'organisation parent. Elle permet ainsi de suivre les différents établissements d'une organisation