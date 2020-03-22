## Change Set 🔁 deploy 🚀

Projet pour déployer des Change Set avec Visual Studio Code 

### Prérequis 

* [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli)
* [Plugin SFDX eFrontForce](https://www.npmjs.com/package/efrontforce-sfdx-plugin)
* [Visual Studio Code](https://code.visualstudio.com)
* [Salesforce Extension Pack](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode)

### Installation

#### 1️⃣ Installer le Salesforce CLI

Télécharger et installer le [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli)

#### 2️⃣ Installer le plugin eFrontForce

Installer le plugin efrontforce en executant la commande suivante 

`sfdx plugins:install efrontforce-sfdx-plugin`

#### 3️⃣ Installer Visual Studio Code

Télécharger et installer [Visual Studio Code](https://code.visualstudio.com)

#### 4️⃣ Installer le pack d'extensions Salesforce pour Visual Studio Code 

Dans Visual Studio Code cliquer sur l'icône extension et chercher "Salesforce Extension Pack" pour l'installer

### Configuration 

#### 1️⃣ Télécharger ce projet 

Télécherger [ce projet github](https://github.com/eFrontForce/changeset-deploy) sur votre PC et ouvrez le sur Visual Studio Code

#### 2️⃣ Authoriser les orgs

Utiliser Visual Studio Code pour authoriser les orgs que vous allez utiliser pour les déploiements

#### 3️⃣ Configurer le tasks.json

Configurer les orgs source et destination 

### Utilisation 

Vous pouvez lancer la tâche "Change Set 🔁 deploy 🚀" depuis 

* Le menu Visual Studio Code : `Terminal -> Run Task`
* Avec le raccourci clavier : `CTRL + SHIFT + B`

