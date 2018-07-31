Dans cet exercice tu devras créer :

### - Trois boss(Sauron,Chronos,Lilith). 
 Chaque boss possédera les propriétés suivantes :
>* Un nom;
>* Un nombre de points de vie;
>* Un nombre de points d'attaque.

#### A Savoir sur les boss :
>* une fois le boss à 20% de ses points de vie, il posera à tes personnages (l'utilisateur) une énigme (choisie aléatoirement entre minimum 3 énigmes) à laquelle ils devront répondre en 3 essais au maximum, s'ils échouent, il mourront, sinon ils vaincront le boss.


### - Trois héros : Un mage, Un guerrier, Un archer.
Avec les propriétés et actions suivantes :

### Le guerrier 
- Propriétés :

  >* nom
  >* points de vie
  >* points d'attaque
  >* point de rage : 0

- Actions de posture :
  >* defense
  >* attaque

  #### A Savoir sur le guerrier 
  >* Tous les tours le guerrier gagne 1 point de rage au bout de 4 points ,le guerrier gagne 25% ( * 1.25 ) d'attaque supplémentaire durant 1 tours puis retombe à 0 de rage et perd ce bonus.

### Le mage 
- Propriétés :
  >* nom
  >* points de vie
  >* points d'attaque
  >* point de mana : chiffre qui sera aléatoirement imposé entre les suivants 7 , 9 ou 11.

- Actions :
  >* defense
  >* attaque

  #### A Savoir sur le mage
  >* Les attaques du mage lui coute 2 points quand il n'a plus assez de point de mana pour attaquer,il passe 1 tour sans attaquer et il récupère 7 points de mana

### L'archer 
- Propriétés :
  >* nom;
  >* points de vie
  >* points d'attaque
  >* nombre de flêches : chiffre qui sera aléatoirement imposé entre  7, 8 , 9 ,10 ,11.

- Actions :
  >* defense
  >* attaque

  #### A Savoir sur l'archer
  >* les attaques de l'archer consomme deux flèches par tour et récupère une flèche chaque tour.Quand il n'a plus de flèches il passe un tour et récupère 6 flèches.

### Les actions de posture : 
  #### Defense :
  >* Diminue de moitié( * 0.5 ) ses dégats d'attaque mais augmente de deux fois et demi ses points de vie ( * 2.5 ). 
  >* Augmente de deux les chances d'être attaqué par le boss

  #### Attaque
  >* Augmente de deux cinquième ( * 1.4 ) ses dégats d'attaque mais diminue d'un quart ses points de vie ( * 0.75 )


## A Savoir en général : 
>* Un boss est choisi aléatoirement parmis les trois, c'est vous qui aurez au préalable choisis ses caractéristiques
>* Vous attribuez des valeurs aux propriétés des boss.
>* L'utilisateur choisi le nom de chaque héros
>* Vous devez fixer un total de point de vies et de points d'attaques que l'utilisateur lui devra distribuer entre ses héros.
>* L'utilisateur pourra choisir une posture 'attaque' ou 'défense' ou le mode 'normal' == rien du tout.Avant le début du combat.
>* Chaque tour les trois personnages attaque une fois le boss.
>* Chaque tour le boss attaque au hasard un des personnages


## Bonus :

- Pour l'énigme, la réponse de l'utilisateur devra être mise en minuscule et les éventuels espace supprimés (exemple : "Un Marron" => "unmarron"). Il faudra aussi trouver une méthode qui permet de vérifier si la bonne réponse est contenue dans la réponse de l'utilisateur (exemple : bonne réponse = "homme", réponse utilisateur = "les HoMmEs" => la réponse est bonne).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAzMjYxMDU5MV19
-->