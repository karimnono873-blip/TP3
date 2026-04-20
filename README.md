# 🐸 Simulateur Interactif Saute-Mouton - TP POO

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-Algorithms-007396?style=for-the-badge&logo=java&logoColor=white)
![USTHB](https://img.shields.io/badge/USTHB-FGE-9334e6?style=for-the-badge)

[cite_start]Ce dépôt contient le projet complet (Code source Java et Interface Web Interactive) pour le **TP N°3 : Programmation des systèmes par les méthodes de POO**[cite: 5]. 

L'application modélise et résout le problème algorithmique du jeu "Saute-Mouton", en intégrant le code source de l'algorithme ainsi qu'une interface graphique moderne (thème Material/Google Pixel) dotée d'un moteur d'exécution en temps réel.

---

## 🎓 Contexte Académique
* [cite_start]**Université :** Université des Sciences et de la Technologie HOUARI BOUMEDIENE - USTHB [cite: 1]
* [cite_start]**Faculté :** Faculté de Génie Electrique FGE - Département d'Automatique [cite: 2]
* [cite_start]**Module :** TP POO [cite: 3]
* [cite_start]**Niveau & Spécialité :** Master 1 AII (Automatique) [cite: 4]
* [cite_start]**Enseignant :** M. MENANI [cite: 38]

---

## 🎯 Règles du Système Modélisé
Le système est basé sur un plateau unidimensionnel avec des règles de transition strictes :
* [cite_start]**Configuration initiale :** Des pions noirs sont placés à gauche et des pions rouges à droite, séparés par une case vide unique[cite: 64]. [cite_start]On pose autant de pions noirs que de pions rouges[cite: 65].
* [cite_start]**Objectif :** Déplacer tous les pions rouges vers la gauche et tous les pions noirs vers la droite, la case vide occupant à la fin du jeu la case du milieu[cite: 67].
* **Contraintes de déplacement :**
  * [cite_start]Les pions noirs ne peuvent se déplacer que vers la droite[cite: 74].
  * [cite_start]Les pions rouges ne peuvent se déplacer que vers la gauche[cite: 75].
  * [cite_start]Un pion peut avancer d'une case si la case adjacente est vide[cite: 77, 82].
  * [cite_start]Un pion peut sauter par-dessus un seul pion adverse si la case située juste après cet obstacle est vide[cite: 80, 83].
* [cite_start]**Condition d'arrêt :** Le jeu s'arrête si la configuration finale est atteinte (victoire) ou si vous avez atteint une situation de blocage matériel (défaite)[cite: 97, 98].

---

## ✨ Fonctionnalités Principales
* **Moteur Logique Strict :** L'algorithme vérifie rigoureusement chaque déplacement selon l'arbre de décision exigé par le cahier des charges.
* **Détection de Deadlock :** Scan matériel complet du tableau à chaque itération pour identifier les situations de blocage irrémédiables.
* **Architecture Web Monolithique :** Un fichier HTML/CSS/JS unique regroupant la théorie, le code Java syntaxiquement mis en valeur, et le simulateur interactif.
* **Design "Google Pixel" :** Interface utilisateur soignée avec une palette de couleurs professionnelle (Bleu, Cyan, Violet), ombres dynamiques et typographie claire (`Roboto` / `Fira Code`).
* **Console d'Exécution Temps Réel :** Panneau de débogage affichant l'historique des coups, les logs systèmes, les index de la mémoire et la détection d'erreurs en direct.

---

## 🚀 Déploiement et Utilisation
L'avantage de cette version "Ultimate" est qu'elle est prête à être déployée sur GitHub Pages et ne nécessite aucune compilation Java pour visualiser les résultats de la logique :
1. Téléchargez le fichier `index.html`.
2. Ouvrez-le simplement dans un navigateur web moderne (Chrome, Edge, Firefox, Safari).
3. [cite_start]Utilisez le panneau de contrôle interactif pour tester l'algorithme : ajustez le nombre de pions (N maximum = 10 [cite: 136]) et cliquez sur les éléments pour simuler les déplacements en mémoire.

---

## 👨‍💻 Auteur
**Dahane Ahmed Lamine** *Spécialité Automatique et Informatique Industrielle - Développement d'Interfaces et Systèmes*
