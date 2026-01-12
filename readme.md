# Traitement Automatique de Langue Naturelle

Ou **Natural Language Processing (NLP)** en anglais. La gestion des données textuelles est complexes. Cette difficulté, combinée au foisonnement des données et des applications (et accessoirement des financements) fait de la communauté NLP, la plus grosse et la plus isolée des communautés du Machine Learning.

* Des conférences à part: ACL, EMNLP, ... [lien vers la biblio](https://aclanthology.org)
* Des pré-requis spécifiques
    * Jouer avec les données textuelles impose la maitrise des expressions régulières: **regex**
    * Maitriser les commandes systèmes de base pour manipuler les fichiers en profondeur, extraire les statistiques de base et vérifier les informations contenues
* Un choix parmi les nombreuses ressources disponibles, celles de l'équipe la plus connue au monde: [Stanford NLP Group](https://nlp.stanford.edu)
    * Ressources pédagogiques: [lien](https://nlp.stanford.edu/teaching/)
    * En particulier, les slides sur les regex à garder sous le coude: [lien](https://web.stanford.edu/class/cs124/lec/124-2021-UnixForPoets.pdf)


## 1. Les tâches de NLP et les approches historiques en sacs de mots

1. Classification de documents

2. Analyse thématique, clustering, approches non-supervisées
    - exploration rapide des approches non supervisées


## 2. Vers le deep-learning

1. Apprentissage de représentation de mots
    * de Bengio et Collobert à Word2Vec et FastText
    * Analyse quantitative sur la sémantique
2. Fonctions d'agrégation
    * RNN, CNN, Transformers
3. Reflexion sur la gestion des connaissances et les modèles génératifs

## 3.Prise de recul sur le NLP post chatGPT

1. Nouveaux Usages

2. Réflexion éthique


# Modélités d'évaluation

Démontrer votre capacité à créer une chaine de traitement des données textuelles sur l'analyse d'opinion et la classification de locuteur

* Travail en monome ou binome
* Jeux de données
    * Revues de films
    * Chirac / Mitterrand
* Analyses obligatoires
    * Comparer les performances avec différents pré-traitements
        * e.g Taille de vocabulaire, unigram/bigram, Stemming, ...
    * Implémenter un post-traitement sur les données Chirac/mittérrand
    * Appliquer les traitements optimaux sur les données de test et sauver les résultats dans un fichier txt
* Compléments optionnels
    * Analyser les performances avec Word2Vec, en utilisant des stratégies d'agrégation naïves
* Ecrire un rapport succinct 
    * Présentant les courbes de perfornces pour les paramètres les plus influents/marquants
    * Quelques conclusions sur le travail effectué
* Soumettre par mail:
    * Rapport, Notebook(s), 2 fichiers de scores (locuteur/opinion)