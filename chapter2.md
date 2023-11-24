# Chapitre 2 : Les Bases de Python

## 2.1 Types de Données de Base

En Python, il existe plusieurs types de données de base que vous utiliserez fréquemment. Les connaître est essentiel pour écrire des programmes efficaces.

### 2.1.1 Entiers (int)
Les entiers sont des nombres sans partie décimale. Ils peuvent être positifs ou négatifs.

Exemple :
```python
a = 10
b = -5
```

### 2.1.2 Nombres Flottants (float)
Les nombres flottants, ou "floats", sont des nombres réels qui contiennent une partie décimale.

Exemple :
```python
pi = 3.14
temperature = -20.5
```

### 2.1.3 Chaînes de Caractères (str)
Les chaînes de caractères, ou "strings", sont des séquences de caractères utilisées pour stocker du texte.

Exemple :
```python
nom = "Alice"
message = "Bonjour le monde !"
```

### 2.1.4 Booléens (bool)
Les booléens représentent l'une des deux valeurs : `True` ou `False`. Ils sont souvent utilisés pour les conditions et les boucles.

Exemple :
```python
estVrai = True
estFaux = False
```

## 2.2 Opérations de Base

### 2.2.1 Opérations Arithmétiques
Python prend en charge toutes les opérations arithmétiques de base.

- **Addition** (`+`)
- **Soustraction** (`-`)
- **Multiplication** (`*`)
- **Division** (`/`)
- **Modulo** (`%`) : Donne le reste d'une division
- **Puissance** (`**`)

Exemple :
```python
# Addition
somme = 7 + 3  # Résultat: 10

# Soustraction
difference = 7 - 3  # Résultat: 4

# Multiplication
produit = 7 * 3  # Résultat: 21

# Division
quotient = 7 / 3  # Résultat: 2.3333

# Modulo
reste = 7 % 3  # Résultat: 1

# Puissance
puissance = 7 ** 3  # Résultat: 343
```

### 2.2.2 Opérations sur les Chaînes de Caractères
Les chaînes de caractères peuvent être concaténées (ajoutées), multipliées, etc.

Exemple :
```python
# Concaténation
salutation = "Bonjour " + "le monde"  # Résultat: "Bonjour le monde"

# Multiplication
rire = "ha" * 3  # Résultat: "hahaha"
```

### 2.2.3 Conversion de Types
Vous pouvez convertir entre différents types en Python.

Exemple :
```python
nombreEntier = int("10")  # Convertit la chaîne de caractères "10" en entier
nombreFlottant = float("10.5")  # Convertit la chaîne "10.5" en flottant
texte = str(10)  # Convertit l'entier 10 en chaîne de caractères
```

## 2.3 Exercices Pratiques

### Exercice 1 : Calcul Simple
Écrivez un programme qui calcule la somme de 15 et 30, puis imprime le résultat.

### Exercice 2 : Manipulation de Chaînes
Créez deux variables contenant des chaînes de caractères et concaténez-les pour former une phrase.

### Exercice 3 : Conversion de Type
Demandez à l'utilisateur d'entrer un nombre, convertissez-le en un entier, puis doublez-le et affichez le résultat.

**Corrections**