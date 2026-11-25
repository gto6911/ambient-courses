TP7: Le filtre à café
Objectifs du TP:
1. Utiliser des information externe, manipuler des données
2. Faire le café Connaître la météo avec ansible ? Utiliser des filtres, manipuler des variables, facts et fichiers ! 
3. Pré-requis 
- Deux machines avec Ansible installé. 
- Un accès à une machine cible (via SSH) : 
  - Une VM Vagrant ou un serveur distant. 
  - L’utilisateur doit avoir les droits sudo.
     
Etape 1: Toujours sur notre dépôt git, créer un répertoire nommé tp7
Etape 2: Importez le fichier de données csv et affichez son contenu
Etape 3: Utilisez les filtres pour supprimer les doublons et remettre dans l’ordre les données de température par heure
Etape 4: Réalisez un code permettant de comparer la température actuelle de votre ville avec celle issue du csv (le code s'exécute uniquement en local). Pour celà on utilise:
     https://api.open-meteo.com/   (https://api.open-meteo.com/v1/forecast?latitude=48.86&longitude=2.33&hourly=temperature_2m)
Une sortie écran affiche les deux températures et indique si il fait plus chaud ou plus froid dans votre ville
Etape 5: Créez un filtre personnalisé qui inverse les caractères d’un chaîne, utilisez ce filtre pour indiquer à nouveau le résultat de comparaison des températures mais cette fois-ci avec tous les caractères inversés  
   
Livrables attendus
   Un projet Git avec : 
-  le playbook, l’inventaire, le filtre et le fichier requirements (optionnel)
-  le playbook est fonctionnel, affiche un message de sortie comparant les températures