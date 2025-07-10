# 🧪 Travail Maison – Groupe 2  
## Article scientifique analysé : *Artificial Intelligence for Atmospheric Sciences – A Research Roadmap*  
📅 Publication : 19 juin 2025  
🔗 Lien : [https://arxiv.org/abs/2506.16281](https://arxiv.org/abs/2506.16281)

---

## 🔍 1. Problématique

Les sciences atmosphériques (météorologie, climatologie) produisent d’immenses volumes de données complexes, issues de modèles physiques, de capteurs et de satellites.  
Cependant, ces données sont encore sous-exploitées à cause de limitations :

- Capacité de calcul insuffisante
- Difficulté à extraire des motifs non linéaires
- Incapacité à adapter les modèles rapidement aux nouvelles conditions climatiques

❗ **Problème clé** : Comment intégrer efficacement les techniques d'intelligence artificielle (IA) pour exploiter ces données, tout en conservant la rigueur scientifique des modèles physiques ?

---

## ⚙️ 2. Approche proposée

L’article propose une feuille de route en quatre volets :

1. **Hybrider l'IA et les modèles physiques** : combiner l’apprentissage automatique avec les équations de la physique pour obtenir des modèles robustes, précis et interprétables.
2. **Créer des benchmarks de données** : jeux de données standardisés, ouverts et traçables pour entraîner et tester les modèles IA.
3. **Renforcer la collaboration interdisciplinaire** : mettre en relation climatologues, data scientists, experts IA.
4. **Automatiser l’évaluation et la validation** : outils pour estimer la confiance, l’incertitude et la robustesse des modèles IA.

---

## 🛠️ 3. Technologies utilisées

- **Apprentissage profond** : réseaux de neurones convolutifs (CNN), modèles récurrents (RNN), Transformers.
- **Calcul parallèle et distribué** : HPC, traitement cloud, GPU, edge computing.
- **Frameworks IA** : PyTorch, TensorFlow, Scikit-learn.
- **Open science** : dépôt GitHub, documentation ouverte, jeux de données publics.

---

## 🔭 4. Perspectives de recherche

- Développement de **modèles auto-adaptatifs**, capables d'apprendre de nouvelles dynamiques sans reformation complète.
- Intégration de **capteurs en temps réel** avec des pipelines IA robustes.
- Accent sur l’**explicabilité** : comprendre pourquoi un modèle IA prédit un événement météorologique extrême.
- Adoption de **langages adaptés au calcul scientifique** de nouvelle génération (Mojo, Julia...).

---

## ⚖️ 5. Étude comparative : Python vs Mojo vs Julia

| Critère                    | Python                        | Mojo                             | Julia                           |
|----------------------------|-------------------------------|-----------------------------------|----------------------------------|
| 📜 Origine                 | 1991, généraliste             | 2023, pour IA/accélération        | 2012, scientifique               |
| 🚀 Performance             | Moyenne (interprété)          | Excellente (proche du C++)        | Très bonne (compilé JIT)        |
| 🧠 IA & ML Support         | Excellent (PyTorch, TF, etc.) | Très bon (Langage IA natif)       | Bon (Flux.jl, MLJ.jl)           |
| 🧪 Calcul scientifique      | Très bon (NumPy, SciPy)       | En cours d’évolution              | Excellente (packages intégrés)  |
| ⚙️ Compilation             | Interprété (mais Cython dispo)| Compilé statiquement              | Compilation JIT (LLVM)          |
| 🌍 Écosystème              | Mature, massif                | En développement                  | En croissance rapide            |
| 👨‍💻 Facilité d’apprentissage | Très facile                   | Moyen à difficile (encore instable)| Facile pour scientifique        |

### ✅ Conclusion :
- **Python** : langage universel, très accessible, idéal pour débuter.
- **Mojo** : très prometteur pour l’IA embarquée/accélérée, mais encore jeune.
- **Julia** : excellent compromis entre performance et expressivité pour les chercheurs.

---

## 🗂️ Fichier original : `AI_atmo_homework.md`
