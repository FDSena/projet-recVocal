# Projet de reconnaissance vocale – "allumer" / "éteindre"

Ce projet vise à reconnaître des mots-clés dans des enregistrements audio, notamment les mots "allumer" et "éteindre", à l'aide de techniques de machine learning en Python.

## Objectif

Développer un système simple de reconnaissance vocale capable d'écouter une commande prononcée, de la traiter et d’identifier si elle correspond à l’un des mots appris.

## Technologies utilisées

- Python
- Librosa : extraction de caractéristiques audio (MFCC)
- Scikit-learn : classification supervisée
- Sounddevice : enregistrement audio live
- NumPy, Matplotlib
- Jupyter Notebook / VS Code

Les fichiers audio ne sont pas inclus dans ce dépôt pour respecter la limite de taille imposée par GitHub. Vous pouvez les ajouter localement dans les dossiers correspondants.

## Utilisation

1. Enregistrer vos propres fichiers audio dans les bons dossiers (par exemple avec `audio_maker.ipynb`)
2. Ouvrir et exécuter `Projet.ipynb` pour :
   - Extraire les caractéristiques MFCC
   - Entraîner le modèle
   - Tester la reconnaissance vocale en direct
