## Changelog

### <a id="1.3"></a>1.3

#### Nouveautés

- Compatibilité avec la 2.59 de Dofus
- Dofixed peut désormais transmettre des informations anonyme sur les monstres à notre partenaire Dofensive pour l'amélioration du service. L'envoi peut se désactiver grâce à une option présente dans l'onglet "Autre"

#### Corrections

- Les rendus des personnages sont désormais présents dans le replayer

#### Régression

- Les fonctionnalités liées aux combats sont temporairement cassées à cause de changements majeurs dans la 2.59. Nous travaillerons prochainement à restaurer ces fontionnalités.


### <a id="1.2.4"></a>1.2.4
<details markdown="1">

#### Corrections

- Le moteur de rendu Flash est de nouveau opérationnel. Les rendus font leur réapparition dans la timeline, les replays ainsi la fenêtre de chat vocal.
</details>

### <a id="1.2.3.1"></a>1.2.3.1
<details markdown="1">

#### Améliorations

- Le module DoFensive retrouve sa couleurs d'antan (avec des images)
</details>

### <a id="1.2.3"></a>1.2.3
<details markdown="1">

#### Améliorations

- Compatibilité avec la 2.58.3.3

#### Corrections

- Les liens discord ne renvoie plus vers un canal à accès restreint
- Désactivation des rendus d'images nécessitant Flash en attendant de trouver une solution
</details>

### <a id="1.2.2"></a>1.2.2
<details markdown="1">

#### Améliorations

- Compatibilité avec la 2.58
</details>


### <a id="1.2.1"></a>1.2.1
<details markdown="1">

#### Nouveautés

- Ajout d'un kikimeter compact

#### Améliorations

- La couleur du mode semi-tactique s'adapte automatiquement aux couleurs de la zone
- La connexion avec le réseau est beaucoup plus stable (il ne devrait plus y avoir de désynchronisation entre le jeu et Dofixed)

#### Corrections

- Fix des crash en cas de combat avec un percepteur
- Fix du crash lors du lancement de Dofixed avec plusieurs fenêtres dofus ouvertes
</details>

### <a id="1.2"></a>1.2
<details markdown="1">

#### Nouveautés

- Ajout d'une coloration de Dofixed en fonction de l'état actuel de Dofixed (hors-ligne, connecté, position détectée, identifié)
- Le replayer est disponible de manière indépendante de l'installation de Dofixed

#### Améliorations

- Refonte globale du système de chat vocal (map/combat)
- Refonte globale de l'interface Dofixed
    - Affichage des images des monstres pour DoFensive
    - Regroupement de tous les paramètres dans un onglet dédié
    
#### Corrections

- Le replayer ne crash plus en cas de fichier .dfxr corrompu
- Fix avec notre partenaire JoL le crash en cas d'ouverture du livre de quêtes dans certains cas
</details>


### <a id="1.1.1"></a>1.1.1
<details markdown="1">

#### Nouveautés

- Compatibilité avec la 2.57

#### Améliorations

- Les fichiers .replay deviennent des fichiers .dfxr. Les fichiers .replay déjà enregistrés peuvent toujours être lus
- Les fichiers .dfxr peuvent désormais être ouverts par défaut par le Dofixed Replayer lorsque Dofixed est installé sur le PC
- Amélioration de la prise en charge des glyphes dans le replayer (cawotte, prémonition ...)
- Le replayer peut désormais charger les noms de cases personnalisés de la même manière que le mode semi-tactique de Dofixed

#### Corrections

- L'érosion actuelle s'affiche désormais correctement à côté du coeur des PV
- Le replayer ne crash plus quand une entité "sans position" (par exemple invisible) joue

#### Succès

- La détection de l'état des succès en temps réel est désactivée suite à l'implémentation de la feature de manière officielle et moins buguée par Ankama
</details>


### <a id="1.1"></a>1.1
<details markdown="1">

#### Nouveautés

- Dofixed se dote d'un nouvel outil : le replayer ! Grâce à lui vous pourrez enregistrer vos combats dans un format léger pour les revivre par la suite
- La session enregistre désormais les Kamas perdus ou détruits (zaap, banque ...), ainsi que les gains bruts (quêtes, succès)
- Un nouveau paramètre permet d'activer la fonctionnalité "Multicompte". Cette dernière n'est pour l'instant compatible que pour enregistrer les gains/pertes de Kamas bruts dans la session, mais d'autres fonctionnalités devraient s'ajouter progressivement

#### Améliorations

- Les notifications de vente sont améliorées sur Windows 10
- Les rendus des personnages dans la timeline et le renderer sont fidèles aux rendus en jeu (mise à l'échelle et recalage des items, pose des personnages etc ...)
- Amélioration de la gestion réseau pour éviter les crash en cas de surcharge (exemple : rentrer en Bethel à 8 comptes)

#### Corrections

- La timeline retrouve les rendus des personnages et des monstres
- Les instances "fantômes" de Dofixed ne l'empêche plus de se lancer
- Les items de quête ne sont plus comptabilisés comme drop par la session
- Les modules Dofixed fonctionnent de nouveau normalement même en cas de présence d'interface réseau virtuelle (Hamachi, VPN etc ...)
- Détection automatique de l'absence des redist VC++ à l'installation pour éviter les crash au démarrage

#### Succès

- Les succès du donjon Akwadala apparaissent correctement
- Focus n'est plus noté comme échoué en cas de résu d'un monstre
- Les succès du Bworker ne sont plus affichés dans le donjon des Bworks
- Mains propres n'est plus noté comme échoué lorsque le kill est fait avec Crocobur en fin de tour
</details>

### <a id="1.0.4"></a>1.0.4
<details markdown="1">

#### Nouveautés

- Compatibilité avec la 2.56.3

#### Corrections

- Fix du crash quand on arrive sur une map avec un percepteur
</details>

### <a id="1.0.3"></a>1.0.3
<details markdown="1">

#### Nouveautés

- Compatibilité avec la 2.56
- Déplacement du bouton Dofixed sur la barre de titre de la fenêtre Dofus lorsque possible pour ne pas déranger les interfaces Dofus sur des petits écrans

#### Corrections

- Remplacement du doublon "Dommage Air" par la bonne ligne "Dommage Feu" dans le rapport de combat
- Correction du crash au démarrage si le service de pare-feu Windows n'est pas disponible
- Correction du lancement automatique avec Dofus
- Correction du crash au démarrage si on essaie d'interagir avec la fenêtre avant que tout soit initialisé

#### Succès

- Les personnages morts n'ont plus besoin de valider Nomade
- Les dégâts sur les invocations ne sont plus comptés pour Duel
- Les invocations (en particulier les doubles Sram) n'ont plus besoin de valider Hardi
- Le Chafer Rōnin retrouve ses succès
</details>


### <a id="1.0.2"></a>1.0.2
<details markdown="1">

#### Corrections

- Fix du crash à l'ouverture du livre de quêtes
- Fix du reset de session quand l'option de sauvegarde est activée
</details>


### <a id="1.0.1"></a>1.0.1
<details markdown="1">

#### Nouveautés

- Ajout d'un bouton pour réinitialiser la session en cours

#### Corrections

- Fix de l'Almanax
- Fix du crash sur les serveurs avec un accent (Mériana on te voit)
- Fix du statut dans Discord
</details>


### <a id="1.0"></a>1.0
<details markdown="1">

Fin de la version bêta, merci à tous ceux qui ont remonté des bugs !

#### Nouveautés

- Tutoriel de lancement
    - Xena La Gruyère vous accueille lors de votre premier lancement de Dofixed pour vous expliquer où se trouve le menu et comment demander de l'aide
- Suivi de session de jeu
    - Permet de suivre vos gains d'XP et de Kamas
    - Utilise le prix moyen pour les items dropés s'il est disponible, sinon le prix de vente aux PNJ
    - Peut afficher le temps estimé avant le prochain up
- Notification de vente
    - Envoie une notification lorsque vous réalisez une vente en HDV
    - Seuil de vente minimal paramétrable
- Dofixed Timeline (bêta)
    - Cache les invocations en dehors du tour de l'invocateur
    - Test technique, n'hésitez pas à faire vos retours sur ce que vous aimeriez ou si vous rencontrez des bugs !
- Changelog
    - Ajout d'une page Changelog sur le site
    
#### Rapport de combat

- Ajout d'un mode compact transparent pouvant se placer au-dessus de Dofus sans cacher 90% de la zone de jeu
- Ajout de l'export des données au format Excel (très simple pour l'instant)
- Ajout de filtres sur les équipes, les morts, les compagnons
- Respect de l'échelle de temps dans les graphiques de PV
- Diverses optimisations pour rendre le tout moins gourmand en ressources, plus fluide et agréable pour nos utilisateurs adorés

#### Succès

- Les succès ne sont plus affichés dans les songes infinis
- Correction sur Liberté, Circulez et Temps Qui Court en cas de rall sur soi-même (Picole) ou sur un allié
- Correction sur Collant avec certaines invocations (notamment le double)
- Correction sur Hardi, Collant, Pusilanime, Anachorète quand un allié décède (F)
- Correction sur Focus avec les invocations adverses
- Correction sur Focus en cas de dégâts sur un allié
- Correction de Mains Propres avec les mobs de Corruption
- Correction d'affichage des succès en cas de monstres multiples (Blops Royaux + Multicolore, Tempête de l'Eliocalypse, ...)
- Réflexions sur comment améliorer la fonctionnalité similaire qui sera proposée par Ankama dans la prochaine mise à jour \~(￣▽￣)\~*

#### Corrections diverses

- Correction de la mise à jour des positions des portails de dimension
- Correction de l'affichage des noms de serveur (Ilyzaelle_222 devient Ilyzaelle)
- Correction du crash en cas de nouvelle vague

#### Améliorations diverses

- Pleins de petites et de grosses optimisations que personne ne verra
- Nettoyage et uniformisation du code
- Accélération du temps de chargement initial
- Ajout d'un lien "tous les mobs" vers DoFensive
- Focus sur la fenêtre Dofus sélectionnée à la fin du chargement de Dofixed
- Ajout d'effets manquants à la fenêtre des effets au survol des entités
- Ajout d'une option pour n'afficher les effets au survol que si la touche Shift est enfoncée
- Changement de la couleur des liens pour éviter le bleu sur fond bleu
- Ajout d'info-bulles un peu partout
- L'indicateur d'activité Discord indique désormais "Dofus avec Dofixed"
</details>
