# Comment contribuer

## Branches
- `main` : stable, protégée, jamais de push direct
- `feature/nom-court` : nouvelle fonctionnalité
- `fix/nom-court` : correction de bug

## Commits (Conventional Commits)
```
feat: ajouter l'export CSV
fix: corriger le calcul de marge
docs: mettre à jour le README
refactor: simplifier le pipeline
chore: mettre à jour les dépendances
```

## Workflow
1. Créer une issue (ou prendre une issue existante)
2. Créer une branche depuis `main`
3. Faire des commits petits et clairs
4. Ouvrir une Pull Request en remplissant le template
5. Attendre 1 review + CI verte
6. Merge (squash), puis supprimer la branche

## Règles
- Une PR = un seul sujet
- Jamais de secrets dans le code (utiliser `.env` et GitHub Secrets)
- Tests demandés pour toute nouvelle logique
- Données sensibles : jamais dans le repo

## Nommage des repos
`kebab-case` avec préfixe : `app-`, `data-`, `lib-`, `infra-`, `poc-`
Exemple : `app-client-dashboard`, `data-sales-forecast`
