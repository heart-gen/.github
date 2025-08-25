# The HEART-GeN Research Group

At the **H**ealth **E**quity for **A**dvancing **R**esearch and **T**echnology
using **Ge**nomic **N**euroscience (HEART-GeN) research group, our goal is to
improve treatments for brain disorders with health disparities.

While 99.99% of our genome is shared across global ancestral populations, the
very small fraction unique to a specific ancestral population can affect how
genes turn on or off. We use this human variation to find these genes that may
play a role in explaining health disparities for brain disorders.

## Research Vision

Our lab aims to improve therapeutics for underrepresented communities by
investigating the influence of genetic ancestry on molecular signatures
in the brain. We use computational tools and disease-relevant models
such as postmortem brain tissues, brain organoids, iPSC-derived glial
cells to uncover how genetic ancestry impacts complex traits in the brain.
This integrative approach provides insights into the interplay between
genetic and environmental factors in complex brain disorders.

We collaborate with the community to direct our efforts in the development
of impactful research. Therefore, one of the main focuses of our lab is
to train a diverse group of next-generation computational scientists
with the ability to communicate our findings with the community.

## Research Interests

### Genetic ancestry in the brain

In neuroscience and genomics, individuals with recent African ancestry (AA)
account for less than 5% of large-scale research cohorts for brain disorders
but are 20% more likely to experience a major mental health crisis.
Furthermore, divergent responses to antipsychotics between AA and European
ancestry (EA) have been linked to genetic differences. Understanding these
genetic and/or regulatory differences between AA and EA in the human brain,
is essential to the development of effective neurotherapeutics and
potentially could decrease health disparities for neurological disorders.

### Schizophrenia
#### Caudate nucleus and schizophrenia
Most studies of gene expression in the brain of individuals with schizophrenia
have focused on cortical regions. However, subcortical nuclei such as the
striatum are prominently implicated in the disease, and current antipsychotic
drugs target the striatum’s dense dopaminergic innervation.

#### Sex differences and schizophrenia
Schizophrenia is a complex neuropsychiatric disorder with sexually dimorphic
features, including differential symptomatology, drug responsiveness, and male
incidence rate. To date, only the prefrontal cortex has been studied in
large-scale transcriptome analyses for sex differences in schizophrenia.

### Software development

#### RFMix-reader: Accelerated reading and processing for local ancestry studies

Local ancestry inference is crucial for understanding population history and
disease genetics, especially for eQTL studies in admixed populations. While
RFMix is widely used, handling its output for large datasets is challenging due
to high memory and processing demands. To address this, `RFMix-reader`
efficiently processes large local ancestry datasets, leveraging GPUs for speed
and minimizing memory usage, enabling deeper insights into human health and
health disparities.

PyPI: <https://pypi.org/project/rfmix-reader/>

Documentation: <http://rfmix-reader.readthedocs.io/>

#### py-qvalue: Python version of q-value
`py-qvalue` is a Python package that provides a robust solution for controlling
the False Discovery Rate (FDR) in multiple hypothesis testing. This package is a
direct port of the well-regarded `qvalue` R package and is designed for
researchers who need to estimate the proportion of true null hypotheses
($\pi_0$), calculate q-values, and estimate local false discovery rates (lfdr).
By implementing key functions like `qvalue`, `pi0est`, and `lfdr`, it enables
straightforward FDR control within the Python ecosystem, making it an essential
tool for statistical analysis and multiple hypothesis testing workflows.

PyPI: <https://pypi.org/project/py-qvalue/>

Documentation: <https://github.com/heart-gen/py-qvalue>

#### dRFEtools: dynamic recursive feature elimination for omics

Technology advances have generated larger ‘OMICs datasets with applications
for machine learning. Even so, sample availability results in smaller sample
sizes compared to features. Dynamic recursive feature elimination (RFE)
provides a flexible feature elimination framework to tackle this problem.
`dRFEtools` provides an interpretable and flexible tool to gain biological
insights from ‘OMICs data using machine learning.

PyPI: <https://pypi.org/project/drfetools/>

Documentation: <http://drfetools.readthedocs.io/>

### Collaborations

#### Angiotensin II receptors in the human lung

Understanding the precise distribution and function of angiotensin receptors
within the lung is crucial for developing effective treatments for lung diseases
like COPD and IPF. Here, our goal is to provide a foundational framework by
mapping the expression patterns of *AGTR1* and *AGTR2* across different lung cell
types and identifying their involvement in specific disease states. Our findings
will offer new insights into the complex role of the renin-angiotensin system in
lung health and disease, paving the way for targeted therapeutic interventions.

Collaborator(s):
- Enid R. Neptune, M.D., at Johns Hopkins University School of Medicine

#### Cerebral organoids for schizophrenia

While significant advances have been made in bulk postmortem functional genomics
for schizophrenia, understanding cell-specific molecular alterations is still
challenging due to the cellular heterogeneity of brain tissue. Single-cell and
single-nucleus RNA-sequencing has helped by revealing disease-associated changes
and cell type-specific enrichment of schizophrenia risk genes. Additionally,
cerebral organoids, which model early human brain development and are amenable
to genetic manipulation, provide a powerful platform for studying cell
type-specific disease mechanisms in a controlled environment. By combining these
approaches, we can examine the specific cellular differences in schizophrenia
within cerebral organoids.

Collaborator(s):
- Richard E. Straub, Ph.D., at Lieber Institute for Brain Development
- Brady J. Maher, Ph.D., at Lieber Institute for Brain Development
