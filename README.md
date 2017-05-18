# espace-membre
Simple interface d'espace membre en php

[FR]
4 petits scripts en php pour une interface d'espace membre sur le web, avec un hash md5 pour les mots de passes
Attention pensez à creer une table sql de la manière suivante:
un champ id AUTO_INCREMENT qui nous permettra d'identifier chaque membre (chaque membre ayant un id différent). Ce sera notre clé primaire.
un champ login de type text qui contiendra le login de chaque membre de l'espace membre
un champ pass_md5 de type text contenant le mot de passe haché de chaque membre

Pensez à remplir les infos dans index aux lignes 6 et 7, et dans inscirption aux lignes 11 et 12

L'interface est très légère et simple, pensez à la personaliser de vous même ;)

[EN]
4 little scripts in php for a simple login interface with md5 passwords hash
Warning! Don't forget to create a sql table like this:
One line named "id" AUTO_INCREMENT to identify members. Primary key
One line "login" type text for the usernames
One line "pass-md5" type text for the passwords

The interface is very simple, think to create your own ;-)

in index change line 6 and 7. And in incription 11 and 12
