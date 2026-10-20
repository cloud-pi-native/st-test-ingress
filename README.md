# Déploiement de test NGINX pour la serviceTeam

## Contenu
- `image/` : image NGINX avec page HTML de test.
- `helm/nginx-test/` : chart Helm de test

## 1. Construire et publier l'image

cf. fichier .gitlab-ci-dso.yml

## 2. Déployer sur OpenShift

ajouter le repo de code, créer un environnement et un déploiement.