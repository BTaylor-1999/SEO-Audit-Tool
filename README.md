# SEO Audit & Strategy Tool

This greenfield project uses [OpenSpec](https://github.com/Fission-AI/OpenSpec) for specification-driven planning before implementation moves into Lovable and Supabase.

## OpenSpec workflow

Install the pinned project dependencies:

```bash
npm install
```

Inspect active changes and validate all artifacts:

```bash
npm run spec:status
npm run spec:validate
```

The initial implementation plan is `bootstrap-seo-audit-platform` under `openspec/changes/`. Review its proposal, capability specs, design, and task checklist before applying it.

To propose another change in Codex, invoke `$openspec-propose` with a description. To begin implementing an approved change, invoke `$openspec-apply-change` with its change name.

Real provider credentials must never be committed. They will be added later as environment-scoped secrets when each integration is enabled.
