Test Technique
================

Bienvenue dans ce test technique !

Celui-ci à pour vocation de nous permettre d'estimer votre niveau technique et comprendre la réflexion suivie pour la résolution des problèmes du quotidien :)

Pour cela, nous vous avons mis à disposition une VM Debian avec un applicatif Web :
 - ip : 46.105.28.233 
 - user: debian
 - mot de passe: communiqué par e-mail 
 
Vous disposez d'un accès SSH sur la VM et l'applicatif est joignable sur l'url "https://46.105.28.233".

Malheuresement le Chaos Monkey est passé par là, charge à vous de réparer les dégats !

Pour vous aidez, je vous invite à suivre les étapes ci-dessous et à nous indiquer brièvement votre réflexion et les actions effectuées pour chacune de ces étapes.

Étapes :
----------

1. Se connecter au serveur à l'aide d'une clé SSH sur l'utilisateur "root"

2. Rétablir le fonctionnement du serveur Web 

3. Vérifier les ports ouverts sur le pare-feu (ufw)

4. Rétablir le fonctionnement du service de base de données

5. Rétablir le fonctionnement de l'applicatif Python

Ansible
---------

Afin de faciliter l'installation de ce service, un playbook Ansible a été écrit mais l'auteur a été un peu vite ...

Pouvez-vous corriger les erreurs présentes dans le playbooks `playbooks/setup_netbox.yml` et ses dépendences ?

