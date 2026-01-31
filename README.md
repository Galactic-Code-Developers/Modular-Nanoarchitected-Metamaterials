# Modular-NM — Release Assets (No Manuscript)

This repository release contains **only non-manuscript artifacts** referenced by the Modular Nanoarchitected Metamaterials project:

- CAD and manufacturing files (STL/OBJ/STEP/3MF)
- Simulation artifacts (if present)
- Figures used for the published PDF (PNG)
- A SHA256 manifest for reproducibility
- Zenodo metadata files for DOI minting

## Folder layout

- `cad/` — STL/OBJ/STEP/3MF manufacturing and geometry assets
- `simulations/` — solver models and input decks (`.mph`, `.inp`) when available
- `images/` — figures (PNG) used in the published PDF
- `zenodo/` — Zenodo metadata helpers

## Important note about stub files

Some filenames are included as **stubs** (plain-text placeholders) to preserve the *exact* file references used in the project.
Stubs contain the message `NOT INCLUDED IN THIS RELEASE`.

If you see a stub, replace it with the corresponding real artifact before manufacturing, simulation, or third-party sharing.

## Reproducibility

- `SHA256SUMS.txt` lists hashes for every file in this release (including stubs).
- For validation: compute SHA256 locally and compare to the manifest.

## Zenodo / DOI

1. Create a Zenodo upload (new version or new record).
2. Upload the **zip** produced from this repository release.
3. Paste metadata from `.zenodo.json` (or let Zenodo read it if supported).
4. Mint the DOI and update your published PDF to reference the DOI.

## License

CC BY-NC 4.0 (see `LICENSE`). Commercial use requires a separate license from the author.
