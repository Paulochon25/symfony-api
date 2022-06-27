Installation
_____

- Clone le dépot où tu veux.
- Installe les dépendances : 
  composer install
  
- Créer la base de données, je l'ai mise en sqlite par défaut qu'on ait pas de problèmes : 
  php bin/console d:d:c
  
- Lancer les migrations : 
  php bin/console make:migration
  php bin/console d:m:m
  
- Lancer le serveur :
  symfony server:start -d
  
