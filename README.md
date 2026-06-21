# Alvise Dei Rossi Personal Website

Personal website for future job applications, built from the HugoBlox Academic CV template.

The first version is optimized for industry R&D roles after the PhD, especially work around machine learning for physiological time series, wearable sensing, sleep, reliable generalization, and health AI. Academic credibility remains visible through selected publications, projects, teaching, supervision, and reviewing service.

## Main Workflow

The normal workflow does not require a local Hugo install:

1. Edit Markdown/YAML content in this repo.
2. Commit and push to GitHub.
3. GitHub Actions builds the HugoBlox site and deploys it to GitHub Pages.

This follows the official HugoBlox deployment model: the hosted pipeline owns the toolchain, while the repo remains plain Markdown and configuration.

## Optional Local Setup

Required tools:

- Hugo Extended, matching the version expected in `hugoblox.yaml`
- Go, required by Hugo Modules
- Node.js
- pnpm

Useful commands:

```powershell
pnpm install
pnpm run dev
pnpm run build
```

Local builds are useful for fast preview, but they are not required for deployment.

## Deployment

The intended deployment target is GitHub Pages from the user-site repository:

```text
https://github.com/Vaeliss/vaeliss.github.io.git
```

The public site URL is:

```text
https://vaeliss.github.io/
```

Once GitHub Pages is enabled, the rendered site will be public even if the source repository remains private.

## Content Policy

- Public contact is limited to email and professional profile links.
- Phone number and private address are intentionally omitted.
- Publications are selected/manual for v1; full BibTeX or Zotero import is deferred.
- Generated `public/`, `resources/`, `pagefind/`, `_outputs/`, and `AGENTS.md` are ignored.
