
# Procédure d’installation
- Créer un compte sur [github](https://github.com/signup) 
  *pour ceux qui veulent contribuer unniquement **Attention: Le seul fait de crée un compte ne permet pas de Push des modification sur github. Pour cela il faut ce rapprocher du lead lore***
- [Télécharger et installer Git](https://git-scm.com/install/windows)
	- Use vim
	- Let git decide
	- Git from the command line and also from 3rd party software
	- Use bundled OpenSSH
	- Use the native windows secure channel library
	- Checkout Windows style commit unix style line endings
	- Use MinTTy the degfault terminal of MSYs2
	- Fast-forward or merge
	- Git credential Manager
	- Enable file system caching
	- Install
	- Launch git bash
- Exécuter la commande `ssh-keygen -t ed25519 -C your_email@example.com`
- Faire entrer plusieurs fois jusque message de validation
- Faire la commande `cat ~/.ssh/id_25519.pub`
- Copier le résultat *A partir de ssh et jusque .com*
- Ajouter le résultat sur votre compte github
	- Profil github
	- Settings
	- SSH and GPG Keys
	- New SSH Key
	- Mettez un title *la valeur est a titre informative*
	- Key type -> authentication ley
	- Key -> coller le résultat de la commande
-  Exécuter la commande `git config --global user.email Your@email`
	- Remplacez **Your@email** par votre email github
- Exécuter la commande `git config --global user.name YourName`
	- Remplacez **YourName** par votre pseudo github
- Dans le git bash utiliser la commande CD pour aller dans le dossier parent d'où vous voulez clone le repo
	- Exemple : `cd Documents/Git/dyingstar/`
- Cloner le repo via la commande *Pour coller la commande fait clic-droit paste*
	- `git clone git@github.com:DyingStar-game/Lore.git`
	- Faites entrer plusieurs fois jusque message de validation
- Une fois le clone fini, déplacez vous dans le repository avec la commande `cd ./Lore`
- Installer et ouvrez [Obsidian](https://obsidian.md/download)
- Ouvrir un dossier comme coffre / Open folder as vault
- Sélectionner le dossier que vous avez cloné puis **DyingStar - Lore**
- Choisir l'option Faire confiance à auteur et activer les modules.
- Fermer la page de Paramètres



# Utilisation git
## Changement de branche
En faisant le raccourcis clavier Ctrl + P, puis la commande `git: switch branch` vous pourrez naviguer entre les différentes branches de travail.
>[!SUMMARY]+ Attention
>- Vous n'avez pas le droit de push des modification sur la branche de travail **Main**
>- De manière générale, il ne faut push des modifications que sur votre branche dédiée

## Push de modifications
- Il faut review les modifications effectuées. Pour cela, ouvrez le git: source control
- Puis sur les fichier dont vous souhaitez valider la modification. Cliquer sur la croix Stage
- Ajouter un message de commit a la place date
- Cliquer sur la flèche commit and sync





