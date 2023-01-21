20/01/2023 - Rélisation de la page d'accueil en HTLM/CSS.

Avancées :

	- Redimensionnement d'éléments qui a conduit à une amélioration de la responsivité (site fonctionnel de 440px à ∞).
	- Amélioration code couleur et refonte du hover qui était innaproprié.
	- Le menu Restaurants est désormais un flex row en desktop et dépasse vers la droite.
			- Le scroll n'est pas encore correctement géré !
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
- La liste des menus ne scroll pas en desktop ! Pourquoi ?

