# Projet de Gestion de Salles et Machines
Ce projet Java a été conçu pour gérer des salles et des machines à l'aide d'une interface graphique Swing. Il utilise Hibernate pour la couche de persistance des données et RMI (Remote Method Invocation) pour la communication client-serveur. La base de données est gérée à l'aide de MySQL.
Ce projet pourrait être utilisé pour gérer les salles de classe, les laboratoires informatiques et les équipements connexes dans un établissement d'enseignement ou entreprises etc.

## Technologies Utilisées

  ### *Java Swing : 
Utilisé pour la création de l'interface utilisateur graphique, offrant une expérience utilisateur conviviale et interactive.

  ### *Hibernate : 
Utilisé comme framework de persistance pour faciliter le mapping objet-relationnel avec la base de données MySQL, simplifiant ainsi les opérations de stockage et de récupération des données.

  ### *MySQL :
Utilisé comme système de gestion de base de données relationnelle pour stocker de manière fiable et sécurisée les informations relatives aux salles, aux machines et à d'autres entités pertinentes du système.

  ### *RMI (Remote Method Invocation) :
Utilisé pour permettre la communication entre le serveur et les clients de manière transparente, permettant ainsi l'accès et la manipulation distants des données et des   
fonctionnalités du système.

## Fonctionnalités
L'application fourinit trois fonctionalites principales:

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/9cad5c3c-ec47-4a3d-9a8f-0179a997a7a4)

### 1.Gestion des Machines
  #### *Ajout de Machine :
L'utilisateur peut ajouter de nouvelles machines en spécifiant les détails pertinents nécessaire.

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/f1098839-c108-4ca6-afc3-a0fabea3e57f)

  #### *Modification des Machines :
Les détails des machines existantes peuvent être modifiés en cas de changements requis, tels que la mise à jour du prix ou du salle.

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/072a20f3-369b-438f-8a92-6c604e9dfafc)

  #### *Suppression de machine :
Les machines inutilisées ou obsolètes peuvent être supprimées du système en toute sécurité.

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/e9157f54-9f96-42a7-94b9-d01bf2ccbd13)



### 2.Gestion des Salles
  #### *Ajout de Salle :
L'utilisateur peut ajouter de nouvelles salles en spécifiant les détails pertinents nécessaire.

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/363432e6-9a3b-40e3-aeab-ddc168c08c3f)

  #### *Modification des Salles :
Les détails des salles existantes peuvent être modifiés en cas de changements requis, tels que la mise à jour code.

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/465baaf2-8dcd-49ce-b0a5-6d89d7e1202c)

  #### *Suppression de machine :
Les salles inutilisées ou obsolètes peuvent être supprimées du système en toute sécurité.Si et seulment si la salle ne contient aucun machine. 

  ###### *En Cas de Salle Contient des machines.
  
  ![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/403b5403-6920-489a-b2a1-63c45e42c64e)

   ###### *En Cas de Salle ne Contient aucun des machines.

   ![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/442974d2-707b-4eda-9fd2-47c40e3126fe)


### 3.Afficher les Machines de chaque salle

L'utilisateur peut voir les machines actuellement associées à chaque salle, ce qui facilite la surveillance et la gestion efficace des équipements dans chaque salle.

![image](https://github.com/ismail-sorhrani/TP-RMI/assets/125312216/e91d92e1-8a88-4423-ad40-52531a62e472)

## Installation

Cloner le dépôt. <br />
Assurez-vous d'avoir les versions compatibles de Java, Hibernate et MySQL installées.

## Configuration 

Configurer les détails de la base de données dans le fichier hibernate.cfg.xml. <br />
Configurer les paramètres RMI dans le fichier de configuration approprié. 

## Utilisation 

Exécutez le serveur RMI avant de lancer l'application client. <br />
Suivez les instructions à l'écran pour gérer les salles et les machines.



