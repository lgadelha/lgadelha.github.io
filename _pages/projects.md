---
layout: page
permalink: /projects/
title: projects
description: Selected work on research data infrastructure, FAIR data management, and computational workflows.
nav: true
nav_order: 2
_styles: >
  .post article h2 { font-size: 1.75rem; margin-top: 2rem; }
  .post article h3 { font-size: 1.2rem; margin-top: 1.25rem; }
  .post article p.tech { font-size: 0.9rem; color: var(--global-text-color-light); }
---

## Research Data Management and Infrastructure

### GreenRobust Central Data Hub

**2026 - present** - Cluster of Excellence GreenRobust, Heidelberg University

Data stewardship for plant sciences research in the [Central Data Hub](https://greenrobust.de/cdh-central-data-hub/): structuring research data as [DataPLANT](https://www.nfdi4plants.org/) Annotated Research Contexts (ARCs), describing it with metadata and ontologies, making analysis workflows FAIR, operating storage and backup infrastructure, and [training researchers](https://lgadelha.github.io/training/) in research data management.

<p class="tech">ARC, RO-Crate, CWL, ontologies, research data infrastructure operations</p>

### German Human Genome-Phenome Archive and the European Genomic Data Infrastructure

**2023 - 2026** - GHGA, German Cancer Research Center (DKFZ)

Coordination of the German node of the European Genomic Data Infrastructure ([GDI](https://gdi.onemilliongenomes.eu/)) at [GHGA](https://www.ghga.de). Deployed a GHGA-GDI integration prototype based on the FAIR Data Point and Beacon, and developed a proof-of-concept Python library for registering GHGA datasets in the Federated EGA through its Submitter API and RabbitMQ messaging.

<p class="tech">FAIR Data Point, Beacon v2, Python, RabbitMQ · <a href="https://github.com/GenomicDataInfrastructure/starter-kit-de-deployment-notes">GDI deployment notes</a> · <a href="https://github.com/EGA-archive/FEGA-onboarding">FEGA onboarding</a> · <a href="https://doi.org/10.1038/s41588-025-02101-9">Federated EGA paper</a> · <a href="https://doi.org/10.52825/cordi.v1i.394">GHGA paper</a></p>

### Research Data Management for the Cluster of Excellence Balance of the Microverse

**2020 - 2023** - University of Jena

Design and implementation of an integrative research data management framework for data on microbial communities (metagenomics, metabolomics, imaging), based on research data repositories, reproducible analysis workflows, and provenance tracking. Contributed to making metabolomics workflows reproducible and FAIR.

<p class="tech">Research data repositories, CWL, provenance · <a href="https://doi.org/10.1109/eScience55777.2022.00080">framework paper</a> · <a href="https://doi.org/10.1186/s13321-023-00695-y">MAW workflow</a> · <a href="https://doi.org/10.3390/metabo14020118">FAIR metabolomics workflows</a></p>

## Computational Workflows and Provenance

### GW-RePO: Genomic Workflow Resource and Parameter Optimization

**2025 - present**

An API that collects provenance and resource usage data from Nextflow workflow runs, so that runs can be queried and visualized, with an early machine learning-based prototype for generating optimized Nextflow tool configurations.

<p class="tech">Python, Nextflow, provenance, observability · <a href="https://github.com/lgadelha/gw-repo-prototype">GitHub</a> · <a href="https://doi.org/10.1145/3736229.3736267">paper</a></p>

### Provenance Management for the Swift Parallel Scripting Language

**2010 - 2013** - LNCC, University of Chicago, and Argonne National Laboratory

Design and implementation of MTCProv, the provenance management system of the [Swift](http://swift-lang.org/main/) parallel scripting language, which records how data was derived in large-scale parallel computations and supports queries correlating resource usage, scientific parameters, and data derivation.

<p class="tech">Relational databases, SQL, Swift · <a href="https://github.com/swift-lang/swift-k">Swift</a> · <a href="https://github.com/lgadelha/swift-provenancedb">provenance database</a> · <a href="https://doi.org/10.1007/s10619-012-7104-4">MTCProv paper</a></p>

### High-Performance Bioinformatics Workflows

**2016 - 2022** - LNCC

Frameworks and workflows for running bioinformatics analyses on the Brazilian National High-Performance Computing System (SINAPAD), including the Santos Dumont supercomputer: BioWorkbench for managing and analyzing bioinformatics experiments, the BioinfoPortal science gateway, and the ParslRNA-Seq workflow.

<p class="tech">Swift, Parsl, Python, HPC · <a href="https://doi.org/10.7717/peerj.5551">BioWorkbench</a> · <a href="https://doi.org/10.1016/j.future.2020.01.030">BioinfoPortal</a> · <a href="https://doi.org/10.1007/978-3-031-23821-5_13">ParslRNA-Seq</a></p>

## Biodiversity Informatics

### Brazilian Biodiversity Information System (SiBBr) and GBIF Brazil

**2014 - 2020** - LNCC

Implementation of [SiBBr](https://sibbr.gov.br/), the national infrastructure for collecting, integrating, and publishing biodiversity data in Brazil, and management of the Brazilian node in the Global Biodiversity Information Facility (GBIF).

<p class="tech">Biodiversity data standards, data integration · <a href="https://sol.sbc.org.br/index.php/bresci/article/view/10477">SiBBr paper</a> · <a href="https://doi.org/10.1002/widm.1394">biodiversity informatics survey</a></p>

### SISS-Geo: Wildlife Health Information System

**2014 - 2020** - LNCC

The Brazilian Wildlife Health Information System, a collaborative platform for monitoring wildlife health in which citizen scientists register wildlife occurrences that support health surveillance and risk assessment.

<p class="tech">Citizen science, data collection, health surveillance · <a href="https://sissgeo.lncc.br/">SISS-Geo</a> · <a href="https://doi.org/10.1007/s41666-019-00055-2">paper</a></p>

### Model-R: Scalable and Reproducible Ecological Niche Modeling

**2017 - 2021** - LNCC

A framework and workflows for running ecological niche and species distribution modeling at scale and reproducibly, including a web application for the modleR package.

<p class="tech">R, Swift, workflows · <a href="https://github.com/Model-R/modleR_shiny_app">modleR app</a> · <a href="https://github.com/lgadelha/sdm-workflows">SDM workflows</a> · <a href="https://doi.org/10.1007/978-3-319-73353-1_15">paper</a></p>
