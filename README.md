https://bioinfo-fr.net/git-usage-collaboratif

### Commandes utiles pour manipuler les branches

Indique uniquement les branches qui ont déjà été fusionnées.
```js
git branch --merged
```
Indique uniquement les branches qui n'ont pas encore été fusionnées.
```js
git branch --no-merged
```
Permet de passer sur la branche nomDeLaBranche (qui doit déjà exister), et qui devient alors la branche courante.
```js
git checkout nomDeLaBranche
```
Crée une nouvelle branche et "switche" sur celle-ci juste après : la branche courante devient nomDeLaBranche.
```js
git checkout -b nomDeLaBranche
```
Permet de détruire une branche.
```js
git branch -d nomDeLaBranche
```
Permet de fusionner la branche nomDeLaBranche avec la branche courante, en détectant éventuellement les conflits. La branche cible (nomDeLaBranche) ne sera pas modifiée lors de cette opération. 
```js
git merge nomDeLaBranche
```

### Utiliser des tags pour indiquer les versions

