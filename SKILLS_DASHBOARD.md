# Computational Biology GitHub Skills Dashboard

**Canonical skills-to-repository tracker for Muhammad Bilal**  
**Last audited:** 2026-08-22  
**Target roles:** Computational Biologist · Bioinformatics Scientist · Genomics Scientist · Research Scientist · Research Software Engineer

This dashboard is intentionally evidence-based. A skill is counted as **proven** only when an existing project contains inspectable implementation, tests, documentation, analysis, or a working application that demonstrates it. Merely naming a tool in a profile does not count.

## Status legend

- ✅ **Proven** — demonstrated by an existing project or reproducible analysis repository.
- 🟡 **Partial** — meaningful evidence exists, but an important part of the skill group is still missing.
- 🔵 **Planned** — identified as strategically important, but no strong dedicated portfolio evidence yet.

> **Current portfolio coverage:** 14/26 skill groups proven, 5/26 partial, 7/26 planned. This is a portfolio-evidence score, not a claim of overall scientific proficiency.

## 1. Master skills ledger

| # | Skill group | Status | Primary repository evidence | Main gap / next proof |
|---:|---|:---:|---|---|
| 1 | Programming & computational foundations | ✅ | [PanGenFlow](https://github.com/mbilal-OU/PanGenFlow), [PanPhyloFlow](https://github.com/mbilal-OU/PanPhyloFlow), [SpeciesResolve](https://github.com/mbilal-OU/SpeciesResolve), [Rosalind-Bioinformatics](https://github.com/mbilal-OU/Rosalind-Bioinformatics) | Continue packaging, tests, CI, error handling, releases |
| 2 | Bioinformatics foundations | ✅ | PanGenFlow, PanPhyloFlow, SpeciesResolve | Expand BAM/CRAM/VCF evidence in future sequencing workflows |
| 3 | Microbial genomics | ✅ | PanGenFlow + SpeciesResolve | Add Bakta and stronger real-data benchmark examples where justified |
| 4 | Pangenomics | ✅ | PanPhyloFlow, [PanGenome-Openness-Estimator](https://github.com/mbilal-OU/PanGenome-Openness-Estimator), [PanOrd](https://github.com/mbilal-OU/PanOrd), [roary-pangenome-heatmaps](https://github.com/mbilal-OU/roary-pangenome-heatmaps) | Build the multi-engine benchmark layer with PIRATE + PPanGGOLiN |
| 5 | Phylogenomics & molecular evolution | ✅ | PanPhyloFlow + SpeciesResolve | Add recombination-aware and marker-gene comparison modules later |
| 6 | Molecular clocks / deep-time evolution | 🟡 | Current research analyses and profile evidence | Create a dedicated Deep-Time Phylogenomics Toolkit with MCMCTree, RelTime, BEAST/BEAST2 and calibration sensitivity |
| 7 | Population & comparative genomics | ✅ | PanOrd + SpeciesResolve + PanPhyloFlow | Add formal microbial association testing, e.g. pyseer, in a justified project |
| 8 | Genome assembly & long-read genomics | 🔵 | — | Build Long-Read Microbial Genomics Pipeline: ONT/PacBio, Flye, minimap2, QUAST, polishing, SVs, Bandage |
| 9 | Workflow engineering | ✅ | PanPhyloFlow (Nextflow DSL2, DAG, stub tests, reports), PanGenFlow | Add production container profiles and broader real-data validation |
| 10 | HPC | ✅ | FORGE Slurm Lab + BLab Slurm Builder + real Slurm genomics workflows | Make the strongest teaching/tooling repositories recruiter-visible when appropriate; add reproducible benchmark records |
| 11 | Containers & reproducibility | 🟡 | Conda environments, CI, reproducible workflow structure across projects | Add Docker + Apptainer/Singularity profiles, locked environments, reproducible container builds |
| 12 | Cloud genomics | 🔵 | — | Build cloud demonstrator using AWS/GCP + Nextflow or WDL/Cromwell with cost/provenance reporting |
| 13 | Research software engineering | ✅ | [Word Journal Manuscript Converter](https://github.com/mbilal-OU/Word-Journal-Manuscript-Converter), BioLab Analytics, PanPhyloFlow, PanGenFlow | Continue stable releases, regression tests, packaging, user feedback, API/interface design |
| 14 | Statistics | ✅ | PanOrd, PanGenome-Openness-Estimator, BioLab Analytics | Add effect-size/CI-first examples and experiment-level statistical notebooks where useful |
| 15 | Bulk transcriptomics | 🟡 | Existing RNA-seq work plus RNA-seq teaching/template components in HPC tools | Convert the real STAR/featureCounts/DESeq2 workflow into a tested flagship repository |
| 16 | Single-cell genomics | 🔵 | — | Build Scanpy/Seurat learning pipeline with QC, UMAP, clustering, markers, annotation, batch correction |
| 17 | Multi-omics | 🔵 | — | Build one integration project connecting at least two molecular layers with explicit provenance |
| 18 | Functional microbial genomics | 🔵 | — | Build AMR/virulence/plasmid/prophage/BGC/HGT explorer using AMRFinderPlus, CARD/RGI, antiSMASH and related tools |
| 19 | Data engineering for biology | 🟡 | PanGenFlow JSONL→TSV metadata processing, BioLab batch/provenance workflows | Add SQLite/PostgreSQL or DuckDB + Parquet + schema validation + accession reconciliation at scale |
| 20 | Machine learning for genomics | 🔵 | Existing `ml` repository is not counted as sufficient evidence | Build Biological ML Benchmark with leakage-safe splitting, CV, calibration, interpretation and reproducible datasets |
| 21 | AI for biology | 🔵 | — | Add PyTorch + biological embeddings/foundation-model benchmark with scientific validation guardrails |
| 22 | Scientific visualization | ✅ | PanOrd, SpeciesResolve, PanGenome-Openness-Estimator, roary-pangenome-heatmaps, BioLab Analytics | Extend to genome tracks, graph views, accessible interactive reporting |
| 23 | Open science & reproducibility | ✅ | Public MIT-licensed projects with CITATION.cff, CHANGELOGs, tests, CI and documentation | Add archived DOI releases/Zenodo for mature stable software |
| 24 | Technical documentation | ✅ | PanPhyloFlow, PanGenFlow, SpeciesResolve, FORGE, Word Journal Manuscript Converter | Continue task-oriented tutorials, troubleshooting and API/reference docs |
| 25 | Scientific communication | ✅ | Teaching-oriented software, interpretation guides, research profile, manuscript tooling | Add polished project case studies linking biological question → method → result → limitation |
| 26 | Research leadership | 🟡 | Maintained multi-repo ecosystem, CONTRIBUTING guides, issue/PR/release workflows, teaching tools | Make maintainer workflows, roadmap decisions, mentoring/contributor activity more visible |

## 2. Current evidence repositories

### Core microbial genomics ecosystem

| Repository | What it proves | Portfolio role |
|---|---|---|
| [PanGenFlow](https://github.com/mbilal-OU/PanGenFlow) | NCBI Datasets, GCA/GCF reconciliation, metadata, CheckM2, FastANI, Python/Bash, CI, reproducible cohort construction | Microbial genome QC & curation |
| [SpeciesResolve](https://github.com/mbilal-OU/SpeciesResolve) | ANI, alignment fraction, GTDB-Tk context, dRep, quality-aware species delineation, testing, scientific guardrails | Microbial taxonomy/species-boundary evidence |
| [PanPhyloFlow](https://github.com/mbilal-OU/PanPhyloFlow) | Nextflow DSL2, Prokka, Roary, Panaroo, IQ-TREE, core-threshold sensitivity, HTML reporting, CI/stub testing | Population-to-phylogeny workflow |
| [PanOrd](https://github.com/mbilal-OU/PanOrd) | PCA, Jaccard PCoA, metadata-aware ordination, gene loadings, R/Python, interpretive statistics | Population/comparative genomics |
| [PanGenome-Openness-Estimator](https://github.com/mbilal-OU/PanGenome-Openness-Estimator) | Heaps' law, permutation accumulation, SciPy/NumPy/pandas/matplotlib, reproducibility | Pangenome statistics |

### Cross-cutting engineering and training evidence

| Repository / product | What it proves | Visibility note |
|---|---|---|
| [Word Journal Manuscript Converter](https://github.com/mbilal-OU/Word-Journal-Manuscript-Converter) | Python packaging, CLI, regression tests, cross-platform releases, GitHub Actions, privacy-aware local software, Word add-in, release engineering | Public |
| BioLab Analytics | Streamlit, scientific calculators, statistics/QC, Primer3 integration, responsive UI, provenance, multi-version pytest validation | Source currently private; live app public |
| FORGE Slurm Lab | Slurm concepts, scheduling simulation, job arrays, dependencies, resource accounting, scientific HPC training, JavaScript app design | Source currently private; live app available |
| BLab Slurm Builder | Slurm script generation/validation, workflow templates, job lifecycle, modules/Conda, resource estimation | Source currently private; live app available |
| [roary-pangenome-heatmaps](https://github.com/mbilal-OU/roary-pangenome-heatmaps) | Pangenome visualization and interactive presence/absence exploration | Public supporting project |
| [Rosalind-Bioinformatics](https://github.com/mbilal-OU/Rosalind-Bioinformatics) | Algorithmic bioinformatics problem solving | Public foundational evidence |

### Repositories that should **not** be used as primary skill proof

Older course, fork, tutorial, empty/minimal, or upstream-copy repositories can remain useful for learning history, but they should not carry recruiter-facing claims when a stronger original project exists. Examples include `ml` in its current minimal state, `seaborn2`, and upstream/tutorial-style repositories. Prefer the flagship projects above.

## 3. Ten-flagship-project roadmap

| Original flagship target | Current state | Existing evidence | Decision |
|---|:---:|---|---|
| 1. Microbial Genome QC & Curation Platform | ✅ Strong | PanGenFlow + SpeciesResolve | Extend; do not create a duplicate repo |
| 2. PanGenome Benchmark Suite | 🟡 Partial | PanPhyloFlow + PanOrd + Openness Estimator | Build a benchmark layer spanning Roary, Panaroo, PIRATE, PPanGGOLiN with runtime/memory/sensitivity/statistics |
| 3. Population-to-Phylogeny Workflow | ✅ Strong | PanPhyloFlow | Finish real-data release gate and containers |
| 4. Deep-Time Phylogenomics Toolkit | 🔵 Planned | Research analyses exist, but not a dedicated software repo | High-value new flagship |
| 5. Long-Read Microbial Genomics Pipeline | 🔵 Planned | — | High-value new flagship |
| 6. Microbial Functional Genome Explorer | 🔵 Planned | — | Build after long-read/RNA-seq foundation |
| 7. RNA-seq → Multi-omics Workbench | 🟡 Early | Real RNA-seq experience + BioLab/HPC teaching pieces | Convert real RNA-seq workflow into reproducible pipeline first; multi-omics later |
| 8. Single-Cell Analysis Learning Pipeline | 🔵 Planned | — | New flagship after bulk RNA-seq |
| 9. Cloud Genomics Demonstrator | 🔵 Planned | — | Add after containers; reuse PanPhyloFlow rather than duplicating biology |
| 10. Biological AI Benchmark | 🔵 Planned | — | Build only after strong classical ML baseline |

## 4. Priority queue

The next work should close portfolio gaps rather than add more pangenomics repos.

1. **Containerize an existing flagship first** — Docker + Apptainer profiles for PanPhyloFlow/PanGenFlow.
2. **Bulk RNA-seq flagship** — turn the real FASTQ → QC → STAR/HISAT2 → featureCounts → DESeq2 workflow into tested software.
3. **Long-read microbial genomics** — ONT/PacBio → assembly → QC → annotation → structural variation.
4. **Cloud execution** — run an existing workflow on AWS/GCP with cost and provenance reporting.
5. **Deep-time phylogenomics toolkit** — MCMCTree/RelTime/BEAST calibration sensitivity and posterior diagnostics.
6. **Functional microbial genomics** — AMR, virulence, mobile elements, plasmids, prophages, BGCs.
7. **Single-cell** — Scanpy/Seurat reproducible teaching/analysis pipeline.
8. **Biological ML → AI** — classical leakage-safe benchmark before foundation-model work.

## 5. Rule for future updates

When a repository is created or substantially upgraded, update this file using the following test:

**A skill moves to ✅ only when there is inspectable proof**, such as code, tests, workflow configuration, documentation, benchmark results, a reproducible analysis, or a working application. If the evidence is only a README claim or a tool name, keep it 🟡 or 🔵.

For every future project, record:

- repository name and URL;
- skill groups demonstrated;
- whether the source is public or private;
- tests/CI status;
- reproducibility mechanism (environment/container/workflow);
- real-data or benchmark validation status;
- release/version status;
- next missing capability.

---

**Canonical tracker:** `mbilal-OU/mbilal-OU/SKILLS_DASHBOARD.md`  
**Audit cadence:** update whenever a flagship repository reaches a meaningful milestone or a new skill becomes genuinely demonstrable.
