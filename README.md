# HenriettSante

Site web vitrine autour de la santé, avec plusieurs pages d'information et de services.

## Aperçu du projet

Le projet est organise en deux grands espaces :

- `code/frontend` : pages HTML et feuilles de style CSS.
- `code/backend` : reserve pour la partie serveur (a completer selon les besoins).

## Arborescence

```text
henriettsante/
├── code/
│   ├── backend/
│   ├── frontend/
│   │   ├── css/
│   │   │   ├── common.css
│   │   │   ├── index.css
│   │   │   └── service.css
│   │   └── html/
│   │       ├── abonne.html
│   │       ├── contact.html
│   │       ├── inscription.html
│   │       ├── prevention.html
│   │       └── services.html
│   ├── photos/
│   └── index.html
├── docs/
└── README.md
```

## Pages disponibles

- `code/index.html` : page d'accueil.
- `code/frontend/html/services.html` : presentation des services.
- `code/frontend/html/prevention.html` : contenu prevention.
- `code/frontend/html/inscription.html` : formulaire d'inscription.
- `code/frontend/html/contact.html` : page de contact.
- `code/frontend/html/abonne.html` : espace abonnement.

## Lancer le projet en local

Le projet est statique (HTML/CSS), donc plusieurs options sont possibles :

1. Ouvrir directement `code/index.html` dans le navigateur.
2. Ou demarrer un petit serveur local (recommande), par exemple avec VS Code Live Server.

Exemple avec Python :

```bash
cd code
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Conventions actuelles

- HTML dans `code/frontend/html`.
- CSS mutualise dans `common.css`.
- CSS specifique par page dans des fichiers dedies (ex. `index.css`, `service.css`).
- Images dans `code/photos`.

## Pistes d'amelioration

- Renommer `service.css` en `services.css` pour correspondre a `services.html`.
- Ajouter un dossier `code/frontend/js/` pour preparer les scripts futurs.
- Completer `code/backend/` quand une API ou une logique serveur sera necessaire.
- Documenter les choix UI/UX dans `docs/`.

## Auteur

Projet realise pour la plateforme HenriettSante.
