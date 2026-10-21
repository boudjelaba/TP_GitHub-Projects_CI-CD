# TP — Intégration continue et initiation à la livraison continue

Ce dépôt sert de support au TP consacré à Git, GitHub, GitHub Actions, GitHub Projects, Python et pytest.

## Objectifs

- Préparer un environnement Python isolé.
- Écrire et exécuter des tests.
- Configurer une intégration continue avec GitHub Actions.
- Diagnostiquer puis corriger une régression.
- Utiliser une Issue, une pull request et un tableau GitHub Projects.
- Découvrir les principes de la livraison continue.

## Démarrage

1. Cloner ce dépôt sur votre poste.
2. Suivre les consignes du TP dans l'ordre.
3. Compléter les fichiers du projet au fur et à mesure des étapes.

### Diagnostic de régression

- **Test en échec :** `test_add`
- **Valeur attendue :** `5`
- **Valeur obtenue :** `-1`
- **Cause :** la fonction `add` utilisait la soustraction au lieu de l'addition.
- **Correction :** rétablissement de `return a + b`.
- **Vérification :** les trois tests passent après correction.
