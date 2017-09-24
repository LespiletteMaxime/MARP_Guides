<!-- $theme: gaia -->
<!-- $width: 1600 -->
<!-- $size: a4 -landscape -->


# MARP Guide de syntaxe


Guide de syntaxe pour [MARP](https://yhatt.github.io/marp/).


### Au sommaire :
- Nouvelle diapositive
- Les titres
- Attributs du texte
- Des couleurs en HTML
- Les listes
- Le tableau


## Délimiter une nouvelle diapositive

Pour insérer une nouvelle diapositive, insérer 3 tirets  en passant une ligne avant et après :

```

---

```


## Les titres existent en 6 tailles

# Taille 1
## Taille 2
### Taille 3
#### Taille 4
##### Taille 5
###### Taille 6


Grâce à une suite de dièses suivis par un espace :

```
# Taille 1
## Taille 2
### Taille 3
#### Taille 4
##### Taille 5
###### Taille 6
```


## Les attributs du texte:

- Texte *en italique*
- Texte **en gras**
- Texte ***en gras et en italique***
- Texte avec ==**fond en évidence**==
- Texte avec `un arrière-plan` gris 


> Une citation d'un grand auteur



Séquences à appliquer :

```
Texte *en italique*
Texte **en gras**
Texte ***en gras et en italique***
Texte avec ==**fond en évidence**==
Texte avec `un arrière-plan` gris 
> Une citation d'un grand auteur
```


## De la couleur 

On peut aussi ajouter de la <span style="color:blue">couleur !</span> avec du code HTML :

```

... de la <span style="color:blue">couleur !</span> avec du code HTML :

```

- Une balise d'ouverture entre crochets ```<span style="color:blue">```
- La couleur est inscrite en anglais ou en hexadécimal [Liste des couleurs et des codes](http://www.commentcamarche.net/contents/490-codes-couleur-html)
- Une balise de fermeture entre crochets ```</span>```


Exemple avec du code hexadécimal :

```
Texte <span style="color:#FF358B">rose</span> !
```

Texte <span style="color:#FF358B">rose</span> !

## Des Emoji

On peut ajouter des **emoji** comme un :smile:

Ou encore :
 :paperclip:   :fr:  :heavy_check_mark:


```
 :paperclip: 
 :fr:
 :heavy_check_mark:
```

Liste des codes emoji : https://www.webpagefx.com/tools/emoji-cheat-sheet/



## Les listes :

### Une liste non numérotée :
- banane
	- verte
	- plantain 
- pomme
- poire



### Une liste numérotée : 
1. banane
2. pomme
3. poirel


Séquences à appliquer, sans oublier l'espace :

```
Une liste non numérotée :
- banane
	- verte
	- plantain 
- pomme
- poire 	

Une liste numérotée : 
1. banane
2. pomme
3. poire
```


## Présenter un tableau

|| Lille |Arras|Amiens|
|-:|:-:|:-:|:-:|
|Anglais|Oui|Oui|Oui|
|Chinois|Non|Oui|Non|
|Allemand|Oui|Oui|Oui|
|Russe|Non|Non|Oui|

---
La première ligne est l'en-tête du tableau
Les cellules sont séparées par un trait | Alt Gr-6
La seconde ligne précise l'alignement
:- à gauche
:-: centré
-: à droite

```
|| Lille |Arras|Amiens|
|-:|:-:|:-:|:-:|
|Anglais|Oui|Oui|Oui|
|Chinois|Non|Oui|Non|
|Allemand|Oui|Oui|Oui|
|Russe|Non|Non|Oui|
```



