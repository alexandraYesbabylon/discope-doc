# Configuration de Ventes

Cette option permet de définir les paramètres pour les réservations, les réductions et les produits automatiques.

## Réservation
### Types de réservation
Cette configuration permet d’établir différents types de réservations selon la clientèle ou l’organisation, ainsi que les délais d’expiration des options associées. Chaque type est identifié par un code spécifique et a un nombre de jours d’expiration unique pour l’option de réservation.

## Clients 
Cette configuration gère les informations des clients, les catégories tarifaires et les tranches d’âge. En général, elle est établie par l’application Discope lors de l’initialisation, bien que des adaptations puissent être effectuées par la suite.
### Types de clients 
Cette classification permet de regrouper les clients selon leur statut juridique ou organisationnel, facilitant ainsi la gestion des relations commerciales et l’adaptation des services.
### Nature du client 
Elle permet de classer les clients en fonction de leur catégorie tarifaire et de leur type d’entité. Chaque type est identifié par un code et se voit attribuer une catégorie tarifaire spécifique, déterminant ainsi les tarifs applicables et les conditions de service.
### Catégories tarifaires
Cette configuration définit des groupes distincts pour faciliter la gestion des tarifs et l’adaptation des services offerts, en fonction des réservations de chaque client ou groupe.
### Tranches d’âge 
Cette fonctionnalité permet de classer les participants d’une réservation selon leur tranche d’âge (Bébé 0-3, Maternelle 3-6, Primaire 6-12, Secondaire 12-26, Adulte 26-99) afin d’adapter les services et les tarifs proposés.


## Catalogue 

### Produits

#### Produits
La configuration des produits permet d’associer chaque produit à un modèle spécifique, garantissant ainsi un SKU unique pour une identification précise. Chaque produit doit comporter un libellé descriptif, un SKU, un modèle de produit correspondant, ainsi que des informations clés telles que son statut de vente, sa possibilité d’être inclus dans un pack et la famille à laquelle il appartient. De plus, un produit peut regrouper plusieurs autres produits, formant ainsi un pack. Enfin, il peut avoir plusieurs prix selon différentes listes de prix.
#### Modelé de produit
La configuration de Modèle de Produits permet de définir et organiser les types de produits dans l'organisation, en spécifiant leur libellé, type, famille et possibilité de vente. Elle inclut aussi des détails sur la comptabilisation, les statistiques de vente, et si le produit est un repas, collation ou logement. Un modèle peut avoir plusieurs variantes et être disponible pour plusieurs groupes.
#### Catégories
La configuration de catégorie permet de regrouper les modèles de produits et les types de réservation. Elle inclut des familles telles que Séjours scolaires (CDV), Produits de caisse (POS) et SPORT (SPT). Chaque catégorie a une description spécifique pour faciliter la gestion
#### Familles
La famille est le regroupement de produits présents dans tous les centres. Par défaut, une famille doit être créée dans laquelle seront regroupés tous les produits de l'organisation
#### Groupes
Il est nécessaire de remplir les champs suivants : Nom du groupe de produits et Centre. La configuration de groupe permet d'organiser les modèles de produits et les produits.


## Prix

### Liste de prix
La configuration de la liste de prix permet de gérer les tarifs applicables sur des périodes spécifiques et selon des catégories de services. La liste  doit être défini une fois par an.  Chaque entrée inclut un identifiant, un statut, des dates de validité et la durée, garantissant l'application des tarifs corrects pour  chaque catégorie de liste de prix. 


## Remises

### Remise
La réduction permet d’offrir des avantages tarifaires aux clients selon des critères spécifiques. Chaque réduction se compose d’un libellé, d’une valeur, d’un type (pourcentage ou gratuité) et de conditions à remplir pour en bénéficier.
 
### Liste de remises
Cette liste définit des remises pour différentes catégories tarifaires sur une période donnée. Chaque entrée inclut un libellé, une catégorie, des dates de validité, une classe tarifaire et des taux de remise minimum et maximum. De plus, la liste de réductions regroupe les différentes remises disponibles.

## Produits automatiques
La liste des produits est organisée par catégorie et par période précise, à partir d'une date de début et d'une date de fin. Elle inclut tous les produits devant être appliqués automatiquement à la réservation, si celle-ci correspond à la période spécifiée et aux conditions de chaque produit.


## Saisons
La saison est définie pour chaque année et catégorie. Dans une saison, chaque période est spécifiée avec une date de début et une date de fin, ainsi qu'un type de saison, qui peut être (Basse, Moyenne, Haute, Très Haute).  Les périodes doivent être créées de manière à s'étendre du 1er janvier au 31 décembre de chaque année, avec une durée d'un jour, commençant à 0 heures et se terminant à 23 heures. 

## Plan de paiement
Le plan de paiement définit les modalités de règlement pour les réservations. Pour chaque plan de paiement, il est nécessaire de préciser le type de réservation, la catégorie tarifaire et les échéances correspondantes.


