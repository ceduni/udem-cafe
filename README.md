# Café sans fil

Ce projet pilote vise à améliorer le service des cafés étudiants de l'UdeM. Il consiste à développer une application web complète (backend + frontend) facilitant la recherche de cafés et produits, la prise de commandes et la gestion du menu et de l'inventaire.   
L'application sera accessible à tout membre de l'UdeM (étudiant, employé, professeur, chercheur...).et offrira certains rôles (membre, staff, admin) donnant accès à certaines fonctionnalités.

![Café La Planck](https://admission.umontreal.ca/fileadmin/_processed_/8/1/csm_Cafe_etudiant_960x720_7865dfbe95.jpg)

## Fonctionnalités

## Roles

L'application offrira certains rôles donnant accès à certaines fonctionnalités. 

- **Membre**: Rôle **de base** dans l'application. Avec ce rôle, un utilisateur peut accéder au menu et passer des commandes.  
- **Staff**: Rôle **réservé aux bénévoles** travaillant au café, incluant toutes les actions du rôle membre. Il permet en plus de traiter les commandes, modifier le menu et gérer l'inventaire.  
- **Admin**: Rôle **réservé aux responsables de la maintenance** de l'application, incluant toutes les actions du rôle membre. Il permet de faire toute opération sur la base de données.

## Échéancier

> Début: 1er mai 2023  
> Fin: 11 aout 2023

Le détail de l'échéancier est présenté dans le fichier [**TIMELINE**](TIMELINE.md)


## Infrastructure

L'infrastructure de l'application consiste principalement en une base de données assurant le stockage efficace des données, 
une API traitant les requêtes envoyées par les clients, et une application web permettant aux utilisateurs de visualiser et interagir avec les
données de l'application.

### Base de données

<!-- Le système de base de données envisagées doit être robuste et simple. -->

- Fichiers et style relationnel  
- SQLite

### API

- En Python  
- FastAPI

### Application web

- JavaScript, SPA (single page application)  
- Vuejs

# Documentation 📖


# Organisation 📂

<!-- Les dossiers du répertoire sont organisés comme suit: -->

# Contributeurs ⭐

Si vous êtes interessé à participer au projet, contactez [Louis-Edouard LAFONTANT](mailto:louis.edouard.lafontant@umontreal.ca)