# Parfumerie
Inspirée par Marionnaud 



BACK END

11- Sécurité de la partie Back end :

 des bibliothèques et des frameworks fiables pour éviter les vulnérabilités de sécurité connues.
Mettez à jour régulièrement les dépendances pour corriger les vulnérabilités de sécurité.
 HTTPS pour chiffrer les données transmises entre le serveur et le client. (pas pour le moment car l'application ne sera pas déployé)
 des tokens d'authentification sécurisés pour protéger les ressources sensibles.
 le nombre de tentatives de connexion pour prévenir les attaques par force brute.
 la vérification en deux étapes pour renforcer la sécurité des comptes utilisateur.
 des captchas pour prévenir les attaques par robot.
 des en-têtes de sécurité tels que Content Security Policy (CSP) et Strict-Transport-Security (HSTS) pour renforcer la sécurité de l'application.
 des paramètres de requête préparés ou des requêtes paramétrées pour éviter les attaques par injection SQL. (pas besoin si vous utilisez postgreSQL car les requetes sont déjà paramètrées et protégé)
 des bibliothèques de validation de schéma pour valider les données d'entrée et de sortie.
 des bibliothèques de journalisation pour enregistrer les activités du serveur et détecter les anomalies.
 pare-feu pour limiter l'accès au serveur et aux ressources sensibles.
 tests de sécurité réguliers pour détecter les vulnérabilités et les failles de sécurité.



FRONT 


 
10- Sécurité de la partie Front :

échappez toutes les entrées utilisateur pour éviter les attaques par injection de code malveillant.
Utilisez des bibliothèques et des frameworks fiables pour éviter les vulnérabilités de sécurité connues.
mettre à jour régulièrement les dépendances pour corriger les vulnérabilités de sécurité.
HTTPS pour chiffrer les données transmises entre le serveur et le client.(pas pour le moment car l'application ne sera pas déployé)
 tokens d'authentification sécurisés pour protéger les ressources sensibles.
le nombre de tentatives de connexion pour prévenir les attaques par force brute.
 la vérification en deux étapes pour renforcer la sécurité des comptes utilisateur.
des captchas pour prévenir les attaques par robot.
 des en-têtes de sécurité tels que Content Security Policy (CSP) et Strict-Transport-Security (HSTS) pour renforcer la sécurité de l'application.
 des tests de sécurité réguliers pour détecter les vulnérabilités et les failles de sécurité.

NB : utiliser Bycrpt pour haché les MDP.
