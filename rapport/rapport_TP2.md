# Rapport TP2 – Python & GitHub Actions

## 1. Introduction
L’objectif de ce TP est de créer un petit programme Python, de le publier sur GitHub
et d’ajouter un workflow GitHub Actions pour automatiser l’exécution du script.

## 2. Description du programme
Le fichier `main.py` contient deux fonctions :
- `addition(a, b)` : retourne la somme de `a` et `b`.
- `multiplication(a, b)` : retourne le produit de `a` et `b`.

Dans la partie principale (`if __name__ == "__main__":`), on teste ces fonctions
avec `a = 5` et `b = 3` et on affiche les résultats dans le terminal.

## 3. Structure du projet
- `main.py` : code Python.
- `.github/workflows/python-ci.yml` : workflow GitHub Actions.
- `captures/` : captures d’écran.
- `rapport/rapport_TP2.md` : ce rapport.
- `README.md` : présentation du projet.

## 4. Workflow GitHub Actions
Le workflow se déclenche à chaque `push` sur la branche `main` :
1. Récupération du code.
2. Installation de Python 3.10.
3. Exécution de `python main.py`.

Cela permet de vérifier automatiquement que le programme fonctionne après chaque modification.

## 5. Conclusion
Le TP respecte les consignes : projet fonctionnel, dépôt GitHub, workflow actif,
rapport et captures d’écran.
