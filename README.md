# Capacité numérique PCSI - Température et pression dans l'atmosphère
## Intitulé du programme de PCSI

> à l’aide d’un langage de programmation, **étudier les variations de température et de pression dans l'atmosphère**.

## épisode I (S1) - modèles isotherme et à gradient constant

Résolution par intégration `odeint`

> Demander de résoudre pour le modèle à gradient constant. 
> 
> Calculer l'écart relatif maximal avec l'atmosphère isotherme et altitude 
d'annulation de la pression.

_Données qui peuvent changer:_ `P0, T0, g0, M, alpha`

## épisode II (S2) - Variation de g avec la gravité

> Demander de résoudre pour le modèle à $g$ variable (avec gradient de température).
> 
> Calculer l'écart absolu maximal avec $g$ constant et altitude d'annulation de la pression.


_Données qui peuvent changer:_ `P0, T0, g0, M, alpha`

## épisode III (S3) - Modèle d'atmosphère normalisée 

Lire https://fr.wikipedia.org/wiki/Atmosphère_normalisée

> Demander de résoudre pour atmosphère normalisée
> 
> Calculer l'écart relatif maximal avec atmosphère isotherme

_Données qui peuvent changer:_ `P0, T0, g0, M`
