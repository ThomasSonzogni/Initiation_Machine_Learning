# 🤖 Initiation au Machine Learning

> Premiers pas en apprentissage automatique avec scikit-learn, sur un jeu de données de mensurations.

**Auteur :** Thomas Sonzogni · Data Analyst

---

## 📌 À propos

Ce dépôt regroupe mes premières manipulations de machine learning. L'objectif n'est pas de produire un modèle destiné à la production, mais de **maîtriser la chaîne complète** sur un cas volontairement simple et interprétable : charger des données, séparer entraînement et test, entraîner un modèle, évaluer sa performance et comprendre ce que le modèle a réellement appris.

Le jeu de données — âge, poids, taille et sexe — a l'avantage d'être immédiatement compréhensible : on sait intuitivement que la taille et le poids sont liés, ce qui permet de vérifier qu'un résultat de modèle a du sens plutôt que de faire confiance à un score aveuglément.

---

## 🗂️ Contenu

| Fichier | Rôle |
|---|---|
| `ML.ipynb` | Notebook principal — exploration, modélisation et évaluation |
| `age_vs_poids_vs_taille_vs_sexe.csv` | Jeu de données : 237 observations, 4 variables |

---

## 📊 Le jeu de données

| Variable | Type | Rôle possible |
|---|---|---|
| `age` | Quantitative | Variable explicative |
| `poids` | Quantitative | Variable explicative ou cible (régression) |
| `taille` | Quantitative | Variable explicative ou cible (régression) |
| `sexe` | Qualitative | Variable explicative ou cible (classification) |

Ce jeu se prête à deux exercices complémentaires :

- **Régression** — prédire le poids à partir de la taille et de l'âge (cible continue)
- **Classification** — prédire le sexe à partir des mensurations (cible catégorielle)

---

## 🔬 Démarche

<!-- 🔧 À COMPLÉTER : précise ici les modèles réellement entraînés dans ML.ipynb
     et les scores obtenus. Exemple de structure ci-dessous. -->

1. **Exploration** — statistiques descriptives, distributions, nuages de points et corrélations entre variables
2. **Préparation** — encodage de la variable qualitative, séparation en jeux d'entraînement et de test (`train_test_split`)
3. **Modélisation** — entraînement du ou des modèles retenus
4. **Évaluation** — mesure de la performance sur le jeu de test, jamais sur les données d'entraînement
5. **Interprétation** — lecture des coefficients ou de l'importance des variables, confrontation au bon sens

### Notions clés travaillées

| Notion | Pourquoi elle compte |
|---|---|
| **Séparation train / test** | Un modèle évalué sur ses propres données d'entraînement affiche toujours un score flatteur et trompeur |
| **Surapprentissage** | Un modèle trop ajusté mémorise le bruit au lieu d'apprendre la tendance |
| **Choix de la métrique** | RMSE ou R² en régression, accuracy ou matrice de confusion en classification — chacune raconte une chose différente |
| **Interprétabilité** | Comprendre *pourquoi* le modèle prédit est aussi important que la performance elle-même |

---

## 🚀 Utilisation

```bash
git clone https://github.com/ThomasSonzogni/Initiation_Machine_Learning.git
cd Initiation_Machine_Learning

pip install pandas numpy scikit-learn matplotlib seaborn jupyter

jupyter notebook ML.ipynb
```

---

## 🛠️ Stack technique

`Python` · `pandas` · `NumPy` · `scikit-learn` · `Matplotlib` · `Seaborn` · `Jupyter`

---

## 🎯 Compétences travaillées

- Chargement et exploration d'un jeu de données avec pandas
- Préparation des données pour un modèle (encodage, découpage train/test)
- Entraînement et évaluation d'un modèle supervisé avec scikit-learn
- Choix et lecture des métriques d'évaluation
- Interprétation d'un modèle et regard critique sur ses résultats

---

## 📬 Contact

**Thomas Sonzogni** — Data Analyst
📧 thomas.paul.sonzogni@gmail.com
🌐 [Site professionnel](https://thomassonzogni.github.io/thomas_sonzogni_github.io/index.html)
🐙 [GitHub](https://github.com/ThomasSonzogni)
