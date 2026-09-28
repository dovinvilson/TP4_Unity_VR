# 🥽 TP4_Unity_VR - Projet de Réalité Virtuelle sous Unity

Bienvenue sur le dépôt de mon **TP4 Unity VR**, réalisé dans le cadre de ma formation d'ingénieur en majeure **T2IA (Technologies, Web et Intelligence Artificielle)** à l'EFREI Paris. Ce projet met en œuvre des mécaniques avancées de Réalité Virtuelle à l'aide d'Unity et du kit d'interaction officiel.

---

## 🚀 À propos du projet
Ce projet a pour objectif de concevoir et de structurer une application immersive en Réalité Virtuelle interactive. Il intègre la gestion des caméras VR, le déplacement dans l'espace virtuel, ainsi qu'un système complet d'interaction avec des objets physiques (notamment la saisie d'armes et une mécanique de tir).

---

## 🛠️ Technologies et Outils Utilisés
* **Moteur de jeu :** Unity (version compatible XR)
* **Kit d'interaction :** XR Interaction Toolkit
* **Langage de script :** C#
* **Gestion de versions :** Git & **Git LFS** (pour la gestion des fichiers 3D et assets lourds)
* **Hébergement :** GitHub

---

## ⚙️ Fonctionnalités & Étapes de Réalisation

1. **Configuration de l'environnement VR :**
   * Mise en place des composants de caméra XR Rig (Left/Right Hand Controllers).
   * Configuration des paramètres de rendu et d'interaction spatiale.

2. **Système de Locomotion et Déplacement :**
   * Implémentation des déplacements fluides et/ou par téléportation pour éviter le mal de mer en VR.
   * Gestion des inputs des manettes (joysticks et boutons).

3. **Interactions avec les objets (`XR Grab Interactable`) :**
   * Paramétrage des objets interactifs de la scène.
   * Création et ajustement d'un **`AttachPoint`** personnalisé pour positionner correctement les objets (comme le modèle 3D du fusil M4A1) dans la main du joueur.

4. **Mécanique de Tir en VR :**
   * Scripting de la logique de tir reliée à l'événement `activated` du composant d'interaction.
   * Gestion de l'apparition des projectiles / rayons et des interactions physiques avec les cibles.

---

## 📂 Structure du Dépôt
* `Assets/` : Contient tous les scripts C#, les scènes, les matériaux, les prefabs et les modèles 3D (gérés via Git LFS).
* `Packages/` : Dépendances et manifestes du projet Unity.
* `ProjectSettings/` : Paramètres de configuration du projet Unity.

---

## 👨‍💻 Auteur
* **Dovin Vilson Tchoffo Manfouo**
* Étudiant en cycle ingénieur — Majeure **T2IA** à l'**EFREI Paris**.
