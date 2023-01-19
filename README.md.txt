19/01/2023 - Rélisation de la page d'accueil en HTLM/CSS.

Avancées :

- Amélioration de la responsivité du header/foot.
- Création d'un média queries Desktop.
- Etape 2 terminée à un soucis près (voir "Problème non résolus" ci-dessous).
- Code couleur background-color appliqué ! Je ne l'avais pas "remarqué" avant à cause de mes yeux... Merci Lisa.

- Instauration d'un media queries Desktop {
	- Général -> Margin importante SAUF footer / menu des restaurants ! C'est moche mais apparement c'est comme ça.
	- "Réservez le menu qui vous convient" est bien plus gros !
	- Les étapes sont désormais en flex row.

A poursuivre demain : 

	- Liste des menus en flex row + menu déroulant.
	- Footer en flex row, column reserve, partant de la droite.




Problème non résolus / à voir :

- Rendre clickable les cards. Comment faire avec une checkbox à l'intérieur ?
	(La faire sortir puis re-rentrer avec position relative ?)
- Object-fit réglerait les soucis de responsivité avec "nouveau" mais ne semble pas fonctionner pour autre chose qu'une image/video...
	(Tricher en important notre bouton comme une image ?) -> Sinon Breakpoint. Comme cela est recommandé étape 4.
- Version toujours non-visible pour les écrans > 400px (menuInstruction & "Nouveau").
- Doute sur le flex plutôt qu'un grid pour le "Fonctionnement" en version desktop.
	-> Un flex permet le wrap.
	-> Mais il est peut-être mieux de "forcer" le triple bouton sur une seule ligne ?
	-> Cela demande de tout repenser, d'abord trouver une répartition grid pour tout reparamétrer.
		-> Les premiers essaies dans ce sens déforment les boutons, le rendu est laid.
- Doute sur l'utilisation d'un margin-right: -100%; sur le menu .restaurants (L.450 environ).


