
## Le Kata
### Minimum Valuable Product - MVP

#### User Story 1
> En tant que banque, j'accepte le dépôt d'argent d'un client vers son compte, s'il est supérieur stictement à 0€

#### User Story 2
> En tant que banque, j'accepte le retrait d'argent d'un client depuis son compte, s'il n'utilise pas le découvert

#### User Story 3
> En tant que banque, j'offre la possibilité à mon client de consulter l'historique des transactions sur son compte

### Features bonus
Les fonctionnalités suivantes sont optionnelles et non exhaustives.  
Elles n'ont pas de priorité entre elles, vous pouvez implémenter celles qui vous intéressent ou même en proposer d'autres.

#### API REST
* Proposer une API REST consommable via http pour interagir avec les services réalisé dans le MVP
* Sécuriser l'API
* Utiliser une solution non-bloquante

#### Clients & Comptes
* La banque a plusieurs clients
* Un client peut avoir plusieurs comptes

#### Persistence
* Proposer une solution de persistence des données

#### Interface Utilisateur
* Proposer une interface graphique pour interagir avec les services réalisés dans le MVP

#### CI/CD
* Utiliser Gradle au lieu de Maven
* Proposer un system de CI/CD pour le projet
* Proposer des tests End to End à destination de votre livrable
