# hogwarts-mystery-script-auto-clicker
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/6950/badge)](https://bestpractices.coreinfrastructure.org/projects/6950)

Ce projet a pour but de générer des scripts pour automatiser des tâches pour une journée de jeux. 

Vous aimez ce projet ? Merci de nous [Soutenir](#soutenir) pour l'améliorer!

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
- [hogwarts-mystery-script-auto-clicker](#hogwarts-mystery-script-auto-clicker)
  - [Usage](#usage)
    - [Interface graphique](#interface-graphique)
      - [Prérequis interface graphique](#prérequis-interface-graphique)
      - [Utilisation interface graphique](#utilisation-interface-graphique)
      - [Modification interface graphique](#modification-interface-graphique)
    - [Script](#script)
      - [Prérequis script](#prérequis-script)
      - [Utilisation script](#utilisation-script)
        - [Avec l'interface graphique](#avec-interface-graphique)
        - [Manuelment](#manuelment)
      - [Modification script](#modification-script)
        - [Mode Débug](#mode-débug)
  - [Soutenir](#soutenir)
    - [Parainage](#parainage)
    - [Cagnotte](#cagnotte)
    - [Abonement et donnation](#abonement-et-donnation)
  - [Contact et suport](#contact-et-suport)
---------------------------------------------------------------------------------------------------------------------------------------------------------------
## Usage
### Interface graphique
#### Prérequis interface graphique
1) Systeme d'expoitation sous windows
#### Utilisation interface graphique
1)
    - Lancer le [main.exe](/main.exe "main.exe") à la [racine du projet](https://github.com/JoDylan404/hogwarts-mystery-script-auto-clicker).
    
      ------- ou ---------
    - Lancer [hogwarts-mystery-script-auto-clicker](/hogwarts-mystery-script-auto-clicker)\ [SCRIPT_HOGWARD_MYSTERY.exe](/hogwarts-mystery-script-auto-clicker/SCRIPT_HOGWARD_MYSTERY.exe)
2) Renseigner les lieux et item dans la fenêtre accesible depuit l'onglet lieu et item du menu et selectioner "OK".
3) Selectioner les parametre de l'instance d'execution du scripte dans l'interface graphyque.
3) Cliquer sur "Executer" ![IconeExecuter style="color: #26B260](hogwarts-mystery-script-auto-clicker/img/executer.PNG "IconeExecuter") dans l'interface graphyque.
4) le script s'execute
#### Modification interface graphique
1) Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\ [Data*](hogwarts-mystery-script-auto-clicker/DataScript/) pour les commandes des instances du script à éffectuer et pour afficher la progression : ([DataExec](hogwarts-mystery-script-auto-clicker/DataScript/DataExec), [DataItem](hogwarts-mystery-script-auto-clicker/DataScript/DataItem), [DataLieu](hogwarts-mystery-script-auto-clicker/DataScript/DataLieu), [DataLog](hogwarts-mystery-script-auto-clicker/DataScript/DataLog), [DataProg](hogwarts-mystery-script-auto-clicker/DataScript/DataProg)...)
- Pour demander la creation d'une branche et ajouter votre interface graphique au projet suivez les lien [Contact et suport](#contact-et-suport).

  ajouter votre nom GitHub au fichier modifier exemple : *-nomGitHub.json

  merci de formuler votre demande en utilisant les template dans ".github/ [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE/)" ([bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md), [custom.md](.github/ISSUE_TEMPLATE/custom.md), [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md))

### Script
#### Prérequis script
1) Systeme d'exploitation sous window.
2) Emulateur androide comme Blue Stack.
3) Le jeux Hogwarts Mystery installer sur l'emulateur.
#### Utilisation script
###### Avec interface graphique
  1)
      - Lancer le [main.exe](/main.exe "main.exe") à la [racine du projet](https://github.com/JoDylan404/hogwarts-mystery-script-auto-clicker).
    
        ------- ou ---------
      - Lancer [hogwarts-mystery-script-auto-clicker](/hogwarts-mystery-script-auto-clicker)\ [SCRIPT_HOGWARD_MYSTERY.exe](/hogwarts-mystery-script-auto-clicker/SCRIPT_HOGWARD_MYSTERY.exe)
  2) Renseigner les lieux et item dans la fenêtre accesible depuit l'onglet lieu et item du menu et selectioner "OK".
  3) Selectioner les parametre de l'instance d'execution du scripte dans l'interface graphyque.
  4) Cliquer sur "Executer" ![IconeExecuter color=#26B260](hogwarts-mystery-script-auto-clicker/img/executer.PNG "IconeExecuter") dans l'interface graphyque.
  5) Le script s'execute
###### Manuelment
  1) Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\ [Data*](hogwarts-mystery-script-auto-clicker/DataScript/) pour les commandes des instances du script à éffectuer et pour afficher la progression : ([DataExec](hogwarts-mystery-script-auto-clicker/DataScript/DataExec), [DataItem](hogwarts-mystery-script-auto-clicker/DataScript/DataItem), [DataLieu](hogwarts-mystery-script-auto-clicker/DataScript/DataLieu), [DataLog](hogwarts-mystery-script-auto-clicker/DataScript/DataLog), [DataProg](hogwarts-mystery-script-auto-clicker/DataScript/DataProg)...)
  2) Lancer SourceScript\AMK\ [AMK_v6.3.8.6](SourceScript/AMK/AMK_v6.3.8.6)\ [AutoMouseKey.exe](SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe) et ouvrer le fichier [hogwarts-mystery-script-auto-clicker](hogwarts-mystery-script-auto-clicker)\ [instance.json](hogwarts-mystery-script-auto-clicker/instance.json)
  3) Cliquer sur "PLAY" ![IconePlay](SourceScript/AMK/AMK_v6.3.8.6/images/start.png "IconePlay") ou ["Shif" + "F1"]
  4) Le script s'execute
#### Modification script
1) Lancer SourceScript\AMK\ [AMK_v6.3.8.6](SourceScript/AMK/AMK_v6.3.8.6)\ [AutoMouseKey.exe](SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe) et ouvrer le fichier [hogwarts-mystery-script-auto-clicker](hogwarts-mystery-script-auto-clicker)\ [instance.json](hogwarts-mystery-script-auto-clicker/instance.json)
2) modifier et enregistrer les modification dans [hogwarts-mystery-script-auto-clicker](hogwarts-mystery-script-auto-clicker)
3) Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\ [Data*](hogwarts-mystery-script-auto-clicker/DataScript/) pour les commandes des instances du script à éffectuer et pour afficher la progression : ([DataExec](hogwarts-mystery-script-auto-clicker/DataScript/DataExec), [DataItem](hogwarts-mystery-script-auto-clicker/DataScript/DataItem), [DataLieu](hogwarts-mystery-script-auto-clicker/DataScript/DataLieu), [DataLog](hogwarts-mystery-script-auto-clicker/DataScript/DataLog), [DataProg](hogwarts-mystery-script-auto-clicker/DataScript/DataProg)...)
4) ##### Mode Débug 
    > Aprés modification, vous pouvez executer le script étape par étape en selectionant le mode debug ![IconeDebug](SourceScript/AMK/AMK_v6.3.8.6/images/debug.png "IconeDebug")
    
- Pour demander la creation d'une branche et ajouter votre script au projet suivez les lien [Contact et suport](#contact-et-suport).

  ajouter votre nom GitHub au fichier modifier exemple : *-nomGitHub.json
  
    merci de formuler votre demande en utilisant les template dans ".github/ [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE/)" ([bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md), [custom.md](.github/ISSUE_TEMPLATE/custom.md), [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md))
---------------------------------------------------------------------------------------------------------------------------------------------------------------
### Soutenir
##### Parainage
###### <a href="https://earnapp.com/i/83x6lce">EarnEpp</a> | <a href="https://sweatco.in/hi/jodylan">SweatCoin</a>
##### Cagnotte
###### <a href="https://lydia-app.com/pots?id=hogwarts-mystery-script-auto-clicker">Lydia</a> 0% de taxe | <a href="https://www.leetchi.com/c/script-auto-clicker-hogwarts-mystery">Leetchi</a> 2% de taxe
##### Abonement et donnation
###### <a href="https://www.paypal.com/donate/?hosted_button_id=2LXKW9JGBMFM6">PayPal</a>  Transactions Supérieures ou égales à 10,01 EUR 0,60 % de taxe
## Contact et suport
#### Pour toute participation, question, demande, détaile et contact : 
###### @ comunication : https://www.facebook.com/groups/2049128385357987/permalink/3377153605888785/
###### @ contact : john19911991@hotmail.fr
###### Merci de formuler votre demande en utilisant les template dans ".github/ISSUE_TEMPLATE" si possible.
---
By [JoDylan404](https://github.com/JoDylan404)
