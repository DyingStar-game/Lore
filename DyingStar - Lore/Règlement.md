
# Procédure d’installation
- Crée un compte sur [github](https://github.com/signup)
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
- Dans le git bash utilisez la commande CD pour allez dans le dossier parent d'où vous voulez clone le repo
	- Exemple : `cd Documents/Git/dyingstar/`
- Clone le repo via la commande *Pour coller la commande fait clic-droit paste*
	- `git clone https://github.com/DyingStar-game/Lore.git`
- Une fois le clone fini déplacez vous dans le repository avec la commande `cd ./Lore`
- Exécutez la commande `git config credential.helper` *pour coller la commande faites click-droit paste*
	- Si vous avez un résultat comme `manager` passer à l'étape suivante
	- Si vous n'avez pas de résultat taper la commande suivante `git config set credential.helper manager`
- Intaller et ouvrez [Obsidian](https://obsidian.md/download)
- Ouvrir un dossier comme coffre / Open folder as vault
- Sélectionnez le dossier que vous avez clone puis DyingStar Lore
- Choisissez l'option Faire confiance à auteur et activer les modules.
- Fermer la page de paramètre



# utilisation git
## Changement de branche
En faisant le raccourcis clavier Ctrl + P, puis la commande `git: switch branch` vous pourrez naviger entre les différentes branches de travail.
>[!SUMMARY]+ Attention
>- Vous n'avez pas le droit de push des modification sur la branche de travail **Main**
>- De manière général, il ne faut push des modification unniquement sur votre branche dédier

## Push de modifications




