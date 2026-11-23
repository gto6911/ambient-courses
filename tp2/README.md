Étape 1: Toujours sur notre dépôt git, créer une branche nommé tp2 
Etape 2: Créer un fichier hosts.yml contenant la machine cible
Etape 3: Créer un playbook qui installe les logiciels suivants sur la machine:
- apache2
- mysql-server
Etape 4: Le playbook doit modifi er le fi chier html servi par apache2 uniquement si apache2 est déjà installé pour afficher “Bonjour depuis Ansible” et démarrer le service apache2


Livrables attendus
Un projet Git avec :
- la branche tp2 contenant le playbook

Un Apache2 fonctionnel sur la machine cible et dont la page web affiche “Bonjour depuis ansible”