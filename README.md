# IA-ECG

# Projet de Détection d'Anomalies dans les Signaux ECG

## Description
Ce projet a été réalisé dans le cadre du cours IUT3.FISA.VT pour le BUT Réseaux et Télécommunications parcours Cybersécurité. Il s'agit d'un système de détection d'anomalies dans les signaux ECG (électrocardiogrammes) utilisant des techniques d'apprentissage automatique.

## Structure du Projet
Le projet est organisé en plusieurs phases :
- **Phase 1** : Analyse descriptive des données ECG
- **Phase 2** : Sélection et déploiement d'un modèle prédictif
- **Phase 3** : Conception d'une solution end-to-end
- **Phase 4** : Présentation du projet avec un cas d'usage

## Données
Le projet utilise la base de données MIT-BIH Arrhythmia Database disponible sur PhysioNet (https://physionet.org/content/mitdb/1.0.0/). Cette base de données contient 48 enregistrements ECG annotés de 30 minutes chacun.

## Fonctionnalités
- Prétraitement et visualisation des signaux ECG
- Segmentation des battements cardiaques
- Extraction de caractéristiques pertinentes
- Classification des battements (normaux vs anomalies)
- Visualisation des résultats de détection

## Technologies Utilisées
- Python
- Bibliothèques : NumPy, Pandas, Matplotlib, WFDB, Scikit-learn
- Algorithme de classification : Random Forest

## Installation et Utilisation

### Prérequis
```
python 3.8+
numpy
pandas
matplotlib
scikit-learn
wfdb
scipy
```

## Résultats
Le modèle Random Forest développé permet de détecter efficacement les anomalies dans les signaux ECG avec une précision d'environ 95%. La solution est capable de traiter des signaux en temps réel et de visualiser les anomalies détectées.

## Auteur
Tom Monin
BUT Réseaux et Télécommunications, parcours Cybersécurité
IUT de Créteil-Vitry
