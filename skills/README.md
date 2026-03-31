# ChemClaw Skills Catalog

### 1. 🗂️ Knowledge Mining
>
> **Description**: Convert literature, charts, and reaction information into structured chemical knowledge.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 1.1 | [`literature-parsing`](./literature-parsing/) | Convert PDF literature to Markdown, and extract charts and images. | MVP |
| 1.2 | [`reaction-data-extraction`](./reaction-data-extraction/) | Extract reactants, conditions, yields from literature and output structured data. | MVP |
| 1.3 | `compound-characterization-extraction` |  | Planned |
| 1.4 | `computational-molecular-structure-extraction` |  | Planned |
| 1.5 | [`chem-data-extractor`](./chem-data-extractor/) | Extract structured compound characterization data (NMR/HRMS/HPLC/mp/ee/yield) from supplementary materials. | MVP |
| 1.6 | [`mineru-pdf-converter`](./mineru-pdf-converter/) | Convert PDF to structured Markdown with images/tables/formulas using MinerU (supports large PDFs). | MVP |
| 1.7 | [`pdf-dft-extractor`](./pdf-dft-extractor/) | Extract DFT coordinates from PDFs and generate Gaussian `.gjf` inputs (single or batch). | MVP |

### 2. 🔄 Chemical Representation
>
> **Description**: Convert between molecular representations such as IUPAC, SMILES, and images.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 2.1 | [`iupac-to-smiles`](./iupac-to-smiles/) | Convert IUPAC names to SMILES (OPSIN). | MVP |
| 2.2 | [`smiles-to-iupac`](./smiles-to-iupac/) | Convert SMILES to IUPAC names (multi-method fallback). | MVP |
| 2.3 | [`mol-image-to-smiles`](./mol-image-to-smiles/) | Recognize molecular structure images into SMILES (DECIMER/MolNextR). | MVP |

### 3. 🔮 Prediction Engines
>
> **Description**: Predict properties and spectra based on molecular representations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 3.1 | [`adme-prediction`](./adme-prediction/) | Predict molecular ADME properties (e.g., Caco-2, HIA, Pgp, bioavailability, lipophilicity). | MVP |
| 3.2 | [`pka-predictor`](./pka-predictor/) | Predict pKa of small molecules, supporting heuristic and Uni-pKa backends. | MVP |
| 3.3 | `et30-prediction` |  | Planned |
| 3.4 | `melting-point-prediction` |  | Planned |
| 3.5 | `boiling-point-prediction` |  | Planned |
| 3.6 | `ch-nmr-prediction` |  | Planned |
| 3.7 | [`boron-nmr-predict`](./boron-nmr-predict/) | Predict 11B NMR chemical shifts for boron-containing compounds, and output annotated spectra. | MVP |
| 3.8 | `p-nmr-prediction` |  | Planned |
| 3.9 | `f-nmr-prediction` |  | Planned |
| 3.10| `si-nmr-prediction` |  | Planned |
| 3.11| [`ir-spectra-simulation`](./ir-spectra-simulation/) | Calculate and visualize IR spectra based on SMILES/XYZ (MLatom). | MVP |
| 3.12| [`raman-spectra-simulation`](./raman-spectra-simulation/) | Calculate and visualize Raman spectra based on SMILES/XYZ (MLatom). | MVP |
| 3.13| [`surface-tension-predictor`](./surface-tension-predictor/) | Reference prediction of surface tension based on SMILES. | MVP |
| 3.14| `viscosity-prediction` |  | Planned |
| 3.15| `tlc-rf-prediction` |  | Planned |
| 3.16| `chiral-separation-prediction`|  | Planned |
| 3.17| [`molecular-properties-predictor`](./molecular-properties-predictor/) | Predict various physicochemical properties (e.g., boiling point, density, viscosity, surface tension). | MVP |
| 3.18| [`nmr-prediction`](./nmr-prediction/) | Predict 1H/13C NMR shifts based on SMILES and generate spectra. | MVP |
| 3.19| [`uv-vis-spectrum-simulation`](./uv-vis-spectrum-simulation/) | Obtain and plot UV-Vis spectra based on SMILES. | MVP |
| 3.20| [`ms-spectra-simulation`](./ms-spectra-simulation/) | Predict and visualize MS/MS spectra based on SMILES, supporting MGF/MSP output. | MVP |
| 3.21| [`md-vib-spectra-simulation`](./md-vib-spectra-simulation/) | Calculate vibrational spectra (power spectrum/IR) based on MD trajectories. | MVP |
| 3.22| [`xrd-spectra-simulation`](./xrd-spectra-simulation/) | Calculate XRD spectra based on CIF structure files. | MVP |

### 4. 🧠 Reaction Intelligence
>
> **Description**: Infer and optimize reaction outcomes, conditions, and selectivity.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 4.1 | `reaction-outcome-prediction` |  | Planned |
| 4.2 | `reaction-condition-optimization`|  | Planned |

### 5. 💻 Computational Chemistry
>
> **Description**: Provide computational chemistry workflows and file processing capabilities.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 5.1 | [`geometry-optimizer`](./geometry-optimizer/) | Optimize molecular geometry using xTB, supporting SMILES/XYZ inputs. | MVP |
| 5.2 | [`chemical-file-converter`](./chemical-file-converter/) | Support interconversion of formats like .xyz/.gjf/.mol/.sdf/.pdb/.mol2. | MVP |
| 5.3 | [`gjf-to-xyz`](./gjf-to-xyz/) | Convert Gaussian `.gjf` input files to `.xyz` format (single file or batch). | MVP |

### 6. 🧪 Experiment Intelligence
>
> **Description**: Provide experimental protocols and execution assistance.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 6.1 | `experimental-protocol-generation`|  | Planned |

### 7. ✍️ Scientific Writing
>
> **Description**: Support scientific writing, reviews, and paper section generation.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 7.1 | `paper-section-generation` |  | Planned |
| 7.2 | `literature-review-writing` |  | Planned |

### 8. 📊 Visualization
>
> **Description**: Provide molecular structure and publication-quality graphic visualizations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 8.1 | [`mol-2d-viewer`](./mol-2d-viewer/) | Convert SMILES/chemical names to 2D structure diagrams. | MVP |
| 8.2 | [`mol-3d-viewer`](./mol-3d-viewer/) | Convert SMILES/chemical names to 3D structures and export interactive web pages. | MVP |
| 8.3 | [`mol-paper-renderer`](./mol-paper-renderer/) | Publication-quality molecular rendering, outputting SVG/PNG/PDF/GIF. | MVP |
