# Blender-Stroke_Builder_Pro

Stroke_Builder est ou outil addon pour Blender 5.0.1, une version stable, et juste avant le grand changement du fonctionnement des objets Grease Pencil. 

Son but est d’optimiser l’animation vectorielle interpolée au Grease Pencil dans Blender.
Pour rappel, ce type d’interpolation automatique a besoin d’une organisation sérieuse au niveau des traits Grease Pencil pour obtenir un résultat cohérent et propre, cet outil est justement conçu  cet effet !

Il permet :
-d’afficher des marqueurs visuels pour les traits du même numéro que celui actif sur les frames avant, actuelle et après, ainsi que le numéro en surbrillance.
-d’inverser le sens des traits pour conserver un maximum de précision et corriger facilement de erreurs d’interpolation,
-de remplacer des traits existant même en plein milieu d’une pile sans changer son numéro, sa couleur, son nombre de points, son épaisseur ou son vertex group, il sufit de passer en edit mode, sélectionner le trait a remplacer, cliquer sur le bouton remplacer, et retracer le trait grâce au draw mode qui vient de se mettre, cliquez sur tab pour valider,
-de convertir un stroke polygonal en catmull-rom (courbes compatibles aux deformations aves poignées automatiques), avec un algoritme et une personalisation plus poussée que la conversion native de blender,
-de selectioner automatiquement des calques et traits étant liés,
-de remplacer le traits sélectionné en edit mode par celui de même nombre de la frame précédente ou suivante.
-de générer automatiquement un enssemble de vertex groups a un objet, correspondant au nom de os de la cible,
-de générer un fausse bibliothèque manuelle multiple dans la timeline (dans les frames negatives pas convention) et de lier une frame a une banque, une banque peut ensuite etre dupliquée a la frame voulue a n'importe quel moment.

a savoir :
-l'outil n'a pas été testé dans les version autre que 5.0.1 et 5.0.0,
-il est concu pour une utilisation du grease pencil et est capriceux avec d'autres objets,
-l'addon n'a pas été traduit en plusisieurs langues mais certaint thermes anglophones et francais mélangés peuvent porter a confusion.

Rejoignez moi sur Youtube si ce n’est pas déjà fait ! Je poste régulièrement des avancées sur des projets en rapport avec le Grease Pencil ! XD


notes :
-cet outil a nécessité l’intervention d’ l’IA generatives pour des bugs complexes et l’organisation globale du fichier, bien qu'il a mis plusiqurs semains a être complètement configuré.
