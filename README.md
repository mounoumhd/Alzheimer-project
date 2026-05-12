# Détection Précoce de la Maladie d'Alzheimer avec Deep Learning

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
