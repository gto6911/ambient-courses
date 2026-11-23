TP : L'amour inconditionnel des conditions
Objectifs du TP:

Utiliser des boucles et conditions complexes
Créer un playbook Ansible pour confi gurer une machine.
   
1.Pré-requis
- Une machine avec Ansible installé.
- Un accès à une machine cible (via SSH) :
- Peut être une VM Vagrant ou un serveur distant.
- L’utilisateur doit avoir les droits sudo.

Etape 1: Toujours sur notre dépôt git, créer un playbook nommé tp3 
Etape 2: Créer un fi chier hosts.yml contenant les machines cibles
Etape 3: Créer un playbook qui installe les logiciels suivants sur la machine 1:
- apache2
- mysql-server
  Sur la machine 2:
- apache2
- mysql-server
  Sur la machine 3:
- git
- nginx
- cowsay
- 
Etape 4: Le playbook doit installer uniquement sur les machines ubuntu le paquet ufw
Etape 5: Le playbook doit modifi er le fi chier html servi par apache2 ou nginx uniquement si apache2 ou nginx est déjà installé pour affi cher “Bonjour depuis Ansible sur machine 1 ou 2 ou 3” et démarrer le service apache2 ou nginx
Etape 6: Dans /etc/jour: - Si on est un jour pair et qu’il est plus de 12h00, inscrire “pair et plus tard que midi” - Si on est un jour pair et qu’il est moins de 12h00, inscrire “pair et avant midi”
- Si on est un jour impair et qu’il est plus de 12h00, inscrire “impair et plus tard que midi” - Si on est un jour impair et qu’il est moins de 12h00, inscrire “impair et avant midi”

Livrables attendus
  Un projet Git avec :
- le playbook et l’inventaire
  Les serveurs web fonctionnels affi chant les bons messages Le fi chier /etc/jour correctement défi nis