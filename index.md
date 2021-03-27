# IHM Project
## Semaine 1 (3 Février)

### PRÉSENTATION/DÉFINITION DU PROJET

Le projet sur lequel nous allons travailler se fait dans le cadre de l'UE IHM du Master ANDROIDE de Sorbonne Université. Il consiste à concevoir, évaluer et reconcevoir un système interactif sous la forme d’un prototype vidéo. Le système devra répondre aux besoins d’**utilisateurs réels** dans un **contexte réel**. Cette année, on choisira une application de cartes.

#### Équipe

Ce projet sera mené par les membres du groupe 2, Mouna Benabid, Marius Le Chapelier, Damien Marillet et Basile Musquer.

### INTROSPECTION

Une première discussion sur le sujet des cartes physiques et applications de cartes a été entreprise. Parmi les problèmes relevés, on peut citer celui du *lien visuel entre la carte et nos alentours*. Cependant, cela n'a pas permi d'établir un thème et une orientation pour notre projet. Nous ferons donc des interviews au cours de la semaine, qui nous permettrons d'évaluer les besoins d'utilisateurs réels et d'en ressortir des problèmes sur lesquels nous pourrons nous pencher.

### INTERVIEW

Après concertation, nous avons consulté les méthodologies fournies dans le cours, et avons établi des questions qui nous permettraient d'en ressortir des problèmes qui mèneraient à des idées d'orientation.

#### Questions 
>* Quand est-ce que vous avez utilisé une carte (physique) pour la dernière fois ?
>* Dans quel contexte l’avez-vous utilisée ?
>* A quelle fréquence utilisez-vous des cartes ?
>* Quelle est la dernière application avec une carte que vous avez utilisé ? (maps, ratp, airbnb…) 
>* Dans quel contexte l’avez-vous utilisée ?
>* A quelle fréquence l'utilisez-vous ?
>* Dans le métro, vous arrive-t-il de vous orienter avec une des cartes mise à votre disposition ? Si oui, à quelles occasions ? Si non, pourquoi pas ?
>* Avez-vous une anecdote en relation avec l’utilisation d’une carte? Une fois où vous avez été mal orienté, ou vous vous êtes perdus, ou bien ça vous a sauvé la mise etc.? 
>* Pour vous orienter dans un endroit que vous ne connaissez pas, préférez-vous utiliser une carte physique ou une application ? Pourquoi privilégiez-vous ce moyen plutôt que l’autre ?
>* Pouvez-vous citer 3 domaines d'utilisation de cartes ? 

#### Réalisation
Chaque membre de l'équipe a interviewé entre 1 et 2 personnes, et a enregistré à l'aide d'audio ou de simples prises de notes. Des observations en ont été tirées, et serviront à la mise en commun des résultats qui aura lieu la semaine du 10 Février.

Vous trouverez ci-joint un lien menant aux [interviews](https://github.com/Guignet/IHMProjet.io/tree/main/Semaine_1) effectués entre le 3 et 12 Février.



## Semaine 2 (10 Février)

### MISE EN COMMUN DES RÉSULTATS

Nous avons discuté de nos interviews et des observations qui en ont été tirées, pour en ressortir plusieurs problématiques telles que : 

>* Les cartes ne sont pas toujours correctements mises-à-jour.
>* Le lien entre le visuel et la carte, qui peut être difficile et mener l'utilisateur à se perdre.
>* La fragilité des cartes physiques qui peuvent se déchirer à cause de l'humidité.
>* L'épuisement des batteries de téléphones.
>* Lecture des cartes papiers non intuitive.
>* Les plans des stations de ski non efficaces.
>* L'absence de cartes des places de parking gratuits.
>* Le nombre, qualité et la précision des éléments sur la carte en fonction du zoom et dimensions du support de visualisation.
>* L'utilisation des cartes que lorsqu'on a un besoin clair, soit aller d'un point A à un point B ou recherche d'un endroit, et pas d'incitation à l'utiliser sans avoir un besoin préalable.

### DÉFINITION DES INTERACTION POINTS

A l'issue de notre discussion, nous avons converti les incidents clés capturés pendant les interviews comme des interaction points.

### PERSONAS ET EXTREME CHARACTERS

En nous inspirant des profils des personnes que nous avons interviewées, nous avons établi des [personas et extreme characters](https://github.com/Guignet/IHMProjet.io/tree/main/Semaine_2).

### SCENARIOS

Nous avons ainsi fait usage des problématiques relevées plus haut pour écrire des [scenarios](https://github.com/Guignet/IHMProjet.io/tree/main/Semaine_2) qui mettraient en scène nos personas et extreme characters de manière à mettre en évidence ces problématiques.



## Semaine 3 (17 Février)

### STANDARD BRAINSTORMING

Nous avons repris la liste de problèmes relevés la semaine précédente pour partager des idées de résolution lors d'un brainstorming. Nous nous sommes fixés un temps de 30 minutes pour développer des idées rapides et sans débats. Le modérateur choisi, chargé d'animer la discussion et faire parler chaque membre de l'équipe, a été Marius Le Chapelier, tandis que Damien Marillet a fait office de scribe.

#### Notes résultantes

##### Chemins pas clairs
> *Idée 1 :* Carte avec support visuel direct, qui affiche le chemin en réalité augmentée :
>  * Rayon de lumière qui représente le chemin.
>  * Rayon de lumière qui part du point de destination vers le ciel pour le voir de loin et pour le reconnaître une fois proche.

##### Recherche des places de parkings
> *Idée 2 :* Carte des places de parkings gratuits.

##### Fragilité des cartes papiers et limitation de batterie
> *Idée 3 :* Carte qui ne s'abîme pas (pluie, humidité, déchirement) et qui ne tombe pas en panne de batterie. Transportable et pas encombrante (liseuse) :
> * L’idée principale tournant autour du papier électronique (qui peut être souple aussi !!). Soit une coque/surface qui la protège comme dans les liseuses, soit  du papier souple avec une surface hydrophobe autour pour conserver la flexibilité de la carte papier.
> * Ou alors lentilles intelligentes.

##### Incitation à l'utilisation
> *Idée 4 :* Une carte qui nous incite à l'utiliser par son interactivité "ludique" qui incite à l'exploration :
> * Inspiration de jeux vidéo : 
>   * Tu commences avec une carte vierge et des points qui représentent des grands monuments ou endroits importants, et la zone autour des points ne se débloque sur la carte que lorsque tu es physiquement allé à ce monument (donc en gros plus t'explores et plus la carte s'agrandit)
>   * Niveaux, points etc...

##### Mise à jour des cartes : en dématérialisé
> *Idée 5 :* Carte participative par exemple pour les places de parking, ou pour la màj des chemins pour les randonneurs (pour voir les chemins les plus pratiqués par ex). 

> *Idée 6 :* Ou alors avec en pseudo-interactif; les données (l’utilisateur est garé dans ce parking dans telle place) sont récupérées par l’application directement, sans que l’utilisateur ait à rentrer ses données. (peut-être associée au problème d’organisation optimale de trajets avec des taches non-ordonnées)

##### Support innovants
> *Idée 7 :* Surface transparente comme du verre, où tous les points d'intérêts s’affichent, qui scannent l’environnement, qu’on utilise en regardant le paysage (projette sur sa surface les informations utiles à l’utilisateur).

> *Idée 8 :* Surface extensible de smartphone (écran déroulable) qui règle les soucis de dimensions de l’écran particulièrement problématique pour l’utilisation des cartes.

##### Problème des cartes de ski
> *Idée 9 :* Avec des cartes interactives en bas des pistes où on peut se déplacer pour observer l’environnement (sorte de streetview).

##### Idées folles
> *Idée 10 :* La carte s’enroule autour de toi comme une bulle et c’est une VR : tu peux te déplacer virtuellement dans la carte, ça peut être un monde non réel basé sur une carte de livre. (On se balade dans le monde de Game of Thrones)

> *Idée 11 :* Téléphone qui vole et qui projette en hologramme les éléments de carte (points d’intérêt etc) autour de nous.

### RÉFLEXION ET INTERSECTION DES IDÉES

À l'issue de ce brainstorming, nous nous sommes intéressés aux **idées 7 et 8**. Nous avons également remarqué que l'idée 7 se rattachait à l'**idée 1** concernant le manque de clarté des chemins, et l'idée 8 à l'**idée 3**. On peut ainsi simultanément régler les *problèmes de clarté des chemins*, ceux concernant la *fragilité des cartes physiques et les limitations de batterie*, celui de la *portabilité de la carte*, ainsi que les *soucis de dimensions de l'écran qui affecte la précision de la carte selon le zoom*, et ce à l'aide d'un produit tel que :
> - Surface transparente comme du verre qui scanne l'environnement lorsqu'on regarde le paysage :
>   * Tous les points d'intérêts s'affichent,
>   * Rayon de lumière qui représente le chemin,
>   * Rayon de lumière qui part du point de destination vers le ciel pour le voir de loin et pour le reconnaître une fois proche.
> - Surface extensible de smartphone :
>   * Écran déroulable,
>   * Écran souple.
> - Surface hydrophobe.

Nous avons également réalisé des [sketchs](https://github.com/Guignet/IHMProjet.io/tree/main/Semaine_3/Sketchs) illustrant notre idée finale.

## Semaine 4 (3 Mars)

### STORYBOARD

Nous avons débuté la séance en réfléchissant à un scenario qui mettrait en scène l'interaction avec notre produit ainsi que ses fonctionnalités. Nous avons ainsi dessiné un [storyboard](https://github.com/Guignet/IHMProjet.io/tree/main/Semaine_4/Prototype%20scenario).

### VIDEO PROTOTYPE

Nous nous sommes appuyés sur le storyboard pour créer une [vidéo prototype](https://github.com/Guignet/IHMProjet.io/blob/main/Semaine_4/Videos/Prototype1_v1.mp4). L'acteur principal choisi pour cette vidéo est Damien Marillet.

{% include youtubePlayer.html id=page.X9e-JnWtano %}
