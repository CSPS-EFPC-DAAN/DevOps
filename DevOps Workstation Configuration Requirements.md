<img align="right" width="300" src="https://upload.wikimedia.org/wikipedia/commons/8/8f/Ken_Thompson_%28sitting%29_and_Dennis_Ritchie_at_PDP-11_%282876612463%29.jpg">

(le français suit)

# DevOps Workstation Configuration Requirements
Your mission should you choose to accept it, will be to build an awesome development workstation! You will use this workstation to complete your work as part of the DevOps cohort.

Your fellow students, facilitators and Digital Academy folks are here to help you via the #devops Slack channel (https://csps-efpc-daan.slack.com/messages/CG1DFTBSP)

## Hardware
We can provide you with the an HP EliteBook 830 G5 laptop, which will be yours for the duration of the course. They have the  the following specs:
- Intel i5-8350U @ 1.7GHz
- 16GB memory
- 250GB SSD drive
- 13" screen

Alternatively you can use your own laptop as long as you have full admin rights and it's an off network device (not connected to any Government of Canada network). This can be something your department provided you or your own personal device.

Contact Cory Dignard to let us know what you plan on doing. Cory.Dignard@canada.ca or on csps-efpc-daan.slack.com.

## Operating System
The HP laptops we provide come pre-installed with Windows 10 Pro. You can choose to use this, or re-image with Linux, such as Ubuntu (https://www.ubuntu.com/download/desktop). If you provide your own device it can be Linux, Windows or macOS.

## Software
Regardless of your device or OS, you need to have the following software installed

| Software | Windows | Linux | macOS |
| ------ | :------: | :------: | :------: |
| Visual Studio Code | [VS Code](https://code.visualstudio.com/) | [VS Code](https://code.visualstudio.com/) | [VS Code](https://code.visualstudio.com/)|
| Git | [Git for Windows](https://git-scm.com/download/win) | [Git for linux](https://git-scm.com/download/linux) | [Git for Mac](https://git-scm.com/download/mac) |
| Docker Community Edition| [Docker CE for Windows](https://docs.docker.com/docker-for-windows/install/) | [Docker CE for Ubuntu](https://docs.docker.com/install/linux/docker-ce/debian/) | [Docker CE for Mac](https://docs.docker.com/docker-for-mac/install/) |
| Node LTS (10.15.*)| [Instructions for Windows](https://nodejs.org/en/download/package-manager/#windows) | [Instructions for Ubuntu & Debian based distros](https://github.com/nodesource/distributions/blob/master/README.md#debinstall) | [Instructions for macOS](https://nodejs.org/en/download/package-manager/#macos) |
| Azure CLI | [Instructions for Windows](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest) | [Instructions for Ubuntu & Debian](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest) | [Instructions for macOS](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest) |
| Anaconda | [Anaconda Distribution](https://www.anaconda.com/distribution/) | [Anaconda Distribution](https://www.anaconda.com/distribution/) | [Anaconda Distribution](https://www.anaconda.com/distribution/) |


The following GitHub repo's from your very own GC colleages have scripts that may be a good place to start to help automate things
- Linux: https://github.com/esdc-devx/dev-laptop
- Mac: https://github.com/cds-snc/laptop
- Windows: https://github.com/CSPS-EFPC-DAAN/Data-AI-Workstation-Config

Fix Right Click Touchpad not working on Ubuntu 18.04: Run this command and follow instructions [here](https://itsfoss.com/fix-right-click-touchpad-ubuntu/)
```sh
sudo apt install gnome-tweaks
```

--------------------------------------------------

# Exigences relatives à la configuration du poste de travail DevOps
Votre mission, si vous l’acceptez, consiste à bâtir un poste de travail dans l’environnement de développement! Vous utiliserez ce poste de travail pour effectuer votre travail en tant que membre de la cohorte de DevOps.

Les autres étudiants, les formateurs et le personnel de l’École numérique sont là pour vous aider par le biais du canal Slack #devops (https://csps-efpc-daan.slack.com/messages/CG1DFTBSP).


## Matériel
Nous pouvons vous fournir un ordinateur portatif HP EliteBook 830 G5, qui sera à vous pour la durée du cours. Voici ses spécifications :
*	Intel i5 8350U 1,7 GHz
* Mémoire vive 16 Go
*	Disque SSD 250 Go
*	Écran de 13 po

Vous pouvez également utiliser votre propre ordinateur portatif, tant que vous avez tous les droits administratifs et qu’il est hors réseau (c’est-à-dire qu’il n’est pas connecté à aucun réseau du gouvernement du Canada). Il peut s’agit d’un appareil qui vous a été fourni par votre ministère ou encore d’un appareil personnel.
Communiquez avec Cory Dignard pour nous informer de l’appareil que vous prévoyez utiliser à l’adresse [Cory.Dignard@canada.ca](mailto:cory.dignard@canada.ca) ou encore sur [csps-efpc-daan.slack.com](csps-efpc-daan.slack.com).


## Système d’exploitation
Windows 10 Pro est préinstallé sur les ordinateurs portatifs HP que nous fournissons. Vous pouvez l’utiliser tel quel ou utiliser une image Linux comme Ubuntu (https://www.ubuntu.com/download/desktop). Si vous fournissez votre propre appareil, le SE peut être une variante Linux, Windows ou macOS.

## Logiciel
Peu importe votre appareil ou votre SE, les logiciels suivants doivent être installés (en anglais seulement)

| Logiciel | Windows | Linux | macOS |
| ------ | :------: | :------: | :------: |
| Visual Studio Code | [VS Code](https://code.visualstudio.com/) | [VS Code](https://code.visualstudio.com/) | [VS Code](https://code.visualstudio.com/)|
| Git | [Git pour Windows](https://git-scm.com/download/win) | [Git pour linux](https://git-scm.com/download/linux) | [Git pour Mac](https://git-scm.com/download/mac) |
| Docker Community Edition| [Docker CE pour Windows](https://docs.docker.com/docker-for-windows/install/) | [Docker CE pour Ubuntu](https://docs.docker.com/install/linux/docker-ce/debian/) | [Docker CE pour Mac](https://docs.docker.com/docker-for-mac/install/) |
| Node LTS (10.15.*)| [Instructions pour Windows](https://nodejs.org/en/download/package-manager/#windows) | [Instructions pour les distributions basées sur Ubuntu et Debian](https://github.com/nodesource/distributions/blob/master/README.md#debinstall) | [Instructions pour macOS](https://nodejs.org/en/download/package-manager/#macos) |
| Azure CLI | [Instructions pour Windows](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest) | [Instructions pour Ubuntu & Debian](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest) | [Instructions pour macOS](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest) |
| Anaconda | [Distribution Anaconda](https://www.anaconda.com/distribution/) | [Distribution Anaconda ](https://www.anaconda.com/distribution/) | [Distribution Anaconda](https://www.anaconda.com/distribution/) |


Les dépôts GitHub suivants de vos propres collègues du GC contiennent des scripts qui peuvent être un bon endroit par où commencer pour faciliter l’automatisation des choses. 

- Linux: https://github.com/esdc-devx/dev-laptop
- Mac: https://github.com/cds-snc/laptop
- Windows: https://github.com/CSPS-EFPC-DAAN/Data-AI-Workstation-Config

Correction du Touchpad du clic droit ne fonctionnant pas sur Ubuntu 18.04 : Exécutez cette commande et suivez les instructions[ici](https://itsfoss.com/fix-right-click-touchpad-ubuntu/)
```sh
sudo apt install gnome-tweaks
```
