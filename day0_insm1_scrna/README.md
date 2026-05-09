# day0_insm1_scrna

Scanpy scRNA-seq workflow for Day 0 `Chx10Cre` control and `Chx10Cre/Insm1` knockout samples.

The input data are the `Gene Expression` features from the multiome 10x H5 files listed in `config/samples.tsv`. The original files are kept in the ArchR/RNA project at `/Users/louis/Desktop/lab/code/r_demo` and are not duplicated here.

## Layout

- `config/`: sample sheet for this scRNA workflow
- `notebooks/`: stepwise Scanpy notebooks
- `data/interim/`: intermediate `.h5ad` files
- `data/processed/`: final annotated `.h5ad` files
- `results/qc/`: QC summaries
- `results/clustering/`: clustering and cluster QC summaries
- `results/annotation/`: cell-type annotation tables
- `results/markers/`: differential expression tables
- `results/figures/`: generated plots
