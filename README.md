 # 🎬 Analyse et Visualisation des Données Netflix

## 📝 Description
Ce projet consiste à analyser et visualiser les données de Netflix afin d’identifier les tendances de production et d’acquisition de contenus. Les données sont extraites, nettoyées et transformées avec Python avant d’être explorées à travers des graphiques interactifs.

## 🚀 Fonctionnalités
- **Extraction des données** à partir d’un fichier CSV.
- **Nettoyage des données** avec Pandas (gestion des valeurs manquantes, typage des données, etc.).
- **Transformation des données** pour faciliter les analyses.
- **Conception de visualisations interactives** :
  - Répartition des productions Netflix selon le type.
  - Histogramme du Top 10 des catégories de production.
  - Analyse des acquisitions Netflix sur la période 2011-2021.
- **Calculs statistiques** sur les productions par pays et tendances temporelles.

## 🛠️ Stack Technique
- **Python** pour l'analyse des données.
- **NumPy, Pandas** pour la manipulation des données.
- **Matplotlib, Seaborn** pour la visualisation.
- **Jupyter Notebook** pour le développement interactif.
- **Git/GitHub** pour le versionnement.

## 📥 Installation et Utilisation
### 📌 Prérequis
- Python 3.x installé.
- Jupyter Notebook installé .
- Bibliothèques Python nécessaires (voir ci-dessous).

### 📂 Clonage du Projet
```sh
git clone https://github.com/JennyTchiegue/Analyse_Films.git
cd Analyse_Films
```

### 📦 Installation des Dépendances
Installe les bibliothèques requises avec :
```sh
pip install -r  

numpy
pandas
matplotlib
seaborn
jupyter
```

### 📊 Lancement de l'Analyse
Ouvre Jupyter Notebook et exécute le fichier principal :
```sh
jupyter notebook
```

## 📈 Analyse des Données
1. **Prétraitement des Données :**
   - Chargement des données depuis un fichier CSV.
   - Nettoyage des données avec Pandas (suppression des valeurs nulles, conversion des types, etc.).
   
2. **Exploration et Visualisation :**
   - Nombre de productions par pays.
   - Tendance des acquisitions Netflix de 2011 à 2021.
   - Classement des genres les plus populaires.
   - Histogramme du Top 10 des catégories de production.
   
## 📌 Structure du Projet
```
├── data/               # Fichiers de données bruts
├── notebooks/          # Jupyter Notebooks pour l'analyse
├── src/               
│   ├── data_cleaning.py  # Script de nettoyage des données
│   ├── analysis.py       # Script d'analyse
│   ├── visualization.py  # Création des graphiques
├── README.md           # Documentation principale
├── requirements.txt    # Liste des dépendances
```

## ✅ Tests et Validation
- Vérification de la cohérence des données après nettoyage.
- Validation des tendances par comparaison avec des sources officielles.
- Analyse des résultats via les graphiques générés.

## 🤝 Contribution
1. Forker le projet
2. Créer une branche (`git checkout -b feature-nouvelle-analyse`)
3. Committer (`git commit -m "Ajout d'une analyse des tendances"`)
4. Pousser (`git push origin feature-nouvelle-analyse`)
5. Ouvrir une Pull Request

 

## 📩 Contact
Si tu as des questions, n'hésite pas à me contacter sur [LinkedIn](https://linkedin.com/in/jenny-tchiegue-907803257) ou à ouvrir une issue sur GitHub ! 🚀

