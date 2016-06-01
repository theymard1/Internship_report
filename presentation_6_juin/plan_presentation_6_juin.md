Présentation du 6 juin
====

# Introduction

- Galaxy
  - Problème d'utilisation des outils bioinfos par les biologistes (ligne de commande)
  - Qu'est-ce que Galaxy? Présentation générale
  - Comment sont intégrés les outils dans Galaxy?
    - def rapide d'un wrapper
- Test logiciel
  - Qu'est-ce que le test logiciel?
  - A quoi ça sert? Le principe derrière
    - Exécution du logiciel et comparaison des sorties avec ce qui est attendu
  - Pourquoi c'est important?
    - Garantir que des changements n'impactent pas les résultats
    - autres arguments?
  - Différents types de tests (rapidement)
    - Tests unitaires
      - Définir ce que c'est
    - Tests fonctionnels
      - Définir ce que c'est et pourquoi c'est différent du test unitaire
- Le test de wrappers
    - wrapper ont besoins de tests fonctionnels

# Processus de tests de wrapper

*Faire un schéma global des différentes étapes en fin pour résumer tout, mais
avant passer étape par étape*

- Familiarisation avec l'outil bioinformatique lié au wrapper
  - Identification des entrées/sorties
  - Génération des entrées/sorties nécessaires pour le test
- Familiarisation et modification du wrapper déjà développé
  - Détailler les différentes choses à modifier dans le
- Test localement avec `planemo`
  - Présenter vite fait `planemo`
  - Comment tester avec `planemo`?
    - `planemo lint`
    - installation de l'outil
    - `planemo test`
- Intégration des modifications dans le dépôt GitHub
- Test dans un environnement "vierge"
  - Environnement "vierge" de Travis CI (Integration continue)
  - Test automatique quand soumission de changements dans le dépôt GitHub

# (je n'ai pas de titre en tête là...)

## Exemple de test

*prendre un wrapper et présenter le résultat final du test*

## Problèmes rencontrés et leurs solutions

*mettre des exemples à chaque fois*

- Des paramètres particuliers
- Des erreurs parfois incompréhensibles
- Problème de dépendances pas installées
    - packages `conda`
- Problèmes d'outils mal documentés
    - difficulté de génération des données pour les tests

## Wrappers testés

*mettre la liste des wrappers sur lesquels tu as fait*

## Et après?

- Merge de la PR
- Déploiement des wrappers sur Galaxy ToolShed

# Conclusion

- Retour : qu'est-ce que le test de wrapper
- Appris
    - Git
    - GitHub pour le travail en collaboration (principe des PR)
    - Principe d'intégration continue avec TravisCI
    - Principe de tests (important en développement logiciel)
