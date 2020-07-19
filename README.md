- [Résumé](#rsum)
- [La défense](#la-dfense)
- [Dégâts](#dgts)
- [Bouclier](#bouclier)
- [Cases et déplacement](#cases-et-dplacement)
- [Effets des réussites critiques](#effets-des-russites-critiques)
	- [Sur les capacités](#sur-les-capacits)
	- [Sur les attaques "normales" (hors capacités)](#sur-les-attaques-normales-hors-capacits)
- [Armes](#armes)
	- [Armes liées à la force](#armes-lies-la-force)
		- [Arme blanche](#arme-blanche-)
			- [Couteau ](#couteau-)
			- [**Epée**](#epe)
		- [Arme contondante](#arme-contondante)
	- [Arme liée à la précision](#arme-lie-la-prcision)
		- [**PROJECTILES**](#projectiles)
		- [**ARME À FEU**](#arme-feu-)
			- [Pistolet](#pistolet-)
			- [Fusil](#fusil-)
		- [Canon](#canon-)
- [Calculs](#calculs)



Avant de rentrer dans le vif du sujet, je dois vous parler du système de combat. Tout d'abord, il faut savoir que tout est automatisé, vous n'avez pas à calculer vos dégâts, je m'occupe de tout.

Les combats se déroulent au tour par tour, avec un lancé d'un dé 10 d'attaque et de défense.

Un tour est lorsque tous les combattants (ennemis compris) ont joué. Mais les cooldown ne s'actualise que durant le tour personnel du joueur et non pas le tour "général" du combat (comme dans la majorité des jeux tactiques, notamment dofus).

# Résumé

-   Lancé de dés d'attaque et de défense
    -   L'endurance permet d'encaisser les dégâts.
    -   L'esquive permet de ne pas prendre de dégât. Elle est réussie si le dé est moitié moins du dé d'attaque de l'adversaire.
-   Dés de 10 lié à votre caractéristiques
    -   Implant : Valeur seuil = strictement inférieure à votre caractéristique (7 pour 8, 6 pour 7, etc).
    -   Pas d'implant : Seuil = caractéristique
-   Meilleur jet : 0, pire jet : 10
    -   Un 0 correspond à une "Ultra réussite critique" et un 1 à une "réussite critique".
    -   Seul un implant (ou remise) permet d'avoir de faire un URC.

# La défense

La caractéristique que vous lancez pour votre défense est soit un dé d'endurance ou d'agilité.

-   L'endurance vous permet d'encaisser le coup, il recevra donc moins de dégâts.
-   L'agilité vous permet d'esquiver le coup (et donc de ne pas prendre de dégâts). De plus, pour réussir votre esquive, vous devez faire moitié moins que votre statistiques d'agilité. Le dé $esquive a été créée spécifiquement pour ça !

Il existe cependant des attaques qui ne rentrent dans cette catégorie : les altérations d'état.

-   Les attaques mentales : Elles nécessitent une défense avec un dé d'intelligence.
-   Les attaques liés aux poisons, maladie et blessures : Elles nécessitent un dé de karma.
    A noter que pour les dégâts persistants, le dés de karma est à lancer chaque tour pour supprimé l'altération. Sinon, cette dernière dure 3 tours au maximum.

Choisissez donc bien en fonction de vos caractéristiques !

Vous devez OBLIGATOIREMENT lancer votre dé avant de déterminer votre action. Mais vous n'êtes pas obligé d'attendre le dé de défense de votre adversaire. Dans tous les cas, l'action finale avec les dégâts sera après le lancé des protagonistes de l'action.

Dans le cas où il y aurait un 1 VS plusieurs, la personne en sous nombre doit lancer un dé de défense pour chaque attaque reçu et peut attaquer un certain nombre de personnage en fonction de son niveau.

# Dégâts

Les dégâts sont déterminés en fonction de l'écart de dé entre l'attaquant et le défenseur dans le cas où le défenseur n'a pas réussi à esquiver l'attaque. Ainsi, plus la différence est haute, plus le défenseur perdra de pv. Il est à savoir que les dégâts sont calculés sur une base de 100 PV. Ainsi :

- Ecart de 9 (voire+): Coup critique : L'adversaire perd 50 PV.

- De 8 à 7 : Très Bon dégât : Le défenseur perd 40 PV.

- De 6 à 5 : Bon dégât : Le défenseur perd 30 PV.

- De 4 à 3 : Dégât moyen: Le défenseur perd 20 PV.

- De 1 à 2  : Dégât faible : Le défenseur perd 10 PV.

- 0 : Dégâts très faible, le défenseur perd 5 PV.

Dans le cas où le défenseur aurait encaissé le coup (dé d'endurance), il perd moins de pv. La valeur de sa caractéristique est une valeur seuil, et plus le dés sera bas mieux le défenseur encaisse. Un score de 0 étant un URC, la personne encaisse tous les dégâts.

> La valeur de la caractéristique détermine le montant maximum qu'il est possible d'encaisser.

# Bouclier

Les boucliers protègent des dégâts. Dans les faits, cela fonctionne exactement comme un encaissement avec un dé d'endurance.

Cependant, les résistances sont fixes et liés soit à votre équipement, soit au rang de votre adversaire. En général, il existe :

-   Armure légère : Diminution de 10%
-   Armure moyenne : Diminution de 25%
-   Pré- requis : Force = 3
-   Malus si porté sans les pré- requis : +1 aux dés d'agilité
-   Armure lourde : Diminution de 50%
-   Pré- requis : Force = 5
-   Malus si porté sans les pré- requis : +2 aux dés d'agilité

Si votre personnage fait un ultra critique,, ou si vous utilisez une capacité perforante, le bouclier est ignoré.

# Cases et déplacement

Lors d'un début de combat, la pièce se sépare en trois rangs :

-   Rang 1 : Corps à corps
-   Rang 2 : Semi- distance
-   Rang 3 : Distance

Les joueurs commencent toujours au rang 3, et les ennemis se trouvent au début au rang 1.

Si un ennemi se déplace sur le Rang 3 et qu'il y a un allié, alors cet allié sera au rang 1 de cet ennemi, mais ne bougera pas pour les autres.
Au contraire, si un allié se trouve au rang 1 et qu'un ennemi va au rang 3, l'allié sera alors au rang 3 de l'ennemi, mais restera au corps à corps des autres.

Tous les joueurs peuvent se déplacer sur les cases comme ils veulent : ils peuvent donc remonter au premier rang en étant au dernier. Cependant, un joueur ne peut pas faire plusieurs déplacement par tour.

Les compétences et les pouvoirs ne prennent pas en compte la distance, contrairement aux armes.



Naturellement, on considère que les personnages "tireurs" sont systématiquement à couvert.



L'action "de s'abriter" permet à un personnage (blessé, par exemple) de se protéger efficacement (derrière un gros meuble, un mur) sans bouger. Les ennemis ont alors bien plus de mal à le viser et ont un malus de +3 en précision lorsqu'ils souhaitent tirer sur lui.

En contrepartie, tant qu'il est abrité, il ne peut plus ni attaquer, ni esquiver (il ne peut qu'endurer les dégâts).



Quand un personnage au corps à corps s'attaque à un autre personnage (notamment les tireurs), ce dernier est automatiquement mis "en duel", ce qui octroies aux attaquants un bonus de précision de -1. En outre, le défenseur à découvert a un malus de précision s'il veut tirer sur une personne en dehors du rang sur lequel il se trouve.



La position à découvert est analogue à la position "en duel", la seule différence étant que le tireur n'a pas de malus de visée sur les autres rangs. Les personnages de corps à corps sont automatiquement à découvert, contrairement aux tireurs.



Il y a donc trois positions :

- Abrité : +3 en précision pour les attaquants, mais ne peut ni attaquer, ni esquiver.
- A découvert : -1 aux jets d'attaques (pour les attaquants).
- Duel : -1 aux jets d'attaques (pour les attaquants), et +2 en précision si visée sur les autres rangs.

# Effets des réussites critiques

## Capacités

Les réussites critiques ont pour effets de multiplier les effets d'une compétences, que ce soit en terme de dégâts pour les compétences offensives, qu'en terme de bonus ou malus.

Dans le cas où votre personnage fait :

-   Une réussite critique : Son bonus sera multiplié par 1,4.
-   Une Ultra réussite critique : Son bonus sera multiplié par 1.8.
    Lorsque l'on multiplie, on ne prend pas en compte le "pourcentage" (la division par 100).

Le calculs des dégâts des compétences offensives sont automatisés, vous n'avez donc pas besoin de vérifier le bonus multiplicateur. Cependant pour les compétences non- offensives, vous devrez calculer en fonction du multiplicateur.

## Attaques normales

A savoir que seuls les implants permettent d'atteindre le score de 0.

-   Les Ultra critiques d'attaque : Les dégâts sont multipliés par 1.8 et on outrepasse la défense de l'adversaire.
-   Les Ultra critique de défense: Lorsqu'un combattant a un score de dés d'endurance ou d'agilité égal à 0, il annule automatiquement l'attaque de son adversaire, quelque soit la valeur de son dé, sauf dans le cas où l'autre attaquant aura un 0 en endurance. Dans ce cas, le défenseur perdra 9 PV.

-   Les réussite- critique d'attaque :  Lorsqu'un combattant a un score de dés égal à 1, le score est multiplié par 1.4, exactement comme dans le cas d'une compétence.

A noter que lors d'une UC d'esquive, le combattant bénéficie d'une riposte avec un bonus de dégâts de 5%, en plus de ses bonus pré- existants. Les RC donnent droit à une riposte, sans bonus d'attaque.

# Armes

##  Armes liées à la force

Les armes liées à la force sont toutes au corps à corps. Le programme bloque donc automatiquement sur cette valeur. Il est cependant possible de créer une arme "spécifique" avec le champ autre.



A savoir aussi que le programme bloque aussi au corps à corps pour la partie "aucun" qui correspond en réalité à un simple coup de poing d'une personne sans aucun équipement (donc, sans gants de boxe, par exemple).

### Armes blanches

#### Couteau

- **Bonus** : 5%
- Utilisation gratuite un tour sur deux. Si double couteau, il est possible d'activer le bonus en même temps et de donner 4 coups un tour sur deux.

#### **Epée**

- **Bonus** : 10%

###  Arme contondante

- **Bonus** : 15%
- **Pré-requis** : 4 en force

## Arme liée à la précision

###  **Projectiles**

- **Bonus** : 5 %
- **Placement** : Rang 1 à 2
> Exemple : Grenade, bombe, couteau...

###  Arme à feu

#### Pistolet

- **Nombre de balles (ou charges)** : 8
- **Bonus** : 8%
- **Placement** : 1 à 2
- **Malus de placement ** : +2 Précision (rang 3)

#### Fusil

- **Nombre de balles (ou charges) ** : 12
- **Bonus** : 10%
- **Placement** : Rang 2 à 3
- **Bonus de placement** : +5% (rang 1)
- **Malus de placement** : +1 Précision (rang 1)

### Canon

- **Bonus** : 20%
- **Malus** : +2 en agilité
- **Pré-requis** : 4 en force
- **Placement** : Rang 2 à 3
- **Limitation** :
	- Une fois tous les 3 tours.
	- Ne peut pas porter de modules
- **Bonus de placement** : +10% (rang 1)
- **Malus de placement** : +2 précision

> Les artilleurs n'ont pas de malus d'agilités et n'ont pas besoin d'avoir 4 en force pour pouvoir porter ses armes.

# Calculs

Après avoir vérifié la table, on récupère les dégâts. Ainsi $$d=dégâts\hspace{10px}de\hspace{10px} la\hspace{10px} table + bonus$$

* **PV perdus** : $$d = d * 100$$

* **Bouclier :** $$d * (1-bouclier)$$

* **Endurance et dégâts finaux** : $$finaux = bouclier * \frac{1-[10*(endurance-défense)+1]}{100}$$

* **PV restants : ** $$PV\hspace{10px}max - finaux$$
