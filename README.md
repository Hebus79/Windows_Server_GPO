# Windows Server GPO
Quête WCS GPO sous Windows Server 2022


## 1) Dans le gestionnaire de serveur sur l'Active Directory, dans le menu déroulant "Outils", choisir "Gestion des stratégies de groupe"

![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/1-Gestion_strategies_groupe.png)



## 2) Création d'un objet GPO dans le domaine "wilders.lan" et le lier à l'OU "Wilders_students"

![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/2-Creation_Objet_GPO_Dans_Domain.png)
![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/2-1-Creation_Objet_GPO_Dans_Domain.png)



## 3) Un double clic sur l'OU "Wilders_students"permet de visualiser dans le gestionnaire de stratégie de groupe les objets GPO liés


![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/3-Visualisation_de_strategie.png)





## 4) Avec un clic droit sur cet objet GPO choisir "Modifier"


![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/4-Edition_Modification_GPO.png)


## 5) L'editeur de gestion de stratégie de groupe s'ouvre, permettant de choisir d'interdir l'accès au panneau de configuration


![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/5-Interdire_acces_panneau_configuration.png)

## 6) Activer la GPO


![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/6-Activation_Interdire_acces_panneau_configuration.png)

## 7) La GPO est activé


![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/7-GPO_Interdire_acces_panneau_configuration_active.png)


## 8) Appliquer la GPO au groupe "Students"

![GPO](https://github.com/Hebus79/Windows_Server_GPO/blob/main/images/8-GPO_active_pour_groupe.png)




## 8) Vérifier que la GPO s'applique bien en se connectant avec un client Windows au domaine "Wilders.lan" et avec un utilisateur appartenant au groupe "Students"


