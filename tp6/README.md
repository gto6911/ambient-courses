TP6: La pression des mots
Objectifs du TP:
1. Utiliser l’ensemble des connaissance acquises des précédentes activités
2. Créer un playbook ansible avec des tags pour installer et déployer wordpress
   Pré-requis
- Deux machines avec Ansible installé.
- Un accès à une machine cible (via SSH) :
- Une VM Vagrant ou un serveur distant.
- L’utilisateur doit avoir les droits sudo.
  Etape 1: Toujours sur notre dépôt git, créer un playbook nommé tp6
  Etape 2: Créer un fichier hosts.yml contenant les machines cibles, deux groupes de
  machines (web et db)
  Etape 3 : Créer un fichier requirements.yml contenant les potentiels rôles nécessaires
  au playbook
  Etape 4: Installer apache2 et tous le pré-requis pour installer wordpress sur la première
  machine
  Etape 5: Installez mysql-server sur la seconde machine
  Etape 6: Connectez wordpress à la base de données de la seconde machine et
  automatisé la configuration de wordpress (le fichier wp-config.php) via un template jinja
  Attention: vous devez conditionner/taguer l’ensemble des tâches pour être exécuté par
  thématique ou par machine (apache2 pour machine 1 et mysql sur machine 2)
  Etape 7: Stockez les variables dans un fichier externe (dans un répertoire vars)
  Etape 8: Utilisez un vault pour conserver les mots de passe de la base de données
  Livrables attendus
  Un projet Git avec :
- le playbook, l’inventaire et le fichier requirements (optionnel)
  Les serveurs contiennent une les paquets et services nécessaires, wordpress fonctionne
  et a été directement configuré par ansible