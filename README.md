### Commandes utiles pour manipuler les branches
  
 - ```git branch --merged```

 Indique uniquement les branches qui ont déjà été fusionnées.
 - ```git branch --no-merged```

 Indique uniquement les branches qui n'ont pas encore été fusionnées.

 - ```git checkout nomDeLaBranche```

 Permet de passer sur la branche nomDeLaBranche (qui doit déjà exister), et qui devient alors la branche courante.

 - ```git checkout -b nomDeLaBranche```

 Crée une nouvelle branche et "switche" sur celle-ci juste après : la branche courante devient nomDeLaBranche.

 - ```git branch -d nomDeLaBranche```

 Permet de détruire une branche.

 - ```git merge nomDeLaBranche```

 Permet de fusionner la branche nomDeLaBranche avec la branche courante, en détectant éventuellement les conflits. La branche cible (nomDeLaBranche) ne sera pas modifiée lors de cette opération. 

### Utiliser des tags pour indiquer les versions

