# Configuration de ton projet AR dans Unity

## 1. Création d'un nouveau projet 3D dans Unity
### Actions :
- Créeation du nouveau projet IRP
- Nom du projet : ARchive

## 2. Ajout du plugin Oculus Integration
### Actions :
- Importation du plugin Oculus Integration
- Vérification des options disponibles via le menu Tools > Oculus, pour l'"Eye Tracking"

## 3. Configuration des Player Settings
### Actions :
- Dans Unity, naviguer vers Edit > Project Settings > XR Plugin Management
- Activer OpenXR pour gérer la compatibilité avec le Meta Quest 3
- Dans Player Settings :
  - Configurer l'option Stereo Rendering Mode sur Single Pass Instanced pour optimiser les performances
  - Activation Oculus Quest comme appareil cible
  - S'assurer que l'application fonctionne à 72 FPS ou plus

## 4. Ajout du eye tracking et des interactions digitales
### Actions :
- Configuration du Eye Tracking :
  - Activer le Eye Gaze dans les paramètres du casque
  - Utiliser les scripts inclus (OVREyeGaze) pour récupérer les coordonnées du regard

## 5. Implementation du script pour détecter un regard prolongé
### Actions :
- Créer un script C# pour détecter un regard prolongé
- Utiliser OVREyeGaze pour obtenir les coordonnées du regard de l'utilisateur

## 6. Raycast pour interaction digitale
### Actions :
- Implémenter le script pour un raycast simulant un faisceau depuis le contrôleur ou le casque

