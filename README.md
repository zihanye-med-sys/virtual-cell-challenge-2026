# Virtual Cell Challenge 2026 data

This repository contains the validation control bundle and working files for the 2026 Virtual Cell Challenge.

## Files

- `context_A.h5ad`, `context_B.h5ad`, `context_C.h5ad`: non-targeting control cells for contexts A, B, and C.
- `gene_names.csv`: ordered list of 18,533 genes.
- `pert_counts.csv`: 300 perturbation targets.
- `manifest.json`: validation panel metadata.

The H5AD files are stored with Git LFS because each file exceeds GitHub's regular file-size limit.

## Open with cellxgene

```powershell
cellxgene launch https://github.com/zihanye-med-sys/virtual-cell-challenge-2026/raw/main/context_A.h5ad --open
```

Repeat with `context_B.h5ad` or `context_C.h5ad` as needed.

These source files do not contain a PCA, UMAP, or t-SNE embedding. A compatible cellxgene/AnnData environment is required to read their current H5AD encoding, and a visualization copy with an embedding may be needed for the two-dimensional explorer view.

## Official resources

- [Virtual Cell Challenge data description](https://virtualcellchallenge.org/app/datasets)
- [VCC CLI guide](https://vcc-cli-wiki.virtualcellchallenge.org/)
