1. Installer apache sur ubuntu:
   
sudo apt update
sudo apt install apache2

2. Configurer le fichier de log:

Les fichiers logs se trouvent dans /var/log/apache2/ 

3. Générer du trafic

curl adress IP

4. Analyser les logs

Requêtes réussies (code 200) :
grep " 200 " /var/log/apache2/access.log

Erreurs 404 :
grep " 404 " /var/log/apache2/access.log
