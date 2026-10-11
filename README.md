# NessFlow MCP

## English

NessFlow audits websites (technical health, content and AI-answer readiness, accessibility, acquisition, crawlability) and follows their visibility over time. The connector gives your assistant access to these audits, for the team you choose when you connect.

### Server address

```
https://mcp.nessflow.com/mcp
```

This is the only official address of the NessFlow connector. Any other address claiming to be NessFlow is not ours.

### Connect your assistant

- **Claude**: Settings, Connectors, Add custom connector, then paste the server address.
- **ChatGPT**: Settings, Apps and Connectors, Create, then paste the server address.
- **Le Chat**: Intelligence, Connectors, Add connector, Custom MCP, then paste the server address.
- **Cursor**: [install in one click](cursor://anysphere.cursor-deeplink/mcp/install?name=nessflow&config=eyJ1cmwiOiJodHRwczovL21jcC5uZXNzZmxvdy5jb20vbWNwIn0=)
- **VS Code**: [install in one click](vscode:mcp/install?%7B%22name%22%3A%22nessflow%22%2C%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.nessflow.com%2Fmcp%22%7D)
- **Claude Code**:

```sh
claude mcp add --transport http nessflow https://mcp.nessflow.com/mcp
```

### What you can ask

- What changed on my site since the last audit, and which regressions are real?
- Write a one page report for my client on this month’s audit.
- Which ten fixes should I do first, ranked by impact and effort?
- Which keywords lost the most positions this month, and on which pages?
- Across all my projects, which site needs my attention this week?

More examples, with the tools each one calls: [examples/prompts.md](examples/prompts.md).

### What stays under your control

You choose the rights when you connect. Any action that uses your plan (an audit, a recommendation run, a ranking check) is quoted first and runs only after you confirm. Every action is logged in NessFlow, and you can disconnect the assistant in one click.

### Plans

| Plan | Read your audits | Launch audits and actions | Assistant connections |
|---|---|---|---|
| Starter | yes | no | 2 |
| Pro | yes | yes | 5 |
| Agency | yes | yes | 15 |
| Scale | yes | yes | 30 |

### Links

- https://nessflow.com
- The AI connector: https://nessflow.com/en/ai-connector
- Connector documentation: https://nessflow.com/en/developers/mcp-connector
- Tool catalogue: [TOOLS.md](TOOLS.md)
- Report a problem: [SECURITY.md](SECURITY.md)

> This repository is generated from the NessFlow service. Manual changes are overwritten by the next export.

## Français

NessFlow audite des sites (santé technique, contenu et lisibilité par les moteurs de réponse, accessibilité, acquisition, exploration) et suit leur visibilité dans le temps. Le connecteur donne à votre assistant l’accès à ces audits, pour l’équipe que vous choisissez à la connexion.

### Adresse du serveur

```
https://mcp.nessflow.com/mcp
```

C’est la seule adresse officielle du connecteur NessFlow. Toute autre adresse qui se présente comme NessFlow n’est pas la nôtre.

### Brancher votre assistant

- **Claude** : Paramètres, Connecteurs, Ajouter un connecteur personnalisé, puis collez l’adresse du serveur.
- **ChatGPT** : Paramètres, Applications et connecteurs, Créer, puis collez l’adresse du serveur.
- **Le Chat** : Intelligence, Connecteurs, Ajouter un connecteur, MCP personnalisé, puis collez l’adresse du serveur.
- **Cursor** : [installer en un clic](cursor://anysphere.cursor-deeplink/mcp/install?name=nessflow&config=eyJ1cmwiOiJodHRwczovL21jcC5uZXNzZmxvdy5jb20vbWNwIn0=)
- **VS Code** : [installer en un clic](vscode:mcp/install?%7B%22name%22%3A%22nessflow%22%2C%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.nessflow.com%2Fmcp%22%7D)
- **Claude Code** :

```sh
claude mcp add --transport http nessflow https://mcp.nessflow.com/mcp
```

### Ce que vous pouvez demander

- Qu’est-ce qui a changé sur mon site depuis le dernier audit, et quelles régressions sont réelles ?
- Rédige pour mon client un rapport d’une page sur l’audit du mois.
- Quelles sont les dix corrections à faire en premier, classées par impact et effort ?
- Quels mots-clés ont le plus perdu de positions ce mois-ci, et sur quelles pages ?
- Parmi tous mes projets, quel site demande mon attention cette semaine ?

D’autres exemples, avec les outils que chacun appelle : [examples/prompts.md](examples/prompts.md).

### Ce qui reste sous votre contrôle

Vous choisissez les droits à la connexion. Toute action qui consomme votre offre (un audit, une génération de recommandations, une vérification de position) fait d’abord l’objet d’un devis et ne part qu’après votre confirmation. Chaque action est journalisée dans NessFlow, et vous déconnectez l’assistant en un clic.

### Offres

| Offre | Lire vos audits | Lancer audits et actions | Connexions d’assistant |
|---|---|---|---|
| Starter | oui | non | 2 |
| Pro | oui | oui | 5 |
| Agency | oui | oui | 15 |
| Scale | oui | oui | 30 |

### Liens

- https://nessflow.com
- Le connecteur IA : https://nessflow.com/fr/connecteur-ia
- Documentation du connecteur : https://nessflow.com/fr/developpeurs/connecteur-mcp
- Catalogue d’outils : [TOOLS.md](TOOLS.md)
- Signaler un problème : [SECURITY.md](SECURITY.md)

> Ce dépôt est généré depuis le service NessFlow. Toute modification manuelle est écrasée par l’export suivant.
