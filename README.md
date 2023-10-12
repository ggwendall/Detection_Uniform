![banner2](https://github.com/ggwendall/Detection_Uniform/assets/48108275/c0191481-e2e2-467d-9edb-57838fb91e23)

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

# Application de Détection de Casque/Gilet de Chantier

## Table des matières

- [Contexte du Projet](#contexte-du-projet)
- [Objectif](#objectif)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Arborescence du Projet](#arborescence-du-projet)
- [Installation et Utilisation](#installation-et-utilisation)
- [Captures d'écran](#captures-décran)
- [Contributions](#contributions)

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Contexte du Projet

Les caméras de surveillance et de sécurité sont devenues un outil essentiel pour garantir la sécurité dans diverses applications. Notre entreprise se spécialise dans le développement de solutions technologiques pour les caméras de surveillance et de sécurité. Dans le cadre de ce projet, nous visons à développer une application web basée sur l'intelligence artificielle (IA) capable de détecter et de localiser la présence de casques et de gilets de chantier dans une vidéo.

L'application que nous développons doit être en mesure d'activer la caméra de l'ordinateur et d'afficher les résultats de la détection en temps réel sur la vidéo. De plus, l'application doit être capable de générer un message d'alerte en dehors de la vidéo si une personne ne porte pas son casque ou son gilet de chantier.

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Objectif

L'objectif principal de ce projet est de créer une application web robuste capable de détecter et de localiser la présence de casques et de gilets de chantier dans une vidéo en temps réel. Les points clés de notre mission sont les suivants :

1. **Détection d'Équipements de Sécurité** : Développer un algorithme d'IA capable de détecter la présence ou l'absence de casques et de gilets de chantier dans une vidéo.

2. **Interface Web Conviviale** : Créer une interface web conviviale qui affiche la vidéo en temps réel et les résultats de la détection.

3. **Gestion des Alertes** : Générer un message d'alerte sur la page web si une personne ne porte pas son casque ou son gilet de chantier.

4. **Vérification de l'Uniforme** : Afficher un message "Uniforme vérifié" si toutes les détections sont conformes, sinon afficher "Uniforme non vérifié".

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Fonctionnalités

- Détection en temps réel de la présence de casques et de gilets de chantier dans une vidéo.
- Affichage de la vidéo en temps réel avec les résultats de la détection.
- Génération d'un message d'alerte en cas de non-port d'un casque ou d'un gilet de chantier.
- Message "Uniforme vérifié" si toutes les détections sont conformes, sinon "Uniforme non vérifié".

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Prérequis

Avant de commencer à travailler sur ce projet, assurez-vous de disposer des éléments suivants :

- **Environnement de Développement** : Un environnement de développement Python 3.x configuré sur votre ordinateur.

- **Bibliothèques Python** : Installez les bibliothèques Python nécessaires, que vous pouvez trouver dans le fichier `requirements.txt`.

- **Caméra PC** : Votre ordinateur doit être équipé d'une caméra pour la détection en temps réel.

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Arborescence du Projet

Organisez le projet sur votre machine selon la structure suivante :

```
Yolo/
│ 
├─── assets/
│   └─── pic1.png
│
├─── images/
│   ├─── worker.png
│   └─── worker_detected.png
│
├─── weights/
│   ├─── best.pt
│   ├─── yolo8n.pt
│   ├─── yolov8n-cls.pt
│   └─── yolov8n-seg.pt
│
├─── .gitignore
├─── README.md
├─── app.py
├─── helper.py
├─── settings.py
└───  requirements.txt

```

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Installation et Utilisation

Pour mettre en place et utiliser l'application de détection de casque/gilet de chantier, suivez ces étapes :

1. Clonez ce référentiel sur votre ordinateur.

2. Installez les dépendances requises en exécutant la commande suivante :
   ```bash
   pip install -r app/requirements.txt
   ```

3. Lancez l'application web en exécutant :
   ```bash
   python app/web_app.py
   ```

4. Ouvrez un navigateur web et accédez à l'URL suivante : `http://localhost:8080` pour utiliser l'application.

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Captures d'écran

<img width="1247" alt="Capture d'écran 2023-10-10 124819" src="https://github.com/ggwendall/Detection_Uniform/assets/48108275/64d9a9f8-8b1e-444e-8919-dc94a0cc74d9">

<img width="1249" alt="Capture d'écran 2023-10-12 125326" src="https://github.com/ggwendall/Detection_Uniform/assets/48108275/14247185-9b74-4271-bfe2-fa793f5d1bf0">

<img width="1248" alt="Capture d'écran 2023-10-12 125257" src="https://github.com/ggwendall/Detection_Uniform/assets/48108275/444ed3ae-c43e-4532-ae11-3e884ecbbb4a">

<img width="1248" alt="Capture d'écran 2023-10-12 125642" src="https://github.com/ggwendall/Detection_Uniform/assets/48108275/5c4f3db9-dbf3-4975-a45a-726defc6b0bb">

<img width="1249" alt="Capture d'écran 2023-10-12 125201" src="https://github.com/ggwendall/Detection_Uniform/assets/48108275/7be41356-82c5-4e7a-b435-104ccf3c0bec">


![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Contributions

Merci au contributeurs de ce projet ! 

<div align=center>

<img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> 

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

![Bottom](https://github.com/ggwendall/ggwendall/assets/48108275/1f58de6a-f411-45fd-86a6-e9aa673332e6)
