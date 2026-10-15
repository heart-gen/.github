# The HEART-GeN Lab

**Health Equity for Advancing Research and Technology using Genomic Neuroscience (HEART-GeN)**

**Understanding how human genomic variation shapes brain biology—from RNA regulation to cellular function—and translating those insights into more equitable neuroscience.**

The HEART-GeN Lab integrates human genetics, transcriptomics, epigenomics, statistical modeling, and experimental systems to investigate the molecular mechanisms of neurological and psychiatric disorders. We study how genetic variation, ancestry, development, aging, and biological context shape gene regulation in the human brain.

Our research is motivated by a central challenge: **discoveries in genomic neuroscience must be biologically informative and generalizable across the populations they aim to serve.** Genetic ancestry is one dimension of human genomic variation—not a biological proxy for race or a complete explanation for health disparities. We seek to understand molecular mechanisms while recognizing that social, environmental, and structural factors also shape brain health and access to care.

## Research vision

We aim to move **from genetic variation to regulatory mechanisms, cellular consequences, and disease-relevant biology**. Rather than relying on gene-level expression alone, we examine how genetic effects operate through transcript choice, splicing, DNA methylation, cell-type-specific regulatory programs, and developmental transitions.

Three principles connect our work:

- **Mechanism over association.** Prioritize the regulatory events and cellular states through which genetic variation may influence brain function and disease.
- **Generalizability by design.** Investigate ancestry-associated and context-dependent effects, evaluate transferability across cohorts, and develop tools that enable more inclusive genomic analyses.
- **Computation linked to biology.** Combine interpretable statistical and machine-learning methods with postmortem human brain datasets, single-cell and spatial genomics, cerebral organoids, and induced pluripotent stem cell (iPSC)-derived models.

Our long-term goal is to generate testable mechanisms and reusable resources that can inform future approaches to prevention, diagnosis, and treatment.

## Research directions

### Ancestry-aware regulatory genomics

**How does human genetic diversity shape gene regulation across brain regions, cell types, and the lifespan?**

We integrate genetic ancestry, local ancestry, expression quantitative trait loci (eQTLs), allele-specific expression, and transcript-level measurements to study regulatory variation in diverse cohorts. We also investigate how ancestry-associated regulatory effects interact with aging and other biological contexts, with attention to neurodegenerative and psychiatric disease.

A major aim is to distinguish reproducible genetic mechanisms from cohort-specific or technical effects, improving the interpretability and portability of genomic discoveries.

### RNA isoforms and neuronal maturation

**When does transcript choice change cellular function rather than simply mark a cell state?**

Genes produce multiple RNA isoforms through alternative splicing and transcript usage. We investigate how coordinated isoform transitions accompany brain development and aging, whether specific transitions regulate neuronal maturation, and how disease-associated genetic variants perturb these programs.

This research connects human brain transcriptomics, statistical genetics, isoform-aware computational methods, and experimental models to identify transcript-level mechanisms that gene-abundance analyses can miss.

### Schizophrenia and neurodevelopmental mechanisms

**How do genetic and molecular changes alter the development and function of disease-relevant neural cell populations?**

We study schizophrenia across postmortem human brain regions—including the caudate nucleus, dorsolateral prefrontal cortex, and hippocampus—and experimental models of human brain development. Our work addresses cell-type-specific molecular regulation, sex-associated differences, cortical projection-neuron maturation, and relationships between developmental programs and disease risk.

In collaboration with experimental neuroscientists, we integrate single-cell RNA sequencing, cerebral organoids, and functional measurements to connect molecular findings to cellular phenotypes and testable hypotheses.

### Brain aging, epigenomics, and neurodegeneration

**How do regulatory and epigenetic programs change with age, and how might those changes contribute to disease vulnerability?**

We examine age-related changes in gene expression, RNA processing, and DNA methylation across human brain regions. Our work includes ancestry-by-aging interactions, allele-specific regulatory effects, local genetic influences on DNA methylation, and molecular processes relevant to Alzheimer's disease and related dementias.

We distinguish predictive molecular signatures from mechanisms supported by genetic, longitudinal, or experimental evidence.

### Interpretable genomic AI and reproducible methods

**How can computational tools reveal biologically meaningful regulatory structure while remaining rigorous, scalable, and reusable?**

We develop statistical genetics software, scalable multi-omics workflows, and interpretable machine-learning approaches for high-dimensional data. These methods span local-ancestry-aware QTL mapping, transcript-network inference, genetic contributions to methylation, and evaluation of single-cell state mapping.

A recurring focus is rigorous benchmarking, uncertainty, external validation, transparent failure modes, and reproducible research.

## Selected open-source software

| Software | Purpose |
| --- | --- |
| **[IsoGraph](https://github.com/heart-gen/IsoGraph)** | Identifies coordinated transcript-switching and gene-abundance programs through isoform-aware network analysis. |
| **[RFMix-reader](https://github.com/heart-gen/rfmix_reader)** | Provides memory-efficient access to RFMix, FLARE, and related local-ancestry outputs, with lazy data access and optional GPU-backed downstream operations. |
| **[localQTL](https://github.com/heart-gen/localQTL)** | Supports scalable, local-ancestry-aware QTL analysis, including GPU-enabled workflows and genetic fine-mapping utilities. |
| **[GENBoostGPU](https://github.com/heart-gen/GENBoostGPU)** | Provides computational workflows for evaluating local genetic contributions to DNA methylation, including relative ranking and out-of-fold prediction. |
| **[py-qvalue](https://github.com/heart-gen/py-qvalue)** | Implements q-value estimation and false discovery rate methods in Python. |
| **[dRFEtools](https://pypi.org/project/drfetools/)** | Supports interpretable feature selection for high-dimensional omics through dynamic recursive feature elimination. |

Explore our [GitHub repositories](https://github.com/orgs/heart-gen/repositories) for software, analysis code, documentation, and reproducibility resources.

## Collaborative science

Our research bridges computational genomics, human neuroscience, and experimental biology. Examples include:

- **Cerebral organoids and schizophrenia:** Working with Richard E. Straub, Ph.D., and Brady J. Maher, Ph.D. (Lieber Institute for Brain Development), to study neurodevelopmental and cell-type-specific molecular changes in schizophrenia.
- **Lung cellular genomics:** Working with Enid R. Neptune, M.D. (Johns Hopkins University School of Medicine), to examine angiotensin signaling and stromal and pericyte biology in human lung health and disease.

We welcome collaborations that connect statistical or computational discoveries to independent datasets, molecular perturbations, and functional experiments.

## Mentorship, equity, and open science

Training and community engagement are central to the HEART-GeN mission. We support trainees from varied backgrounds in developing skills in **computational biology, statistical genetics, scientific reasoning, reproducible software, and clear communication**. We emphasize rigorous interpretation, collaborative mentorship, and responsible engagement with the communities affected by the disorders we study.

We aim to share methods and results openly whenever permitted by data-use agreements, participant privacy protections, and collaborators' publication plans.

---

**Explore our work:** [HEART-GeN on GitHub](https://github.com/heart-gen) · [Repositories](https://github.com/orgs/heart-gen/repositories)
