# RGD-DemoGit

## Les commandes Git les plus utiles

### Sommaires : 
1. commandes de configuration
	* init
	* config
	* remote
2. commandes uilisables en locale
	* add
	* commit
	* branch
	* merge
3. Commandes pour la gestion des branches distante
	* fetch
	* pull
	* push

### Commandes de configuration

 **Initialisation du "repository"**
```
cd myproject/
git init
```
**Création du lien avec le répertoire distant**
```
git remote add origin https://github.com/userName/myprojectr.git

```
### commandes uilisables en locale
 **Add**
 Ajoute des fichiers modifés à la "working copy"
```
git add file.txt   	// ajout le fichier "file.txt"
git add .   		// ajoute tous les fichiers du repertoire courant
```
**Commit**
Valide les modifications au sein de la branche courante  
```
git commit --m 'Message de description du commit'
```
**Branch**
permet la création d'une nouvelle branche de travail
```
git branch nomdelabranche
```
**Merge**
permet de fusionner 2 branches, generalement une branche de travail et le master
```
git merge nomdelabranchdetravail
```
L'option -- abort, permet d'annuler un merge en cours et de revenir à l'état précédent les différents conflit apparu durant le merge.

### Commandes pour la gestion des branches distante
**Pull**
Permet de récupérer les modifications d'une branche distante
```
git pull origin nomdelabranchedistante
```
**Push**
Permet de pousser les commits locale sur une branche distante
```
git push origin nomdelabranchelocal
```
Quelques options utiles :
* -- all : permet de pousser toutes les branches en même temps
* -- prune : permet de nettoyer les branches distantes qui n'ont plus équivalent en locale (les branches déjà merger)

##### Mon projet de DemoGit sur GitHub
* ![GitHub Logo](/images/logo.png) [DemoGit](https://github.com/remiGenydumont/RGD-DemoGit)
* ![Profil Picture](https://pbs.twimg.com/profile_images/928001057954979840/CmwgU2so_bigger.jpg) [Mon Twitter](https://twitter.com/Keiro__)

<img src="http://gph.is/Vwznl1"></img>

