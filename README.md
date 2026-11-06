# Mon extension QGIS
Cette extension QGIS a été réalisée dans le cadre du cours de Programmation sous QGIS.

## Fonctionnalitées implémentées
1. Possibilité de choisir une couche vectorielle de points uniquement dans la combobox.
2. Affichage des coordonnées dans le système de coordonnées de référence WGS84 du point exact ou l'on clique.
3. Affichage de l'adresse postale la plus proche de ce point.
4. Possibilité de déterminer un tampon de la taille que l'on souhaite (1000m par défaut) autour de notre point dans lequel nous trouverons tous les éléments de la couche vectorielle ciblée qui intersectent ce tampon.
5. A chaque clic, le tampon précédent est supprimé et remplacé par un nouveau tampon stocké dans la couche temporaire "temp_buffer".

## Limites de l'extension
1. Une erreur est générée lorsque l'on clique à une distance trop grande de la couche cible.
2. Une erreur est générée lorsque l'on supprime la couche temporaire du buffer et que l'on clique ensuite sans relancer l'extension.
3. Manque de l'US n°6.