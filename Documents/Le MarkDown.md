MarkDown
========
Titres
------

La documentation de GitHub du Markdown est disponible sur [cette page](https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# Titre 1
## Titre 2
### Titre 3
#### Titre 4
##### Titre 5
###### Titre 6
Titre alt 1
===========
Titre alt 2
-----------

Paragraphes et leur style
-------------------------

**paragraphe** quelconque

__2e paragraphe__ *quel*conque

Python _est_ le meilleur langage du monde de l'informatique

\* : *Italique*
\*\* : **Gras**
\*\*\* : ***Gras et Italique***

Les tiret du bas ne pevent pas être misent entre d'autres charactère contrairement aux étoiles


~~Un texte barré~~

avec un emoji c'est plus cool :joy:

Et un élément chimique H~2~O c'est deux fois plus cool

Les indices sur github c'est en mettant la balise HTML `<sub>` H<sub>2</sub>O

Ps: les balise HTML c'est ce qu'il y a entre les chevron \<\>, la majoritée des balises s'ouvre et se ferme, celles qui fermes commence par \<\\

Et avec un exposant x^9^ c'est, ouais bref j'arrête

Les exposants sur github c'est en mettant la balise HTML `<sup>` x<sup>9</sup>


Citations
---------

> voici une citation

> Et là
>
> Une grande citation
>> ET dessous une citation imbriquer

Listes
------

et une liste :
1. le numéro
2. avant le
3. point 
1. n'as aucune
	1. valeur

+ différent point  
+ pour une liste

* qui n'est
* pas ordonnée

- Attention
	- À ne pas les mélanger

- [x] Une liste
- [ ] de 
- [x] tâche

Codes
-----

```Python
for i in range(len(a)):
	print(i)
```
```HTML
<html>
 	<head>
  		<title>MarkDown</title>
 	</head>
</html>
```

Tableau
-------
|   Syntax    | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

| Right Align | Left Align | Center Align |
| -----------:|:---------- |:------------:|
| 1           | 1          |      1       |
| 11 | 11         |      11      |
|         111 | 111        |     111      |
|        1111 | 1111       |     1111     |

mettres les espaces ne change rien mais c'est plus lisible

Images
------

	![Mazda logo](E:/Banque d'image/Mazda_logo_icon.png)
> Une simple image

	[![SublimText logo]("\Image Illustratives\sublimetext.png")](https://www.https://www.sublimetext.com/)
> Une image qui mène vers le site officiel de Sublime text (c'est sensé marcher mais ça marche pas sur github ou j'ai fais une erreur)

pour afficher les charactère suivant il faut mettre \\ devant :
```
\ ` * _ {} [] <> () # + - . ! |
```


Liens
-----

et ça cest un lien
[mot afficher](le_lien_n'import "le texte afficher en survolant le lien")
<louis.pouvreau@gmail.com> et ça c'est pareil en plus rapide

[SLM][SLM]

le lien est plus loins dans le fichier pour rendre le texte plus lisible
(engénérale à la fin du fichier)

Notes de pages
--------------

Cela mène vers le lien en fin de fichier

Divers
------

---
c'est une ligne !

**Attention** entre chaque paragraphe sauter une ligne sinon ça se met sur la même ligne

Il est aussi possible d'utiliser des balise **HTML** dans les fichier **Markdown** SI ET SEULENTMENT SI votre application **Markdown** vous le permet

[^1]: le lien est en dessous
[SLM]: https://fr.wikipedia.org/wiki/Fusion_s%C3%A9lective_par_laser
