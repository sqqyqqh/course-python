# Chapitre 4 : Structures de Données en Python

## 4.1 Listes

Les listes en Python sont des séquences ordonnées modifiables pouvant contenir des éléments de différents types.

### 4.1.1 Création et Accès aux Éléments
```python
maListe = [1, 2, 3, "Python", True]
premierElement = maListe[0]  # Accès au premier élément
```

### 4.1.2 Méthodes de Liste
- **Ajout** : `maListe.append(element)`
- **Suppression** : `maListe.remove(element)`
- **Tri** : `maListe.sort()`

## 4.2 Dictionnaires

Les dictionnaires stockent les données sous forme de paires clé-valeur. Ils sont rapides pour la recherche et la mise à jour.

### 4.2.1 Création et Accès aux Éléments
```python
monDictionnaire = {"nom": "Alice", "âge": 30}
nom = monDictionnaire["nom"]  # Accès à la valeur associée à la clé "nom"
```

### 4.2.2 Méthodes de Dictionnaire
- **Ajout/Modification** : `monDictionnaire["clé"] = valeur`
- **Suppression** : `del monDictionnaire["clé"]`
- **Obtenir les clés** : `monDictionnaire.keys()`

## 4.3 Tuples

Les tuples sont similaires aux listes, mais ils sont immuables (non modifiables). Ils sont souvent utilisés pour des données qui ne doivent pas changer.

### 4.3.1 Création et Accès
```python
monTuple = (1, 2, 3, "Python")
element = monTuple[2]  # Accès au troisième élément
```

## 4.4 Ensembles

Les ensembles sont des collections non ordonnées et sans doublons. Ils sont utiles pour les opérations mathématiques comme les unions et intersections.

### 4.4.1 Création et Opérations
```python
monEnsemble = {1, 2, 3, 4}
monEnsemble.add(5)  # Ajout d'un élément
```

## 4.5 Exercices Pratiques

### Exercice 1 : Manipulation de Listes
Créez une liste de nombres, ajoutez-y des éléments, puis triez-la.

### Exercice 2 : Gestion d'un Dictionnaire
Créez un dictionnaire représentant une personne, incluant des informations telles que le nom, l'âge, et l'adresse.

### Exercice 3 : Opérations sur les Ensembles
Définissez deux ensembles et effectuez des opérations comme l'union et l'intersection.

**Corrections**