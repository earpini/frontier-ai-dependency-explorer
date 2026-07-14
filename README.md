# Frontier AI Dependency Explorer

An interactive map of how frontier AI models are governed and where geopolitical leverage sits across the AI value chain.

## Purpose

The explorer addresses two questions:

1. How are frontier AI models governed today?
2. Which countries, institutions, firms, and infrastructure providers hold power over their development and deployment—and why?

## Main views

- **Overview** — a simplified visual of governance above frontier labs and enabling dependencies below them.
- **Geopolitics** — countries, institutions, firms, resources, agreements, and policies organized by strategic role.
- **Map** — geographic leverage and cross-border supply, dependency, and diplomatic relationships.
- **Network diagram** — a relationship-driven network with PageRank, betweenness, degree, and weighted-degree sizing.
- **Value chain** — governance, security, and verification above country contributions and horizontal value-chain stages.
- **References** — source library and connection-level evidence register.

## Evidence methodology

Connections are classified as directly documented relationships, formal institutional memberships, regulatory or jurisdictional reach, or analytical inferences from documented dependencies. The References view explains what each line represents and links to its supporting sources.

The explorer is a qualitative strategic model, not a trade-flow database. Inclusion signals analytical relevance; it does not imply equivalence among actors or quantify leverage with precision.

## Run locally

No installation or build process is required. Open `index.html` in a modern browser.

For a local web server, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

In the repository settings, open **Pages** and select:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

GitHub Pages will serve `index.html` as the homepage.

## Data vintage and limitations

The current research reflects sources and policy developments available through 2026. Laws, institutional memberships, company relationships, export controls, and supply-chain dependencies can change quickly. Verify important claims against the primary sources linked in the explorer before policy or publication use.

## License

Released under the MIT License. Linked third-party sources remain subject to their original terms.
