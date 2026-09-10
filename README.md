Q1 — Créer le fichier de données
Installer Mongodb et créer une base et une collection dans Compass
![Installer Mongodb et créer une base](/imges/question1-creationBBD.png)
Q2 — Importer dans MongoDB Compass
Importer ce fichier via le bouton d'import.
![Importer ce fichier via le bouton d'import](/imges/question2_importe_livres.png)
Q3 — Combien de documents ?
Nombre de documents : 8 documents

Q4 — Le premier document
Premier document : Titre "Le Petit Prince"

Q5 — Le deuxième document
Deuxième document : Auteur "George Orwell"

Q6 — Un document précis
Trouve le document dont le titre est celui de ton livre à auteurs multiples. A-t-il bien un champ auteurs au
pluriel ?

Q7 — Chapitres
Ce même document a-t-il un champ chapitres ? Liste-les.

Le champ chapitres est présent sous forme de tableau (Array (3))

Q8 — Le plus ancien
Trouve le document le plus ancien de la collection.
Livre le plus ancien : "L'Étranger" sorti en 1942.

Q9 — Le plus récent
Trouve le document le plus récent.
Livre le plus récent : "Guide de survie en forêt" sorti en 2020.

Q10 — Champ unique
Un seul document a un champ qui n'existe sur aucun autre. Lequel, et lequel est ce champ ?
Champ unique : Le champ illustrations : true, présent uniquement dans le document "Guide de survie en forêt"

Q11 — Filtre sur une année précise
![](/imges/Q11.png)

 Q12- Filtre ">"
Combien de livres ont été publiés après 2000 ?

Q13 — Filtre "<"
Combien de livres ont été publiés avant 1950 ?
![](/imges/Q13.png)
Q14 — Filtre sur un tableau
Trouve le livre qui contient un chapitre précis.
![](/imges/Q14.png)
Q15 — Filtre sur l'auteur
Trouve un livre à partir du nom exact de son auteur.
![](/imges/Q15.png)
Q16 — Ajouter un champ
Ouvre un document et ajoute-lui un champ note avec une valeur de ton choix.

Q17 — Vérifier l'ajout
Rouvre ce document pour confirmer que le champ est bien là.
![](/imges/Q17.png)
Q18 — Ajouter un document
Insère un nouveau document avec un titre et une année de ton choix.
![](/imges/Q18.png)
Q19 — Vérifier le compteur
Le nombre total de documents a-t-il bien augmenté de 1 ?

Q20 — Supprimer
Supprime ce document ajouté. Le compteur est-il revenu à sa valeur initiale ?
