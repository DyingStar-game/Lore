
# Procédure d’installation
- [Télécharger et installer Git](https://git-scm.com/install/windows)
- Télécharger le repo du lore depuis [github](https://github.com/DyingStar-game/Lore) ![[Pasted image 20251112205611.png]]
- Une fois le fichier zip télécharger dézippez le dans votre espace de travail




- Lancé le logiciel git bash
- Dans le terminal déplacez vous vers votre répertoire de travail puis dans le repository que vous avez déziper
	- Pour cela utiliser la commande CD ex: `cd Documents/Git/dyingstar/Lore/`
- Une fois fait utiliser la commande : `git config credential.helper`
	- Si vous avez un résultat comme ceci, passez à l'étape suivante
	- Si vous n'avez aucun résultat comme ceci ![[Pasted image 20251112205048.png]]
		- Fait la commande : `git config set credential.helper manager`
- Intaller et ouvrez [Obsidian](https://obsidian.md/download)
- Ouvrir un dossier comme coffre
- Sélectionnez le dossier Lore que vous avez dézipé
- Choisissez l'option Faire confiance à auteur et activer les modules.
A présent vous pouvez librement naviger dans le vault obsidian.

# utilisation git
## Changement de branche
En faisant le raccourcis clavier Ctrl + P, puis la commande `git: switch branch` vous pourrez naviger entre les différentes branches de travail.
>[!SUMMARY]+ Attention
>- Vous n'avez pas le droit de push des modification sur la branche de travail **Main**
>- De manière général, il ne faut push des modification unniquement sur votre branche dédier

## Push de modifications




