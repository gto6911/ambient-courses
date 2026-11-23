TP : Utilisation de git et création d’un premier playbook d’installation
Objectifs du TP:
1. Apprendre à utiliser Git pour versionner un projet Ansible.
2. Créer un playbook Ansible pour installer et configurer Apache2 sur une machine.
3. Tester le playbook sur une machine cible.

4. Pré-requis
- Une machine avec Ansible installé.
- Un accès à une machine cible (via SSH) :
- Peut être une VM Vagrant ou un serveur distant.
- L’utilisateur doit avoir les droits sudo.
- Git installé sur votre machine locale.

Etape 1: Utiliser les commande git pour initialiser le projet, créer un fichier Readme.md et .gitignore
Etape 2: Créer un fichier hosts.yml contenant la machine cible
Etape 3: Créer et tester le playbook
Etape 4: Publier votre code
 
Livrables attendus
  Un projet Git avec :
- inventory.yml / hosts / hosts.yml : fi chier d’inventaire.
- apache2.yml : playbook pour installer Apache2.
- .gitignore : fi chier pour exclure les fi chiers inutiles.
- README.md : instructions pour exécuter le projet.
- Un Apache2 fonctionnel sur la machine cible.