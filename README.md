# projet1
Planificateur de Transport:
Description:
Le Planificateur de Transport est un programme Prolog conçu pour faciliter la navigation des utilisateurs à travers le réseau complexe des systèmes de transport entre différentes stations. Dans les environnements urbains dynamiques d'aujourd'hui, un outil de planification de transport efficace et convivial devient essentiel pour les navetteurs. Ce programme Prolog vise à offrir une solution intuitive et personnalisable aux utilisateurs pour planifier leurs trajets, en prenant en compte des facteurs tels que le choix des réseaux de transport, les préférences pour le trajet le plus court et le moins de correspondances.

Fonctionnalités:
Planification de trajets à partir de différentes stations.
Prise en compte des réseaux de transport (métro, bus, train).
Option de préférence pour le trajet le plus court.
Limite du nombre maximal de correspondances.

*pour executer ce programme il faut installer prolog. 
exaamples:
Addh([13 , 30],30, [14 , 0]).
affiche(13, 39]).
lig(jourdain, chatelet, 11).
ligtot(place_fetes, goncourt, 11, [5,17]).
ligtard(telegraphe, jourdain, 11, [5,28]).
?- interface_utilisateur .
Stations desservies par les transports publics :
[station1, station2, station3, ...]
Choisissez une station de départ : station1.
Choisissez une station d'arrivée : |: station2.
Choisissez le type de réseau (metro, bus, train) : |: metro.
Préférence par rapport à la longueur du trajet (court, normal, long) : |: normal.
Nombre de correspondances maximal : |: 1.
ligtot(place_fetes, goncourt, 11, [5,17]).
