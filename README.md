# Ace Attorney Idler

## 1) Préambule
Bon, voilà, Nico a eu l'idée, et j'aimerais bien que l'on fasse quelque chose de concret, de beau, et non pas un énième pétanque simulator, (D'ailleurs, on sait quand Charles aura fini le POC d'IHM qu'il est sensé nous faire ?).

## 2) Motivation
Enfin voila, le but du projet serait de faire un vrai projet abouti, et soigné, quelque chose dont on pourra être fiers. 
Le jeu devra donc comporter on mode incremental game, je ne sais pas si d'autre chose, des mini-jeux par exemple, pourrait être ajoutés, en tout cas, pas dans l'initial release.

## 3) Concept
Le concept serait ce que tout ce qu'un idle game de base est, on fait une action, pour gagner des ressources, on investi des ressources, pour en gagner encore plus, via une variété de méthode, que l'on débloque progressivement.
A un certain point, on pourra "soft reset" sa partie, pour recommencer en conservant un certain bonus. A voir si l'on inclue plusieurs forme de reset, l'un étant plus conséquent que l'autre (voir abdication et réincarnation dans Realm Grinder). Enfin, on pourra peut etre ajouter des défi, qui octroieront des bonus (ou pas), ainsi qu'un ensemble d'achievements.

## 4) Univers
L'univers sur le quel sera basé le jeu est celui d'Ace Attorney.

**Remarque** : On peut se poser la question du spoil, dans quelle limite doit t'on s'inspirer de l'univers, et doit on se pauser des contrainte pour eviter de spoiler l'utilisateur ?

Je l'avoue, c'est la partie sur laquelle je ne suis pas fixé... Premièrement, l'idée de Nico est de mettre un écran pour lancer des objection, tu click, tu lance une objection, je pense qu'on peut étendre a d'autre scènes, peut être 3 scènes différentes, un scène d’enquête, un scène de logique, une scène de procès. Avec différentes parties aux trois scènes. (Par exemple, la scène procès peut être décomposée en interrogatoire, objection, poursuite etc...)

Ensuite, quand on a gagné suffisamment de ressource (Idée, ressource dépendant du perso, ex : badge d'avocat pour pw, magatama, perle, etc.), tu peux débloquer un nouveau personnage, et recommencer.

## 5) Outils & langages
Pour ce projet, je propose de crée un dépot git hub sur le quel nous seront tous les trois admins. Je propose une compilation sous gradle qui semble être dans l'air du temps.
Pour les langages, ce qui a été proposé est la Kotlin, ce qui pourrait permettre de crée une application mobile aisément, tout en garantissant l'accès aux bibliothèques java. 
Ne m'y connaissant pas en kotlin, ni en graphique avec java, je vous laisse proposer vos idée pour les bibliothèques / frameworks utiliser. Personnellement j'ai vu que "libgdx" ce comportait très bien avec Kotlin, a voir.

## 6) Remarques
- Il est très important vu la nature du jeu, d'apporter un soin particulier à l'équilibrage. En effet, il ne faut pas que le jeu devienne a un moment trop facile, et à l'opposé, qu'il ne soit jamais trop dur, et bloque l'utilisateur a une étape (A voir avec les soft reset). Je sais que des docs ont été écrit la dessus, il faudra se renseigner.
- Il faut penser a un mode offline, qui soit efficace, mais pas cheaté, sinon, le jeu perdrait de l’intérêt.
- On faut bien voir le jeu de façon incrémentale (wow inception !) c'est à dire, la première release ne doit pas être la version finale, il faudra pourvoir trouver du contenu supplémentaire, afin de ne pas laisser l'utilisateur sur ça fin.
- Bien que la première version du jeu soit prévu pour mobile, on peut concevoir une version navigateur.
- Il faut aussi penser a l'aspect légal, je ne pense pas que capcom laisse toucher à ses perso comme ça. (Après vu la prolifération des jeu ou on doit coiffer/maquiller, faire des cézarienne a des perso disney, je pense que les gens laisseront un idle game, enfin ...) Au besoin, le jeu peut être légerement modifié afin d'empecher le take down, genre on joue (foénix vvright).
- En parlant des noms des perso du jeu, je propose d'utilisé leur toponymie anglaise.
- Nico propose de mettre des easter eggs, a voir si on met des achievements relatifs
- Non, nous n'utiliseront pas les sprites de minecraft. Mais à voir si quelqu'un connais un personne douée en dessin pour nous faire des sprites, a défaut, on pourra en trouver sur le web.
- A voir aussi, la licence qu'on lui donne, n'ayant pas les droits de la licence, je laisse a Nico le soin de choisir, comme c'est lui qui s'y connais le plus.

  
