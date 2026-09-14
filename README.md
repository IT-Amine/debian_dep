# debian_dep

## Git VM Linux 

Fiche recette

Connecter sur le compte local du poste avec le compte administrateur.
Venir changer son DNS Préfére et le pointer vers celui du windows serveur donc, 172.16.54.1

Après, aller sur système du poste, puis Renommer ce PC (avancé). Mettre un nom sur la machine client pour le référencer correctement. Puis aller dans Modifier pour mettre le domaine. Donc passer de Work à Domaine et mettre local.ecocert4.fr et mettre la connection administrateur et le mot de passe de l'AD.

Puis faire un test des users importer dans l'AD, en mettant prenom.nom (je test avec le compte de david.geran).
Comment on peut le voir il demande de changer le mot de passe car les compte en premier connection il demande de modifier le mot de passe. Mettre un nouveau mot de passe, puis il viendra à ce connecter au compte. Puis sa confirme le test que la machine client et bien en relation avec le le windows serveur et son service Active Directory.


Pour voir plus et être sûr, aller sur le terminal et écrire "ipconfig /all" et nous affichera toute les informations réseaux de la machine cliente.
