# Cours_DevOps

Le repository contient le travail effectué en binôme avec Taslim hammoud.

Le travail a été réalisé avec une machine virtuelle ubuntu. La VM ubuntu contient une vm vagrant ainsi que ansible.
La vm vagrant sera la machine cible à administrer avec ansible 

Le fichier VagrantFile est créé et contient la configuration de la vm vagrant.

Le fichier provisionning à été créé et contient:

- Un fichier group_vars contenant les variables 
- Un fichier hosts contenant la liste des hosts (les cibles) 
- Le playbook.yml
- Les dossiers roles. Les dossier roles contiennent les roles pour PHP, NGINX, MYSQL-SERVER et COMMON. Chaque role contient des fichiers main.yml dans un dossier tasks. Ce fichier main.yml contient les tâches éffectuées sur les/les machines cibles

Tous les déploiements ansible on fonctionnés sur la machine cible (vm vagrant) pour les roles PHP, NGINX, MYSQL-SERVER et COMMON.
