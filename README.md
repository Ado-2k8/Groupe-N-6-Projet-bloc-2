# Groupe-N-6-Projet-bloc-2
# Architecture logicielle — DevStart Agency
**Bloc 2 · Module 2 · Académie de Programmation IFRI**
Groupe 4 · L1 Informatique · Avril 2026

---

## C'est quoi ce projet ?

On repart du code analysé au Module 1 — la page du stagiaire de **DevStart Agency**.
Cette fois, notre mission n'est pas de lire ni de réécrire : c'est de **concevoir une architecture**.

Avant d'écrire une seule ligne de code, on a réfléchi à comment organiser les fichiers,
les composants et les responsabilités pour que le projet reste maintenable quand il grossit.

> On n'a pas codé. On a **conçu**.

---

## Le principe directeur

Tout ce module repose sur une seule règle :

```
Une partie du code = Une seule responsabilité
```

Si tu dois expliquer ce que fait un fichier et que ta réponse contient le mot **«et»**,
c'est qu'il fait trop de choses.

---

## Structure du dépôt

```
/original      → Le code source du Module 1, non touché (branche main)
/module2       → Le code réorganisé selon notre architecture (branche module2)
README.md      → Ce fichier
```

> **Branches GitHub**
> - `main` — code original du Module 1, intact
> - `module2` — code découpé et réorganisé selon notre plan d'architecture

---

## Notre démarche

### Jour 1-2 — Cartographie
On a ouvert le fichier `style.css` et listé toutes les sections qu'il couvrait.
On a identifié chaque bloc HTML, ses dépendances (images, liens, textes),
et les règles CSS à lui associer. Résultat : un schéma de cartographie de la page existante.

### Jour 3-4 — Conception de l'architecture
On a conçu la nouvelle structure de dossiers **sur papier d'abord**, puis on l'a formalisée.
Pour chaque fichier CSS prévu, on a écrit son nom, sa responsabilité en une phrase,
et les éléments qu'il allait gérer. On a aussi prévu les futures pages (Portfolio, Blog, Espace Client).

### Jour 5 — Implémentation & Présentation
On a découpé le `style.css` du stagiaire en fichiers séparés, vérifié que la page
restait visuellement identique, puis présenté et défendu nos choix devant l'académie.

---

## Architecture cible

```
index.html
styles/
├── base.css          → Reset, variables, typographie globale
├── header.css        → Navigation et logo
├── hero.css          → Section d'accroche
├── services.css      → Cartes services
├── about.css         → Section À propos
├── testimonials.css  → Témoignages clients
├── contact.css       → Formulaire de contact
└── footer.css        → Pied de page
```

---

## Ce qu'on a livré

- Schéma de cartographie de la page existante
- Schéma de la structure de dossiers cible (avec justifications)
- Tableau des fichiers : nom · responsabilité · éléments gérés
- Stratégie d'évolution pour les futures pages
- Code réorganisé sur la branche `module2`
- Rapport d'architecture (PDF)


---

## Membres du groupe

| Membre | Rôle | Phase principale |
|---|---|---|
| Egbêhitchè Hermione Adorée  KPENONHOUN| Chef de groupe et responsable synthèse | Cartographie, Témoinage et service |
|  Orphéric Géovany SANGNIDJO|Responsable technique  | Base, Header et implémentation |
| John Elie LOKOSSOU| Appui a la mise en forme | A propos |
| Bilal Fernand Pers PEDRO| Rédacteur | Footer et stratégie d'évolution |
|Farel Kant MAHUGNON AHIDEDJI | Coordonnateur |Contact, Hero et rapport  |


---

*Académie de Programmation · IFRI · 2026*# Groupe-N-6-Projet-bloc-2






