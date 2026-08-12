# Coding Showcase

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

| Repository                                                                                                                | Description                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [Simian Viewer Plugin](https://github.com/ManiVaultStudio/SimianViewerPlugin)                                             | Core Cytosplore Simian Viewer plugin for interactive exploration and comparison of multi-species single-cell transcriptomic data |
| [Simian Viewer Multiple Differential Expression Plugin](https://github.com/ManiVaultStudio/SimianViewerMultExpCompPlugin) | View for comparing gene expression and differential-expression patterns across multiple species                                  |
| [Simian Viewer Pair Differential Expression Plugin](https://github.com/ManiVaultStudio/SimianViewerPairExpCompPlugin)     | View for pairwise comparison of gene-expression differences between two species                                                  |
| [Subset From Selection Plugin](https://github.com/ManiVaultStudio/SubsetFromSelectionPlugin)                              | ManiVault plugin for creating data subsets from the current selection                                                            |
| [Chart Legend Plugin](https://github.com/ManiVaultStudio/ChartLegendViewPlugin)                                           | Reusable chart-legend view support for ManiVault visualizations                                                                  |

**Tech:** `C++` `Qt` `JavaScript` `D3.js`

---

### Cytosplore EvoViewer

Visual analytics for exploring conserved evolutionary patterns in
multi-species single-cell sequencing data. EvoViewer links cell-type
hierarchies, differential-expression analysis, tables, scatterplots, and
phylogenetic trees to investigate how genes and cellular characteristics vary
across species.

| Repository                                                                                                           | Description                                                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [Tree MetaData Plugin](https://github.com/ManiVaultStudio/XSCTreeMetaData)                                           | Provides metadata support for phylogenetic tree data used throughout the EvoViewer workflow                                                     |
| [Tree Data Plugin](https://github.com/ManiVaultStudio/XSCTreeData)                                                   | Provides the shared tree-data representation and integration used by EvoViewer components                                                       |
| [Phylogenetic Tree View](https://github.com/ManiVaultStudio/XSCPhyTVuPlugin)                                         | Interactive phylogenetic-tree visualization for exploring species relationships and mapped attributes                                           |
| [Icicle Plot Cluster Processing Plugin](https://github.com/ManiVaultStudio/XSCClusterRankPlugin)                     | Processes and ranks hierarchical cluster information for visual exploration of cell-type structure                                              |
| [Tree Data Metadata Loader Plugin](https://github.com/ManiVaultStudio/XSCLoaderPlugin)                               | Loads tree-related data and metadata into the ManiVault workflow                                                                                |
| [Gene Marker Identification and Evo Viewer Processor Plugin](https://github.com/ManiVaultStudio/XSCGeneDetectPlugin) | Identifies and ranks marker genes across species and links gene and cluster level statistics to scatterplot, table, and phylogenetic-tree views |

**Tech:** `C++` `Qt` `JavaScript` `D3.js`

---

### Cytosplore Gradient Surfer

Comparative visual analysis of spatial gene-expression gradients across
spatial transcriptomics datasets and modalities. Gradient Surfer supports
interactive selection of spatial directions, identification of correlated
genes, line-based expression plots, dimensionality reduction, and
cross-dataset comparison of spatial patterns.

| Repository                                                                                          | Description                                                                                     |
| --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| [Gradient Surfer Plugin](https://github.com/ManiVaultStudio/GradientSurferPlugin)                   | Interactive visualization and comparison of spatial gene-expression gradients across datasets   |
| [Data Transformation Plugin](https://github.com/ManiVaultStudio/GradientSurferTransformationPlugin) | Data transformation and processing components supporting gradient-based analysis workflows      |
| [Line Plot View Plugin](https://github.com/ManiVaultStudio/LinePlotViewPlugin)                      | Reusable line-plot visualization for displaying gene-expression profiles and other ordered data |

**Tech:** `C++` `Qt` `Python` `JavaScript` `WebGL`

---

### Cytosplore ATAC Viewer

Interactive analysis connecting chromatin accessibility, gene expression, and
spatial context. The project combines data-processing plugins with
visualization and controller components for exploring spatial multi-omic data.

| Repository                                                                                            | Description                                                                                         |
| ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| [Cluster Averages Mapping Plugin](https://github.com/ManiVaultStudio/ProjectAveragesPlugin)           | Computes and maps cluster-level averages to support comparative data exploration                    |
| [ATAC RNA Spatial Data Mapping Plugin](https://github.com/ManiVaultStudio/ATACViewPlugin)             | Integrates ATAC and RNA-derived spatial information for interactive exploration                     |
| [Stacked Bar Chart / ATAC Controller Plugin](https://github.com/ManiVaultStudio/ATACControllerPlugin) | Controls and coordinates ATAC-related views and chart-based summaries within the ManiVault workflow |

**Tech:** `C++` `Qt` `Python` `WebGL`

---

## Framework Contributions

### ManiVault Studio

Contributions to the open-source visual analytics framework for high-dimensional
data, including core application development, reusable plugins, and deployment
infrastructure.

| Repository                                                           | Description                                                                                      |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [ManiVault Core](https://github.com/ManiVaultStudio/core)            | Fixes, enhancements, and framework-level development for the ManiVault visual analytics platform |
| [Mac Installer](https://github.com/ManiVaultStudio/MacOS_Installer)  | macOS installer and packaging workflow for distributing ManiVault (Publicly available soon)      |
| [Scatterplot Plugin](https://github.com/ManiVaultStudio/Scatterplot) | Fixes and enhancements to ManiVault's scatterplot visualization components                       |

**Tech:** `C++` `Qt` `OpenGL`

---

## Official Websites

Contributions to developing, enhancing, and maintaining official project
websites and documentation.

| Repository                                                                                        | Description                                                                                                      |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| [Cytosplore Viewer official website](https://github.com/Cytosplore/viewer)                        | Jekyll-based website containing Cytosplore documentation, tutorials, project information, and release resources. |
| [ManiVault Studio official website](https://github.com/ManiVaultStudio/manivaultstudio.github.io) | Official ManiVault Studio website and project pages                                                              |

---

## Other Projects & Experiments

Smaller open-source projects, prototypes, supporting libraries, and technical
experiments.

| Repository                                                                      | Description                                                                                                             |
| ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [Joint t-SNE Analysis](https://github.com/ManiVaultStudio/Joint-t-SNE-Analysis) | ManiVault-based project for joint t-SNE analysis, including plugin integration, example data, and supporting components |
| [JointTsneLib](https://github.com/ManiVaultStudio/JointTsneLib)                 | Supporting C++ library for Joint t-SNE analysis, including a modified HDI component used by the analysis plugin         |

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

## Selected Highlights

- Developed interactive visual analytics tools for large,
  high-dimensional datasets
- Built and contributed to open-source C++/Qt visualization software
- Developed plugins and extensions for the ManiVault visual analytics
  framework
- Designed linked views and interactive workflows for single-cell,
  evolutionary, and spatial transcriptomics analysis
- Worked across visualization, data processing, UI development, and
  scientific computing
- Contributed to reusable visualization components, supporting libraries,
  deployment tooling, tutorials, and scientific websites
- Developed analysis workflows connecting scatterplots, tables, hierarchical
  views, spatial maps, and phylogenetic trees

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
