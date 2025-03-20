# basic-docker-project
## Automatisation CI/CD

Le pipeline CI/CD est configuré avec GitHub Actions pour automatiser la construction et le push de l'image Docker vers DockerHub à chaque modification sur la branche `main`.

1. Le fichier de workflow se trouve dans `.github/workflows/docker-push.yml`.
2. Les secrets `DOCKERHUB_USERNAME` et `DOCKERHUB_TOKEN` doivent être configurés dans les paramètres du dépôt GitHub.
3. L'image est automatiquement poussée vers DockerHub après chaque commit sur la branche `main`.