# Infinite Myco Packs

Downloadable **region packs** for the *Infinite Myco Nexus* iPhone app ("Myco"), an
offline field guide and photo identifier for fungi and slime moulds.

Each pack is one SQLite file published as a release asset under the
[`packs`](../../releases/tag/packs) release, with `manifest.json` listing the available
regions. The app downloads a pack once and then works fully offline. Britain & Ireland
is built into the app itself.

This repository contains **data only** — no app code.

## What is in a pack

- Species list, names (incl. other languages), identification features, season charts
- Short descriptive text from Wikipedia
- One small thumbnail per species; links to full-size reference photos at their source
- Numerical image "fingerprints" (BioCLIP 2 embeddings) used for on-device identification

## Sources and licences

Only material that allows commercial reuse is included; every photo keeps its author and
licence, shown in the app.

| Data | Source | Licence |
|---|---|---|
| Species occurrence counts, seasons | [GBIF.org](https://www.gbif.org) (CC0 and CC BY datasets only) | CC0 / CC BY 4.0 |
| Taxonomy | GBIF Backbone Taxonomy | CC BY 4.0 |
| Names | [Wikidata](https://www.wikidata.org), GBIF vernacular names, UK Species Inventory | CC0 / CC BY |
| Text | [Wikipedia](https://www.wikipedia.org) contributors, shortened; edibility statements removed | CC BY-SA 4.0 |
| Photos (thumbnails, links) | Wikimedia Commons, Mushroom Observer, recording schemes publishing via GBIF | CC0 / CC BY / CC BY-SA (per photo) |
| Embedding model | [BioCLIP 2](https://huggingface.co/imageomics/bioclip-2), Imageomics Institute | MIT |

iNaturalist data is not used.

## Safety

The app and these packs never state that a species is edible. Never eat a wild mushroom
on the strength of an app.
