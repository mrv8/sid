# Architecture des sytèmes d'information (TD)

:loudspeaker: Mise en place de 3 types d'architecture avec un exemple simple en nodejs :

* Service web soap
* API RESTFULL (openapi)
* Serverless (serverless framework)

Une fonction "hello world" avec un paramètre "name", retourne Hello {{ name }}"

:point_right: Pourquoi nodejs ? https://insights.stackoverflow.com/survey/2018#technology

Objectifs : 

- Réaliser les implémentations du service web, de l'API REST et de la fonction serverless avec les instructions communiquées.

- Tester et valider le comportement de chaque.

- Identifier les avantages et les inconvénients (Compréhesion & rapidité du dev, taille du code source, temps de réponse, poid de la réponse...)

## Setup

### Environnement de travail 

#### Mac OSX

##### Installation Homebrew

https://brew.sh/

##### Installation outils

* Nodejs / Mongodb : brew install node mongodb
* Postman : https://learning.getpostman.com/docs/postman/launching_postman/installation_and_updates/#macos-installation
* Vscode : https://code.visualstudio.com/docs/setup/mac
* Robot 3T : https://studio3t.com/download-thank-you/?OS=osx

#### Ubuntu

##### Installation nodejs

sudo apt install curl
curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -
sudo apt install nodejs


##### Installation outils

* Mongodb : https://hevodata.com/blog/install-mongodb-on-ubuntu/
* Postman : https://learning.getpostman.com/docs/postman/launching_postman/installation_and_updates/#linux-installation
* Vscode : https://code.visualstudio.com/docs/setup/linux
* Robot 3T : https://studio3t.com/download-thank-you/?OS=x64

#### Windows

##### Installation chocolatey

https://chocolatey.org/docs/installation

##### Installation outils

choco install postman nodejs.install mongodb.install robo3t.install vscode hyper --confirm;
Homebrew
Homebrew
The Missing Package Manager for macOS (or Linux).

Running Visual Studio Code on macOS
Get Visual Studio Code up and running on Mac (macOS).

Studio 3T
Thank you for downloading Studio 3T! | Studio 3T
Stack Overflow
Stack Overflow Developer Survey 2018
Get insights on the world’s developers from the largest and most comprehensive survey ever. Demographics. Technologies. Salaries. Career satisfaction.
