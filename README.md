# End-to-end-untargeted-metabolomics
A simple end-to-end untargeted metabolomics analysis workflow.

Some preparation steps:  

- Please ensure you have the latest version of R installed locally. You can find
  about it here: [url](https://cran.r-project.org/src/base/R-4/)

-  Packages: you can copy/paste the code down here to install the bioconductor 
   packages needed to run the analysis. If at any point when running the code you get 
   an error message that a function cannot be found tell me and I will help. We also advise
   to chack for update as often as possible so you can properly enjoy the latest
   development in LC-MS/MS analysis.

```{r}
BiocManager::install("rformassspectrometry/Spectra")
BiocManager::install("sneumann/xcms")
BiocManager::install("RforMassSpectrometry/ProtGenerics")
BiocManager::install("RforMassSpectrometry/MsCoreUtils")
BiocManager::install("RforMassSpectrometry/Spectra")
BiocManager::install("RforMassSpectrometry/MSnbase")
BiocManager::install("RforMassSpectrometry/MetaboCoreUtils")
BiocManager::install("RforMassSpectrometry/CompoundDb")
BiocManager::install("RforMassSpectrometry/MetaboAnnotation")
BiocManager::install("RforMassSpectrometry/MsExperiment")
BiocManager::install("RforMassSpectrometry/MsBackendSql") # no need for now but maybe later
BiocManager::install("RforMassSpectrometry/SummarizedExperiment")
```

The other packages are part of CRAN so should be easy to install.


For co-auhtors: 

- Don't forget to regularly check if the main branch  was updated and merge it 
with your own branch as to not get out of sync with the main branch.

- I would advise to do your review by chunks such as: preprocessing, 
normalization/filtering, differential abundance analysis, annotation. This way
we avoid super big pull request. 

- Don't hesitate  to make changes, we need your input ! We can  discuss when 
you do  the pull request. 

-We will publish in the journal F1000 you can check this tosee the format we
are aiming for:
[url](https://f1000research.com/articles/5-2122)

Don't hesitate to contact me or johannes if you have technical problems

Good reading and thanks again!

