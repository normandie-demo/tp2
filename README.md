# TP numéro 2

## Objectif:

Démontrer la création d'un utilisateur pour Ansible
Construire un inventaire Ansible

## Besoin:

- Se connecter à *server-4.scc-edu* et créer un utilisateur *ansible* avec comme mot de passe *ansible*
- Depuis *bastion-0* copier la clef ssh sur *ansible@server-4.scc-edu*
- Sur *server-4.scc-edu*, supprimer le mot de passe de l’utilisateur *ansible*
- Créer un fichier nommé *inventory*
- Ajouter 2 groupes *front* et *back*
- Ajouter *server-0.scc-edu* et *server-1.scc-edu* à *front*
- Ajouter *server-2.scc-edu* et *server-3.scc-edu* à *back*
- Ajouter *localhost* avec une connexion de type *local* (hors groupe)
- Ajouter *server-4.scc-edu* avec comme utilisateur de connexion *ansible* (hors groupe)
- Optionnel: utiliser *ansible_host* pour raccourcir le nom de *server-0*
