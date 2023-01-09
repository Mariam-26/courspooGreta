# courspooGreta

En ligne 3 se trouve une instruction demandant à PHP d'être exigeant avec le typage. Le mot clédeclare permet d'indiquer à PHP un comportement spécifique pour le fichier dans lequel nous nous trouvons. Si vous êtes curieux, d'autres instructions existent dans la documentation PHP. 

En ligne 7 se trouve la déclaration de la propriété. Elle se compose : 

du mot clépublic, afin de définir l'accessibilité de la propriété, nous y reviendrons ; 

du type de la propriété, ici float (ce n’est pas obligatoire mais c’est une très bonne pratique) ;

et enfin, du nom de la propriété préfixé du symbole$. Ce symbole est présent pour la même raison que la déclaration de vos variables : pour distinguer la propriété de la constante. 

Sur cette même ligne vous pouvez constater que la propriété aura pour valeur 0 si je ne précise rien.

En ligne 11 nous assignons la valeur pour notre instance$pont. 

Essayez de changer la valeur par une chaîne de caractère, quelle erreur obtenez-vous ? A vous de tester !

L'écriture du code PHP est assez bien normée. Vous pouvez retrouver l'ensemble des règles en suivant les PHP Standard Recommendations. Entre autres les PSR-1 et PSR-12.

Il existe des méthodes dites magiques, qui sont appelées automatiquement par PHP. Elles commencent par __. 

__construct  est la méthode appelée lors de la création d’un objet ;  __destruct  lors de sa suppression de la mémoire.

Il existe de nombreuses autres méthodes magiques disponibles sur la documentation PHP


 
