<!-- $theme: gaia -->
<!-- $width: 1600 -->
<!-- $size: a4 -landscape -->


# MARP Guide de syntaxe


Guide de syntaxe pour [MARP](https://yhatt.github.io/marp/).

<!-- footer: MARP guide de syntaxe Version 1.1 -->

---
### Au sommaire :
- Nouvelle diapositive
- Les titres
- Attributs du texte
- Des couleurs en HTML
- Les listes
- Le tableau

---



Pour insérer une nouvelle diapositive, ajouter 3 tirets au début de la diapositive en passant une ligne avant et après :

```

---

```

<!--Commentaire 
3 quotes inversés Alt Gr-7 délimitent un cadre dans lequel les codes de formatage ne sont pas interprétés 
-->

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

 ##### On peut aussi ajouter de la <span style="color:blue">couleur !</span> avec du HTML :

```
# De la <span style="color:blue">couleur !</span>
```

Couleur en anglais ou en hexadécimal [Liste des couleurs](http://www.commentcamarche.net/contents/490-codes-couleur-html)


```
Texte <span style="color:#FF358B">rose</span> !
```

Texte <span style="color:#FF358B">rose</span> !

---

On peut ajouter des **emoji** comme un :smile:

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

### Une liste non numérotée :
- banane
	- verte
	- plantain 
- pomme
- poire

---

### Une liste numérotée : 
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



