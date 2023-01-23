23/01/2023 - Rélisation de la page d'accueil en HTLM/CSS.


Avancées :

/!\ Patch-day !

- Les badges "nouveau" sont désormais résponsives grâve à un positionnement absolute dans un parent relative, cela permet de tracker parfaitement la position voulue.
- Redimensionnement des unités d'instruction, un widht globale légarement moins important permet d'atteindre 320px et ne déforme pas les éléments du flex à 320+.
- Le menu des restaurants n'est pas scrollable car la présence d'un script est requise. Le JS étant interdit, le projet restera ainsi, affaire conclue.
- Le texte des cards menu des restaurants disposent désormais d'un break point en cas de résolution très basse. Cela permet d'atteindre le 320px.
- Cards rendues clickables via un z-index sur les boderbox et balise div qui passe en a avec href.
- Passage en 7-1.


A suivre :

- Relire le code pour en retirer le superflu / retenir l'essentiel.
- Confirmer le validateur W3C.

-> Une fois les points du dessus validés, passer au page des menu en CSS.
-> Ne pas oublier de commit les changements de la page d'accueil sur le main.



