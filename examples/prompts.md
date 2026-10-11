# Prompts

## English

Words in braces, such as {project}, stand for your own project, campaign, keyword or domain.

### Understand what changed since the last audit

> Compare the latest audit of {project} with the previous one. Separate real regressions, noise, and what you cannot decide for lack of measurement. For each real regression, give the most affected page.

The real regressions, told apart from what cannot be measured yet.

- Tools called: `nessflow_crawls_compare`, `nessflow_issues_summary_get`, `nessflow_issues_list`
- From plan: Starter

### Prepare the client report

> Prepare the monthly report of {project} for my client: what improved, what regressed, what cannot be measured yet. Ten lines at most, every figure with its denominator.

A client report in seconds, with sourced figures.

- Tools called: `nessflow_project_scorecard_get`, `nessflow_crawls_compare`, `nessflow_recommendations_get`
- From plan: Starter

### Prioritise fixes

> Which ten fixes would raise the health score of {project} the most for the least effort? For each: the pillar it touches, the number of pages, and an example URL.

A list of fixes ranked by impact and effort.

- Tools called: `nessflow_recommendations_get`, `nessflow_project_scorecard_get`
- From plan: Starter

### Check that a fix worked

> I fixed the title tags of the product pages. Run the audit of {campaign} again, tell me first what it will use, then remind me when we can conclude whether the fix worked.

The fix then verify cycle, with a quote before any spending.

- Tools called: `nessflow_crawl_launch`, `nessflow_crawl_get`, `nessflow_crawls_compare`
- From plan: Pro
- Uses your plan: quoted before it runs.

### Find orphan pages that get traffic

> Which pages of {project} are orphans or more than four clicks from the home page, and which of them still get Search Console traffic?

Internal linking crossed with visibility, which nobody does by hand.

- Tools called: `nessflow_crawl_structure_get`, `nessflow_search_console_get`
- From plan: Starter

### Build this month’s action plan

> Build the SEO action plan of {project} for this month from its recommendations: three workstreams at most, ranked by impact and effort, with the health score pillar each one improves.

A short, reasoned plan drawn from the project’s recommendations.

- Tools called: `nessflow_project_scorecard_get`, `nessflow_recommendations_get`
- From plan: Starter

### Know which AI crawlers can read the site

> Which AI answer engine crawlers are allowed to read {project}, which are blocked, and is the rule blocking them intended or accidental?

AI crawler access, read from the site’s actual rules.

- Tools called: `nessflow_crawl_geo_get`
- From plan: Starter

### Measure readability by AI engines

> Is my website readable by AI answer engines? Give the GEO score of {project}, the three main blockers, and the most exemplary page to imitate.

The GEO module, explained by the assistant itself.

- Tools called: `nessflow_crawl_geo_get`, `nessflow_pages_list`
- From plan: Starter

### Review the portfolio

> Go through all my projects: which one dropped the most since its last audit, and why? Ignore those whose audit is too recent to conclude.

An agency portfolio in a single question.

- Tools called: `nessflow_projects_list`, `nessflow_project_scorecard_get`, `nessflow_crawls_compare`
- From plan: Starter

## Français

Les mots entre accolades, comme {project}, désignent votre projet, votre campagne, votre mot-clé ou votre domaine.

### Comprendre ce qui a changé depuis le dernier audit

> Compare le dernier audit de {project} au précédent. Sépare les régressions réelles, le bruit, et ce que tu ne peux pas trancher faute de mesure. Pour chaque régression réelle, donne la page la plus touchée.

Les vraies régressions, distinguées de ce qui n’est pas encore mesurable.

- Outils appelés : `nessflow_crawls_compare`, `nessflow_issues_summary_get`, `nessflow_issues_list`
- Dès l’offre : Starter

### Préparer le compte rendu client

> Prépare le compte rendu mensuel de {project} pour mon client : ce qui a progressé, ce qui a régressé, ce qui n’est pas encore mesurable. Dix lignes maximum, chaque chiffre avec son dénominateur.

Un compte rendu client en quelques secondes, chiffres sourcés.

- Outils appelés : `nessflow_project_scorecard_get`, `nessflow_crawls_compare`, `nessflow_recommendations_get`
- Dès l’offre : Starter

### Prioriser les correctifs

> Quels sont les dix correctifs qui feraient le plus monter le score de santé de {project} pour le moins d’effort ? Pour chacun : le pilier touché, le nombre de pages, et un exemple d’URL.

Une liste de correctifs classée par impact et effort.

- Outils appelés : `nessflow_recommendations_get`, `nessflow_project_scorecard_get`
- Dès l’offre : Starter

### Vérifier qu’une correction a marché

> J’ai corrigé les balises title des fiches produit. Relance l’audit de {campaign}, dis-moi d’abord ce que ça va consommer, puis rappelle-moi quand on pourra conclure si la correction a marché.

Le cycle corriger puis vérifier, avec un devis avant toute dépense.

- Outils appelés : `nessflow_crawl_launch`, `nessflow_crawl_get`, `nessflow_crawls_compare`
- Dès l’offre : Pro
- Consomme votre offre : devis avant exécution.

### Trouver les pages orphelines qui ont du trafic

> Quelles pages de {project} sont orphelines ou à plus de quatre clics de l’accueil, et lesquelles reçoivent pourtant du trafic Search Console ?

Le croisement maillage et visibilité, que personne ne fait à la main.

- Outils appelés : `nessflow_crawl_structure_get`, `nessflow_search_console_get`
- Dès l’offre : Starter

### Bâtir le plan d’action du mois

> Construis le plan d’action SEO de {project} pour ce mois-ci à partir de ses recommandations : trois chantiers au maximum, classés par impact et effort, avec le pilier du score de santé que chacun fait progresser.

Un plan court et argumenté, tiré des recommandations du projet.

- Outils appelés : `nessflow_project_scorecard_get`, `nessflow_recommendations_get`
- Dès l’offre : Starter

### Savoir quels robots IA peuvent lire le site

> Quels robots des moteurs de réponse IA ont le droit de lire {project}, lesquels sont bloqués, et la règle qui les bloque est-elle voulue ou accidentelle ?

L’accès des robots IA, lu dans les règles réelles du site.

- Outils appelés : `nessflow_crawl_geo_get`
- Dès l’offre : Starter

### Mesurer la lisibilité par les moteurs IA

> Mon site est-il lisible par les moteurs de réponse IA ? Donne le score GEO de {project}, les trois blocages principaux, et la page la plus exemplaire à imiter.

Le module GEO, expliqué par l’assistant lui-même.

- Outils appelés : `nessflow_crawl_geo_get`, `nessflow_pages_list`
- Dès l’offre : Starter

### Faire le tour du portefeuille

> Fais le tour de tous mes projets : lequel a le plus baissé depuis son dernier audit, et pourquoi ? Ignore ceux dont l’audit est trop récent pour conclure.

Le portefeuille d’une agence en une question.

- Outils appelés : `nessflow_projects_list`, `nessflow_project_scorecard_get`, `nessflow_crawls_compare`
- Dès l’offre : Starter
