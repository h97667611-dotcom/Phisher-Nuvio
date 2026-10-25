# Phisher-Nuvio

A community porting workspace for the [Phisher CloudStream Extensions](https://github.com/phisher98/cloudstream-extensions-phisher) catalog to Nuvio.

## Status

This repository has been created and the upstream catalog has been indexed. **It is not yet a working Nuvio scraper/plugin.** CloudStream `.cs3` provider bundles are compiled CloudStream extensions and cannot be installed as Nuvio plugins simply by renaming them or changing `repo.json`. Each provider needs a native Nuvio implementation and testing against Nuvio's supported plugin API.

## Upstream

- Repository: https://github.com/phisher98/cloudstream-extensions-phisher
- Original manifest: https://raw.githubusercontent.com/phisher98/cloudstream-extensions-phisher/refs/heads/builds/repo.json
- Original plugin list: https://raw.githubusercontent.com/phisher98/cloudstream-extensions-phisher/refs/heads/builds/plugins.json
- Catalog snapshot: [`catalog/upstream-plugins.json`](catalog/upstream-plugins.json)

## Catalog

The snapshot contains 86 entries (85 marked enabled upstream at retrieval time). See the catalog for source URL, provider name, language, version, supported content types, and upstream hashes. This is metadata only; no provider code or streaming files are included.

## Porting

1. Select a provider from the catalog.
2. Review the upstream project/license and permitted use of the target source.
3. Implement its search, detail, episode, and playback-link resolution in Nuvio's native plugin API.
4. Add provider-specific tests and verify playback behavior in Nuvio.
5. Update this README and the Nuvio install manifest only after the provider is genuinely functional.

## Legal / attribution

This project is not affiliated with Phisher98 or Nuvio. Provider names and metadata are included for attribution and compatibility planning. Respect upstream licenses, site terms, and applicable law. The catalog does not download or redistribute copyrighted video.
