# 🐸 Jeu de Saute-Mouton - Interface Interactive (TP POO)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![USTHB](https://img.shields.io/badge/USTHB-FGE-9334e6?style=for-the-badge)

Ce dépôt contient le compte rendu et la solution interactive pour le **TP N°3 : Programmation des systèmes par les méthodes de POO**, réalisé dans le cadre du module de Programmation Orientée Objet (M1 AII).

L'implémentation algorithmique initiale en Java a été transposée en une **interface Web interactive** avec un design inspiré du *Google Pixel* (tons bleu, cyan et violet).

---

## 📋 Table des matières
1. [À propos du projet](#-à-propos-du-projet)
2. [Fonctionnalités et Interface](#-fonctionnalités-et-interface)
3. [Règles du jeu](#-règles-du-jeu)
4. [Installation et Exécution](#-installation-et-exécution)
5. [Structure Technique](#-structure-technique)
6. [Auteur](#-auteur)

---

## 💡 À propos du projet

Ce projet démontre l'application des concepts algorithmiques de la POO pour résoudre le casse-tête classique du "Saute-Mouton". Au lieu d'une simple exécution statique en console, ce compte rendu intègre un panneau d'exécution dynamique jouable directement dans le navigateur.

**Contexte académique :**
* **Université :** USTHB (Université des Sciences et de la Technologie Houari Boumediene)
* **Faculté :** FGE (Génie Électrique) - Département d'Automatique
* **Niveau :** Master 1 AII
* **Enseignant :** M. MENANI

---

## ✨ Fonctionnalités et Interface

* **Design "Google Pixel" :** Interface utilisateur épurée utilisant les polices `Roboto` et une palette de couleurs moderne (Bleu Google, Cyan, Violet).
* **Panneau Interactif Temps Réel :** Les pions sont cliquables et se déplacent dynamiquement sur l'écran avec des animations de survol.
* **Console Intégrée (Live Log) :** Une fausse console stylisée affiche en temps réel les mouvements effectués, les erreurs (coups interdits) et les états de fin de partie.
* **Moteur Logique JS :** L'algorithme de vérification des coups et de détection de blocage/victoire tourne en temps réel en arrière-plan.

---

## 🎯 Règles du jeu

Sur un plateau défini par l'utilisateur, des pions **Noirs (N)** sont placés à gauche et des pions **Rouges (R)** à droite, séparés par une **case vide**. 

* **But :** Inverser les positions (Rouges à gauche, Noirs à droite, espace au centre).
* **Déplacements :**
  * Les **Noirs** se déplacent uniquement vers la **droite**.
  * Les **Rouges** se déplacent uniquement vers la **gauche**.
  * Un pion peut avancer d'une case (si vide) ou sauter **un** pion adverse (si la case suivante est vide).

---

## 🚀 Installation et Exécution

Oubliez la compilation Java complexe pour tester le rendu visuel ! 

1. **Cloner ou télécharger** ce dépôt.
2. Ouvrez simplement le fichier `index.html` (ou le nom que vous avez donné au fichier) avec n'importe quel navigateur web moderne (Chrome, Firefox, Edge, Safari).
3. Le jeu est prêt à être utilisé dans la section "Panneau d'Exécution Temps Réel".

---

## ⚙️ Structure Technique

Le fichier unique regroupe :
* **HTML5 :** Sémantique et structure du compte rendu académique.
* **CSS3 :** Variables personnalisées (`:root`), Flexbox pour le plateau de jeu, et effets visuels (ombres, transitions).
* **JavaScript (Vanilla) :** * `initialiserJeu()` : Construction dynamique du plateau.
  * `jouerCoup(index)` : Cœur algorithmique gérant les règles d'avancement et de saut.
  * `verifierFin()` : Analyse du tableau pour déclarer la victoire ou un blocage.
  * `log()` : Injection de texte dans la console virtuelle.

---

## 👨‍💻 Auteur

**Dahane Ahmed Lamine** *Étudiant en M1 Automatique et Informatique Industrielle (AII)* *Design & Code : Interface Utilisateur Professionnelle*
