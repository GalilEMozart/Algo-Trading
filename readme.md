# TRADING ALGO

Ce projet consiste à développer un bot qui implémente une stratégie basée sur un algorithme de machine learning.

Le trading algorithmique est une täche qui permet d'utiliser l'ordinateur au sens plus large ou des programmes informatiques pour prendre des décisions d'investissement.

ÉTAPE :
1. COLLECTE DES DONNÉES
2. DÉVELOPPEMENT DE LA STRATÉGIE (ENTRAINEMENT DU MODÈLE)
3. TESTER LA STRATÉGIE
4. MISE EN PRODUCTION DE LA STRATÉGIE


## Structures

- Le dossier data contient toutes les données nécessaires lies à ce projet
- Le dossier notebook contient les notebooks contenants les analyses, etc
- Le dossier src contient les scripts pour le bot

## Quelques idées 

- Dans un premier temps l'idée est de développer un modèle assez simple de bout en bout, ensuite penser aux autres stratégies plus complexes, avoir donc un POC.
- Api yfinance, Vantage API.
- Courtier : RobinHood, Alpaca.
- Utiliser Lambda aws pour le deploiement
- Goal : Prédire si le prix d'une action va augmenter ou baisser, et de combien (return) ??? Une régression
- Certaine approche traditionnelle ne peuvent pas être appliquées sur ce type de série temporelle au manque de certains caractéristiques : non stationnaire, non saisonnalité, etc


## Quelques termes financiers

- momentum: est le moment d'investir dans l'actif dont le prix a le plus augmenté
- une action : c'est une propriété partielle d'une entreprise, lorsque vous achetez une action, vous achetez une part de cette entreprise. C'est donc posséder une fraction sur les actifs de l'entreprise et donc un droit sur les prochaines bénéfices.
- Indice boursier ;

Ancienne stratégie : buy and hold, moving average strategie


## Piste amélioration

- Data augmentation
- Ensemble methods