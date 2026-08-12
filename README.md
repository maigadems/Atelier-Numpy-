# Atelier-numpy

Atelier pas à pas de prise en main de NumPy, dans un contexte IoT : une entreprise
dispose de capteurs (température, humidité, pression, consommation) répartis dans
plusieurs bâtiments. L'objectif est de préparer et d'analyser ces données avant de
les transmettre à un futur système de Machine Learning de détection d'anomalies.

## Livrable

Le notebook [`atelier_numpy_iot.ipynb`](./atelier_numpy_iot.ipynb) contient l'ensemble
des exercices, résolus et exécutés.

## Progression

- [x] Partie 1 — Listes Python vs tableaux NumPy
- [x] Partie 2 — Création des données
- [x] Partie 3 — Exploration des tableaux
- [ ] Partie 4 — Indexation et slicing
- [ ] Partie 5 — Filtrage booléen
- [ ] Partie 6 — Manipulation des dimensions
- [ ] Partie 7 — Concaténation
- [ ] Partie 8 — Calcul scientifique
- [ ] Partie 9 — Broadcasting
- [ ] Partie 10 — Bonus

## Installation

```bash
python3 -m venv .venv
source .venv/bin/activate   # sous Windows : .venv\Scripts\activate
pip install -r requirements.txt
```

## Exécution

```bash
jupyter notebook atelier_numpy_iot.ipynb
```
