# Donner la main au client (IsAdmin uniquement !!) pour modifier les statuts des rapports envoyés

## Demande

![image](https://github.com/MathisCastell/Stage-Donner-la-main-au-client/assets/148212506/821918af-5cd2-47b1-a68d-b7133502f408)


## Création de la page de validation du passage en statut généré

Je défini dans un premier temps quelques variables qui seront affichée dans la page grâce à la requête SQL. Les variables sont ensuite utilisées dans la partie HTML qui suit la requête SQL.
Tout ceci est dans la variable e_info qui est affichée ensuite dans la dernière partie.

![image](https://github.com/MathisCastell/Stage-Donner-la-main-au-client/assets/148212506/4b06996b-2d3e-44e8-b930-20a9fd42b724)
![image](https://github.com/MathisCastell/Stage-Donner-la-main-au-client/assets/148212506/caeb43b4-b614-40f1-9aa0-bf1742ebb805)

Le bouton valider appelle une PS qui fera les modifications dans la base de donnée.

## Procédure

Si la variable in_xStatut est à Genere tout est mis à null.

![image](https://github.com/MathisCastell/Stage-Donner-la-main-au-client/assets/148212506/9037b7dd-7e9d-4d37-b6b8-88a61b5afdcc)
