# hogwarts-mystery-script-auto-clicker
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/6950/badge)](https://bestpractices.coreinfrastructure.org/projects/6950)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Ce projet a pour but de générer des scripts pour automatiser des tâches pour une journée de jeux.

Pour toute participation, question, demande (ajout de licence commerciale...), détaile et contact :  
[Contact et suport](#contact-et-suport)

Ce(tte) œuvre est mise à disposition selon les termes de la :  
> <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Licence Creative Commons Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 4.0 International</a>.
> [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
> 1) Avec réstriction de la distribution du code source sous :  
> [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License: GPL v3](https://img.shields.io/badge/%20License%20compatiblility-CC%20BY--NC--SA%204.0%2FGPLv3--green-SUCCESS)](https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses) [ [License compatiblility Wiki : CC BY-NC-SA 4.0/GPLv3](https://wiki.creativecommons.org/wiki/ShareAlike_compatibility:_GPLv3) ]  
> 2) Avec réstriction pour diffusion de Modification = sans frai, valider et ajouter au dépot.

Vous aimez ce projet ? Merci de nous [Soutenir](#soutenir) pour l'améliorer!

---------------------------------------------------------------------------------------------------------------------------------------------------------------
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
    - [Parainage](#parainage--earnapp--sweatcoin)
    - [Cagnotte](#cagnotte--lydia-0-de-taxe--leetchi-2-de-taxe)
    - [Abonement et donnation](#abonement-et-donnation--paypal--transactions-supérieures-ou-égales-à-1001-eur-060--de-taxe)
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

- pour toute modification :
  - Les fichier source des .exe qui sont a disposision ce trouve dans [hogwarts-mystery-script-auto-clicker/CodeSourceScript/*.json](hogwarts-mystery-script-auto-clicker/CodeSourceScript)
  - Les fichier sourse non compiler en .exe se trouve dans [hogwarts-mystery-script-auto-clicker/*.json](hogwarts-mystery-script-auto-clicker/)
  - Pour demander la creation d'une branche et ajouter vos modification au projet suivez les lien [Contact et suport](#contact-et-suport).  
  - Ajouter votre nom GitHub au fichier modifier exemple : *-nomGitHub.json

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
  4) Cliquer sur "Executer" ![IconeExecuter](hogwarts-mystery-script-auto-clicker/img/executer.PNG "IconeExecuter") dans l'interface graphyque.
  5) Le script s'execute
###### Manuelment
  1) Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\ [Data*](hogwarts-mystery-script-auto-clicker/DataScript/) pour les commandes des instances du script à éffectuer et pour afficher la progression : ([DataExec](hogwarts-mystery-script-auto-clicker/DataScript/DataExec), [DataItem](hogwarts-mystery-script-auto-clicker/DataScript/DataItem), [DataLieu](hogwarts-mystery-script-auto-clicker/DataScript/DataLieu), [DataLog](hogwarts-mystery-script-auto-clicker/DataScript/DataLog), [DataProg](hogwarts-mystery-script-auto-clicker/DataScript/DataProg)...)
  2) Lancer SourceScript\AMK\ [AMK_v6.3.8.6](SourceScript/AMK/AMK_v6.3.8.6)\ [AutoMouseKey.exe](SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe) et ouvrer le fichier [hogwarts-mystery-script-auto-clicker](hogwarts-mystery-script-auto-clicker)\ [instance.json](hogwarts-mystery-script-auto-clicker/instance.json)
  3) Cliquer sur "PLAY" ![IconePlay](SourceScript/AMK/AMK_v6.3.8.6/images/start.png "IconePlay") ou ["Shif" + "F1"]
  4) Le script s'execute
#### Modification script
1) Lancer SourceScript\AMK\ [AMK_v6.3.8.6](SourceScript/AMK/AMK_v6.3.8.6)\ [AutoMouseKey.exe](SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe) et ouvrer le fichier [hogwarts-mystery-script-auto-clicker](hogwarts-mystery-script-auto-clicker)\ [instance.json](hogwarts-mystery-script-auto-clicker/instance.json)
2) Modifier et enregistrer [![IconeSave](SourceScript/AMK/AMK_v6.3.8.6/images/save.png "IconeSave")ou "Ctrl + S"] les modification dans [hogwarts-mystery-script-auto-clicker](hogwarts-mystery-script-auto-clicker)
3) Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\ [Data*](hogwarts-mystery-script-auto-clicker/DataScript/) pour les commandes des instances du script à éffectuer et pour afficher la progression : ([DataExec](hogwarts-mystery-script-auto-clicker/DataScript/DataExec), [DataItem](hogwarts-mystery-script-auto-clicker/DataScript/DataItem), [DataLieu](hogwarts-mystery-script-auto-clicker/DataScript/DataLieu), [DataLog](hogwarts-mystery-script-auto-clicker/DataScript/DataLog), [DataProg](hogwarts-mystery-script-auto-clicker/DataScript/DataProg)...)
4) ##### Mode Débug 
    > Aprés modification, vous pouvez executer le script étape par étape en selectionant le mode debug ![IconeDebug](SourceScript/AMK/AMK_v6.3.8.6/images/debug.png "IconeDebug")
    
- pour toute modification :
  - Les fichier source des .exe qui sont a disposision ce trouve dans [hogwarts-mystery-script-auto-clicker/CodeSourceScript/*.json](hogwarts-mystery-script-auto-clicker/CodeSourceScript)
  - Les fichier sourse non compiler en .exe se trouve dans [hogwarts-mystery-script-auto-clicker/*.json](hogwarts-mystery-script-auto-clicker/)
  - Pour demander la creation d'une branche et ajouter vos modification au projet suivez les lien [Contact et suport](#contact-et-suport).  
  - Ajouter votre nom GitHub au fichier modifier exemple : *-nomGitHub.json

    merci de formuler votre demande en utilisant les template dans ".github/ [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE/)" ([bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md), [custom.md](.github/ISSUE_TEMPLATE/custom.md), [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md))
---------------------------------------------------------------------------------------------------------------------------------------------------------------
## Soutenir
> ##### Parainage : <a href="https://earnapp.com/i/83x6lce">EarnApp</a> | <a href="https://sweatco.in/hi/jodylan">SweatCoin</a>
> ##### Cagnotte : <a href="https://lydia-app.com/pots?id=hogwarts-mystery-script-auto-clicker">Lydia</a> 0% de taxe | <a href="https://www.leetchi.com/c/script-auto-clicker-hogwarts-mystery">Leetchi</a> 2% de taxe
> ##### Abonement et donnation : <a href="https://www.paypal.com/donate/?hosted_button_id=2LXKW9JGBMFM6">PayPal</a>  Transactions Supérieures ou égales à 10,01 EUR 0,60 % de taxe
## Contact et suport
#### Pour toute participation, question, demande, détaile et contact : 
> ###### Facebook : https://www.facebook.com/groups/2049128385357987/permalink/3377153605888785/
> ###### Reddit : https://www.reddit.com/r/HogwartsMysteryHP/comments/110psh4/script_auto_clicker_for_hogwarts_mystery/
> ###### Email : john19911991@hotmail.fr
###### Merci de formuler votre demande en utilisant si possible les template dans : ".github/ [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE/)" ([bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md), [custom.md](.github/ISSUE_TEMPLATE/custom.md), [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md))".
This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License :  
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
> 1) Avec réstriction de la distribution du code source sous  
> [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License: GPL v3](https://img.shields.io/badge/%20License%20compatiblility-CC%20BY--NC--SA%204.0%2FGPLv3--green-SUCCESS)](https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses) [ [License compatiblility Wiki : CC BY-NC-SA 4.0/GPLv3](https://wiki.creativecommons.org/wiki/ShareAlike_compatibility:_GPLv3) ]  
> 2) Avec réstriction pour diffusion de Modification = sans frai, valider et ajouter au dépot.   

  * To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
---

By [JoDylan404](https://github.com/JoDylan404)  

<details id=1>
<summary><h2>Usage</h2> : </summary>
  <details id=11>
  <summary><h3>Interface graphique</h3> : </summary>
    <details id=111>
    <summary><h4>Prérequis interface graphique</h4> : </summary>
    1) Systeme d'expoitation sous windows
    </details>
    <details id=112>
    <summary><h4>Utilisation interface graphique</h4> : </summary>
    <ol>
      <li>
         <ul>
          <li>Lancer le <a rel="main.exe" href="/main.exe">main.exe</a> à la 
            <a rel="racine du projet" href="https://github.com/JoDylan404/hogwarts-mystery-script-auto-clicker">racine du projet</a>.</li>
           ------- ou ---------<br/>
          </li>
          <li>Lancer 
            <a rel="/hogwarts-mystery-script-auto-clicker" href="/hogwarts-mystery-script-auto-clicker">hogwarts-mystery-script-auto-clicker</a> \
            <a rel="/hogwarts-mystery-script-auto-clicker/SCRIPT_HOGWARD_MYSTERY.exe" 
               href="/hogwarts-mystery-script-auto-clicker/SCRIPT_HOGWARD_MYSTERY.exe">SCRIPT_HOGWARD_MYSTERY.exe</a>.
          </li>
        </ul>
      <li>
        Renseigner les lieux et item dans la fenêtre accesible depuit l'onglet lieu et item du menu et selectioner "OK".
      <li>
        Selectioner les parametre de l'instance d'execution du scripte dans l'interface graphyque.
      <li>
        Cliquer sur "Executer"  <img src="hogwarts-mystery-script-auto-clicker/img/executer.PNG" alt="IconeExecuter" title="IconeExecuter">  dans l'interface graphyque.
      <li>
        Le script s'execute
      </li>
    </ol>
    </details>
    <details id=113>
    <summary><h4>Modification interface graphique</h4> : </summary>
    <ol>
      <li>
        Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\<a rel="hogwarts-mystery-script-auto-clicker/DataScript/" href="hogwarts-mystery-script-auto-clicker/DataScript/">Data*</a> pour les commandes des instances du script à éffectuer et pour afficher la progression : <br/>
<a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataExec" href="hogwarts-mystery-script-auto-clicker/DataScript/DataExec">DataExec</a>, 
<a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataItem" href="hogwarts-mystery-script-auto-clicker/DataScript/DataItem">DataItem</a>, 
<a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataLieu" href="hogwarts-mystery-script-auto-clicker/DataScript/DataLieu">DataLieu</a>, 
<a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataLog" href="hogwarts-mystery-script-auto-clicker/DataScript/DataLog">DataLog</a>, 
<a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataProg" href="hogwarts-mystery-script-auto-clicker/DataScript/DataProg">DataProg</a>...)
      </li>
    </ol>
    <ul>
      <li>
        Pour demander la creation d'une branche et ajouter votre interface graphique au projet suivez les lien 
        <a rel="Contact et suport" href="#contact-et-suport">Contact et suport</a>.<br/>
        Ajouter votre nom GitHub au fichier modifier exemple : *-nomGitHub.json <br/>
        Merci de formuler votre demande en utilisant les template dans ".github/<a rel="ISSUE_TEMPLATE" href=".github/ISSUE_TEMPLATE/">ISSUE_TEMPLATE</a>"<br/>
        ( <a rel="bug_report.md" href=".github/ISSUE_TEMPLATE/bug_report.md">bug_report.md</a>, <a rel="custom.md" href=".github/ISSUE_TEMPLATE/custom.md">custom.md</a>, <a rel="feature_request.md" href=".github/ISSUE_TEMPLATE/feature_request.md">feature_request.md</a> )
      </li>
    </ul>
    </details>
  </details>
  <details id=12>
  <summary><h3>Script</h3> : </summary>
    <details id=121>
    <summary><h4>Prérequis script</h4> : </summary>
      <ol>
        <li>
          Systeme d'exploitation sous window.
        </li>
        <li>
          Emulateur androide comme Blue Stack.
        </li>
        <li>
          Le jeux Hogwarts Mystery installer sur l'emulateur.
        </li>
      </ol>
    </details>
    <details id=122>
    <summary><h4>Utilisation script</h4> : </summary>
      <details id=1221>
      <summary><h5>Avec interface graphique</h5> : </summary>
        <ol>
          <li>
            <ul>
              <li>Lancer le <a rel="main.exe" href="/main.exe">main.exe</a> à la 
                    <a rel="racine du projet" href="https://github.com/JoDylan404/hogwarts-mystery-script-auto-clicker">racine du projet</a>.</li>
                  ------- ou ---------<br/>
              </li>
              <li>Lancer 
                  <a rel="/hogwarts-mystery-script-auto-clicker" href="/hogwarts-mystery-script-auto-clicker">hogwarts-mystery-script-auto-clicker</a> \
                  <a rel="/hogwarts-mystery-script-auto-clicker/SCRIPT_HOGWARD_MYSTERY.exe" 
                  href="/hogwarts-mystery-script-auto-clicker/SCRIPT_HOGWARD_MYSTERY.exe">SCRIPT_HOGWARD_MYSTERY.exe</a>.
              </li>
            </ul>
          <li>
        Renseigner les lieux et item dans la fenêtre accesible depuit l'onglet lieu et item du menu et selectioner "OK".
      <li>
        Selectioner les parametre de l'instance d'execution du scripte dans l'interface graphyque.
      <li>
        Cliquer sur "Executer"  <img src="hogwarts-mystery-script-auto-clicker/img/executer.PNG" alt="IconeExecuter" title="IconeExecuter">  dans l'interface graphyque.
      <li>
        Le script s'execute
      </li>
    </ol>
      </details>
      <details id=1222>
      <summary><h5>Manuelment</h5> : </summary>
        <ol>
          <li>
            Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\
            <a rel="hogwarts-mystery-script-auto-clicker/DataScript/" href="hogwarts-mystery-script-auto-clicker/DataScript/">Data*</a> 
            pour les commandes des instances du script à éffectuer et pour afficher la progression : (
            <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataExec" href="hogwarts-mystery-script-auto-clicker/DataScript/DataExec">DataExec</a>, 
            <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataItem" href="hogwarts-mystery-script-auto-clicker/DataScript/DataItem">DataItem</a>, 
            <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataLieu" href="hogwarts-mystery-script-auto-clicker/DataScript/DataLieu">DataLieu</a>, 
            <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataLog" href="hogwarts-mystery-script-auto-clicker/DataScript/DataLog">DataLog</a>, 
            <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataProg" href="hogwarts-mystery-script-auto-clicker/DataScript/DataProg">DataProg</a>...)<br/>
          </li>
          <li>
            Lancer SourceScript\AMK\ 
            <a rel="SourceScript/AMK/AMK_v6.3.8.6" href="SourceScript/AMK/AMK_v6.3.8.6">AMK_v6.3.8.6</a>\
            <a rel="SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe" href="SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe">AutoMouseKey.exe</a> 
            et ouvrer le fichier 
            <a rel="hogwarts-mystery-script-auto-clicker" href="hogwarts-mystery-script-auto-clicker">hogwarts-mystery-script-auto-clicker</a>\
            <a rel="hogwarts-mystery-script-auto-clicker/instance.json" href="hogwarts-mystery-script-auto-clicker/instance.json">instance.json</a>
          </li>
          <li>
            Cliquer sur "PLAY" <img src="SourceScript/AMK/AMK_v6.3.8.6/images/start.png" alt="IconePlay" title="IconePlay"> ou ["Shif" + "F1"]
          </li>
          <li>
            Le script s'execute
          </li>
        </ol>
      </details>
    </details>
    <details id=123>
    <summary><h4>Modification script</h4> : </summary>
      <ol>
        <li>
            Lancer SourceScript\AMK\ 
            <a rel="SourceScript/AMK/AMK_v6.3.8.6" href="SourceScript/AMK/AMK_v6.3.8.6">AMK_v6.3.8.6</a>\
            <a rel="SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe" href="SourceScript/AMK/AMK_v6.3.8.6/AutoMouseKey.exe">AutoMouseKey.exe</a> 
            et ouvrer le fichier 
            <a rel="hogwarts-mystery-script-auto-clicker" href="hogwarts-mystery-script-auto-clicker">hogwarts-mystery-script-auto-clicker</a>\
            <a rel="hogwarts-mystery-script-auto-clicker/instance.json" href="hogwarts-mystery-script-auto-clicker/instance.json">instance.json</a>
        </li>
        <li>
          Modifier et enregistrer [<img src="SourceScript/AMK/AMK_v6.3.8.6/images/save.png" alt="IconeSave" title="IconeSave"> ou "Ctrl + S"] les modification dans 
          <a rel="hogwarts-mystery-script-auto-clicker" href="hogwarts-mystery-script-auto-clicker">hogwarts-mystery-script-auto-clicker</a>
        </li>
        <li>
          Utiliser les fichier hogwarts-mystery-script-auto-clicker\DataScript\
          <a rel="hogwarts-mystery-script-auto-clicker/DataScript/" href="hogwarts-mystery-script-auto-clicker/DataScript/">Data*</a> 
          pour les commandes des instances du script à éffectuer et pour afficher la progression : (
          <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataExec" href="hogwarts-mystery-script-auto-clicker/DataScript/DataExec">DataExec</a>, 
          <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataItem" href="hogwarts-mystery-script-auto-clicker/DataScript/DataItem">DataItem</a>, 
          <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataLieu" href="hogwarts-mystery-script-auto-clicker/DataScript/DataLieu">DataLieu</a>, 
          <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataLog" href="hogwarts-mystery-script-auto-clicker/DataScript/DataLog">DataLog</a>, 
          <a rel="hogwarts-mystery-script-auto-clicker/DataScript/DataProg" href="hogwarts-mystery-script-auto-clicker/DataScript/DataProg">DataProg</a>...)<br/>
        </li>
      </ol>
      <details id=1231>
      <summary><h5>Mode Débug</h5> : </summary>
            Aprés modification, vous pouvez executer le script étape par étape en selectionant le mode debug 
        <img src="SourceScript/AMK/AMK_v6.3.8.6/images/debug.png" alt="IconeDebug" title="IconeDebug">
    
- Pour demander la creation d'une branche et ajouter votre script au projet suivez les lien [Contact et suport](#contact-et-suport).

  ajouter votre nom GitHub au fichier modifier exemple : *-nomGitHub.json
  
    merci de formuler votre demande en utilisant les template dans ".github/ [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE/)" ([bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md), [custom.md](.github/ISSUE_TEMPLATE/custom.md), [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md))
      </details>
    </details>
  </details>
</details>
<details id=2>
<summary><h2>Soutenir</h2> : </summary>
  Parainage : <a href="https://earnapp.com/i/83x6lce">EarnApp</a> | <a href="https://sweatco.in/hi/jodylan">SweatCoin</a><br/>
  Cagnotte : <a href="https://lydia-app.com/pots?id=hogwarts-mystery-script-auto-clicker">Lydia</a> 0% de taxe | <a href="https://www.leetchi.com/c/script-auto-clicker-hogwarts-mystery">Leetchi</a> 2% de taxe<br/>
  Abonement et donnation : <a href="https://www.paypal.com/donate/?hosted_button_id=2LXKW9JGBMFM6">PayPal</a>  Transactions Supérieures ou égales à 10,01 EUR 0,60 % de taxe<br/>
</details>
<details id=3>
<summary><h2>Contact et suport</h2> : </summary>
  Pour toute participation, question, demande, détaile et contact : <br/>
  <ul>
    <li>
      Facebook : https://www.facebook.com/groups/2049128385357987/permalink/3377153605888785/
    </li>
    <li>
      Reddit : https://www.reddit.com/r/HogwartsMysteryHP/comments/110psh4/script_auto_clicker_for_hogwarts_mystery/
    </li>
    <li>
      Email : john19911991@hotmail.fr
    </li>
  </ul>
Merci de formuler votre demande en utilisant les template dans ".github/<a rel="ISSUE_TEMPLATE" href=".github/ISSUE_TEMPLATE/">ISSUE_TEMPLATE</a>"<br/>
        ( <a rel="bug_report.md" href=".github/ISSUE_TEMPLATE/bug_report.md">bug_report.md</a>, <a rel="custom.md" href=".github/ISSUE_TEMPLATE/custom.md">custom.md</a>, <a rel="feature_request.md" href=".github/ISSUE_TEMPLATE/feature_request.md">feature_request.md</a> )<br/>
  <br/>
  This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License : <br/>
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img src="https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg" alt="License: CC BY-NC-SA 4.0" title="License: CC BY-NC-SA 4.0"></a>
  <ol>
    <li>
      Avec réstriction de la distribution du code source sous : <br/>
      <a href="https://www.gnu.org/licenses/gpl-3.0.html"><img src="https://img.shields.io/badge/License-GPLv3-blue.svg" alt="License-GPLv3" title="License-GPLv3"></a>
      <a href="https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses"><img src="https://img.shields.io/badge/%20License%20compatiblility-CC%20BY--NC--SA%204.0%2FGPLv3--green-SUCCESS" alt="compatible-licenses" title="compatible-licenses"></a>
      <a rel="License compatiblility Wiki : CC BY-NC-SA 4.0/GPLv3" href="https://wiki.creativecommons.org/wiki/ShareAlike_compatibility:_GPLv3">License compatiblility Wiki : CC BY-NC-SA 4.0/GPLv3</a>  
    </li>
    <li>
      Avec réstriction pour diffusion de Modification = sans frai, valider et ajouter au dépot.<br/>
    </li>
  </ol>
  * To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.<br/>
---

By [JoDylan404](https://github.com/JoDylan404)  
</details>
