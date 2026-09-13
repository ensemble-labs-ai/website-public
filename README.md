# Ensemble Labs website

This repository is the generated, artifact-only deployment target for the Ensemble Labs
website. GitHub Pages deploys the committed `dist/` directory directly; no editable site
source is stored here.

The private [`ensemble-labs-ai/marketing`](https://github.com/ensemble-labs-ai/marketing)
repository builds and validates the Astro site, replaces only `dist/`, and records the
source revision in `dist/.ensemble-source-revision`.

Do not edit generated files in `dist/` by hand. The next successful publish from the
private source repository will overwrite direct changes.
