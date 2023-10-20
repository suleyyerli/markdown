# Markdown

## Titres

- Un dièse # pour le titre principal du docment
- Deux dièses # pour les titres des chapitres
- Trois, quatre, cinq, six dièses pour les sous-titre

### Titre Niveau 3

#### Titre niveau 4

##### Titre niveau 5

###### Titre niveau 6

## Mise en forme de texte

- ` _italique_ ` : _italique_
- `**gras**` **gras**
- `**_gras italique_**` : **_gras italique_**
- `~~barée~~` : ~~barée~~

 Une ligne vide un saut de ligne permet de créer un nouveau paragraphe
Le paragraphe reste sur une seule ligne
Ajouter deux espaces `  ` en fin de ligne au milieu d'un paragraphe

Le symbole > permet d'inserer une citation.

> Markdown est une manière de formater du texte
> qui apparait correctement sur tous les apareils

## Listes

### Listes simples

Utiliser le trait d'union ( tiret du 6) pour une liste

- un point
- un point
- un point

### Liste numérotées

1. Un
2. Deux
3. Trois

### Case à cocher

[ ] A faire
[X] Fait

## Code

Un seul backstik en début et en fin d'expression à mettre en évidence : `code`. Deux backstick pour afficher un backstick au milieu : `` C'est tout le `code`. ``

Trois backstick avec le nom du langage pour mettre du code en forme:

```markdown
# Titre Markdown
```

## Liens

Vers un site web : [Wikipedia](https://fr.wikipedia.org/)

Avec un titre :  [Wikipedia](https://fr.wikipedia.org/ "wikipedia")

Lien interne : [Haut de page](#markdown) [Titre 6](#titre-niveau-6)

## Image

Pour insérer une image : `![texte alternatif décrivant l'image](image.png)`

![Markdown](markdown.png.png)

<div class="page">

### Note de bas de page

`[^1] Note 1 [^2] Note 2
beaucoup de texte
[^1] Réf. 1
[^2] Réf. 2

### Tableau

| Titre col 1 | Titre col 2 |
--------------|--------------
|L1 col 1     | L1 col 2    |
|L2 col 1     | L2 col 2    |

### Autres

Ligne horizontale : `---`

Saut de page passer par HTML :  `<div class="page">`

---
