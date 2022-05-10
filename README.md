# Etude-du-marche-agroalimentaire-poulet

Mes mission Pour identifier les pays propices à une insertion dans le marché du poulet, il vous a été demandé de cibler les pays. Il vous faudra également étudier les régimes alimentaires de chaque pays, notamment en termes de protéines d'origine animale et en termes de calories.

Construisez votre échantillon contenant l'ensemble des pays disponibles, chacun caractérisé par ces variables :

différence de population entre une année antérieure (au choix) et l'année courante, exprimée en pourcentage ; proportion de protéines d'origine animale par rapport à la quantité totale de protéines dans la disponibilité alimentaire du pays ; disponibilité alimentaire en protéines par habitant ; disponibilité alimentaire en calories par habitant. Construisez un dendrogramme contenant l'ensemble des pays étudiés, puis coupez-le afin d'obtenir 5 groupes.

Caractérisez chacun de ces groupes selon les variables cités précédemment, et facultativement selon d'autres variables que vous jugerez pertinentes (ex : le PIB par habitant). Vous pouvez le faire en calculant la position des centroïdes de chacun des groupes, puis en les commentant et en les critiquant au vu de vos objectifs.

Donnez une courte liste de pays à cibler, en présentant leurs caractéristiques. Un découpage plus précis qu'en 5 groupes peut si besoin être effectué pour cibler un nombre raisonnable de pays.

Visualisez vos partitions dans le premier plan factoriel obtenu par ACP.

Dans votre partition, vous avez obtenu des groupes distincts. Vérifiez donc qu'ils diffèrent réellement. Pour cela, réalisez les tests statistiques suivants :

un test d'adéquation : parmi les 4 variables, ou parmi d'autres variables que vous trouverez pertinentes, trouvez une variable dont la loi est normale ; un test de comparaison de deux populations (dans le cas gaussien) : choisissez 2 clusters parmi ceux que vous aurez déterminé. Sur ces 2 clusters, testez la variable gaussienne grâce à un test de comparaison.

Cette étude consistera à cibler les pays présentant globalement les "plus hauts chiffres" de chacune de ces 5 variables. En effet, imaginons le "pays cible idéal", il disposerait: D'une forte disponibilité alimentaire, que ce soit en terme de calories ou de protéines, ce qui nous indiquerait un bon niveau de consommation. D'un pourcentage important de protéines animales dans la disponibilité totale en protéines, ce qui nous indiquerait une forte consommation de protéine animale. D'une évolution de la population importante qui nous indiquerait un renouvellement régulier de la clientèle. D'un bon PIB par habitant, trivial de dire que ce serait avantageux pour nos ventes. D'un bon rapport entre l'importation de viande de volaille et la production locale, qui nous indique le "niveau d'ouverture" à l'importation de nos produits.
