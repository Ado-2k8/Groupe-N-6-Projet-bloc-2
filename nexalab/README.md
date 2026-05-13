# NexaLab - Page d'accueil

## Présentation

NexaLab est un laboratoire fictif d'innovation technologique pour les entreprises africaines. Cette page d'accueil présente son identité, sa mission, ses expertises, son impact, son équipe, des témoignages clients et un formulaire de contact.

Le projet respecte les contraintes du cahier des charges : HTML5 sémantique, CSS modulaire, responsive design, Flexbox, aucune dépendance JavaScript et aucun framework.

## Structure du projet

```text
nexalab/
├── index.html
├── README.md
├── assets/
│   ├── icons/
│   └── images/
│       └── icons/
└── styles/
    ├── base.css
    ├── header.css
    ├── hero.css
    ├── about.css
    ├── services.css
    ├── stats.css
    ├── team.css
    ├── testimonials.css
    ├── contact.css
    └── footer.css
```

Cette organisation sépare clairement la structure HTML, les ressources visuelles et les styles. Chaque section dispose de son propre fichier CSS pour faciliter la lecture, la maintenance et les modifications futures.

## Responsabilités des fichiers CSS

| Fichier | Responsabilité | Éléments gérés |
| --- | --- | --- |
| `base.css` | Fondations globales | Variables, reset, typographie, boutons, focus, effets réutilisables |
| `header.css` | En-tête | Logo, navigation, menu responsive |
| `hero.css` | Première section | Accroche, CTA, visuel principal, badges technologiques |
| `about.css` | Mission | Présentation de NexaLab, valeurs, cartes de différenciation |
| `services.css` | Expertises | Cartes IA, Data, cybersécurité |
| `stats.css` | Chiffres clés | Indicateurs d'impact et statistiques crédibles |
| `team.css` | Équipe | Membres principaux et rôles |
| `testimonials.css` | Témoignages | Avis clients, étoiles, auteurs |
| `contact.css` | Contact | Informations, formulaire stylisé, inputs |
| `footer.css` | Pied de page | Liens, identité, email, copyright |

## Logique de nommage

Les classes sont nommées en anglais, avec des noms descriptifs liés au rôle de l'élément : `service-card`, `team-avatar`, `stats-grid`, `contact-form`. Les identifiants correspondent aux sections principales pour permettre la navigation interne : `#hero`, `#services`, `#stats`, `#team`, `#contact`.

## Choix de design

L'identité visuelle repose sur un univers sombre, technologique et professionnel :

- fond bleu nuit pour inspirer la rigueur et la confiance ;
- accent cyan pour évoquer la data, l'innovation et la précision ;
- typographie `Sora` pour les titres et `Inter` pour le texte courant ;
- cartes sombres, bordures discrètes et effets de verre pour renforcer l'ambiance laboratoire ;
- SVG local pour éviter toute dépendance à une image externe non maîtrisée.

## Responsive design

Le site utilise Flexbox pour les mises en page principales. Les media queries adaptent les sections aux écrans mobiles jusqu'à `768px` : colonnes empilées, largeur complète, espacements réduits et navigation simplifiée.

## Ajouter une nouvelle page

Pour ajouter une nouvelle page :

1. Créer un fichier HTML dédié, par exemple `about.html`.
2. Réutiliser `base.css`, `header.css` et `footer.css`.
3. Créer un fichier CSS spécifique à la page si nécessaire.
4. Ajouter les liens de navigation dans le header et le footer.
5. Garder la même logique de nommage et les mêmes variables de design.

## Membres et commits

Le développement doit continuer sur la branche `projet-integrateur` avec des commits réguliers, explicites et professionnels.
