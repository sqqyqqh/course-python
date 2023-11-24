# Chapitre 5 : Fonctions en Python

## 5.1 Introduction aux Fonctions

Les fonctions sont des blocs de code qui sont conçus pour effectuer une tâche spécifique et peuvent être réutilisées dans votre programme.

### 5.1.1 Définition et Appel de Fonctions

Pour définir une fonction, utilisez le mot-clé `def` suivi du nom de la fonction et des parenthèses.

Exemple :
```python
def saluer():
    print("Bonjour tout le monde!")
```

Pour appeler une fonction, utilisez son nom suivi de parenthèses.

Exemple :
```python
saluer()  # Affichera "Bonjour tout le monde!"
```

### 5.1.2 Paramètres et Arguments

Les fonctions peuvent prendre des paramètres, qui sont des variables passées à la fonction.

Exemple :
```python
def saluer_par_nom(nom):
    print("Bonjour, " + nom)

saluer_par_nom("Alice")  # Affichera "Bonjour, Alice"
```

### 5.1.3 Valeurs de Retour

Les fonctions peuvent retourner une valeur à l'aide de l'instruction `return`.

Exemple :
```python
def additionner(a, b):
    return a + b

resultat = additionner(5, 3)  # resultat vaut 8
```

## 5.2 Portée des Variables

La portée d'une variable détermine où elle peut être utilisée dans votre code. Les variables définies à l'intérieur d'une fonction ne sont accessibles que dans cette fonction, sauf si elles sont retournées.

### 5.2.1 Variables Locales

Les variables créées à l'intérieur d'une fonction sont appelées variables locales.

Exemple :
```python
def ma_fonction():
    variable_locale = "Je suis locale"
    print(variable_locale)

ma_fonction()
```

### 5.2.2 Variables Globales

Les variables définies en dehors de toutes les fonctions sont appelées variables globales.

Exemple :
```python
variable_globale = "Je suis globale"

def ma_fonction():
    print(variable_globale)

ma_fonction()
```

## 5.3 Exercices Pratiques

### Exercice 1 : Création de Fonction
Écrivez une fonction qui prend deux nombres en paramètre et retourne leur produit.

### Exercice 2 : Fonction avec Valeurs de Retour
Développez une fonction qui calcule la moyenne de trois nombres et retourne le résultat.

### Exercice 3 : Utilisation des Variables Globales et Locales
Créez un exemple montrant la différence entre une variable locale et une variable globale.

**Corrections**