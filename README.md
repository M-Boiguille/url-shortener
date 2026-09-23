# url-shortener

Petite API de raccourcissement d'URL (**FastAPI** + **PostgreSQL**), fil rouge
pour apprendre le DevOps de bout en bout : Docker local → k3s → CI/CD →
Terraform/AWS → GitOps → EKS.

## Endpoints
- `POST /api/shorten` → 201
- `GET /{short}` → 302
- `GET /healthz` → 200

## Statut
Étape 1 — bootstrap du dépôt.

## Architecture cible
> À compléter au fil des étapes (diagramme final à l'étape 20).

## Lancer
> À compléter à l'étape 3 (Docker).
