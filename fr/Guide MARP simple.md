<!-- $theme: gaia -->
<!-- $width: 1024 -->
<!-- $size: 16:9 -->


MARP Guide rapide
---


Pour insérer une nouvelle diapositive, ajouter 3 tirets au début de la page en passant une ligne avant et après :

```

---

```

<!--Commentaire 3 quotes inversés Alt Gr-7 délimitent un cadre dans lequel les codes de formatage ne sont pas interprétés -->

---

Les titres existent en 6 tailles :

# Taille 1
## Taille 2
### Taille 3
#### Taille 4
##### Taille 5
###### Taille 6

---

Ils s'effectuent avec des dièses suivis par un espace :

```
# Taille 1
## Taille 2
### Taille 3
#### Taille 4
##### Taille 5
###### Taille 6
```

---

## Attributs du texte:

Texte *en italique*
Texte **en gras**
Texte ***en gras et en italique***
Texte avec ==**fond en évidence**==
Texte avec `un arrière-plan` gris 
> Une citation d'un grand auteur


---

Séquences à appliquer :

```
Texte *en italique*
Texte **en gras**
Texte ***en gras et en italique***
Texte avec ==**fond en évidence**==
Texte avec `un arrière-plan` gris 
> Une citation d'un grand auteur
```
---

# On peut aussi ajouter de la <span style="color:blue">couleur !</span>

---

C'est un peu plus compliqué...

On encadre le texte avec les balises HTML suivantes :

```
# De la <span style="color:blue">couleur !</span>
```

Modifier **blue** par la couleur exprimée en anglais ou par un équivalent en hexadécimal (http://www.code-couleur.com/)

Texte <span style="color:#FF358B">rose</span> !

```
Texte <span style="color:#FF358B">rose</span> !
```

---

On peut ajouter des emoji comme un :smile:

Ou encore :
 :paperclip:   :fr:  :heavy_check_mark:


```
 :paperclip: 
 :fr:
 :heavy_check_mark:
```

Liste des codes emoji : https://www.webpagefx.com/tools/emoji-cheat-sheet/

--- 

## Les listes :

Une liste non numérotée :
- banane
	- verte
	- plantain 
- pomme
- poire

Une liste numérotée : 
1. banane
2. pomme
3. poirel

---

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
---

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
La seconde ligne précise précise l'alignement
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

---

## Lien vers un site ou une page

:white_check_mark: Copier et coller le lien directement dans l'éditeur:

https://images.google.fr/

:white_check_mark: Lien sur un mot, exemple :

Rendez-vous sur [Google Images](https://images.google.fr/) pour effectuer la recherche.

---

La syntaxe est très simple :
- entre crochets le texte du lien 
- entre parenthèses le lien complet

```
Rendez-vous sur [Google Images](https://images.google.fr/)
pour effectuer la recherche.
```

---

### Insérer une image

Tout d'abord, il faut stocker l'image dans le même dossier que celui du fichier Marp ou dans un sous-dossier, comme par exemple *images/*. 

![40% center](images/Plan-Campus-Arras-2017.jpg)

---

## La syntaxe est presque identique aux liens :

```
![40% center](images/Plan-Campus-Arras-2017.jpg)
```

On ajoute un ! devant
Paramètres optionnels : 
:arrow_right: 40% taille de l'image (150% pour agrandir de moitié)
:arrow_right: center ou rien pour à gauche

---

# Papier peint

![bg](images/paper.jpg)

---

# Cette instruction doit être ajoutée à toutes les pages

![bg](images/paper.jpg)

bg pour BackGround


```
![bg](images/paper.jpg)
```

Paramètres optionnels : 
50% :arrow_right:  de la taille originale du fichier
original :arrow_right: pas d'adaptation à l'écran

```
![bg 50%](images/paper.jpg)
![bg original](images/paper.jpg)
```
