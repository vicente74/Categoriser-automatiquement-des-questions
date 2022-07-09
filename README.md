# Categorisez automatiquement des questions

Projet n°5 de la formation Ingénieur Machine Learning d'OpenClassrooms: https://openclassrooms.com/fr/paths/148-ingenieur-machine-learning#path-tabs

## Présentation du projet:

Stack Overflow est un site célèbre de questions-réponses liées au développement informatique.

Pour poser une question sur ce site, il faut entrer plusieurs tags afin de retrouver facilement la question par la suite. Pour les utilisateurs expérimentés, cela ne pose pas de problème, mais pour les nouveaux utilisateurs, il serait judicieux de suggérer quelques tags relatifs à la question posée.

Amateur de Stack Overflow, qui vous a souvent sauvé la mise, vous décidez d'aider la communauté en retour. Pour cela, vous développez un système de suggestion de tags pour le site. Celui-ci prendra la forme d’un algorithme de machine learning qui assignera automatiquement plusieurs tags pertinents à une question.

**Les données:**

Stack Overflow propose un outil d’export de données, ["StackExchange Data Explorer"](https://data.stackexchange.com/stackoverflow/query/new), qui recense un grand nombre de données authentiques de la plateforme d’entraide. 

**Contraintes:**

- Appliquer des méthodes d’extraction de features spécifiques des données textuelles.
- Mettre en œuvre une approche non supervisée afin de proposer des mots clés.
- Mettre en œuvre une approche purement supervisée et comparer les résultats avec l’approche non supervisée. Plusieurs méthodes d’extraction de features seront testées et comparées ; au minimum :
  - une approche de type bag-of-words ;
  - 3 approches de Word/Sentence Embedding : Word2Vec (ou Doc2Vec, Glove…), BERT et USE. 
- Mettre en place une méthode d’évaluation propre, avec une séparation du jeu de données pour l’évaluation.
- Utiliser un logiciel de gestion de versions, par exemple Git, pour suivre les modifications du code final à déployer.

**Livrables:** 

- Un notebook d’exploration comprenant une analyse univariée, une analyse multivariée, une réduction dimensionnelle et les différentes questions de recherche associées (non cleané, pour comprendre votre démarche).
- Un notebook de test de différents modèles (non cleané, pour comprendre votre démarche).
- Le code final à déployer présenté dans un répertoire et développé progressivement à l’aide d’un logiciel de gestion de versions (plusieurs commits cohérents).
- Le point d’entrée d’une API disponible pour le test.
- Une présentation servant de support à la soutenance.

**Compétences évaluées:**

- Représenter graphiquement des données à grandes dimensions
- Mettre en œuvre des techniques de réduction de dimension
- Prétraiter des données non structurées pour obtenir un jeu de données exploitable
- Mettre en œuvre des techniques d’extraction de features pour des données non structurées
