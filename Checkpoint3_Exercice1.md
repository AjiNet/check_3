# Exercice 1 : Manipulations pratiques sur VM Windows 


## Partie 1 : Gestion des utilisateurs

*L'utilisateur Kelly Rhameur a quitté l'entreprise.Elle est remplacée par Lionel Lemarchand*

Q.1.1.1 Créer l'utilisateur Lionel Lemarchand avec les même attribut de société que Kelly Rhameur.
![](assets/kelly_1.png) ![](assets/kelly_2.png) 

![](assets/kelly_3.png)![](assets/kelly_4.png)

![](assets/lionel_1.png) ![](assets/lionel_3.png)

![](assets/lionel_2.png) ![](assets/lionel_4.png)

Q.1.1.2 Créer une OU DeactivatedUsers et déplace le compte désactivé de Kelly Rhameur dedans.

![](assets/ou_deac_1.png) ![](assets/ou_deac_2.png)

![](assets/kelly_deac.png) ![](assets/kelly_deac_2.png)

![](assets/kelly_move_1.png) ![](assets/kelly_move_2.png)

![](assets/kelly_move_3.png)


Q.1.1.3 Modifier le groupe de l'OU dans laquelle était Kelly Rhameur en conséquence.

![](assets/kelly_grp.png) ![](assets/kelly_grp_2.png) 


Q.1.1.4 Créer le dossier Individuel du nouvel utilisateur et archive celui de Kelly Rhameur en le suffixant par -ARCHIVE.

![](assets/dossier_1.png) ![](assets/dossier_2.png) 

![](assets/property.png) 

![](assets/property_2.png)

![](assets/property_3.png)

## Partie 2 : Restriction utilisateurs

Q.1.2.1 Faire en sorte que l'utilisateur Gabriel Ghul ne puisse se connecter que du lundi au vendredi, de 7h à 17h.
![](assets/gab_1.png)

![](assets/gab_2.png)

Q.1.2.2 De même, bloquer sa connexion au seul ordinateur CLIENT01.

![](assets/gab_3.png)

![](assets/gab_4.png)

Q.1.2.3 Mettre en place une stratégie de mot de passe pour durcir les comptes des utilisateurs de l'OU LabUsers.

![](assets/fine_1.png)

![](assets/fine_2.png)

![](assets/fine_3.png)

## Partie 3 : Lecteurs réseaux

Q.1.3.1 Créer une GPO Drive-Mount qui monte les lecteurs E: et F: sur les clients.

![](assets/disk_1.png)

![](assets/disk_2.png)

![](assets/disk_path.png)

![](assets/gpo_1.png)

![](assets/gpo_2.png)

![](assets/gpo_3.png)

![](assets/gpo_4.png)

![](assets/gpo_5.png)


