# Chapitre 6 : Programmation Orientée Objet en Python

## 6.1 Introduction à la POO

La programmation orientée objet est un paradigme de programmation qui utilise des "objets" pour modéliser des données et des comportements. Python est un langage qui supporte la POO, ce qui vous permet de créer des programmes complexes et bien organisés.

## 6.2 Classes et Objets

Les classes sont des modèles pour créer des objets, qui sont des instances de ces classes.

### 6.2.1 Définition d'une Classe
```python
class Voiture:
    def __init__(self, marque, modele):
        self.marque = marque
        self.modele = modele

    def afficher_description(self):
        print(f"Cette voiture est une {self.marque} {self.modele}.")
```

### 6.2.2 Création d'Objets
```python
ma_voiture = Voiture("Toyota", "Corolla")
ma_voiture.afficher_description()
```

## 6.3 Héritage

L'héritage permet à une classe de hériter des attributs et méthodes d'une autre classe.

### 6.3.1 Création d'une Classe Parent
```python
class Vehicule:
    def __init__(self, type_vehicule):
        self.type_vehicule = type_vehicule

    def afficher_type(self):
        print(f"Type de véhicule: {self.type_vehicule}")
```

### 6.3.2 Classe Enfant Héritant d'une Classe Parent
```python
class Voiture(Vehicule):
    def __init__(self, marque, modele):
        super().__init__("Voiture")
        self.marque = marque
        self.modele = modele
```

## 6.4 Polymorphisme

Le polymorphisme permet aux classes d'utiliser des méthodes communes de différentes manières.

### 6.4.1 Définition de Méthodes Polymorphiques
```python
class Chien:
    def parler(self):
        return "Wouf!"

class Chat:
    def parler(self):
        return "Miaou!"

def faire_parler(animal):
    print(animal.parler())

# Utilisation
faire_parler(Chien())
faire_parler(Chat())
```

## 6.5 Exercices Pratiques

### Exercice 1 : Création d'une Classe
Développez une classe `Livre` avec des attributs pour le titre et l'auteur, et une méthode pour afficher ces informations.

### Exercice 2 : Héritage
Créez une classe `VoitureElectrique` qui hérite de la classe `Voiture` et ajoutez-lui un attribut spécifique.

### Exercice 3 : Polymorphisme
Écrivez deux classes avec une méthode commune, mais des implémentations différentes, et démontrez le polymorphisme.

**Corrections**