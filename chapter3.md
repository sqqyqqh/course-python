# Chapitre 3 : Structures de Contrôle en Python

## 3.1 Instructions Conditionnelles

Les instructions conditionnelles permettent à votre programme de prendre des décisions en fonction de certaines conditions.

### 3.1.1 Instruction `if`
L'instruction `if` est utilisée pour exécuter un bloc de code si une condition spécifiée est vraie.

Exemple :
```python
age = 20
if age >= 18:
    print("Vous êtes majeur.")
```

### 3.1.2 Instruction `else`
L'instruction `else` est utilisée en combinaison avec `if` pour exécuter un bloc de code si la condition `if` n'est pas vraie.

Exemple :
```python
age = 16
if age >= 18:
    print("Vous êtes majeur.")
else:
    print("Vous êtes mineur.")
```

### 3.1.3 Instruction `elif`
L'instruction `elif` (abréviation de "else if") est utilisée pour vérifier plusieurs conditions, une après l'autre.

Exemple :
```python
age = 65
if age < 18:
    print("Vous êtes mineur.")
elif age < 65:
    print("Vous êtes adulte.")
else:
    print("Vous êtes senior.")
```

## 3.2 Boucles

Les boucles permettent de répéter un bloc de code plusieurs fois.

### 3.2.1 Boucle `for`
La boucle `for` est utilisée pour itérer sur une séquence (comme une liste, un tuple, un dictionnaire, un ensemble, ou une chaîne).

Exemple :
```python
for i in range(5):
    print(i)
```

### 3.2.2 Boucle `while`
La boucle `while` permet d'exécuter un ensemble d'instructions aussi longtemps qu'une condition est vraie.

Exemple :
```python
i = 0
while i < 5:
    print(i)
    i += 1
```

## 3.3 Exercices Pratiques

### Exercice 1 : Choix Multiple
Demandez à l'utilisateur de saisir son âge, puis utilisez les instructions `if`, `elif`, et `else` pour afficher s'il est mineur, adulte, ou senior.

### Exercice 2 : Comptage
Utilisez une boucle `for` pour imprimer les nombres de 1 à 10.

### Exercice 3 : Deviner un Nombre
Créez un programme où l'utilisateur doit deviner un nombre secret. Utilisez une boucle `while` et des instructions conditionnelles.

**Corrections**
