# Financement

## Comptabilité

### Plan comptable
Le plan comptable est associé à une organisation et regroupe toutes les règles comptables qui lui sont liées. Par défaut, un plan comptable est défini pour correspondre à l'organisation par défaut.

### Règles de TVA 

Les règles de TVA permettent de spécifier quel taux de TVA s'applique à un type d'opération donné. Ces règles peuvent être modifiées ou complétées en fonction des besoins.

| **ID** | **Nom**            | **Taux** |
|--------|--------------------|----------|
| **1**  | Vente TVA 0%       | 0.00     |
| **2**  | Vente TVA 6%       | 0.06     |
| **3**  | Vente TVA 12%      | 0.12     |
| **4**  | Vente TVA 21%      | 0.21     |


### Règles comptables
Il permet de définir et d'organiser les différentes catégories de transactions financières au sein de l'établissement. Chaque règle comptable est identifiée par un libellé et une description, correspondant à un type de vente spécifique. Cette classification favorise une gestion efficace des recettes et des dépenses, simplifiant ainsi le suivi financier et la création de rapports comptables précis

## Facture
La classe Facture représente un document juridique émis par un vendeur à un acheteur, relatif à une vente, et fait partie du système comptable. Elle contient des informations essentielles telles que le numéro de facture, la référence client, le montant total à payer, ainsi que des informations sur les lignes de la facture et les paiements.

Elle permet de suivre l'état de paiement (en attente, en retard, payé, etc.) et de gérer les termes de paiement. La facture peut être associée à des bons de commande (PoS), et inclut des détails sur les financements et les entrées comptables.
