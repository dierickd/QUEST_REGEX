# REGEX

#### 1. Trouve l'expression régulière qui cherche la seule occurrence du deuxième prénom de Néo (soit le A. de "Thomas A. Anderson). 
> Hint : cherches vite Néo avant qu'il ne s'échappe...

``` php
([A]\.)
```

#### Trouve l'expression régulière qui cherche la date contenue dans le document.
> Hint: il ne s'agit pas juste de chercher le texte 31/03/1999, mais de chercher deux chiffres et un slash, suivi de deux chiffres et d'un slash, suivi de quatre chiffres.

``` php
([0-2][0-9]|[3][0-1])(\/)([0][1-9]|[1][1-2])(\/)[0-9]{4}
```

#### Trouve l'expression qui cherche la note contenue dans le texte, sans pour autant sélectionner une partie de la date (tu peux t'aider du caractère espace avant la note).
> Hint; , il ne s'agit pas de chercher directement le texte 9/10, mais de chercher un chiffre et un slash, suivi de deux chiffres.

``` php
([0-9])(\/10)
```

#### Trouve l'expression régulière qui renvoie les mots ayant au moins 14 caractères (tu devrais trouver l'age du capitaine, à moins que ça ne soit son vaisseau !)

``` php
[a-zA-Z]{14,}
```

#### Trouve l'expression régulière qui correspond à l'url de la fiche du fils sur IMDB https://www.imdb.com/title/tt0133093 (attention à ne pas sélectionner les parenthèses).

``` php

```
