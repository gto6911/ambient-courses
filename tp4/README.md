TP4 : Un rôle très au sérieux
Objectifs du TP:
1. Utiliser des roles pour simplifier le code
2. Créer un playbook Ansible pour configurer une machine et y installer docker.

3. Pré-requis
- Une machine avec Ansible installé.
- Un accès à une machine cible (via SSH) :
- Peut être une VM Vagrant ou un serveur distant.
- L’utilisateur doit avoir les droits sudo.

Etape 1: Toujours sur notre dépôt git, créer un playbook nommé tp4 
Etape 2: Créer un fi chier hosts.yml contenant les machines cibles
Etape 3: Créer un fi chier requirements.yml contenant les roles nécessaires au playbook
Etape 4: Créer un playbook qui installe docker via le rôle geerlingguy.docker
  
Livrables attendus
 Un projet Git avec :
- le playbook, l’inventaire et le fi chier requirements
- les serveurs contiennent une installation de docker