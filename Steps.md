## Configuration de ton projet AR dans Unity

1. Création d'un nouveau projet 3D dans Unity
 
Action :

Go Unity Hub.
Création du nouveau projet en sélectionnant le template 3D.
Nom du projet : ARchive

2. Ajout du plugin Oculus Integration

Action :

Asset Store intégré à Unity.
Importation du plugin Oculus Integration.
Go pour menu Tools > Oculus pour vérification des options disponibles, pour le "Eye Tracking".

3. Configuration des Player Settings

Action :

Dans Unity, Edit > Project Settings > XR Plugin Management.
Active OpenXR pour gérer la compatibilité avec le Meta Quest 3.
Dans Player Settings :
Configuration de l’option Stereo Rendering Mode sur Single Pass Instanced pour optimiser les performances.

Activation d'Oculus Quest comme appareil cible.
S'assurer que l'application fonctionne à 72 FPS ou plus.

4. Ajout du eye tracking de regard et des interactions digitales.

Action :

Configuration du Eye Tracking :
Activation du Eye Gaze dans les paramètres du casque.
Utilisation des scripts inclus ( OVREyeGaze) pour récupérer les coordonnées où l'utilisateur regarde.

5. Implementation du script pour détecter un regard prolongé

Action :

Création d'un script C# pour détecter un regard prolongé.
Utilisation de OVREyeGaze pour obtenir les coordonnées où l'utilisateur regarde.

6. Raycast pour interaction digitale

Action :
Implémentation du script pour un raycast simulant un faisceau depuis le contrôleur ou le casque.

