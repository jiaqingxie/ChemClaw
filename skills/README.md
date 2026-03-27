# ChemClaw Skills Catalog

本文件用于管理 ChemClaw 的技能分类与建设清单。
<br>*This document is used to manage the skill classification and development checklist for ChemClaw.*

---

### 1. 🗂️ Knowledge Mining
> **描述 / Description**：将文献、图表和反应信息转换为结构化化学知识。<br>*Convert literature, charts, and reaction information into structured chemical knowledge.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 1.1 | `literature-parsing` | PDF 文献转 Markdown，并提取图表图片。<br>*Convert PDF literature to Markdown, and extract charts and images.* | ✅ 已完成<br>*(Completed)* |
| 1.2 | `reaction-data-extraction` | 从文献提取反应物、条件、产率并输出结构化数据。<br>*Extract reactants, conditions, yields from literature and output structured data.* | ✅ 已完成<br>*(Completed)* |
| 1.3 | `compound-characterization-extraction` | | ⬜ 待建设<br>*(Pending)* |
| 1.4 | `computational-molecular-structure-extraction` | | ⬜ 待建设<br>*(Pending)* |

### 2. 🔄 Chemical Representation
> **描述 / Description**：在 IUPAC、SMILES、图像等分子表示之间进行转换。<br>*Convert between molecular representations such as IUPAC, SMILES, and images.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 2.1 | `iupac-to-smiles` | 将 IUPAC 名称转换为 SMILES（OPSIN）。<br>*Convert IUPAC names to SMILES (OPSIN).* | ✅ 已完成<br>*(Completed)* |
| 2.2 | `smiles-to-iupac` | 将 SMILES 转换为 IUPAC 名称（多方法回退）。<br>*Convert SMILES to IUPAC names (multi-method fallback).* | ✅ 已完成<br>*(Completed)* |
| 2.3 | `mol-image-to-smiles` | 分子结构图片识别为 SMILES（DECIMER/MolNextR）。<br>*Recognize molecular structure images into SMILES (DECIMER/MolNextR).* | ✅ 已完成<br>*(Completed)* |

### 3. 🔮 Prediction Engines
> **描述 / Description**：基于分子表示进行性质与谱学相关预测。<br>*Predict properties and spectra based on molecular representations.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 3.1 | `adme-prediction` | 预测分子 ADME 性质（如 Caco-2、HIA、Pgp、生物利用度、亲脂性）。<br>*Predict molecular ADME properties (e.g., Caco-2, HIA, Pgp, bioavailability, lipophilicity).* | ✅ 已完成<br>*(Completed)* |
| 3.2 | `pka-predictor` | 预测小分子的 pKa，支持启发式与 Uni-pKa 后端。<br>*Predict pKa of small molecules, supporting heuristic and Uni-pKa backends.* | ✅ 已完成<br>*(Completed)* |
| 3.3 | `et30-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.4 | `melting-point-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.5 | `boiling-point-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.6 | `ch-nmr-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.7 | `boron-nmr-predict` | 预测含硼化合物的 11B NMR 化学位移，并可输出标注图。<br>*Predict 11B NMR chemical shifts for boron-containing compounds, and output annotated spectra.* | ✅ 已完成<br>*(Completed)* |
| 3.8 | `p-nmr-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.9 | `f-nmr-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.10| `si-nmr-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.11| `ir-spectra-simulation` | 基于 SMILES/XYZ 计算并可视化 IR 光谱（MLatom）。<br>*Calculate and visualize IR spectra based on SMILES/XYZ (MLatom).* | ✅ 已完成<br>*(Completed)* |
| 3.12| `raman-spectra-simulation`| 基于 SMILES/XYZ 计算并可视化 Raman 光谱（MLatom）。<br>*Calculate and visualize Raman spectra based on SMILES/XYZ (MLatom).* | ✅ 已完成<br>*(Completed)* |
| 3.13| `surface-tension-predictor`| 基于 SMILES 的表面张力参考预测。<br>*Reference prediction of surface tension based on SMILES.* | ✅ 已完成<br>*(Completed)* |
| 3.14| `viscosity-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.15| `tlc-rf-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 3.16| `chiral-separation-prediction`| | ⬜ 待建设<br>*(Pending)* |
| 3.17| `molecular-properties-predictor`| 预测多种物化性质（如沸点、密度、黏度、表面张力等）。<br>*Predict various physicochemical properties (e.g., boiling point, density, viscosity, surface tension).*| ✅ 已完成<br>*(Completed)* |
| 3.18| `nmr-prediction` | 基于 SMILES 预测 1H/13C NMR 位移并生成谱图。<br>*Predict 1H/13C NMR shifts based on SMILES and generate spectra.* | ✅ 已完成<br>*(Completed)* |
| 3.19| `uv-vis-spectrum-simulation`| 基于 SMILES 获取并绘制 UV-Vis 光谱。<br>*Obtain and plot UV-Vis spectra based on SMILES.* | ✅ 已完成<br>*(Completed)* |
| 3.20| `ms-spectra-simulation` | 基于 SMILES 预测并可视化 MS/MS 光谱，支持 MGF/MSP 输出。<br>*Predict and visualize MS/MS spectra based on SMILES, supporting MGF/MSP output.* | ✅ 已完成<br>*(Completed)* |
| 3.21| `md-vib-spectra-simulation` | 基于 MD 轨迹计算振动谱（power spectrum/IR）。<br>*Calculate vibrational spectra (power spectrum/IR) based on MD trajectories.* | ✅ 已完成<br>*(Completed)* |
| 3.22| `xrd-spectra-simulation` | 基于 CIF 结构文件计算 XRD 光谱。<br>*Calculate XRD spectra based on CIF structure files.* | ✅ 已完成<br>*(Completed)* |

### 4. 🧠 Reaction Intelligence
> **描述 / Description**：围绕反应结果、条件和选择性进行推断与优化。<br>*Infer and optimize reaction outcomes, conditions, and selectivity.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 4.1 | `reaction-outcome-prediction` | | ⬜ 待建设<br>*(Pending)* |
| 4.2 | `reaction-condition-optimization`| | ⬜ 待建设<br>*(Pending)* |

### 5. 💻 Computational Chemistry
> **描述 / Description**：提供计算化学流程与文件处理能力。<br>*Provide computational chemistry workflows and file processing capabilities.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 5.1 | `geometry-optimizer` | 使用 xTB 进行分子几何优化，支持 SMILES/XYZ 输入。<br>*Optimize molecular geometry using xTB, supporting SMILES/XYZ inputs.* | ✅ 已完成<br>*(Completed)* |
| 5.2 | `chemical-file-converter`| 支持 `.xyz/.gjf/.mol/.sdf/.pdb/.mol2` 等格式互转。<br>*Support interconversion of formats like .xyz/.gjf/.mol/.sdf/.pdb/.mol2.* | ✅ 已完成<br>*(Completed)* |

### 6. 🧪 Experiment Intelligence
> **描述 / Description**：提供实验方案与实验执行辅助。<br>*Provide experimental protocols and execution assistance.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 6.1 | `experimental-protocol-generation`| | ⬜ 待建设<br>*(Pending)* |

### 7. ✍️ Scientific Writing
> **描述 / Description**：支持科研写作、综述与论文段落生成。<br>*Support scientific writing, reviews, and paper section generation.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 7.1 | `paper-section-generation` | | ⬜ 待建设<br>*(Pending)* |
| 7.2 | `literature-review-writing` | | ⬜ 待建设<br>*(Pending)* |

### 8. 📊 Visualization
> **描述 / Description**：提供分子结构与论文级图形可视化。<br>*Provide molecular structure and publication-quality graphic visualizations.*

| 编号<br>(No.) | 技能名称<br>(Name) | 功能描述<br>(Description) | 状态<br>(Status) |
|:---|:---|:---|:---|
| 8.1 | `mol-2d-viewer` | SMILES/化学名称转 2D 结构图。<br>*Convert SMILES/chemical names to 2D structure diagrams.* | ✅ 已完成<br>*(Completed)* |
| 8.2 | `mol-3d-viewer` | SMILES/化学名称转 3D 结构并可导出交互网页。<br>*Convert SMILES/chemical names to 3D structures and export interactive web pages.* | ✅ 已完成<br>*(Completed)* |
| 8.3 | `mol-paper-renderer`| 论文级分子渲染，输出 SVG/PNG/PDF/GIF。<br>*Publication-quality molecular rendering, outputting SVG/PNG/PDF/GIF.* | ✅ 已完成<br>*(Completed)* |
