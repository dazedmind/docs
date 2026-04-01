# RLink documentation

Mintlify documentation for [RLink](https://github.com/dazedmind/rlink), the internal admin portal (CMS, CRM, IAM).

## Local preview

Install the [Mintlify CLI](https://www.npmjs.com/package/mint), then from this directory:

```bash
mint dev
```

Open `http://localhost:3000`. Run `mint broken-links` before publishing when the CLI is available.

## Structure

- **`guides/`** — Onboarding, deployment, docs-site customization
- **`reference/`** — Architecture, schema, sitemap
- **`auth/`** — Better Auth and security
- **`operations/`** — Troubleshooting and maintenance
- **`api-reference/`** — API overview and full REST reference

## AI-assisted writing

```bash
npx skills add https://mintlify.com/docs
```

See [AI tools](/ai-tools/cursor) for editor-specific notes.

## Publishing

Connect the Mintlify GitHub app from your [dashboard](https://dashboard.mintlify.com) so pushes deploy the docs site.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [RLink source](https://github.com/dazedmind/rlink)
