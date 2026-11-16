# url-shortener

Petite API de raccourcissement d'URL (**FastAPI** + **PostgreSQL**), fil rouge
pour apprendre le DevOps de bout en bout : Docker local → k3s → CI/CD →
Terraform/AWS → GitOps → EKS.

## Endpoints
- `POST /api/shorten` → 201
- `GET /{short}` → 302
- `GET /healthz` → 200

## Statut
Étape 1 — bootstrap du dépôt. L'API et son environnement d'exécution seront
ajoutés au fil des étapes ; les endpoints ci-dessus décrivent la cible.

## Architecture cible
> À compléter au fil des étapes (diagramme final à l'étape 20).

## Lancer
Le lancement local sera documenté à l'étape 3, avec la configuration Docker.
À ce stade, le dépôt ne contient pas encore d'application exécutable.

## Développement
- Consultez [`docs/development.md`](docs/development.md) pour le parcours de
  développement prévu.
- Consultez [`docs/quality-checklist.md`](docs/quality-checklist.md) pour les
  vérifications à effectuer avant de valider une étape.
