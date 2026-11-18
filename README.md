Repère — bibliothèque d'icônes et prototype

Projet 8 · Design & formations D404A2

Prototype interactif : https://eveilenfantteam-wq.github.io/repere-prototype/

Contenu du dépôt
repere-prototype/
├─ index.html                 prototype interactif (neuf écrans)
├─ repere_icons.sprite.svg    22 symboles
└─ svg/
   ├─ 10 icônes + 2 variantes icônes de domaine, objet du projet
   └─ systeme/                10 glyphes système, hors périmètre de conception
Icônes de domaine
Fonction	Fichier
Cours	course_icon.svg
Planning	schedule_icon.svg
Planning, sous 20 px	schedule_icon_sm.svg
Cartes mémoire	flashcard_icon.svg
Cartes mémoire, sous 20 px	flashcard_icon_sm.svg (pas encore testée)
Quiz	quiz_icon.svg
Progression	progress_icon.svg
Session focus	timer_icon.svg
Notes	note_icon.svg
Objectif	goal_icon.svg
Groupe d'étude	study_group_icon.svg
Ajouter	add_course_icon.svg

Les deux variantes _sm sont des tailles optiques : elles remplacent l'icône standard sous 20 px. schedule_icon_sm a été retenue après les tests (phase C, préférée par 4 participants sur 5). flashcard_icon_sm a été dessinée après les tests et reste à valider à 16 px.

Spécifications

Grille 24 × 24 · marge 2 px · zone vive 20 × 20 · trait 1,5 · terminaisons et jointures arrondies · aucun aplat : fill="none" · stroke="currentColor".

Le fichier unitaire porte stroke-width="1.5". Le symbole du sprite n'en porte aucune : l'épaisseur est fixée par le conteneur <svg> (1,5, ou 1,875 à 16 px).

L'identifiant de chaque symbole du sprite est le nom de son fichier, sans extension.
