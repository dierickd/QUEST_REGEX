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

