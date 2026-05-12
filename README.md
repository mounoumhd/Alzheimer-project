# Détection Précoce de la Maladie d'Alzheimer avec Machine Learning

## Description
Ce projet utilise l’intelligence artificielle et le deep learning pour détecter précocement la maladie d’Alzheimer à partir d’images IRM cérébrales.

L’application permet à l’utilisateur de charger une image IRM et d’obtenir :
- un diagnostic prédictif,
- un niveau de risque,
- une explication médicale,
- les probabilités de chaque classe.

## Technologies utilisées
- Python
- TensorFlow / Keras
- Gradio
- NumPy
- OpenCV
- Google Colab

## Dataset
Le modèle a été entraîné sur un dataset d’IRM cérébrales contenant plusieurs classes :
- Non Demented
- Very Mild Demented
- Mild Demented
- Moderate Demented

## Fonctionnalités
- Upload d’image IRM
- Analyse automatique par IA
- Affichage des probabilités
- Interface utilisateur interactive avec Gradio

## Lancement du projet

### Installation des bibliothèques
```bash
pip install tensorflow gradio opencv-python numpy pillow

#Limites du Projet

Ce système constitue une aide au diagnostic et ne remplace pas l’avis d’un médecin spécialiste.

Les résultats dépendent :

de la qualité des images IRM,
du dataset utilisé,
du niveau d’entraînement du modèle.

## Exécution sur Google Colab

Le projet a été développé et exécuté sur Google Colab.

Étapes :
1. Ouvrir le notebook `.ipynb`
2. Monter Google Drive
3. Charger le modèle `.h5`
4. Exécuter toutes les cellules
