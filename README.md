This code repo hosts scripts and analysis protocols used to generate results that are reported in our study: 
> [Yao, L. et al. High-resolution reconstruction of cell-type-specific transcriptional regulatory processes from bulk sequencing samples. Nat Biotechnol 1–12 (2026) doi:10.1038/s41587-026-03218-w.](https://doi.org/10.1038/s41587-026-03218-w).

## Structure of this repo
### Protocols
This folder stores major protocols/pipelines that we used to analyze/simulate sequencing data. 
Files are in json format; they are structured as follows:
* `name`
* `description`
* `step`: a list of steps in this protocol/pipeline
    * `step_order`: the order of this step in the protocol
    * `software`: software used
    * `parameter`: parameters for the software
    * `version_check`: how to report the version of the software
* `reference`: a dictionary of predefined variables that are referred to in this protocol
    * key: name of the reference
    * value: description about this reference

### Notebooks
Jupyter Notebooks used to analyze data and create figures for our manuscript.

### Software
In house scripts and modifications to published tools to incorporate them into our pipeline.
