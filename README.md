# **Projet 3 : Concevez une application au service de la santé publique**
## <u>Mission</u>
L'objectif du projet était de proposer une idée innovante d'application, en lien avec l'alimentation, après l'appel à projets par l'agence Santé Publique France.

<u>Idée d'application</u> : L'application Eat'M a pour rôle de proposer, à un utilisateur, différents choix de produits appartenant à la même catégorie que celui sélectionné après scan du code barre. L'intérêt est de proposer l'ensemble des choix possibles qui s'offrent à lui et présents dans la base de données. Les produits présentés à l'utilisateur sont triés dans l'ordre du plus sain au plus douteux/toxique pour la santé humaine en se basant sur un score. Ce score est créé en tenant compte à la fois du nutriscore (calculé à partir des valeurs nutritionnelles du produit) et de la présence d'additifs, ainsi que de leur toxicité.

## <u>Données</u>
Les données sont disponibles sur le site officiel [Open Food Facts](https://world.openfoodfacts.org/).
Les données donnent des renseignements sur : 

- Les informations générales sur la fiche du produit : nom, date de modification, etc.
- Un ensemble de tags : catégorie du produit, localisation, origine, etc.
- Les ingrédients composant les produits et leurs additifs éventuels.
- Des informations nutritionnelles : quantité en grammes d’un nutriment pour 100 grammes du produit.

## <u>Description du répertoire</u>
Le répertoire est constitué de deux notebooks jupyter dont l'un `Rondeau_Eva_1_notebook_nettoyage_122022.ipynb` concerne le nettoyage et le second `Rondeau_Eva_2_notebook_exploratoire_122022.ipynb` concerne l'analyse exploratoire des données. Le fichier `Rondeau_Eva_3_presentation_122022.odp` sert de support de présentation. 

## <u>Prérequis</u>
* [Python](https://www.python.org/downloads/release/python-3109/) : version 3.10.9
* [Windows](https://www.microsoft.com/fr-fr/software-download/windows11) 11 
* [Git](https://git-scm.com/downloads) : version 2.41.0