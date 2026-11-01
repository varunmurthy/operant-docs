# Operant Health help center

Customer-facing help for practices using Operant Health, built with [Mintlify](https://mintlify.com).

```bash
npx mint dev            # preview at http://localhost:3000
npx mint broken-links   # check internal links
npx mint validate       # strict build check
```

Pushing to `main` publishes the site to https://help.operanthealth.com (also https://operant-health.mintlify.app). Mintlify skips commits that change no files. Writing and accuracy rules are in [AGENTS.md](AGENTS.md).

Keep the base path empty in the Mintlify dashboard. Adding a domain with the `/docs` base path moves every page under `/docs` on every domain.
