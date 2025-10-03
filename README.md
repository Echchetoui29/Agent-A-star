# Agents de Navigation dans une Grille

Ce projet illustre la comparaison entre deux types d’agents dans un environnement en grille avec obstacle :  
- **Agent Stupide (Réactif)** : suit un comportement simple et linéaire sans réelle stratégie.  
- **Agent Intelligent (Optimal avec A\*)** : utilise l’algorithme A* avec mouvements diagonaux pour trouver le chemin le plus court vers l’objectif.

---

## ⚙️ Fonctionnalités
- Grille de taille configurable (`GRID_SIZE`)  
- Position de départ (`START_POS`), objectif (`GOAL_POS`) et obstacle (`OBSTACLE_POS`)  
- Implémentation d’un agent réactif (chemin naïf)  
- Implémentation d’un agent intelligent basé sur **A\*** avec diagonales et coût différencié (1 pour mouvement droit, √2 pour diagonale)  
- Visualisation et animation avec **Matplotlib**  

---

## 📂 Structure du code
1. **Configuration de l’environnement** : définition de la grille, du départ, de l’arrivée et des obstacles.  
2. **Agent Stupide (Réactif)** : suit un chemin direct tant qu’aucun obstacle ne bloque.  
3. **Agent Intelligent (A\*)** : calcule le chemin optimal en utilisant une heuristique de Manhattan.  
4. **Animation** : comparaison visuelle entre les deux agents.  

---

## 🚀 Utilisation
### Prérequis
- Python 3.x  
- Bibliothèques : `numpy`, `matplotlib`, `IPython`  

### Installation
```bash
pip install numpy matplotlib
