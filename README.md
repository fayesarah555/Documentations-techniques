# Documentations-techniques

## Organisation support de la réalisation professionnelle :
Société OKAYO à Paris, dans le cadre du contrat d’alternance

## Intitulé de la réalisation professionnelle : 
création de requêtes, adaptation et paramétrage de requêtes SQL

## Période de réalisation : 
février à mai 2023	 Lieu : 35, rue du Général Foy, 75008 Paris

## Modalité :
☒  Seul(e)		☒  En équipe

## Compétences travaillées
	- Concevoir et développer une solution applicative
	- Assurer la maintenance corrective ou évolutive d’une solution applicative
	- Gérer les données
  
## Conditions de réalisation (ressources fournies, résultats attendus)
Demandes établies par messagerie ou lors des réunions de travail. Les travaux sont réalisés en connexion avec le système d’information de l’entreprise. Les résultats sont obtenus par exécution des requêtes élaborées, résultats qui sont disponibles sur les postes de travail de l’équipe OKAYO.

## Descriptif de la réalisation professionnelle, y compris les productions réalisées et schémas explicatifs

Adaptation de requêtes existantes et création de nouvelles requêtes dans le cadre de l’interrogation des données d’assurances exploitées par les utilisateurs des logiciels développés par OKAYO.

Les requêtes sont en SQL, et applicables dans les bases de données usuelles des plateformes logicielles OKAYO. Ces requêtes utilisent différentes capacités de jointures, avec application de contraintes ou non, selon les tables impactées.

La pratique adoptée par l’équipe OKAYO décrit les données à exploiter selon un modèle de données caractérisé par des champs ‘in’ et ‘out’, en fonction des propriétés des attributs (champs) des relations (tables).

Le contexte de travail sur les données précise, dans le cadre des pratiques de l’équipe, les natures des données manipulées :

- Obligatoire (valeur obligatoire)
- Default (valeur par défaut si aucune valeur entrée)
- Modifiable (qui peut être modifié)
- Post-saisie (contrôle nécessaire de l’information précédente et de l’information constatée dans le cadre d’un champ ‘in’ et d’un champ ‘out’ associés)
- Contrôle post-saisie (contrôle des champs obligatoires et lancement des scripts associés si besoin)
- Action post-saisie si des champs impactés sont à traiter)
- …

Les traitements sont susceptibles de porter sur un périmètre Web, ou Web Services.

Les interrogations sur les données peuvent porter sur des questions comme :

- extraire les PS actives des contrats RC
- extraire les contrats RC en cours
- extraire les adresses mails des souscripteurs des contrats RC en cours
- lister les AN 2022
- lister les contrats en cours ayant une activité courtier
- lister toutes les garanties souscrites sur un contrat en cours ayant une activité d'agent général (AG)
- calculer le total net, taxe et ttc des garanties souscrites d’un contrat
- lister les garanties souscrites d’un contrat sur 1 seule ligne
- lister les garanties souscrites et non souscrites d’un contrat sur 1 seule ligne
- afficher le numero d’un contrat, l'adresse postale, l’adresse mail du bénéficiaire, son téléphone …
- sortir les 10 derniers devis créés en attente de signature
- …

Quelques exemples associés à la liste partielle présentée ci-dessus sont présentés dans les annexes.

## Annexe 1

<img src = "/images-annexes/Image 14-04-2023 at 01.39.jpg" alt="annexe1"> 


## Annexe 2

<img src="/images-annexes/Image 14-04-2023 at 01.41.jpg" alt="annexe2" >

