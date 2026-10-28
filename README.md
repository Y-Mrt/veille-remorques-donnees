# Données de la veille remorques porte-voiture

Ce dépôt ne contient que `annonces.json`, écrit deux fois par jour par la tâche planifiée Claude.

Le dépôt [veille-remorques](https://github.com/Y-Mrt/veille-remorques) le récupère toutes les 15 minutes, le vérifie avec son propre contrôleur (`scripts/validate_annonces.py`) et ne publie sur le site que des données valides. Rien d'autre de ce dépôt n'est utilisé.

L'app GitHub de Claude n'a accès qu'à ce dépôt : la tâche planifiée ne peut donc pas modifier le site, l'application ni les workflows. Les Actions sont désactivées ici.
