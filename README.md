# Phisher Nuvio

Nuvio-style repository scaffold inspired by the structure used in [German-streams](https://github.com/h97667611-dotcom/German-streams).

## Important compatibility note

The upstream Phisher repository publishes CloudStream `.cs3` extensions. These are not Nuvio JavaScript plugins and cannot be installed or scraped by Nuvio merely by changing the repository JSON. This repository currently contains a Nuvio manifest, entry point, metadata catalog placeholder, and install page; it does **not** claim that the upstream providers have been ported.

## Install

Use the direct repository manifest URL:

`https://raw.githubusercontent.com/h97667611-dotcom/Phisher-Nuvio/main/manifest.json`

Or open [Install page](./install.html).

## Upstream

- [Phisher CloudStream extensions](https://github.com/phisher98/cloudstream-extensions-phisher/tree/builds)
- [Original repository JSON](https://raw.githubusercontent.com/phisher98/cloudstream-extensions-phisher/refs/heads/builds/repo.json)

Only add provider implementations for sources that you are authorized to access and whose content is legally usable. See `catalog/providers.json`.
