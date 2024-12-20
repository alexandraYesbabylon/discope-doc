
# Organisation 

## Organisation 

Une organisation est une entité légale qui peut fonctionner de manière autonome ou en tant que filiale d'une organisation mère unique. Chaque organisation possède un numéro d'identification d'entreprise et un numéro d'enregistrement à la TVA uniques.  

Elle peut comporter :  

- Plusieurs unités d'établissement.  
- Plusieurs adresses de contact, bien que seule l'adresse officielle du siège soit requise sur les documents officiels. 

Informations nécessaires sur une organisation:  

Par défaut, une organisation est initialisée avec l'identifiant 1. Il est ensuite nécessaire d'ajouter les informations suivantes :  

- Nom de l'organisation.  
- Email et numéro de téléphone.  
- Numéro d'entreprise et numéro de TVA.  
- Adresse complète incluant le pays, la ville, la rue, le numéro et le code postal.  
- Coordonnées bancaires : IBAN, BIC. 
- Langue de communication. 

Cette approche garantit une gestion structurée des informations, facilitant la communication, la facturation et le suivi administratif des organisations.


## Équipe de gestion

L'équipe de gestion est responsable de la gestion de plusieurs centres, tout en centralisant la facturation et la comptabilité pour ces derniers.

Pour assurer une gestion efficace, les informations suivantes sont requises :

- Nom : Nom de l'équipe de gestion ou du bureau associé au centre.
- Code de groupe : Identifiant unique du bureau de gestion (au format hexadécimal sur un chiffre).
- IBAN : Numéro de compte bancaire utilisé pour la facturation des services associés aux centres.
- Type d'imprimante : Format d'impression des documents officiels : `POS-80` pour les tickets ou `ISO-A4` pour les rapports.
- Mode par défaut pour les documents : Détermine l'affichage des documents : `simple`, `groupé` ou `détaillé`.

**Fonctionnalités**

- Gestion des centres associés : Chaque équipe de gestion peut être liée à une ou plusieurs entités Centres.
- Journaux comptables : Gestion des journaux comptables associés à l'équipe, permettant un suivi financier détaillé.
- Signature électronique : Signature personnalisée pouvant être ajoutée aux communications officielles.

## Centre

Le centre est un établissement d'hébergement qui offre des unités locatives pour des séjours, qu'il s'agisse de courts ou longs séjours. 

Il nécessite de compléter les informations suivantes :

- Nom du centre
- Code alpha
- Équipe de gestion
- Type de séjour
- Organisation associée


## Unité locative

L'unité locative permet de gérer les unités de location, leur disponibilité, ainsi que les consommations et actions nécessaires

- Nom: Nom de l'unité locative.
- Type: Type d'unité locative (en lien avec la capacité).

    - Bâtiment
    - Chambre
    - Lit
    - Salle de réunion
    - Réfectoire
    - Salle
    - Mobilier, accessoires et équipement
  
- Catégorie: Catégorie des produits auxquels l'unité peut être assignée.
- Capacité: Le nombre de personnes pouvant séjourner dans l'unité.
- Logement: L'unité locative est un logement.
- Sous-unités: Drapeau indiquant que l'unité a des sous-unités.
- A parent: Drapeau indiquant que l'unité a des sous-unités.
- Peut être loué: Unité disponible à la location.
- Location partielle ? L'unité peut être louée partiellement.


