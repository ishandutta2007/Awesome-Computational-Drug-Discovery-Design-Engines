# Awesome-Computational-Drug-Discovery-Design-Engines

## Top Computational Drug Discovery & Design Engines Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Virtual Screening, Generative Design & ADMET Prediction*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Computational Drug Discovery & Design**. These tools enable researchers to screen billions of compounds, generate novel molecules with desired properties, predict ADMET profiles, and evaluate target-ligand interactions—accelerating hit identification and lead optimization.



**Examples** include Schrödinger, Recursion Pharmaceuticals, Insilico Medicine, Genesis Therapeutics, Iktos, Relay Therapeutics, Atomwise, Exscientia, Owkin, and Valo Health (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, ligand-based and structure-based virtual screening, and open generative models—ideal for computational chemists, academic researchers, and developers seeking transparent, vendor-independent drug design tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Schrödinger](https://www.schrodinger.com/)**  

  Industry-leading computational platform for molecular modeling and drug discovery. Features physics-based simulation, machine learning, and predictive analytics for lead identification and optimization. Widely used in pharmaceutical and biotechnology R&D.



- **[Recursion Pharmaceuticals](https://www.recursion.com/)**  

  Clinical-stage biotech combining AI with high-throughput biology. Features automated phenomics, deep learning for cellular image analysis, and digital chemistry for compound design.



- **[Insilico Medicine](https://insilico.com/)**  

  AI-driven drug discovery platform. Features generative chemistry (Chemistry42), target identification (PandaOmics), and clinical trial prediction. Lead candidate discovered and designed using AI reached Phase II trials.



- **[Genesis Therapeutics](https://www.genesistherapeutics.ai/)**  

  AI platform for drug discovery focused on molecular property prediction and generative design. Features neural network potentials and physics-based simulation.



- **[Iktos](https://iktos.ai/)**  

  AI-driven drug design platform. Features generative chemistry, retrosynthesis, and multi-parametric optimization for lead optimization.



- **[Relay Therapeutics](https://relaytx.com/)**  

  Clinical-stage biotech using computational approaches to drug discovery. Features protein dynamics simulation and AI-driven lead optimization.



- **[Atomwise](https://www.atomwise.com/)**  

  AI-powered virtual screening platform. Features deep learning for structure-based drug discovery and hit identification.



- **[Exscientia](https://www.exscientia.ai/)**  

  AI-driven precision medicine platform. Features generative design, active learning, and patient-centric drug design.



- **[Owkin](https://www.owkin.com/)**  

  AI platform for biomedical research and drug discovery. Features federated learning for multi-institutional data analysis and predictive biomarker discovery.



- **[Valo Health](https://valohealth.com/)**  

  AI-native drug discovery company. Features human data-driven target identification and generative chemistry for cardiovascular and neurodegenerative diseases.



## Open-Source GitHub Projects



- **[AdaptiveFlow](https://github.com/AdaptiveFlow-ai/adaptiveflow)**  

  Open-source platform for ultra-large virtual screening (ULVS) making billion-molecule screens more accessible, scalable, and efficient (open-source). **The largest ready-to-dock library available**—**69 billion compounds** from Enamine REAL Space, also available in SELFIES format. **18-dimensional grid** of molecular properties prioritizes promising chemical subspaces, with optional active learning reducing computational costs by orders of magnitude. Integrates **1,500+ docking protocols** including GPU-accelerated and ML-based methods (DiffDock, TANKBind). Achieves **near-linear scaling on up to 5.6 million CPUs** in AWS cloud. Identified nanomolar inhibitors of FSP1 and PARP1, with co-crystal structures providing mechanistic insights. **The most scalable open-source virtual screening platform available** .



- **[GNINA](https://github.com/gnina/gnina)**  

  Open-source molecular docking software with deep learning CNN scoring functions (license varies). **Version 1.3** updated from Caffe to **PyTorch**, enabling easier integration of custom PyTorch models. Retrained CNN scoring functions on updated CrossDocked2020 v1.3 dataset. Introduces **knowledge-distilled CNN scoring functions** for faster high-throughput screening. Adds **covalent docking** functionality. **The most user-friendly open-source docking framework with deep learning scoring** .



- **[PyRMD Studio](https://github.com/pyrmd/pyrmd)**  

  Unified suite for AI-powered virtual screening with graphical user interface (open-source). Combines **PyRMD** (ligand-based virtual screening) and **PyRMD2Dock** (structure-based virtual screening) in a single GUI. Features **Non-Expert Mode** requiring no CLI knowledge and **Expert Mode** for advanced fine-tuning. **Successfully evaluated 1 million compound screening on a standard consumer laptop** (AMD Ryzen 7 5700U, 16 threads, 8 GB RAM). Automates data curation from ChEMBL, docking score parsing, and result analysis. **The most accessible open-source virtual screening tool for non-expert users** .



- **[PyaiVS](https://github.com/danqingmk/OpenVS_PyaiVS)**  

  Unified Python package for AI-assisted ligand-based virtual screening (MIT). Integrates **multiple ML algorithms** (KNN, RF, SVM, XGBoost, DNN, GNN, GAT, MPNN, Attention FP), **five molecular representations** (2D-3D descriptors, PubChem fingerprints, MACCS, ECFP4, molecular graphs), and **three data splitting strategies** (random, scaffold, clustering-based). Automates model construction and hyperparameter tuning. Evaluated on six benchmark datasets (BACE, BBBP, Tox21, ClinTox, HIV, SIDER). Applied to ABCG2 inhibitor discovery. **The most comprehensive open-source AI-VS framework** .



- **[VeGA](https://github.com/piedelre93/VeGA-for-de-novo-design)**  

  Versatile generative architecture for bioactive molecules across multiple therapeutic targets (open-source, TensorFlow 2.9). **Leaner architecture** with fewer parameters than contemporary models while maintaining robust generative performance. Evaluated on MOSES benchmark (top-performing), ChEMBL generation (competitive with S4 and R4, superior scaffold diversity), and **transfer learning across five targets** (PKM2, MAPK1, GBA, mTORC1, FXR) with limited data. **Superior data efficiency** in low-data scenarios. Prospective FXR study generated novel ligands validated via docking. **The most data-efficient open-source molecular generator** .



- **[DrugDiff](https://github.com/drugdiff/drugdiff)**  

  Latent diffusion model for property-guided small molecule generation (open-source). Three parts: **VAE** trained on SELFIES from ZINC250K, **latent diffusion model** in VAE latent space, and **property predictors** for guidance. Uses **predictor guidance** rather than conditional training—new properties can be added without retraining the diffusion model. Achieves **internal diversity 0.912**, high novelty and uniqueness. Validated on GuacaMol Distribution-Learning benchmarks. **The most flexible open-source generative model for multi-property optimization** .



- **[Protenix](https://github.com/bytedance/Protenix)**  

  Open-source biomolecular structure prediction model toward high-accuracy AlphaFold3-class performance (open-source, PyPI installable). **Protenix-v2** (464M params, April 2026) shows clear gains on **antibody-antigen structure prediction** and ligand-related plausibility. **PXDesign** (built on Protenix) achieves **20–73% experimental success rates** across multiple targets—**2–6× higher than AlphaProteo and RFdiffusion**. **Protenix-Dock** provides classical protein-ligand docking with empirical scoring functions. Full training data pipeline and MSA pipeline open-sourced. **The most accurate open-source structure prediction model available** .



- **[RefProGen](https://github.com/refprogen/refprogen)**  

  Reference-guided molecular generation model with protein-ligand joint representation for property-aware drug design (open-source, ScienceDirect 2026). Features **multi-level protein representation** (residue-level features + local coordinate systems), **molecule-retrieval module** for structurally similar reference compounds, and **property-conditioned generation**. Evaluated on CrossDockedPocket10 (100,000+ protein-ligand pairs, 2,922 pockets). Outperforms SOTA baselines in binding affinity, drug-likeness, and synthesizability. **The most protein-aware open-source generative model** .



- **[PharmoADMET](https://zenodo.org/records/19648345)**  

  Integrated open-source platform for in silico ADMET prediction and analysis (Zenodo, April 2026). Supports **single-molecule and batch processing** workflows. Incorporates physicochemical property calculations, drug-likeness filters, and predictive models aligned with medicinal chemistry principles. Features **intuitive visualization** for interpreting ADMET profiles. Part of **Pharmoinformatics ecosystem**—integrates with molecular docking, QSAR, and pharmacophore tools. **The most comprehensive open-source ADMET platform** .



- **[Optimus Chem](https://github.com/pritampanda15/Optimus_Chemical_Analyzer)**  

  Comprehensive Python package for molecular property calculations and ADMET rules analysis (PyPI installable, open-source). Implements **all 14 major drug screening rules**: Lipinski, Veber, Ghose, Egan, Muegge, Rule of 3, CNS MPO, bRo5, PAINS, Pfizer 3/75, GSK 4/400, Lead-likeness, Brenk filters, REOS. Accurate RDKit-based calculations matching Discovery Studio standards. Features **CLI commands** (analyze, batch, report, validate) and **batch processing** to DataFrame. **The most complete open-source ADMET rules implementation** .



- **[GYDE](https://github.com/gyde-ai/gyde)**  

  Open-source, web-based collaboration platform for AI-powered protein design and engineering (Europe PMC, March 2026). Makes computational analyses of proteins and antibodies **accessible to bench scientists**. Features **tightly integrated visual interface** for exploring sequence-structure-function relationships, **seamless access to cutting-edge AI models** for structure prediction, design, and downstream analyses. Uses **Slivka compute API** for flexible tool addition. **Saved sessions** enable sharing findings across teams. **The most accessible open-source platform for experimental biologists** .



- **[SMASH](https://github.com/eddylab/SMASH)**  

  Fast, user-friendly molecular docking tool enhanced with ML virtual screening (Springer, 2026). **Automated receptor preparation** from PDB identifiers. **Binding-site identification** using co-crystallized ligands or **P2Rank** for apo structures. **Rigid-receptor docking framework** with AutoDock Vina. Designed for **small hardware**—runs efficiently on standard workstations. **The most automated open-source docking workflow** .



- **[Biomedical Data Translator](https://github.com/NCATSTranslator)**  

  Open-source knowledge graph-based system integrating clinical, genomic, pharmacological, and biomedical data (Mayo Clinic/Europe PMC, 2025). **Federated knowledge graph framework** enabling query retrieval, inference, and hypothesis generation. **User interface designed for non-technical users** gradually revealing evidence, provenance, and confidence information. Demonstrated on rare disease therapeutics, mechanism of action, and model organism validation. **The most comprehensive open-source biomedical knowledge integration platform** .



### Additional Strong Open-Source Options



- **[Open Molecular Software Foundation (OMSF)](https://omsf.io/)** — Umbrella organization coordinating open-source molecular modeling projects including OpenFold, OpenFF, OpenFE, and OpenADMET. **OpenFold3** represents significant advance in cofolding capability. **The most important open-source ecosystem for computational drug discovery** .

- **[Drugability Toolkit](https://zenodo.org/records/21652624)** — RDKit-based workflow for small-molecule developability assessment (MIT, Zenodo 2026). Features molecular descriptors, drug-likeness assessment, ADMET flags, synthetic accessibility, batch screening, and report generation .

- **[PyTrial](https://github.com/RyanWangZf/PyTrial)** — Python package for AI in drug development including patient-trial matching.

- **[OpenVS](https://github.com/danqingmk/OpenVS_PyaiVS)** — Community virtual screening tools.

- Community **n8n** workflows for screening pipeline automation and result alerting.



**Frameworks for building custom systems**: Combine **AdaptiveFlow** for ultra-large library screening with **GNINA** for deep learning docking, **PyaiVS** for ligand-based ML screening, **VeGA** or **DrugDiff** for generative design, **Optimus Chem** for ADMET filtering, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade drug discovery platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Computational drug discovery tools are **research aids, not clinical decision systems**. All predictions require experimental validation before clinical use.

- **Open-source drug discovery is advancing rapidly but remains research-stage for production pipelines.** AdaptiveFlow, GNINA, and PyaiVS are production-grade for virtual screening . Generative models (VeGA, DrugDiff, RefProGen) produce candidates requiring synthesis and assay validation .

- **Benchmark performance ≠ real-world success.** Models excelling on MOSES, GuacaMol, or CrossDocked benchmarks may not generalize to novel targets. Prospective validation (as VeGA and AdaptiveFlow demonstrated) is the true test .

- **Data quality determines model quality.** Generative models trained on ChEMBL or ZINC inherit biases and gaps in those datasets. Transfer learning to new targets with limited data (77–882 compounds) shows promise but requires careful validation .

- **Hardware requirements vary dramatically.** PyRMD Studio runs on consumer laptops ; AdaptiveFlow scales to 5.6 million CPUs on AWS . Choose tools appropriate for your computational resources.

- Self-hosted open-source solutions require proper security hardening, model validation, and ongoing maintenance. Molecular data and proprietary targets demand access controls and audit trails.



---



**Made for computational chemists, medicinal chemists, structural biologists, and developers building transparent drug discovery solutions.**  

Let's make Computational Drug Discovery more open, data-driven, and effective.
