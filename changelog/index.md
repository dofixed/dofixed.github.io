## Changelog

### <a id="1.0.4"></a>1.0.4

#### Nouveautés

- Compatibilité avec la 2.56.3

#### Corrections

- Fix du crash quand on arrive sur une map avec un percepteur

### <a id="1.0.3"></a>1.0.3
<details>
    <summary>Détails</summary>

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
