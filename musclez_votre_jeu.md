
# Musclez votre Jeu

###  Présentation du contexte

Dans le cadre du projet informatique 1 de Master 1 MIAGE, il nous a été demandé de développer une application de suivi d’entrainement sportif appelée Musclez votre Jeu !

###  Définition du projet
	
##### Problématique

L’idée est de développer une application permettant le suivi et la mise en perspective des progrès pour la pratique sportive, mais comment suivre au mieux un entrainement sportif ? Quelles sont les fonctionnalités à mettre en place ?	

##### Objectifs

L’objectif est tout d’abord permettre l’enregistrement d’un certain nombre d’exercices et l’enregistrement des informations utiles à leur suivi ainsi que les informations concernant le sportif à suivre. Les informations qui découlent de ce suivi doivent être mises sous forme de graphiques divers pour permettre à l’utilisateur « le sportif » de voir ses progrès sous différents angles. Cet outil devra proposer un plan d’entrainement généré automatiquement en fonction de l’historique de l’utilisateur, celui-ci sera en mesure de modifier le plan obtenu.	

* [Début du projet] - Le 14 janvier 2015
* [Fin du projet] - Le 26 mars 2015
* [Budget] - Le projet étant réalisé par un groupe d’étudiants dans le cadre de l’EC projet informatique 1, le budget est nul.
* [Intervenants projet]	- 	Nous serons cinq à intervenir sur ce projet :

```
Clément Burgaud
Manel Gharbi
Shitai Wu
Leite Nzamba-Maleck
Amel Brahim
```

### Contraintes à respecter

##### Contraintes de délais

Le projet doit être terminé pour le mois de mars 2015. Un rapport d’analyse devra être remis le 18 janvier 2015 et un rapport d’architecture le 30 janvier 2015. Les délais doivent être respectés impérativement. Un suivi régulier est prévu pour éviter au groupe de travail de prendre du retard sur la réalisation. Le chef de projet doit veiller au respect de la planification établie.

##### Contraintes budgétaires

Le budget étant nul, nous n’avons aucune contrainte d’ordre budgétaire.
	
##### Contraintes de performance

Le rendu doit être complet et facile d’utilisation. Le projet doit être réalisé en JAVA, les documents rendus doivent être en Markdown. Le dépôt accessible depuis le compte GitHub du MIAGE.

### Spécifications fonctionnelles

##### Fonctions
* Interface  textuelle et graphique, agréable pour l’utilisateur (optionnel : une interface pour mobile)
* Créer un profil d’utilisateur (identifiant, âge, hauteur, …)
* Enregistrer d’autres mesures dans le temps (poids, sommeil, tour de taille, tour de bras, …), qui sont modifiables en fonction du changement du corps grâce aux entraînements. Il est important de garder l’historique de ces évolutions afin de générer un graphique de progression.
* Enregistrer un exercice, et certaines valeurs associées (temps, répétitions, km, nombre de série, …)
* Enregistrer le travail réellement effectué en comparaison au plan donné par l’application, afin de permettre à l’application d’adapter au mieux le prochain plan d’entrainement.	
* Permettre à l’utilisateur de visualiser ses progrès dans le temps et les mettre en perspective avec les éléments enregistrés (autres exercices ou autres mesures)
* Permettre à l’utilisateur de définir un plan d’entrainement.
* Proposer à l’utilisateur son prochain exercice.
* Proposer à l’utilisateur un plan d’entraînement.


##### Classements des fonctions
	
###### Création de profil 
	
Pour utiliser l’application, un client doit créer un profil. Un profil est caractérisé par un identifiant et un mot de passe. L’utilisateur doit ensuite renseigner plusieurs informations : sa date de naissance afin de connaître son âge, sa hauteur. Pour pouvoir suivre sa progression un utilisateur enregistre son poids, son tour de taille, tour de bras, tour de cuisse, tour de poitrine et tout ceci doit être renseigné à l’instant T ce qui permettra de faire les statistiques. Ces informations peuvent être modifiées.

###### Enregistrement d’un exercice
    
Pour l’enregistrement d’un exercice, les informations à donner seront différentes selon que si c’est un exercice de cardio, ou un exercice de renforcement musculaire. Pour les exercices de cardio, nous aurons par exemple le nombre de kilomètres parcourus en combien de temps. Et pour le renforcement musculaire, le nombre de série et le nombre de répétitions par série.
	
##### Cas d’utilisation 

![alt text][1]

##### Diagramme de classe  

![alt text][2]

##### Maquettes 

Les maquettes permettent de mettre en scène les scénarios suivants : 
*Page Authentification : Un utilisateur se connecte grace à son mot de passe et son login 
*Page d'accueil : grâce au menu, l'utilisateur peux effectuer un nouvel entrainement, enregistrer un exercice de son choix, consulter ses statistiques, et mettre à jour son profil.

![alt text][3]

![alt text][4]

##### Conclusion 

Pour conclure, des éléments seront ajoutés au fur et a mesure afin de completer le projet et l'améliorer avec les idées de chacun des membres du groupe.


  [1]: https://raw.githubusercontent.com/amelamelou/SportDepot/master/DCU%20MusclerSport%20annexe1.png
  [2]: https://raw.githubusercontent.com/amelamelou/SportDepot/master/DC%20MusclezSport%20-%20annexe2.png
  [3]: https://raw.githubusercontent.com/amelamelou/SportDepot/master/annexe3.png
  [4]: https://raw.githubusercontent.com/amelamelou/SportDepot/master/annexe4.png
