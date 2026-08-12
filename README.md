# Coding Showcase

Personal website: [sbvis.github.io/soumyadeep](https://sbvis.github.io/soumyadeep/)

A selection of open-source software, visual analytics tools, and framework
contributions focused on scientific visualization, high-dimensional data,
single-cell genomics, and interactive visual analytics.

---

## Featured Projects

### Cytosplore Simian Viewer

Interactive exploration and comparative analysis of single-cell RNA-seq data
across multiple primate species. The Simian Viewer combines linked visual
analytics views for exploring cell types, gene expression, and cross-species
differences. The associated plugins provide multi-species expression
comparison, pairwise analysis, subset creation, and chart-support functionality.

| Repository                                                                                                                | Description                                                                                                                      | Contribution Overview                                                                      |
| ------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [Simian Viewer Plugin](https://github.com/ManiVaultStudio/SimianViewerPlugin)                                             | Core Cytosplore Simian Viewer plugin for interactive exploration and comparison of multi-species single-cell transcriptomic data | Core plugin implementation, linked-view coordination, and cross-species analysis workflows |
| [Simian Viewer Multiple Differential Expression Plugin](https://github.com/ManiVaultStudio/SimianViewerMultExpCompPlugin) | View for comparing gene expression and differential-expression patterns across multiple species                                  | Cross-species expression comparison and chart interaction logic                            |
| [Simian Viewer Pair Differential Expression Plugin](https://github.com/ManiVaultStudio/SimianViewerPairExpCompPlugin)     | View for pairwise comparison of gene-expression differences between two species                                                  | Pairwise comparison workflows and supporting visualization behavior                        |
| [Subset From Selection Plugin](https://github.com/ManiVaultStudio/SubsetFromSelectionPlugin)                              | ManiVault plugin for creating data subsets from the current selection                                                            | Selection-driven subset creation and data-transfer plumbing                                |
| [Chart Legend Plugin](https://github.com/ManiVaultStudio/ChartLegendViewPlugin)                                           | Reusable chart-legend view support for ManiVault visualizations                                                                  | Reusable legend view support and legend interaction wiring                                 |

**Tech:** `C++` `Qt` `JavaScript` `D3.js`

---

### Cytosplore EvoViewer

Visual analytics for exploring conserved evolutionary patterns in
multi-species single-cell sequencing data. EvoViewer links cell-type
hierarchies, differential-expression analysis, tables, scatterplots, and
phylogenetic trees to investigate how genes and cellular characteristics vary
across species.

| Repository                                                                                                           | Description                                                                                                                                     | Contribution Overview                                              |
| -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| [Tree MetaData Plugin](https://github.com/ManiVaultStudio/XSCTreeMetaData)                                           | Provides metadata support for phylogenetic tree data used throughout the EvoViewer workflow                                                     | Tree metadata loading, serialization, and viewer integration       |
| [Tree Data Plugin](https://github.com/ManiVaultStudio/XSCTreeData)                                                   | Provides the shared tree-data representation and integration used by EvoViewer components                                                       | Shared tree-data structures, serialization, and integration points |
| [Phylogenetic Tree View](https://github.com/ManiVaultStudio/XSCPhyTVuPlugin)                                         | Interactive phylogenetic-tree visualization for exploring species relationships and mapped attributes                                           | Phylogenetic-tree visualization, navigation, and UI behavior       |
| [Icicle Plot Cluster Processing Plugin](https://github.com/ManiVaultStudio/XSCClusterRankPlugin)                     | Processes and ranks hierarchical cluster information for visual exploration of cell-type structure                                              | Cluster ranking, filtering, and hierarchical processing logic      |
| [Tree Data Metadata Loader Plugin](https://github.com/ManiVaultStudio/XSCLoaderPlugin)                               | Loads tree-related data and metadata into the ManiVault workflow                                                                                | Tree metadata import, loader workflow, and configuration updates   |
| [Gene Marker Identification and Evo Viewer Processor Plugin](https://github.com/ManiVaultStudio/XSCGeneDetectPlugin) | Identifies and ranks marker genes across species and links gene and cluster level statistics to scatterplot, table, and phylogenetic-tree views | Marker-gene detection, ranking, and cross-view statistics plumbing |

**Tech:** `C++` `Qt` `JavaScript` `D3.js`

---

### Cytosplore Gradient Surfer

Comparative visual analysis of spatial gene-expression gradients across
spatial transcriptomics datasets and modalities. Gradient Surfer supports
interactive selection of spatial directions, identification of correlated
genes, line-based expression plots, dimensionality reduction, and
cross-dataset comparison of spatial patterns.

| Repository                                                                                          | Description                                                                                     | Contribution Overview                                                 |
| --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Gradient Surfer Plugin](https://github.com/ManiVaultStudio/GradientSurferPlugin)                   | Interactive visualization and comparison of spatial gene-expression gradients across datasets   | Gradient selection, dataset comparison, and view interaction behavior |
| [Data Transformation Plugin](https://github.com/ManiVaultStudio/GradientSurferTransformationPlugin) | Data transformation and processing components supporting gradient-based analysis workflows      | Normalization, subsampling, loading, and transformation pipeline work |
| [Line Plot View Plugin](https://github.com/ManiVaultStudio/LinePlotViewPlugin)                      | Reusable line-plot visualization for displaying gene-expression profiles and other ordered data | Line-plot rendering, stat-line controls, and chart interaction fixes  |

**Tech:** `C++` `Qt` `Python` `JavaScript` `WebGL`

---

### Cytosplore ATAC Viewer

Interactive analysis connecting chromatin accessibility, gene expression, and
spatial context. The project combines data-processing plugins with
visualization and controller components for exploring spatial multi-omic data.

| Repository                                                                                            | Description                                                                                         | Contribution Overview                                                |
| ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [Cluster Averages Mapping Plugin](https://github.com/ManiVaultStudio/ProjectAveragesPlugin)           | Computes and maps cluster-level averages to support comparative data exploration                    | Cluster-average computation, CSV export, and serialization work      |
| [ATAC RNA Spatial Data Mapping Plugin](https://github.com/ManiVaultStudio/ATACViewPlugin)             | Integrates ATAC and RNA-derived spatial information for interactive exploration                     | ATAC/RNA spatial mapping, dataset synchronization, and view plumbing |
| [Stacked Bar Chart / ATAC Controller Plugin](https://github.com/ManiVaultStudio/ATACControllerPlugin) | Controls and coordinates ATAC-related views and chart-based summaries within the ManiVault workflow | Bar/legend interaction handling, spatial-data support, and UI fixes  |

**Tech:** `C++` `Qt` `Python` `WebGL`

---

## Framework Contributions

### ManiVault Studio

Contributions to the open-source visual analytics framework for high-dimensional
data, including core application development, reusable plugins, and deployment
infrastructure.

| Repository                                                           | Description                                                                                      | Contribution Overview                                            |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------- |
| [ManiVault Core](https://github.com/ManiVaultStudio/core)            | Fixes, enhancements, and framework-level development for the ManiVault visual analytics platform | Serialization, dataset-picker, HUD, workflow, and platform fixes |
| [Mac Installer](https://github.com/ManiVaultStudio/MacOS_Installer)  | macOS installer and packaging workflow for distributing ManiVault (Publicly available soon)      | macOS packaging and release-distribution workflow                |
| [Scatterplot Plugin](https://github.com/ManiVaultStudio/Scatterplot) | Fixes and enhancements to ManiVault's scatterplot visualization components                       | Dataset synchronization, serialization, and scatterplot behavior |

**Tech:** `C++` `Qt` `OpenGL`

---

## Official Websites

Contributions to developing, enhancing, and maintaining official project
websites and documentation.

| Repository                                                                                        | Description                                                                                                      | Contribution Overview                                                         |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| [Cytosplore Viewer official website](https://github.com/Cytosplore/viewer)                        | Jekyll-based website containing Cytosplore documentation, tutorials, project information, and release resources. | Website redesign, documentation refresh, and release/publication link updates |
| [ManiVault Studio official website](https://github.com/ManiVaultStudio/manivaultstudio.github.io) | Official ManiVault Studio website and project pages                                                              | Project pages, site copy, and content updates                                 |

---

## Other Projects & Experiments

Smaller open-source projects, prototypes, supporting libraries, and technical
experiments.

| Repository                                                                      | Description                                                                                                             | Contribution Overview                                                          |
| ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [Joint t-SNE Analysis](https://github.com/ManiVaultStudio/Joint-t-SNE-Analysis) | ManiVault-based project for joint t-SNE analysis, including plugin integration, example data, and supporting components | Joint t-SNE integration, build/CI updates, and example workflow support        |
| [JointTsneLib](https://github.com/ManiVaultStudio/JointTsneLib)                 | Supporting C++ library for Joint t-SNE analysis, including a modified HDI component used by the analysis plugin         | Joint t-SNE library maintenance, CMake/packaging updates, and algorithm tweaks |

---

## Technical Focus

**Languages:**

`C++` `Python` `JavaScript`

**Frameworks & Libraries:**

`Qt` `OpenGL` `WebGL` `D3.js` `Jekyll`

**Areas:**

`Visual Analytics` `Data Visualization` `Scientific Computing`
`High-Dimensional Data` `Interactive Visualization`
`Single-Cell Genomics` `Spatial Transcriptomics`
`Comparative Genomics`

---

## Publications & Research

Several projects were developed as part of published research:

- **Cytosplore Simian Viewer** : _Visual Exploration for Multi-Species
  Single-Cell RNA Sequencing Data._ VCBM 2023.
  [DOI: 10.2312/vcbm.20231219](https://doi.org/10.2312/vcbm.20231219)

- **ManiVault** : _A Flexible and Extensible Visual Analytics Framework for
  High-Dimensional Data._ IEEE VIS 2023 / IEEE Transactions on Visualization
  and Computer Graphics.
  [DOI: 10.1109/TVCG.2023.3326582](https://doi.org/10.1109/TVCG.2023.3326582)

- **Comparative Transcriptomics Reveals Human-Specific Cortical Features.**
  _Science_, 2023.
  [DOI: 10.1126/science.ade9516](https://doi.org/10.1126/science.ade9516)

- **Cytosplore EvoViewer** : _Visual Analytics of Conserved Evolutionary
  Patterns in multi-species single-cell sequencing data._ PacificVis 2025.
  [DOI: 10.1109/PacificVis64226.2025.00021](https://doi.org/10.1109/PacificVis64226.2025.00021)

- **Cytosplore Gradient Surfer** : _Comparative Visual Analysis of Spatial
  Gene Expression Gradients Across Datasets._ VCBM 2025.
  [VCBM 2025 publication](https://publications.graphics.tudelft.nl/)

- **A cross-species spatial transcriptomic atlas of the human and non-human primate basal ganglia.**
  _bioRxiv_, 2025.
  [DOI: 10.1101/2025.11.22.688128v1](https://www.biorxiv.org/content/10.1101/2025.11.22.688128v1)

- **Spatial patterning of transcriptional and regulatory programs in the primate subcortex.**
  _bioRxiv_, 2025.
  [DOI: 10.1101/2025.11.22.689869v1](https://www.biorxiv.org/content/10.1101/2025.11.22.689869v1)

---
