# Formation Data Cleansing

**Professeur :** Alain Cariou  
**École :** EPSI  
**Section :** Développeur Data-Science, Développeur IA et Machine Learning  
**Date :** Janvier 2025  

[← Retour à la base du wiki](https://asyhnes.github.io/mon_wiki/)  

[cours complet](Data_Science/Cours_data_cleasing)


---

## I. Qualité des données et Data Cleansing

### Définition
Le **data cleansing** ou nettoyage des données est un processus visant à identifier et corriger les données altérées, inexactes ou non pertinentes.  
Ces erreurs incluent : 
- Données manquantes ou mal renseignées
- Erreurs de saisie
- Données dupliquées, non pertinentes ou corrompues  

**Objectif :** Améliorer la cohérence, la fiabilité et la valeur des données.  

---

## II. Les étapes du Data Cleansing

### Étape 1 : Identifier les sources de données essentielles
Avant de commencer le nettoyage, il est crucial de :  
- Déterminer quelles données sont les plus utiles pour le projet.  
- Tracer la **provenance des données** et identifier où se trouvent les erreurs les plus fréquentes.  

Cela permet de mieux cibler les corrections nécessaires et de gagner du temps lors des étapes suivantes.

---

### Étape 2 : Collecter les données
Une fois les sources identifiées, procédez à la collecte des données :  
- Vérifiez la qualité et la cohérence des données collectées.  
- Assurez-vous que les différentes sources sont compatibles pour éviter des incohérences dès le départ.  

L'objectif est de partir sur une base solide pour les étapes suivantes.

---

### Étape 3 : Gérer les doublons
Les **doublons** peuvent apparaître lorsque les données proviennent de plusieurs sources. Pour les traiter :
1. Identifiez les données dupliquées en vérifiant les valeurs répétées.  
2. Conservez la version la plus récente ou la plus fiable.  

Cela empêche de fausser les analyses et garantit une meilleure précision des résultats.

---

### Étape 4 : Résoudre les valeurs manquantes
Les **valeurs vides ou manquantes** sont fréquentes. Plusieurs stratégies permettent de les traiter :  
- **Supprimer** les lignes où des valeurs sont manquantes.  
- **Compléter** les valeurs manquantes en utilisant des méthodes comme :
  - Moyenne
  - Médiane
  - Valeur la plus fréquente
  - Algorithmes (ex. k-nearest neighbors).  
- **Étiqueter** les valeurs comme "manquantes" pour signaler leur absence.  

L'objectif final est de garantir un dataset complet et cohérent.

---

### Étape 5 : Automatiser et standardiser le processus
L'automatisation est essentielle pour garantir une cohérence dans le nettoyage des données :  
- **Standardisez** les processus pour les rendre reproductibles.  
- Déterminez :
  - Les données les plus utilisées.
  - La fréquence à laquelle le nettoyage doit être effectué (quotidien, hebdomadaire, mensuel).  
  - Les responsables de la maintenance du processus.

Cela permet un gain de temps considérable et évite des erreurs humaines répétées.

---

### Étape 6 : Évaluer et adapter le processus
Le nettoyage des données est un processus itératif. À cette étape, il est important de :  
- **Évaluer** l'efficacité du processus : 
  - Quels sont les points positifs ?
  - Quels aspects peuvent être améliorés ?
- **Identifier** les problèmes récurrents et ajuster le processus en conséquence.  
- **Communiquer** avec l'équipe pour partager les retours et les améliorations.

Le but est de surveiller les données régulièrement pour anticiper et corriger les problèmes émergents.

---

## III. Les outils du Data Cleansing

### Bibliothèques Python :
- **Pandas**  
  - Manipule et nettoie les datasets.  
  - Documentation : [Pandas Docs](https://pandas.pydata.org/docs/index.html)  
- **Pyjanitor**  
  - Extension pour un nettoyage lisible et efficace.  
  - Documentation : [Pyjanitor Docs](https://pyjanitor-devs.github.io/pyjanitor/)  

### Logiciels :
- **OpenRefine**  
  - Nettoie et structure les données en CSV, XML, JSON, etc.  
  - Téléchargement : [OpenRefine](https://openrefine.org/download)  

---

## IV. TP : Nettoyage de données

### Étape 1 : Choix d’un dataset
Choisissez un dataset parmi les options suivantes ou proposez-en un à valider :
- [Airbnb Open Data](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
- [Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  

### Étape 2 : Étude du dataset
Analysez le dataset et identifiez :
- Le sujet traité.
- Les erreurs les plus courantes.
- Les moyens de représenter ces problèmes (ex. graphes).  

### Étape 3 : Script avec Pandas
Rédigez un script Python qui :
- Supprime les doublons.
- Remplace ou étiquette les valeurs manquantes.
- Corrige les erreurs de format.  

### Étape 4 : Script avec Pyjanitor
Refaites le nettoyage avec **Pyjanitor** et comparez-le avec Pandas :
- Quels avantages ou inconvénients remarquez-vous ?
- Le script peut-il être générique pour d'autres datasets ?

### Étape 5 : Utilisation d’OpenRefine
Utilisez OpenRefine pour appliquer les mêmes étapes. Comparez les résultats avec ceux de vos scripts.

### Étape 6 : Présentation
- Documentez vos recherches et résultats.
- Partagez vos conclusions avec vos collègues.

---

## Ressources complémentaires
- [Tutoriel OpenRefine](https://www.patrimoine-et-numerique.fr/tutoriels/52-36-openrefine-excel-aux-hormones-pour-nettoyage-de-donnees)
- [Documentation Pandas](https://pandas.pydata.org/docs/index.html)
- [Documentation Pyjanitor](https://pyjanitor-devs.github.io/pyjanitor/)

---

[← Retour à la base du wiki](https://asyhnes.github.io/mon_wiki/)

**David Chardon**  
*Développeur Data-Science, IA et Machine Learning*  
