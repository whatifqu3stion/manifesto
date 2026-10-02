# A Cypherpunk's Manifesto — inherited experiment

This is a fork of an existing Bitcoin Ordinals project that presents *A Cypherpunk's Manifesto* through a small HTML inscription.

The original experiment uses shared inscription resources for styling and JavaScript rather than packaging them inside the HTML file. It is an example of working within an unusual platform constraint.

## Provenance and status

**Inherited project, retained as a historical reference.** This repository is a fork of [satoshi0770/manifesto](https://github.com/satoshi0770/manifesto); the original documentation references the Cypherpunklab project. The upstream project and authors deserve credit for the concept and implementation. This repository is not presented as an original application built from scratch.

The original 2023 instructions are preserved in [the historical README](docs/HISTORICAL_README.md). They include platform links and hardware estimates that have not been revalidated and should not be treated as current setup recommendations.

## Explore

- [`manifesto.html`](manifesto.html): the compact entry point.
- [`validate_manifesto.js`](validate_manifesto.js): collection validation.
- [`collection.json`](collection.json): inscription records.
- [`LICENSE`](LICENSE): licensing information.

The HTML references `/content/...` inscription resources. Opening the file from disk alone will not reproduce its intended environment.
