# Abstract for conferences

Streamlining LC-MS/MS Data Analysis in R with Open-Source *xcms* and
*RforMassSpectrometry*: An End-to-End Workflow

Despite untargeted LC-MS/MS data being a powerful approach for large-scale
metabolomics analysis, a significant challenge in the field lies in the
reproducible and efficient analysis of such data, in particular. The power of
R-based analysis workflows lies in their high customizability and adaptability
to specific instrumental and experimental setups, but, while various specialized
packages exist for individual analysis steps, their seamless integration and
application to large cohort datasets remains elusive. Addressing this gap,
we present an comprehensible end-to-end R workflow that leverages *xcms* and
packages of the *RforMassSpectrometry* environment to encompass all aspects of
pre-processing and downstream analyses for LC-MS/MS datasets in a reproducible
manner.

This poster/presentation delineates a step-by-step analysis of an example
untargeted metabolomics dataset tailored to quantify the small polar metabolome
in human plasma samples and aimed to identify differences between individuals
suffering from a cardiovascular disease and healthy controls. The objective of
the workflow is to meticulously detail each step, from the preprocessing of raw
mzML files to the annotation of differentially abundant ions between the two
groups.

Our  workflow seamlessly integrates Bioconductor packages, offering adaptability
to diverse study designs and analysis requirements. This workflow facilitates
preprocessing, feature detection, alignment, normalization, statistical
analysis and annotation within a unified framework, thereby enhancing the
efficiency of metabolomic investigations. We also discuss alternative
approaches to accommodate various dataset and goals, while emphasizing proper
quality management for LC-MS data analysis.
