# Locus Plugin Registry

Personal public plugin registry for Locus.

Plugin source entries live under `entries/v1/plugins/<bucket>/<plugin-id>.json`.
The public registry API is generated under `public/v1`:

- `public/v1/manifest.json`
- `public/v1/shards/<bucket>.json`
- `public/v1/plugins/<bucket>/<plugin-id>.json`
- `public/v1/search/summaries.json`

Use this registry base URL in Locus:

`https://raw.githubusercontent.com/JupiterTheWarlock/locus-plugin-registry/main/public/v1`

