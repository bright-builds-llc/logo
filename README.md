# Bright Builds Logo Assets

<!-- coding-and-architecture-requirements-readme-badges:begin -->
[![GitHub Stars](https://img.shields.io/github/stars/bright-builds-llc/logo)](https://github.com/bright-builds-llc/logo)
[![License](https://img.shields.io/github/license/bright-builds-llc/logo?s)](./LICENSE)
[![Bright Builds Requirements](https://raw.githubusercontent.com/bright-builds-llc/coding-and-architecture-requirements/main/public/badges/bright-builds.svg)](https://github.com/bright-builds-llc/coding-and-architecture-requirements)
<!-- coding-and-architecture-requirements-readme-badges:end -->

This repository stores the Bright Builds logo asset library imported from the original source folder, organized for straightforward reuse across product, print, and fabrication workflows.

## At a Glance

The gallery below highlights the repo's most useful preview-ready assets for quick scanning on GitHub.

<table>
  <tr>
    <td align="center">
      <a href="assets/logo/primary/bright-builds-logo.png">
        <img src="assets/logo/primary/bright-builds-logo.png" alt="Primary Bright Builds logo" width="180">
      </a>
      <br>
      <strong>Primary Logo</strong>
      <br>
      <sub><a href="assets/logo/primary/bright-builds-logo.png"><code>assets/logo/primary/bright-builds-logo.png</code></a></sub>
    </td>
    <td align="center">
      <a href="assets/logo/legacy/bright-builds-logo-v2-cropped.png">
        <img src="assets/logo/legacy/bright-builds-logo-v2-cropped.png" alt="Legacy Bright Builds square crop" width="180">
      </a>
      <br>
      <strong>Legacy Square Crop</strong>
      <br>
      <sub><a href="assets/logo/legacy/bright-builds-logo-v2-cropped.png"><code>assets/logo/legacy/bright-builds-logo-v2-cropped.png</code></a></sub>
    </td>
    <td align="center">
      <a href="assets/supporting/frame/bright-builds-frame.png">
        <img src="assets/supporting/frame/bright-builds-frame.png" alt="Bright Builds supporting frame asset" width="180">
      </a>
      <br>
      <strong>Supporting Frame</strong>
      <br>
      <sub><a href="assets/supporting/frame/bright-builds-frame.png"><code>assets/supporting/frame/bright-builds-frame.png</code></a></sub>
    </td>
  </tr>
</table>

## Legacy Variants

These earlier logo treatments remain available for reference and compatibility.

<table>
  <tr>
    <td align="center">
      <a href="assets/logo/legacy/bright-builds-logo-v1.svg">
        <img src="assets/logo/legacy/bright-builds-logo-v1.svg" alt="Legacy Bright Builds logo v1" width="220">
      </a>
      <br>
      <strong>Legacy Logo v1</strong>
      <br>
      <sub><a href="assets/logo/legacy/bright-builds-logo-v1.svg"><code>assets/logo/legacy/bright-builds-logo-v1.svg</code></a></sub>
    </td>
    <td align="center">
      <a href="assets/logo/legacy/bright-builds-logo-v2.png">
        <img src="assets/logo/legacy/bright-builds-logo-v2.png" alt="Legacy Bright Builds logo v2" width="220">
      </a>
      <br>
      <strong>Legacy Logo v2</strong>
      <br>
      <sub><a href="assets/logo/legacy/bright-builds-logo-v2.png"><code>assets/logo/legacy/bright-builds-logo-v2.png</code></a></sub>
    </td>
  </tr>
</table>

## WIP Print Assets

These business-card previews are intentionally shown as works in progress and should not be treated as canonical brand assets.

<table>
  <tr>
    <td align="center">
      <a href="assets/print/business-cards/wip/bright-builds-business-card-front-wip.svg">
        <img src="assets/print/business-cards/wip/bright-builds-business-card-front-wip.svg" alt="Bright Builds business card front work in progress" width="260">
      </a>
      <br>
      <strong>Business Card Front (WIP)</strong>
      <br>
      <sub><a href="assets/print/business-cards/wip/bright-builds-business-card-front-wip.svg"><code>assets/print/business-cards/wip/bright-builds-business-card-front-wip.svg</code></a></sub>
      <br>
      <sub><a href="assets/print/business-cards/wip/bright-builds-business-card-front-wip.pdf">PDF export</a></sub>
    </td>
    <td align="center">
      <a href="assets/print/business-cards/wip/bright-builds-business-card-back-wip.png">
        <img src="assets/print/business-cards/wip/bright-builds-business-card-back-wip.png" alt="Bright Builds business card back work in progress" width="260">
      </a>
      <br>
      <strong>Business Card Back (WIP)</strong>
      <br>
      <sub><a href="assets/print/business-cards/wip/bright-builds-business-card-back-wip.png"><code>assets/print/business-cards/wip/bright-builds-business-card-back-wip.png</code></a></sub>
      <br>
      <sub><a href="assets/print/business-cards/wip/bright-builds-business-card-back-wip.pdf">PDF export</a></sub>
    </td>
  </tr>
</table>

## Canonical Assets

The default logo set is the `logov3` family:

- `assets/logo/primary/bright-builds-logo.svg`
- `assets/logo/primary/bright-builds-logo.png`

Legacy logo variants remain available under `assets/logo/legacy/` for reference and compatibility.

## Logo Colors

This section documents the main colors used in the official logo SVGs and separates visible logo artwork from editor metadata that also appears in the files. The swatches below are README-only helper assets, not source logo deliverables.

### Main Palette

| Role | Swatch | Hex | Where it appears | Notes |
| --- | --- | --- | --- | --- |
| Dark primary fill | <img src="docs/color-swatches/logo-color-dark-primary.svg" alt="Dark primary fill swatch" width="24" height="24"> | `#1c0a38` | Primary logo SVG and legacy v2 SVG | Main dark body fill in the current two-color logo construction |
| Bright accent purple | <img src="docs/color-swatches/logo-color-accent-purple.svg" alt="Bright accent purple swatch" width="24" height="24"> | `#7f2aff` | Primary logo SVG and legacy v2 SVG | Accent purple used for the highlighted logo form |
| Legacy outline / scaffold | <img src="docs/color-swatches/logo-color-legacy-outline.svg" alt="Legacy outline scaffold swatch" width="24" height="24"> | `#000000` | Primary logo SVG, legacy v2 SVG, legacy v1 SVG | Present as stroke code in the newer SVGs and as the full monochrome outline treatment in legacy v1 |

### Per-file Mapping

#### `assets/logo/primary/bright-builds-logo.svg`

The current primary SVG uses `fill:#1c0a38` for the dark base shapes and `fill:#7f2aff` for the accent shape. The file also contains `stroke:#000000` in code, including a dark fill plus black stroke combination on one path, so black is present as a code-level outline value rather than the main visible palette.

#### `assets/logo/legacy/bright-builds-logo-v2.svg`

The legacy v2 SVG uses the same two-color structure as the primary SVG: `fill:#1c0a38` for the dark base and `fill:#7f2aff` for the bright accent. Like the primary SVG, it also includes `stroke:#000000` values in code, so black is documented as supporting outline/scaffold color rather than a primary brand fill.

#### `assets/logo/legacy/bright-builds-logo-v1.svg`

The legacy v1 SVG is a monochrome outline construction. Its logo paths are built with `fill:none;stroke:#000000`, so it should be treated as a legacy black outline variant rather than part of the main two-color purple palette.

### Excluded / Non-palette SVG Values

The logo SVG files also include `#ffffff` and `#d1d1d1`, but these appear in Inkscape page or editor metadata such as `pagecolor` and `inkscape:deskcolor`. They should not be treated as official logo colors. Supporting-frame and WIP business-card SVG colors are also out of scope for this logo color spec.

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
