Contexte
Un hôpital de la province du Groenland tente d'améliorer ses conditions de soins en analysant l'historique de survie des patients. L'analyse de ses données n'a pas permis d'identifier les principaux facteurs responsables de ces taux de survie élevés.
Contenu
L'ensemble de données contient les dossiers médicaux recueillis dans un hôpital du Groenland. La colonne « Survived_1_year » est une variable cible dont les valeurs sont binaires (0 ou 1).
Survived_1_year == 0, implique que le patient n'a pas survécu après 1 an de traitement
Survived_1_year == 1, implique que le patient a survécu après 1 an de traitement
Description des données :
1.	ID_Patient_Care_Situation : Situation de soins d'un patient pendant le traitement
2.	Diagnosed_Condition : l'état diagnostiqué du patient
3.	ID_Patient : numéro d'identification du patient
4.	Traitement_médicamenteux : Classe de médicaments utilisés pendant le traitement
5.	Survived_1_year : si le patient a survécu après un an (0 signifie n'a pas survécu ; 1 signifie a survécu)
6.	Patient_Age : Âge du patient
7.	Patient_Body_Mass_Index : une valeur calculée en fonction du poids, de la taille, etc. du patient.
8.	Patient_Fumeur : si le patient était fumeur ou non
9.	Patient_Rural_Urban : si le patient a séjourné dans une partie rurale ou urbaine du pays
10.	Condition_Précédente : État du patient avant le début du traitement (Cette variable est divisée en 8 colonnes - A, B, C, D, E, F, Z et Number_of_prev_cond. A, B, C, D, E, F et Z sont les conditions antérieures du patient. Supposons que pour un patient, si l'entrée dans la colonne A est 1, cela signifie que la condition antérieure du patient était A. Si le patient n'avait pas cette condition, elle est 0 et idem pour les autres conditions. Si un patient a une condition antérieure comme A et C, les colonnes A et C auront des entrées comme 1 et 1 respectivement tandis que l'autre colonne B, D, E, F, Z aura des entrées comme 0, 0, 0, 0, 0 respectivement. La colonne Number_of_prev_cond aura une entrée comme 2, c'est-à-dire 1 + 0 + 1 + 0 + 0 + 0 + 0 = 2 dans ce cas.)
