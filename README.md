# powerbi-formation — domaine Commercial

Dépôt d’exercice de la formation Git & CI/CD Power BI. Public, sans contenu client.

- `.github/workflows/` : le contrôle des bonnes pratiques (sur chaque pull request) et le déploiement.
- `.github/regles/` : les règles Tabular Editor (modèles) et PBI Inspector (rapports).
- `.github/config/Mapping_repo_deploymentPipeline.json` : quel deployment pipeline déploie quel dossier.
- `PowerBI/Commercial/` : le contenu synchronisé du workspace de dev. **C’est ici que vous enregistrez vos rapports au format pbip.**

Branches protégées : `dev` (pull request + contrôle obligatoire) et `main` (pull request + une approbation).
Les branches de travail se nomment `feature/…` ou `hotfix/…`.
