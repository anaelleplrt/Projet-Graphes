# 📊 Projet SM601 - Ordonnancement (Théorie des Graphes)

Ce projet a été réalisé dans le cadre du cours **SM601 – Théorie des graphes** à l’Efrei. Il vise à modéliser un problème d’ordonnancement sous forme de graphe, à partir d’un tableau de contraintes fourni dans un fichier texte.
Contributeurs : Anaëlle Pollart, Tristan Martinez, Jérôme Balthazar, Louise Monciero et Diaby Diakite.

## 🚀 Objectif

- Lecture d'un fichier `.txt` contenant un tableau de contraintes
- Affichage du tableau de contraintes (sous formes de lignes et de matrice)
- Vérification du graphe d'ordonnancement (absence de circuits, pas d’arcs négatifs)
- Calculer et afficher :
  - Les rangs des tâches
  - Le calendrier au plus tôt
  - Le calendrier au plus tard
  - Les marges
  - Le ou les chemins critiques
- Produire des **traces d’exécution** dans des fichierssauvegarde `.txt` pour chaque tableau

---

## 🧩 Fonctionnalités

- 📄 Lecture dynamique de tableaux de contraintes depuis des fichiers texte
- 🔍 Vérification de la validité du graphe d'ordonnancement (circuit, arcs négatifs)
- 📐 Construction de la matrice de valeurs
- 🧠 Tri topologique pour calculer les rangs
- 📆 Calcul des calendriers (au plus tôt / au plus tard)
- 📉 Calcul des marges totales
- 🔴 Affichage des chemins critiques
- 🗂️ Traces d’exécution générées automatiquement dans des fichiers sauvegardes
- 🔁 Test de plusieurs fichiers en boucle, sans redémarrage manuel

---

## 📦 Prérequis

- Python 3.x
- Aucun module externe requis (tout est en Python natif)

---

## ▶️ Utilisation

1. Placez vos fichiers `.txt` de contraintes dans le dossier prévu (dossier "tests").
2. Lancez le fichier principal (main.py) :
