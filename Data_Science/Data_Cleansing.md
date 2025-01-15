# Data Cleansing

**Professeur :** Alain Cariou  
**École :** EPSI  
**Section :** Développeur Data-Science, Développeur IA et Machine Learning  
**Date :** Janvier 2025  

---
[← Retour à la base du wiki](https://asyhnes.github.io/mon_wiki/)

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

### Importance dans la gestion des données
- **2019 :** 30 % des données d'entreprise étaient imprécises, engendrant des coûts significatifs.  
  [Source](https://www.edq.com/blog/highlights-from-our-2019-global-data-management-research/)
- Avantages du nettoyage des données :
  - Mise en conformité légale (ex. RGPD)
  - Réduction des coûts et optimisation de la productivité
  - Amélioration de l'expérience client et de la rétention
  - Meilleures prises de décisions stratégiques  

---

### Types de problèmes fréquents
- **Données non sécurisées :** mot de passe ou données bancaires en clair
- **Données obsolètes :** client décédé, adresse non mise à jour
- **Données incorrectes ou contradictoires :** formatage, syntaxe ou duplication
- **Données manquantes**  

---

## II. Les étapes du Data Cleansing

### Étapes générales
1. **Identifier** les sources de données essentielles
2. **Collecter** les données
3. **Gérer** les doublons
4. **Résoudre** les valeurs manquantes
5. **Automatiser** et standardiser le nettoyage
6. **Évaluer** et adapter le processus  

---

### Outils de Data Cleansing

#### Bibliothèques Python :
- **Pandas**  
  Manipulation et nettoyage des données. [Documentation Pandas](https://pandas.pydata.org/docs/index.html)
- **Pyjanitor**  
  Extension de Pandas pour un nettoyage plus lisible. [Documentation Pyjanitor](https://pyjanitor-devs.github.io/pyjanitor/)

#### Logiciels :
- **OpenRefine**  
  Logiciel open-source pour nettoyer et structurer les données.  
  [Télécharger OpenRefine](https://openrefine.org/download)  

---

## III. TP : Nettoyage de données

### Étape 1 : Choix d’un dataset
- Sélectionnez un dataset parmi ceux proposés :  
  - [Airbnb Open Data](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
  - [Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
  *(ou un dataset validé par le professeur)*  

### Étape 2 : Étude du dataset
- Analysez le contenu et identifiez les erreurs courantes
- Visualisez les problèmes sous forme de graphe  

### Étape 3 : Script avec Pandas
- Écrivez un script pour nettoyer les données :
  - Supprimez les doublons
  - Gérez les valeurs manquantes
  - Corrigez les erreurs de format  

### Étape 4 : Script avec Pyjanitor
- Reprenez le processus avec Pyjanitor et comparez avec Pandas.

### Étape 5 : Utilisation d’OpenRefine
- Appliquez le même processus de nettoyage qu'avec vos scripts
- Comparez les résultats obtenus  

### Étape 6 : Présentation
- Documentez vos recherches et résultats.
- Présentez votre travail à vos collègues.

---

## Ressources complémentaires
- [Tutoriel OpenRefine](https://www.patrimoine-et-numerique.fr/tutoriels/52-36-openrefine-excel-aux-hormones-pour-nettoyage-de-donnees)
- [Documentation Pandas](https://pandas.pydata.org/docs/index.html)
- [Documentation Pyjanitor](https://pyjanitor-devs.github.io/pyjanitor/)

---

**David Chardon**  
Etudiant *Développeur Data-Science, IA et Machine Learning*  
