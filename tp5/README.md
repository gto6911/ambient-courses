TP5: Inclusion et linters
Objectifs du TP:
1. Utiliser des inclusions pour rendre le code plus facile à maintenir et plus lisible
2. Créer deux playbooks Ansible pour configurer des machines

3. Pré-requis 
   Trois machines avec Ansible installé.
   Un accès à une machine cible (via SSH) : - -
   Peut être une VM Vagrant ou un serveur distant.
   L’utilisateur doit avoir les droits sudo.
   
Etape 1: Toujours sur notre dépôt git, créer un playbook nommé tp5
Etape 2: Créer un fichier hosts.yml contenant les machines cibles
Etape 3: Créer un fichier requirements.yml contenant les roles nécessaires au playbook
Etape 4: Utilisez le playbook du tp4 ou sa correction qui installe docker via le rôle geerlingguy.docker
Etape 5: Utilisez le playbook du tp3 ou sa correction
Etape 6: Dans le playbook tp5.yml incluez les deux précédents playbook et ajouter une tâche qui vient écrire la date et l’heure dans un fichier nommé /etc/last_changed
Etape 7: Installer ansible-lint, créer un fichier de configuration .ansible-lint et corrigez l’ensemble des playbook pour être conformes aux règles du linter
   
Livrables attendus
Un projet Git avec : 
- le playbook, l’inventaire et le fichier requirements
- Les serveurs contiennent une installation de docker