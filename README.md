# Bright Builds Logo Assets

<!-- coding-and-architecture-requirements-readme-badges:begin -->
[![GitHub Stars](https://img.shields.io/github/stars/bright-builds-llc/logo)](https://github.com/bright-builds-llc/logo)
[![License](https://img.shields.io/github/license/bright-builds-llc/logo?s)](./LICENSE)
<!-- coding-and-architecture-requirements-readme-badges:end -->

This repository stores the Bright Builds logo asset library imported from the original source folder, organized for straightforward reuse across product, print, and fabrication workflows.

## Canonical Assets

The default logo set is the `logov3` family:

- `assets/logo/primary/bright-builds-logo.svg`
- `assets/logo/primary/bright-builds-logo.png`

Legacy logo variants remain available under `assets/logo/legacy/` for reference and compatibility.

## Repository Layout

```text
assets/
  logo/
    primary/
    legacy/
    3d/
  print/
    business-cards/
      wip/
  supporting/
    frame/
docs/
  source-manifest.md
```

## Asset Notes

- `assets/logo/primary/` contains the current default vector and raster logo assets.
- `assets/logo/legacy/` preserves earlier logo variants and related export formats.
- `assets/logo/3d/` contains fabrication-oriented source material.
- `assets/print/business-cards/wip/` contains in-progress business card exports and source artwork.
- `assets/supporting/frame/` contains supporting frame assets that are not treated as the default logo.

## Provenance

Imported files are stored as byte-identical copies of the source assets. Original filenames, source timestamps, categories, and normalized repo paths are documented in `docs/source-manifest.md`.
