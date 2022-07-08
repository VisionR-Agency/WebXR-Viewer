# WebXR-Viewer

## Description

Un moyen de tester nos applications Web sur n'importe quel appareil.
Sert surtout pour les applications AR.

## Pré-requis

Suivre ceux du projet WebXR.

## Changements

### La vidéo 360

* Séléctionnez le fichier __index.html__.
* Au niveau du code ci-dessous, changez : "./textures/gemab2021_01_BD.mov" avec le nouveau nom de la vidéo.

![Capture d’écran 2022-07-08 à 15 24 27](https://user-images.githubusercontent.com/47010358/178000726-460aabe2-1c02-429c-8577-352adcf80f78.png)

* Stockez la nouvelle vidéo dans le dossier textures.

### Rajouter des vidéos et boutons

* Sélectionnez le fichier __index.html__.
* Copier / coller le code ci-dessous en dessous de celui-ci.

![Capture d’écran 2022-07-08 à 15 27 00](https://user-images.githubusercontent.com/47010358/178001110-381ac951-d8d0-418d-b63a-adafa4876a9c.png)

* Changez chaque instance du nom du bouton (oublier pas celui dans les guillemets a la première ligne).
* Changez les lignes _changeVideo.verticalAlignment = BABYLON.GUI.Control.VERTICAL_ALIGNMENT_BOTTOM_ et _changeVideo.horizontalAlignment = BABYLON.GUI.Control.HORIZONTAL_ALIGNMENT_RIGHT;_ pour pas que les boutons se superpose.
* Dans la méthode _onPointerUpObservable_ changez l'url avec celle de la nouvelle vidéo.
