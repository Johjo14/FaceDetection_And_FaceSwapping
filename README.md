# Détection de visage et echange de visages via OpenCV

Ce petit projet consiste à détecter des visages ainsi que des yeux sur des images grâce aux classificateurs(Face, eyes) en cascade d'OpenCV. Par la suite on échange deux visages entre eux.

##L'objectif du projet

- Détection de visages sur des portraits et des photos de groupe
- Détection des yeux pour affiner la précision
- Extraction des visages détectés
- Petit plus : Échange automatique de deux visages sur une photo (si deux visages détectés)

## Exemple utilisés

Trois images ont servit de test pour ce petit projet:
- `portrait_1.jpg` : Portrait d’une seule personne
- `couple_macron.jpg` : Photo de couple pour extraire les visages
- `couple_acteurs.jpg` : Utilisé pour l’échange automatique de visages
  
## Lancement du projet
1. Cloner le dépôt :

```bash
git clone https://github.com/Johjo14/FaceDetection_And_FaceSwapping.git
cd face-detection
