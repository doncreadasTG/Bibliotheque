Bibliotheque
============

Une petite application permettant de gérer une bibliothèque.

Cette application est composée de trois classes : Livre, Bibliotheque
et 

la classe Livre qui contient :
1) les variables d'instances suivantes : titre, auteur, editeur et nbpage.
2) les accesseurs et mutateurs associés à ces variables d'instance.
3) une méthode permettant d'acher les références du livre.
4) une méthode permettant de vérier si deux livres sont identiques.
Rappel. La méthode boolean equals(Object anObject) de la classe String compare
l'objet A de type String invoquant cette méthode à l'objet B passé en
argument. Le résultat est vrai ssi B est non null, de type String, et égal à A.


la classe Bibliotheque qui contient :
1) les variables d'instance suivantes : nom, adresse, max, et un tableau de
Livre d'au plus max Livre.
2) les accesseurs et mutateurs associés à ces variables d'instance.
3) une méthode permettant d'acher les livres de la bibliothèque.
4) une méthode permettant d'ajouter un livre de la bibliothèque.
5) une méthode permettant de retirer un livre de la bibliothèque.
6) une méthode permettant d'éliminer les doublons de la bibliothèque.
7) une méthode qui prend comme argument une bibliothèque et ache à
l'écran les livres présents dans les deux bibliothèques.
8) une méthode permettant de trier les livres de la bibliothèque par auteur.


la classe InterfaceBibliotheque:
Cette classe doit proposer à un utilisateur un menu complet pour interagir
avec la bibliothèque
