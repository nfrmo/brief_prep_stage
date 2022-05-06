# brief_prep_stage
brief_prep_stage

# Gestion de bibliothèque

Creer une interface de gestion de biblithèque permettant de :
- GET /books --> consulter la liste de tout les livres
- POST /books/id --> emprunter un livre
- /admin --> CRUD gerer les livres, il faut pouvoir changer facilement le statut d'un livre (emprunté/rendu/en attente de traitement)

## BONUS:
- authentification
    - admin --> crud
    - client --> reserver un livre
    - client --> consulter la liste de ses livres empruntés
- ajouter un systeme de catégories pour les livres