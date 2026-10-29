# SilverPan — UX case study

**[English](#english) · [Français](#français)**

---

## English

### Reversing prediabetes, one meal kit at a time.

SilverPan is a meal-kit service for prediabetic seniors. It turns a vague doctor's advice to "eat better" into personalised, ready-to-cook boxes designed by nutritionists.

It targets the narrow window, HbA1c 5.7–6.4%, where change is still reversible.

| | |
|---|---|
| **Context** | Master in Interaction Design, SUPSI (Switzerland), 2020 |
| **Partner** | Spark Reply, Milan |
| **Team** | Ana Gasharova, Anne Kwaro, Mihir Joshi, Rishabh Hattikudur |
| **My role** | User research & wireframes |
| **Methods** | Desk research, interviews, persona mapping, journey map, IA, wireframes, UI |

### The brief

Spark Reply asked us to design a service across several touchpoints, focused on the health and wellbeing of people over 65. We started from a definition of healthy ageing that does not require being free of illness, which pointed us toward a condition that is common, silent, and still reversible: prediabetes.

### Key findings

- **352M** people worldwide were prediabetic in 2017, and **50%** of them were over 50.
- **24.2M** Americans aged 65+ were prediabetic (figure used in 2020). The CDC now estimates **31.3M**.
- We interviewed 4 prediabetic and 3 diabetic people, 1 doctor and 1 nutritionist (Switzerland, India, Italy, Kenya).
- **The real divide is willingness, not knowledge.** Our target is motivated, but has no easy way to act.

### Approach

Using **BJ Fogg's Behaviour Model** (Behaviour = Motivation × Ability × Prompt), we found seniors already had the motivation. What they lacked was ability. So we made the healthy choice the easy one:

- **Motivation:** a plan with her name on it
- **Ability:** pre-portioned ingredients and a recipe, delivered
- **Prompt:** "Here is your plan for the day"

The concept: a platform where people over 65 with prediabetes buy or subscribe to meal kits designed by experts. It is built on six principles: meal kit, familiar, simple, less distraction, less legwork, engaging.

### Value proposition

> The only service designed for prediabetic seniors that helps them shift to a healthy diet, with personalised, ready-to-cook meal kits composed by nutritionists.
>
> **Shop easy, eat healthy.**

### Deliverables in the case study

Personas (Marie, Samuel, Rahul, Dr. Ranieri) · persona map · market gap analysis · user journey · five-tab information architecture · 11-step wireframe flow · final UI · [prototype video](https://vimeo.com/459934222)

### What I would do next

- **Test with seniors:** run usability sessions on onboarding and the six-question quiz.
- **Accessibility first:** larger text, stronger contrast and bigger touch targets, checked against WCAG 2.2 AA.
- **Close the loop with doctors:** a shareable weekly summary of what the patient cooked.
- **Build it:** I'm rebuilding SilverPan as a working Angular app.

---

## Français

### Inverser le prédiabète, un panier-repas à la fois.

SilverPan est un service de paniers-repas pour seniors prédiabétiques. Il transforme le conseil flou du médecin, « mangez mieux », en box personnalisées et prêtes à cuisiner, conçues par des nutritionnistes.

Il cible l'étroite fenêtre, HbA1c entre 5,7 et 6,4 %, où le changement reste réversible.

| | |
|---|---|
| **Contexte** | Master en Interaction Design, SUPSI (Suisse), 2020 |
| **Partenaire** | Spark Reply, Milan |
| **Équipe** | Ana Gasharova, Anne Kwaro, Mihir Joshi, Rishabh Hattikudur |
| **Mon rôle** | Recherche utilisateur et wireframes |
| **Méthodes** | Recherche documentaire, entretiens, mapping de personas, parcours, architecture de l'information, wireframes, UI |

### Le brief

Spark Reply nous a demandé de concevoir un service sur plusieurs points de contact, centré sur la santé et le bien-être des plus de 65 ans. Nous sommes partis d'une définition du bien-vieillir qui n'exige pas d'être en parfaite santé. Ce cadrage nous a orientés vers une condition fréquente, silencieuse et encore réversible : le prédiabète.

### Constats clés

- **352 M** de personnes étaient prédiabétiques dans le monde en 2017, dont **50 %** avaient plus de 50 ans.
- **24,2 M** d'Américains de 65 ans et plus étaient prédiabétiques (chiffre utilisé en 2020). Le CDC en estime désormais **31,3 M**.
- Nous avons interrogé 4 personnes prédiabétiques, 3 diabétiques, 1 médecin et 1 nutritionniste (Suisse, Inde, Italie, Kenya).
- **Le vrai clivage, c'est la volonté, pas le savoir.** Notre cible est motivée, mais sans moyen simple d'agir.

### Démarche

Avec le **modèle comportemental de BJ Fogg** (Comportement = Motivation × Capacité × Déclencheur), nous avons constaté que les seniors étaient déjà motivés. Ce qui leur manquait, c'était la capacité. Nous avons donc rendu le bon choix facile :

- **Motivation :** un plan à son nom
- **Capacité :** ingrédients prédosés et recette, livrés
- **Déclencheur :** « Voici votre programme du jour »

Le concept : une plateforme où les plus de 65 ans prédiabétiques achètent ou s'abonnent à des paniers-repas conçus par des experts. Il repose sur six principes : panier-repas, familier, simple, moins de tentations, moins d'effort, engageant.

### Proposition de valeur

> Le seul service conçu pour les seniors prédiabétiques qui les aide à adopter une alimentation saine, grâce à des paniers-repas personnalisés, prêts à cuisiner et composés par des nutritionnistes.
>
> **Achetez simple, mangez sain.**

### Livrables présentés

Personas (Marie, Samuel, Rahul, Dr Ranieri) · mapping des personas · analyse du marché · parcours utilisateur · architecture de l'information en cinq onglets · parcours wireframe en 11 étapes · design final · [vidéo du prototype](https://vimeo.com/459934222)

### Ce que je ferais ensuite

- **Tester avec des seniors :** tests d'utilisabilité sur l'inscription et le questionnaire en six questions.
- **Accessibilité d'abord :** texte plus grand, contraste renforcé, zones tactiles adaptées, selon le RGAA et les WCAG 2.2 AA.
- **Impliquer les médecins :** un récapitulatif hebdomadaire partageable des repas cuisinés.
- **Le développer :** je reconstruis SilverPan en application Angular fonctionnelle.

---

## Deploy / Déploiement

The site is a single static file (`index.html`) with no build step. / Le site est un fichier statique unique (`index.html`), sans étape de build.

**Vercel**

1. Import this repo at [vercel.com/new](https://vercel.com/new). / Importer ce dépôt sur [vercel.com/new](https://vercel.com/new).
2. Framework preset: **Other**. Leave build command and output directory empty. / Preset : **Other**. Laisser la commande de build et le dossier de sortie vides.
3. Deploy. / Déployer.

**Language / Langue:** the page picks English or French from the browser language. Force one with `#en` or `#fr` in the URL. / La page choisit l'anglais ou le français selon la langue du navigateur. Pour forcer une langue, ajouter `#en` ou `#fr` à l'URL.

**Local preview / Aperçu local:** open `index.html` in a browser. / Ouvrir `index.html` dans un navigateur.

---

Anne Kwaro · UX designer & web developer, Grenoble · [linkedin.com/in/anne-kwaro](https://www.linkedin.com/in/anne-kwaro)
