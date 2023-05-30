Nom de la ressource : SlashReport
Auteur : DeWebNer
Version : 1.0.0
Description : Cette ressource permet aux joueurs d'utiliser la commande /report pour signaler des probl�mes ou des comportements inappropri�s. 
Seuls les administrateurs et mod�rateurs peuvent lire les rapports.

Instructions d'installation :

1. Copiez le dossier de la ressource dans le r�pertoire "resources" de votre serveur FiveM.
2. Ajoutez "start SlashReport" � votre fichier "server.cfg" 
3. Red�marrez votre serveur FiveM.

Structure des fichiers :

- server/
    - main.lua : Charge le fichier report.lua lors du d�marrage de la ressource.
    - report.lua : Contient le code pour g�rer la commande /report et v�rifier si un joueur est administrateur ou mod�rateur.
    - fxmanifest.lua : D�clare les scripts serveur � charger pour cette ressource.

Configuration :

Pour configurer la v�rification des administrateurs et mod�rateurs, modifiez la fonction "isAdminOrModerator" dans le fichier "server/report.lua". Ajoutez votre propre logique pour v�rifier si un joueur est administrateur ou mod�rateur en fonction de votre syst�me de permissions.

Utilisation :

Les joueurs peuvent utiliser la commande /report suivie d'un message pour signaler des probl�mes ou des comportements inappropri�s. Par exemple :

/report Un joueur utilise des cheats.

Seuls les administrateurs et mod�rateurs pourront lire les rapports.

Support :

Si vous avez des questions ou rencontrez des probl�mes avec cette ressource, veuillez me contacter sur Twitter: @DeWebNer