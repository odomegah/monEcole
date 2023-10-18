# monEcole

[Voir l'application](https://monecole-se2r.onrender.com)

**monEcole** est une application minimaliste, developpé avec les technologies suivantes:
 1. NodeJS
 1. Express
 1. EJS
 1. MongoDB

 **monEcole** est une application permetant de gerer une ecole en intergrant des fonctionnaliteés tel que:
 1. un formulaire d'inscription
 1. un formulaire de connection
 1. un tableau de bord
 1. un annuaire de catalogue
 1. un emploi du temps pour chaque etudiant connecté

 ## Pourquoi avoir choisi ces technologie ?
J'ai choisi ces technologies:

_D'abord,_
la technologie **nodeJS** permet une implementation **d'application-orienteé API et SSR** sans avoir besoin d'une **librairie ou framework SPA**.
Aussi, si l'application demande une maintenance evolutive orienteé **Mobile App**, soit en **application mobile native ou PWA**, l'evolution sera encore plus maintenable.

_Ensuite,_
**EJS** etant un moteur de template parmis tant d'autre, ma permit d'avoir une **application SSR** assez facilement.

_Enfin,_
J'ai choisi un base de donnee de type ***noSQL*** pour sa rapidité en **lecture et ecriture** comparé a un ***SQL***. 
**MongoDB** a ete un choix arbitraire. Pour ce projet miniliste, j'avais opté pour **firebase** mais le choix s'est retrouvé sur MongoDB.

## Style et Icone
A l'exception du **google font**, **monEcole** a été stylé en ***CSS*** native sans ajout de librairie CSS.
Les icones sont des **svg** et sont intergrés par code source et non par fichier.

## L'authentification
Apres chaque _inscription et connection_, l'etudiant est authentifié et redirigé dans son espace.
J'ai choisi une authentification basée sur les sessions, parcequ'une application orientée rendu-coté-serveur doit gerer une session par le bien des cookies coté-client ce qui nous donne une bonne gestion de la session a chaque requette envoyée.

## Le tableau de bord
**OdoDash** est un dashboard developpé par moi meme et disponible gratuitement en version differente.
Voir OdoDash sur github [OdoDash](https://github.com/odomegah/OdoDash)



## Odomegah
:link: [odomegah](https:odomegah.com)