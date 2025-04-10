# Guide de contribution

Merci de votre intérêt pour contribuer à la documentation de Qlub ! Ce guide vous aidera à comprendre comment participer au projet.

## Comment contribuer

### 1. Signaler un problème
- Utilisez l'onglet "Issues" sur GitHub
- Décrivez le problème en détail
- Incluez des captures d'écran si pertinent
- Suivez le template fourni

### 2. Proposer une modification
1. Fork le dépôt
2. Créez une branche (`git checkout -b feature/ma-modification`)
3. Committez vos changements (`git commit -am 'Ajout de...'`)
4. Push vers la branche (`git push origin feature/ma-modification`)
5. Créez une Pull Request

### 3. Améliorer la documentation
- Corriger les erreurs
- Ajouter des exemples
- Améliorer la clarté
- Mettre à jour les captures d'écran

## Standards de documentation

### Style d'écriture
- Utilisez un ton professionnel mais accessible
- Évitez le jargon technique inutile
- Soyez concis et clair
- Utilisez des exemples concrets

### Format Markdown
- Utilisez les titres de manière hiérarchique
- Incluez des descriptions pour les images
- Utilisez des listes pour la clarté
- Ajoutez des liens pertinents

### Captures d'écran
- Suivez les spécifications dans `docs/screenshots/README.md`
- Optimisez les images
- Ajoutez des descriptions alt
- Maintenez la cohérence visuelle

## Processus de revue

### Pull Requests
1. Vérifiez que votre PR suit les standards
2. Attendez la revue des mainteneurs
3. Répondez aux commentaires
4. Effectuez les modifications demandées

### Critères d'acceptation
- Documentation claire et précise
- Respect des standards
- Tests effectués
- Pas de régression

## Structure du projet

```
docs/
├── _config.yml          # Configuration Jekyll
├── index.md            # Page d'accueil
├── guides/            # Guides détaillés
│   ├── publishing.md
│   ├── networking.md
│   └── moderation.md
└── screenshots/       # Captures d'écran
    ├── publishing/
    ├── networking/
    └── moderation/
```

## Ressources

- [Guide Markdown](https://www.markdownguide.org/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages](https://pages.github.com/)
- [Style Guide](style-guide.md)

## Contact

- Documentation : docs@qlub.social
- Support : support@qlub.social
- Modération : moderation@qlub.social 