### Commandes utiles pour manipuler les branches
  
  "git branch --merged" indique uniquement les branches qui ont déjà été fusionnées.
  "git branch --no-merged" indique uniquement les branches qui n'ont pas encore été fusionnées.

La commande "git checkout nomDeLaBranche" permet de passer sur la branche nomDeLaBranche (qui doit déjà exister), et qui devient alors la branche courante.

La commande "git checkout -b nomDeLaBranche" crée une nouvelle branche et "switche" sur celle-ci juste après : la branche courante devient nomDeLaBranche.

La commande "git branch -d nomDeLaBranche" permet de détruire une branche.

La commande "git merge nomDeLaBranche" permet de fusionner la branche nomDeLaBranche avec la branche courante, en détectant éventuellement les conflits. La branche cible (nomDeLaBranche) ne sera pas modifiée lors de cette opération. 

### Utiliser des tags pour indiquer les versions

