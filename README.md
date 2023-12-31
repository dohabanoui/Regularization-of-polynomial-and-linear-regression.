# Multi-Polynomial Regression

## Table of Contents
1. [Le modèle](#le-modèle)
2. [Les erreurs du modèle](#les-erreurs-du-modèle)
3. [Gradient](#gradient)
4. [Évaluation du modèle](#évaluation-du-modèle)
5. [Analyse du dataset](#analyse-du-dataset)
6. [Split des données](#split-des-données)
7. [La normalisation du dataset](#la-normalisation-du-dataset)
8. [Pour le cas de la régression linéaire](#pour-le-cas-de-la-régression-linéaire)
9. [Pour la régression polynomiale multivariée](#pour-la-régression-polynomiale-multivariée)
10. [Conclusion](#conclusion)

## Le modèle
- **Création de la matrice X**
  - [x_train](#) et [x_test](#)
- **Création d'un vecteur paramètre θ**
  - Initialisation avec des coefficients aléatoires
- **Fonction coût : Erreur Quadratique Moyenne**
  - [Cost Function](#)
- **Phase d'entraînement**
  - [Descente de gradient](#) avec et sans régularisation
- **Vecteur de prédiction**
  - [Predictions](#)

## Les erreurs du modèle
- Erreurs quadratiques moyennes pour différentes régularisations

## Gradient
- [Courbes d'apprentissage](#)

## Évaluation du modèle
- Coefficient de détermination
  - [Performances](#)
