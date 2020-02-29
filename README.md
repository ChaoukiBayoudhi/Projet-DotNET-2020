# Projet-DotNET-2020

## Sujet: Organize-Me "نظِمني" 

### Présentation

Dans le but d'aider les gens à mieux s'orgainser, Nous vous demandons d'implementer une application en c# dont les détails sont décrits ci-dessous.
L'application contient deux partie une première exécuter lors du premier lancement de votre application par un utilisateur, la deuxième sera exécuter par la suite, pour chaque lancement selon la configuration precisée par l'utilisateur.
	
Donnons comme noms Setting-Part et Principal-Part respectivement pour la premère et la deuxième partie.


### Contexte de l'application

L'utilisateur est identifié par un login, un password, un nom, un prénom, une date de naissance, un genre, une photon, une fonction, une adresse mail, une adresse (un numéro, une rue et une localisation) et des autres détails comme état civil, nombres des enfants,... 
Toutes ces informations sont à preciser lors de la configuration.
Si l'utilisateur est marié alors des détails supplementaires de son conjoint sont à saisir comme son planning du jours, son état de santé sa fonction,...
Si l'utilisateur a des enfants ou des parents qui vient avec alors il doit introduire des informations comme le niveaux d'étude pour chaque enfant, nom de l'école, la distance entre l'école et sa maison, le planning des études, le panning de ses parents,...
Nous voulons dire par planning une sequence des tâches.
Chaque tâche est caractérisée par son nom, sa date de debut, sa date de fin, une durée de tolérence, son emplacement (où cette tâche sera réalisée), les personnes qui y sont impliquées, une description et un type (normale, urgente, habituelle, inhabituelle).
	
### Besoins


* Avant toute utilisation de l'application (Principal-Part), l'utilisateur doit se connecter via login et password ou en utilisant un de ses comptes Gmail, Facebook ou Tweetter.
	
* Les propriétés d'une tâche peuvent être precisées par voix en dictant respectivement le nom de la propriété et sa valeur.
* L'application affiche à la demande des statistiques comme le taux de réalisation des tâches par jour, par mois ou par année.
* L’utilisateur peut imprimer un planning d’une durée à priciser et/ou le résultat des statistiques.
* L'application doit afficher des notifications pour rappéler le planning du jour suivant ou de tâche urgente ou inhabituelle.
* Utiliser ML.Net pour proposer une amelioration du panning du jour de l’utilisateur

### Points Requis


* Concevoir toutes les *formes* nécessaires.
* Créez une *base du données* pour le projet.
* Implémenter les différentes *fonctionnalités*.
* Toutes les *extensions* seront bien considérées.


### Stack techniques


* Visual Studio 2019,
* L'une des bibliothèques graphiques comme Metro, Bunifu,...
* SQL Server 2017+,
* Sql Server Management Studio (SSMS),
* La bibliothèque Microsoft.Speech.Synthesis
* L'une des bibliothèques suivantes pour la gestion des PDF : Spire.pdf ou iTextSharp ou SharpPDF ou Report.NET
 * SQL Server Reporting Services (SSRS) ou R et
* La bibliothèque ML.NET.

Hard Luck
