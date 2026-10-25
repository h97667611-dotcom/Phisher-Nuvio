# Phisher-Nuvio

[![Install in Nuvio](https://img.shields.io/badge/Nuvio-Install-blue?style=for-the-badge)](https://raw.githubusercontent.com/h97667611-dotcom/Phisher-Nuvio/main/repo.json)

**Direct JSON install link:**  
https://raw.githubusercontent.com/h97667611-dotcom/Phisher-Nuvio/main/repo.json

A community porting workspace for the [Phisher CloudStream extensions](https://github.com/phisher98/cloudstream-extensions-phisher) catalog to Nuvio.

## Status

This repository has been created and the upstream catalog has been indexed. **It is not yet a working Nuvio scraper/plugin.** CloudStream `.cs3` provider bundles are compiled CloudStream extensions and cannot be installed in Nuvio simply by renaming them or changing `repo.json`. Each provider needs a native Nuvio implementation and testing against Nuvio's supported plugin API.

## Upstream

- Repository: https://github.com/phisher98/cloudstream-extensions-phisher
- Original manifest: https://raw.githubusercontent.com/phisher98/cloudstream-extensions-phisher/refs/heads/builds/repo.json
- Original plugin list: https://raw.githubusercontent.com/phisher98/cloudstream-extensions-phisher/refs/heads/builds/plugins.json
- Catalog snapshot: [`catalog/upstream-plugins.json`](catalog/upstream-plugins.json)

## Catalog

The snapshot contains 86 entries (85 marked enabled upstream). It records provider metadata and source URLs; it does not include provider code or stream files.

## Porting

1. Select a provider from the catalog.
2. Review the upstream project/license and the source site's terms.
3. Implement search, details, episode, and playback-link resolution using Nuvio's native plugin API.
4. Add provider-specific tests and verify playback behavior in Nuvio.
5. Update the install manifest only after the provider is functional.

## Legal / attribution

This project is not affiliated with the upstream project or Nuvio. Provider names and metadata are included for attribution and compatibility planning. Respect upstream licenses, site terms, and applicable law. The catalog does not download or redistribute copyrighted video.
