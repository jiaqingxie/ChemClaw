# ChemClaw Skills Catalog

This document is used to manage the skill classification and development checklist for ChemClaw.

---

### 1. 🗂️ Knowledge Mining
> **Description**: Convert literature, charts, and reaction information into structured chemical knowledge.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 1.1 | `literature-parsing` | Convert PDF literature to Markdown, and extract charts and images. | ✅ Completed |
| 1.2 | `reaction-data-extraction` | Extract reactants, conditions, yields from literature and output structured data. | ✅ Completed |
| 1.3 | `compound-characterization-extraction` | | ⬜ Pending |
| 1.4 | `computational-molecular-structure-extraction` | | ⬜ Pending |

### 2. 🔄 Chemical Representation
> **Description**: Convert between molecular representations such as IUPAC, SMILES, and images.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 2.1 | `iupac-to-smiles` | Convert IUPAC names to SMILES (OPSIN). | ✅ Completed |
| 2.2 | `smiles-to-iupac` | Convert SMILES to IUPAC names (multi-method fallback). | ✅ Completed |
| 2.3 | `mol-image-to-smiles` | Recognize molecular structure images into SMILES (DECIMER/MolNextR). | ✅ Completed |

### 3. 🔮 Prediction Engines
> **Description**: Predict properties and spectra based on molecular representations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 3.1 | `adme-prediction` | Predict molecular ADME properties (e.g., Caco-2, HIA, Pgp, bioavailability, lipophilicity). | ✅ Completed |
| 3.2 | `pka-predictor` | Predict pKa of small molecules, supporting heuristic and Uni-pKa backends. | ✅ Completed |
| 3.3 | `et30-prediction` | | ⬜ Pending |
| 3.4 | `melting-point-prediction` | | ⬜ Pending |
| 3.5 | `boiling-point-prediction` | | ⬜ Pending |
| 3.6 | `ch-nmr-prediction` | | ⬜ Pending |
| 3.7 | `boron-nmr-predict` | Predict 11B NMR chemical shifts for boron-containing compounds, and output annotated spectra. | ✅ Completed |
| 3.8 | `p-nmr-prediction` | | ⬜ Pending |
| 3.9 | `f-nmr-prediction` | | ⬜ Pending |
| 3.10| `si-nmr-prediction` | | ⬜ Pending |
| 3.11| `ir-spectra-simulation` | Calculate and visualize IR spectra based on SMILES/XYZ (MLatom). | ✅ Completed |
| 3.12| `raman-spectra-simulation`| Calculate and visualize Raman spectra based on SMILES/XYZ (MLatom). | ✅ Completed |
| 3.13| `surface-tension-predictor`| Reference prediction of surface tension based on SMILES. | ✅ Completed |
| 3.14| `viscosity-prediction` | | ⬜ Pending |
| 3.15| `tlc-rf-prediction` | | ⬜ Pending |
| 3.16| `chiral-separation-prediction`| | ⬜ Pending |
| 3.17| `molecular-properties-predictor`| Predict various physicochemical properties (e.g., boiling point, density, viscosity, surface tension).| ✅ Completed |
| 3.18| `nmr-prediction` | Predict 1H/13C NMR shifts based on SMILES and generate spectra. | ✅ Completed |
| 3.19| `uv-vis-spectrum-simulation`| Obtain and plot UV-Vis spectra based on SMILES. | ✅ Completed |
| 3.20| `ms-spectra-simulation` | Predict and visualize MS/MS spectra based on SMILES, supporting MGF/MSP output. | ✅ Completed |
| 3.21| `md-vib-spectra-simulation` | Calculate vibrational spectra (power spectrum/IR) based on MD trajectories. | ✅ Completed |
| 3.22| `xrd-spectra-simulation` | Calculate XRD spectra based on CIF structure files. | ✅ Completed |

### 4. 🧠 Reaction Intelligence
> **Description**: Infer and optimize reaction outcomes, conditions, and selectivity.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 4.1 | `reaction-outcome-prediction` | | ⬜ Pending |
| 4.2 | `reaction-condition-optimization`| | ⬜ Pending |

### 5. 💻 Computational Chemistry
> **Description**: Provide computational chemistry workflows and file processing capabilities.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 5.1 | `geometry-optimizer` | Optimize molecular geometry using xTB, supporting SMILES/XYZ inputs. | ✅ Completed |
| 5.2 | `chemical-file-converter`| Support interconversion of formats like .xyz/.gjf/.mol/.sdf/.pdb/.mol2. | ✅ Completed |

### 6. 🧪 Experiment Intelligence
> **Description**: Provide experimental protocols and execution assistance.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 6.1 | `experimental-protocol-generation`| | ⬜ Pending |

### 7. ✍️ Scientific Writing
> **Description**: Support scientific writing, reviews, and paper section generation.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 7.1 | `paper-section-generation` | | ⬜ Pending |
| 7.2 | `literature-review-writing` | | ⬜ Pending |

### 8. 📊 Visualization
> **Description**: Provide molecular structure and publication-quality graphic visualizations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 8.1 | `mol-2d-viewer` | Convert SMILES/chemical names to 2D structure diagrams. | ✅ Completed |
| 8.2 | `mol-3d-viewer` | Convert SMILES/chemical names to 3D structures and export interactive web pages. | ✅ Completed |
| 8.3 | `mol-paper-renderer`| Publication-quality molecular rendering, outputting SVG/PNG/PDF/GIF. | ✅ Completed |# ChemClaw Skills Catalog

This document is used to manage the skill classification and development checklist for ChemClaw.

---

### 1. 🗂️ Knowledge Mining
> **Description**: Convert literature, charts, and reaction information into structured chemical knowledge.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 1.1 | `literature-parsing` | Convert PDF literature to Markdown, and extract charts and images. | ✅ Completed |
| 1.2 | `reaction-data-extraction` | Extract reactants, conditions, yields from literature and output structured data. | ✅ Completed |
| 1.3 | `compound-characterization-extraction` | | ⬜ Pending |
| 1.4 | `computational-molecular-structure-extraction` | | ⬜ Pending |

### 2. 🔄 Chemical Representation
> **Description**: Convert between molecular representations such as IUPAC, SMILES, and images.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 2.1 | `iupac-to-smiles` | Convert IUPAC names to SMILES (OPSIN). | ✅ Completed |
| 2.2 | `smiles-to-iupac` | Convert SMILES to IUPAC names (multi-method fallback). | ✅ Completed |
| 2.3 | `mol-image-to-smiles` | Recognize molecular structure images into SMILES (DECIMER/MolNextR). | ✅ Completed |

### 3. 🔮 Prediction Engines
> **Description**: Predict properties and spectra based on molecular representations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 3.1 | `adme-prediction` | Predict molecular ADME properties (e.g., Caco-2, HIA, Pgp, bioavailability, lipophilicity). | ✅ Completed |
| 3.2 | `pka-predictor` | Predict pKa of small molecules, supporting heuristic and Uni-pKa backends. | ✅ Completed |
| 3.3 | `et30-prediction` | | ⬜ Pending |
| 3.4 | `melting-point-prediction` | | ⬜ Pending |
| 3.5 | `boiling-point-prediction` | | ⬜ Pending |
| 3.6 | `ch-nmr-prediction` | | ⬜ Pending |
| 3.7 | `boron-nmr-predict` | Predict 11B NMR chemical shifts for boron-containing compounds, and output annotated spectra. | ✅ Completed |
| 3.8 | `p-nmr-prediction` | | ⬜ Pending |
| 3.9 | `f-nmr-prediction` | | ⬜ Pending |
| 3.10| `si-nmr-prediction` | | ⬜ Pending |
| 3.11| `ir-spectra-simulation` | Calculate and visualize IR spectra based on SMILES/XYZ (MLatom). | ✅ Completed |
| 3.12| `raman-spectra-simulation`| Calculate and visualize Raman spectra based on SMILES/XYZ (MLatom). | ✅ Completed |
| 3.13| `surface-tension-predictor`| Reference prediction of surface tension based on SMILES. | ✅ Completed |
| 3.14| `viscosity-prediction` | | ⬜ Pending |
| 3.15| `tlc-rf-prediction` | | ⬜ Pending |
| 3.16| `chiral-separation-prediction`| | ⬜ Pending |
| 3.17| `molecular-properties-predictor`| Predict various physicochemical properties (e.g., boiling point, density, viscosity, surface tension).| ✅ Completed |
| 3.18| `nmr-prediction` | Predict 1H/13C NMR shifts based on SMILES and generate spectra. | ✅ Completed |
| 3.19| `uv-vis-spectrum-simulation`| Obtain and plot UV-Vis spectra based on SMILES. | ✅ Completed |
| 3.20| `ms-spectra-simulation` | Predict and visualize MS/MS spectra based on SMILES, supporting MGF/MSP output. | ✅ Completed |
| 3.21| `md-vib-spectra-simulation` | Calculate vibrational spectra (power spectrum/IR) based on MD trajectories. | ✅ Completed |
| 3.22| `xrd-spectra-simulation` | Calculate XRD spectra based on CIF structure files. | ✅ Completed |

### 4. 🧠 Reaction Intelligence
> **Description**: Infer and optimize reaction outcomes, conditions, and selectivity.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 4.1 | `reaction-outcome-prediction` | | ⬜ Pending |
| 4.2 | `reaction-condition-optimization`| | ⬜ Pending |

### 5. 💻 Computational Chemistry
> **Description**: Provide computational chemistry workflows and file processing capabilities.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 5.1 | `geometry-optimizer` | Optimize molecular geometry using xTB, supporting SMILES/XYZ inputs. | ✅ Completed |
| 5.2 | `chemical-file-converter`| Support interconversion of formats like .xyz/.gjf/.mol/.sdf/.pdb/.mol2. | ✅ Completed |

### 6. 🧪 Experiment Intelligence
> **Description**: Provide experimental protocols and execution assistance.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 6.1 | `experimental-protocol-generation`| | ⬜ Pending |

### 7. ✍️ Scientific Writing
> **Description**: Support scientific writing, reviews, and paper section generation.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 7.1 | `paper-section-generation` | | ⬜ Pending |
| 7.2 | `literature-review-writing` | | ⬜ Pending |

### 8. 📊 Visualization
> **Description**: Provide molecular structure and publication-quality graphic visualizations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 8.1 | `mol-2d-viewer` | Convert SMILES/chemical names to 2D structure diagrams. | ✅ Completed |
| 8.2 | `mol-3d-viewer` | Convert SMILES/chemical names to 3D structures and export interactive web pages. | ✅ Completed |
| 8.3 | `mol-paper-renderer`| Publication-quality molecular rendering, outputting SVG/PNG/PDF/GIF. | ✅ Completed |# ChemClaw Skills Catalog

This document is used to manage the skill classification and development checklist for ChemClaw.

---

### 1. 🗂️ Knowledge Mining
> **Description**: Convert literature, charts, and reaction information into structured chemical knowledge.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 1.1 | `literature-parsing` | Convert PDF literature to Markdown, and extract charts and images. | ✅ Completed |
| 1.2 | `reaction-data-extraction` | Extract reactants, conditions, yields from literature and output structured data. | ✅ Completed |
| 1.3 | `compound-characterization-extraction` | | ⬜ Pending |
| 1.4 | `computational-molecular-structure-extraction` | | ⬜ Pending |

### 2. 🔄 Chemical Representation
> **Description**: Convert between molecular representations such as IUPAC, SMILES, and images.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 2.1 | `iupac-to-smiles` | Convert IUPAC names to SMILES (OPSIN). | ✅ Completed |
| 2.2 | `smiles-to-iupac` | Convert SMILES to IUPAC names (multi-method fallback). | ✅ Completed |
| 2.3 | `mol-image-to-smiles` | Recognize molecular structure images into SMILES (DECIMER/MolNextR). | ✅ Completed |

### 3. 🔮 Prediction Engines
> **Description**: Predict properties and spectra based on molecular representations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 3.1 | `adme-prediction` | Predict molecular ADME properties (e.g., Caco-2, HIA, Pgp, bioavailability, lipophilicity). | ✅ Completed |
| 3.2 | `pka-predictor` | Predict pKa of small molecules, supporting heuristic and Uni-pKa backends. | ✅ Completed |
| 3.3 | `et30-prediction` | | ⬜ Pending |
| 3.4 | `melting-point-prediction` | | ⬜ Pending |
| 3.5 | `boiling-point-prediction` | | ⬜ Pending |
| 3.6 | `ch-nmr-prediction` | | ⬜ Pending |
| 3.7 | `boron-nmr-predict` | Predict 11B NMR chemical shifts for boron-containing compounds, and output annotated spectra. | ✅ Completed |
| 3.8 | `p-nmr-prediction` | | ⬜ Pending |
| 3.9 | `f-nmr-prediction` | | ⬜ Pending |
| 3.10| `si-nmr-prediction` | | ⬜ Pending |
| 3.11| `ir-spectra-simulation` | Calculate and visualize IR spectra based on SMILES/XYZ (MLatom). | ✅ Completed |
| 3.12| `raman-spectra-simulation`| Calculate and visualize Raman spectra based on SMILES/XYZ (MLatom). | ✅ Completed |
| 3.13| `surface-tension-predictor`| Reference prediction of surface tension based on SMILES. | ✅ Completed |
| 3.14| `viscosity-prediction` | | ⬜ Pending |
| 3.15| `tlc-rf-prediction` | | ⬜ Pending |
| 3.16| `chiral-separation-prediction`| | ⬜ Pending |
| 3.17| `molecular-properties-predictor`| Predict various physicochemical properties (e.g., boiling point, density, viscosity, surface tension).| ✅ Completed |
| 3.18| `nmr-prediction` | Predict 1H/13C NMR shifts based on SMILES and generate spectra. | ✅ Completed |
| 3.19| `uv-vis-spectrum-simulation`| Obtain and plot UV-Vis spectra based on SMILES. | ✅ Completed |
| 3.20| `ms-spectra-simulation` | Predict and visualize MS/MS spectra based on SMILES, supporting MGF/MSP output. | ✅ Completed |
| 3.21| `md-vib-spectra-simulation` | Calculate vibrational spectra (power spectrum/IR) based on MD trajectories. | ✅ Completed |
| 3.22| `xrd-spectra-simulation` | Calculate XRD spectra based on CIF structure files. | ✅ Completed |

### 4. 🧠 Reaction Intelligence
> **Description**: Infer and optimize reaction outcomes, conditions, and selectivity.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 4.1 | `reaction-outcome-prediction` | | ⬜ Pending |
| 4.2 | `reaction-condition-optimization`| | ⬜ Pending |

### 5. 💻 Computational Chemistry
> **Description**: Provide computational chemistry workflows and file processing capabilities.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 5.1 | `geometry-optimizer` | Optimize molecular geometry using xTB, supporting SMILES/XYZ inputs. | ✅ Completed |
| 5.2 | `chemical-file-converter`| Support interconversion of formats like .xyz/.gjf/.mol/.sdf/.pdb/.mol2. | ✅ Completed |

### 6. 🧪 Experiment Intelligence
> **Description**: Provide experimental protocols and execution assistance.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 6.1 | `experimental-protocol-generation`| | ⬜ Pending |

### 7. ✍️ Scientific Writing
> **Description**: Support scientific writing, reviews, and paper section generation.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 7.1 | `paper-section-generation` | | ⬜ Pending |
| 7.2 | `literature-review-writing` | | ⬜ Pending |

### 8. 📊 Visualization
> **Description**: Provide molecular structure and publication-quality graphic visualizations.

| No. | Name | Description | Status |
|:---|:---|:---|:---|
| 8.1 | `mol-2d-viewer` | Convert SMILES/chemical names to 2D structure diagrams. | ✅ Completed |
| 8.2 | `mol-3d-viewer` | Convert SMILES/chemical names to 3D structures and export interactive web pages. | ✅ Completed |
| 8.3 | `mol-paper-renderer`| Publication-quality molecular rendering, outputting SVG/PNG/PDF/GIF. | ✅ Completed |
