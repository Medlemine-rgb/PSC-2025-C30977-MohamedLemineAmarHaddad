# Semaine 1 : Résumé personnel — Chapitres 1 à 3

## Chapitre 1 : Getting Started

Ce chapitre introduit les fondamentaux de Python dans le contexte du calcul scientifique. Il couvre :

- **Installation recommandée** : utilisation d’Anaconda, Spyder comme IDE, et IPython pour une interaction fluide.
- **Structure de base d’un programme Python** : instructions, blocs conditionnels, boucles (`for`, `while`), et définitions de fonctions.
- **Types de données fondamentaux** : entiers, flottants, chaînes de caractères, listes.
- **Utilisation des scripts et modules** : différence entre `run`, `exec`, `import`, `from ... import`.
- **Notions clés** : indentation, commentaires `#`, continuation de ligne `\`, interpréteur Python et Jupyter Notebooks.

### Maîtrisé :
- Utilisation de Spyder, IPython et Anaconda.
- Syntaxe de base : variables, boucles, conditions, fonctions.

### À approfondir :
- Modules et espaces de noms (`namespace`).
- Utilisation avancée de Jupyter (slides, web pages).
- Les options d’aide dans IPython (`%magic`, `?`, etc.).

---

##  Chapitre 2 : Variables and Basic Types

Ce chapitre se concentre sur les types fondamentaux de données en Python :

###  Types numériques :
- **int** : nombres entiers.
- **float** : nombres à virgule flottante, représentés en double précision.
- **complex** : nombres complexes (ex. `3 + 4j`).

###  Types booléens :
- Opérateurs logiques : `and`, `or`, `not`.
- Comparateurs : `==`, `!=`, `<`, `<=`, `>`, `>=`.

### Chaînes de caractères :
- Déclaration : `'...'`, `"..."`, `'''...'''`.
- Méthodes courantes : `len()`, `.format()`, concaténation, slicing.

###  Détails intéressants :
- `inf`, `nan`, et comportement en cas de débordement ou division indéfinie.
- `float32`, `float64`, `sys.float_info.epsilon` pour machine epsilon.

###  Maîtrisé :
- Manipulation de `float`, `int`, `bool`, `str`.
- Opérations mathématiques de base.

###  À approfondir :
- Comparaison sécurisée de floats (`isclose()`, `finfo()`).
- Comportement de `nan` et `inf`.
- NumPy `float32` vs `float64`.

##  Chapitre 3 : Container Types

Ce chapitre présente les structures de données fondamentales :

###  Listes (`list`)
- Indexation, slicing, compréhension de liste (`[x**2 for x in range(5)]`), méthodes (`append`, `extend`, `zip`).

###  Tuples (`tuple`)
- Immuables, utiles pour le packing/unpacking.

### Dictionnaires (`dict`)
- Paires clé/valeur, boucle `for k, v in d.items()`.

###  Ensembles (`set`)
- Unicité des éléments, opérations d’union/intersection.

###  Conversion et typage :
- `type(obj)`, `isinstance()`, conversions entre types (`list()`, `tuple()`, `dict()`...).

###  Maîtrisé :
- Listes, dictionnaires, tuples.
- Compréhension de liste.
- Boucle `for` et `zip`.

###  À approfondir :
- Ensembles (`set`) et leurs applications.
- Distinguer clairement `list`, `tuple`, `dict` selon leur usage.
- Techniques avancées de `dict` (e.g., `defaultdict`, `Counter`).

---

## Fichiers Python produits durant les exercices

Les fichiers `.py` générés incluent :

- `calcul_fonction.py` : fonctions `f(x)`, `g(x)`, `h(x)`.
- `smartscript.py` : exemple d’utilisation d’une fonction dans un script.
- `types_demo.py` : affichage des types `float`, `complex`, `bool`.
- `containers_demo.py` : manipulation de listes, dictionnaires et tuples.

---

## Réflexion personnelle

La progression dans ces trois chapitres permet de consolider une base solide en Python, en particulier pour les applications scientifiques. Je me sens à l’aise avec la syntaxe générale et les structures de contrôle. Il me faut cependant travailler davantage sur :
- la manipulation correcte des floats (comparaison, précision),
- les structures de données avancées (`set`, `dict` imbriqués),
- l’usage optimal des modules et de l’espace de noms Python.
