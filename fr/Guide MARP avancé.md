<!-- $theme: gaia -->
<!-- $width: 1024 -->
<!-- $size: 16:9 -->

## Les directives

Directives globales : agissent sur la présentation complète

Directive locales : agissent sur la diapositive (ex numérotation)

---

# Le thème

Menu View/Thème ou insérer 
```
<!-- $theme: default -->
ou
<!-- $theme: gaia -->
```
Le thème Gaia est actif.

---

<!-- template: invert -->

# Inversion du thème

Cette directive permet d'afficher la diapositive courante en vidéo inverse : 


```
<!-- template: invert -->
```

---

## Préréglages des diapositives

Selon le ratio de l'écran : 16/9 ou 4/3
Ou une taille d'impression : a3, a4 ou a5 avec orientation possible en portrait

```
<!-- $size: a4 -portrait -->
```

Ce diaporama est en 16/9 paysage, en focntion du video porjecteur choisir 4/3

---

## Dimension des diapositives

Exprimée en pixel par défaut ou en `cm`, `mm`, `in`, `pt`, et `pc`.

```
<!-- $width: 1024 -->
<!-- $height: 768 -->
```
La dimension active est 1024 pixels x 768,
Autres choix : 1600x1200

---

## Pied de page

Cette directive ajoute un pied de page en bas de chaque diapositive :

```
<!-- footer: Marp Avancé -->
```

<!-- footer: Marp Avancé -->


---

## Numérotation des pages

La numérotation des pages commencent à partir de la page qui contient cette directive :
```
<!-- page_number: true -->
```

Il est donc logique de l'insérer à la première ou la seconde page du diaporama.

<!-- page_number: true -->

---

## Cette page est numérotée

---

#### Cela signifie qu'il est aussi possible de `désactiver` l'affichage de la numérotation grâce à la directive : 
```
<!-- page_number: false -->
```
<!-- page_number: false -->

---



