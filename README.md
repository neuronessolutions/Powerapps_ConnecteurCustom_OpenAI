# Powerapps_ConnecteurCustom_OpenAI
Connecteur personnalisé OpenAI pour applications PowerApps

## Création Pas à pas du connecteur personnalisé OpenAI pour intégrer des fonctions d'OpenAI dans les applications PowerApps
Dans PowerApps, choisir "Connecteurs personnalisés" et cliquez sur **"Nouveau connecteur personnalisé"**, puis sur "Créer à partir de zéro"
![Capture d’écran, le 2023-09-26 à 14 42 35](https://github.com/nuage365/Powerapps_ConnecteurCustom_OpenAI/assets/102873102/66aa2f67-feac-4c75-80f3-786b53b900db)

Lui donner un nom, ici **"OpenAI Connecteur"**

![Capture d’écran, le 2023-09-26 à 14 43 05](https://github.com/nuage365/Powerapps_ConnecteurCustom_OpenAI/assets/102873102/b8f22d1e-03c5-4ce0-95cb-d720e40e5624)

Ensuite, dans l'écran suivant, ajouter un icône pour votre connecteur. Choisir le schéma HTTPS, Puis dans le champ Hôte, indiquer l'adresse principale de notre API qui compose le connecteur. Passez ensuite à l'étape suivante en cliquant sur "Sécurité".
![Capture d’écran, le 2023-09-26 à 16 21 21](https://github.com/nuage365/Powerapps_ConnecteurCustom_OpenAI/assets/102873102/ce252d6f-5c3f-4048-8849-20fad83e5703)

Choisir ensuite le type d'authentification. Pour notre Api OpenAI, on utilise une Clé API.
On indique ensuite :
* L'étiquette du paramètre (API Key)
* Le nom du paramètre (Authorization)
* L'emplacement du paramètre (En-tête)
![Capture d’écran, le 2023-09-26 à 20 40 08](https://github.com/nuage365/Powerapps_ConnecteurCustom_OpenAI/assets/102873102/069191c1-f90d-4885-886e-3822c58536a2)


Ensuite on passe à la "Définition" de notre connecteur personnalisé.
On indique :
* Un résumé : OpenAI ChatGPT API
* Un Id de l'opération : dans notre exemple APIChat

Pour reproduire le comportement de ChatGPT pour notre connecteur, nous allons devoir saisir une demande et nous allons la créer à partir d'un exemple :)
Cliquer sur "Importer à partir de l'exemple"
![Capture d’écran, le 2023-09-26 à 20 52 15](https://github.com/nuage365/Powerapps_ConnecteurCustom_OpenAI/assets/102873102/616b75bd-5d96-4e63-81a3-55f0e1e1995a)



