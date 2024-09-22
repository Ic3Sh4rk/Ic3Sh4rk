Introduction
============

Le language Python suit une convention pour normaliser la lisibilitée et la syntaxe dont les nom de variables, la Python Enhancement Proposals (PEP) qui est constitué d'article actif, annulé, supprimer ou en attente comme des textes de loi.

Les tutoriels sur Youtube sont en générale bien fait, personnelement j'ai suivis la chaine Graven.

1. ## Variable

+ ### Formation des variables

Le premier caractère d'une variable soit absolument être une lettre ou d'un \"\_\" mais par convention les noms de variable doivent être en minuscule, si la variable contient plusieur \"mot\" ceci peuvent être séparer d'un \"\_\".

On peut aussi définir ce qu'est senser contenir la variable à l'aide des \"\:\" \+ int ou float ou str ou list ou dict ou tuple. Cette notation est strictement indicatif, elle ne sert qu'à la compréhension du programme, on peux très bien écrire : 

```Python
shopping_list: int = ['patates', 'courgette']
```

Et la variable `shopping_list` sera une liste.


### Variables Bruts
#### Entiers (int())

Existe aussi sur Excel en VBA sous le même nom : \"Integer\"

```Python
	tour: int = 0
```
##### Divisions Euclidiennes
```Python
	bread: int = 5
	client: int = 2
>>> bread//client # division Euclidienne
2
>>> bread%client # Reste de la division Euclidienne
1
```

#### Nombre à virgule (float())

Existe aussi sur Excel en VBA sous le même nom : \"float\"

#### Chaîne de caractère (str())

Existe aussi sur Excel en VBA sous le même nom : \"Strings\"

```Python
	message: str
```
### Variables Composées
#### Liste (list())

#### Tuples (tuple())

#### Dictionnaires (dict())
``` Python
	data: dict = {"Animals": "Cow", "Number": 5}

	data
```

### Conclusion

Parmis les 6 types de variable seul les `list()` et les `tuple()` sont des variable itérable puis qu'ils peuvent contenir plusieur c'est a dire que l'on peut appelere

2. ## Fonctions
``` Python
>>>	list(data.keys())
["Animals", "Number"]

>>> tuple(data.keys())
("Animals", "Number" )

>>> print("hello World")
Hello World
```

3. ## Boucle for

```Python
	for i in range(1,5,2):
		print(i)
```
`1
3`

3. ## Autres fonction (Built-in Function)

### Fonction sur des Itérable

###### all()
```Python
	test = [True, True, True, True] # test peut être tout type de variable itérable
	test2 = [True, False, True, True]
	all(test) # >>> True
	all(test2) # >>> False
```

###### any()
```Python
	test = [False, False, True, False] # test peut être tout type de variable itérable
	test2 = [False, False, False, False]
	any(test) # >>> True
	any(test2) # >>> False
```

###### chr()
```Python
	i = 97 # i peut être tout entier entre 0 et 1,114,111 (0x10FFFF en base 16)
	chr(i)# >>> "a"
```

###### id()

retourne un entier à partir de n'import quel objet 

###### méthode de classe \[@classmethod\]
```Python
	
```
4. ### Modules Utiles

#### Les interfaces

###### Tkinter

###### PyQt

#### Avancées

###### os
Ce module ne fait pas que ça mais c'est la partie interessante
Pour récupérer les dimentions en caractère de la console ou s'éxecute un scripte
```Python
	import os
	console_size = os.get_terminal_size()

	# ou pour avoir seulement la hauteur ou seulement la largeur 
	console_size_height = os.get_terminal_size().lines
	console_size_width = os.get_terminal_size().columns
```
###### Threading
Pour lancer plusieur programmes parallèlement :
```Python
	import threading
	import time

	def main():
		print(1)
		sleep(2)
		print(3)

	def main2():
		sleep(1)
		print(2)
		sleep(2)
		print(4)

	thread1 = threading.Thread(target=main)
	thread2 = threading.Thread(target=main2)

	thread1.start()
	thread2.start()

1
2
3
4
```

5. ### Autres
###### Docsrting
Les docstrings sont des documentation commenter dirrectement dans python
Elles se présentes comme tel :
```Python
	def hello(x: int=1):
		u"""affiche hello * x"""
		print("hello"*x)
```

###### Vocabulaire

objet.attribut
``` Python
	class Objet():
		"""docstring for Objet"""
		def __init__(self, price):
			self.price = price
	
	Objet.price = 0
	print(Objet.price)
```

###### Import de module
```Console
	py -m pip install %module%
```

######
```Console
	cd /D %dirrectory%
```
