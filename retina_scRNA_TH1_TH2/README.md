# retina_scRNA_TH1_TH2

Project structure for retinal scRNA-seq analysis with raw 10x matrices stored under `data/raw/10x/`.

## Layout

- `config/`: analysis parameters and sample sheets
- `data/raw/10x/`: untouched raw 10x count matrices
- `data/external/`: reference genomes, annotations, marker sets
- `data/interim/`: merged or partially processed objects
- `data/processed/`: final cleaned analysis-ready objects
- `metadata/`: sample- or cell-level metadata tables
- `notebooks/`: exploratory notebooks
- `scripts/`: reusable analysis scripts
- `results/`: figures, marker tables, clustering outputs
- `reports/`: exported summaries and reports
- `refs/`: reference assets used directly by the workflow
- `logs/`: pipeline and session logs

## Raw data

- `data/raw/10x/TH1/`
- `data/raw/10x/TH2/`

Each sample directory contains the standard 10x files:

- `barcodes.tsv.gz`
- `features.tsv.gz`
- `matrix.mtx.gz`
