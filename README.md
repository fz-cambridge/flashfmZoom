# flashfmZoom

<!-- badges: start -->
[![DOI](https://zenodo.org/badge/461200048.svg)](https://zenodo.org/badge/latestdoi/461200048)
<!-- badges: end -->

[*flashfmZoom*](https://drive.google.com/drive/folders/1lG6fKGYwLgJkKLj-ArnMZPNS-evsX5mg): a tool for joint fine-mapping and exploration of GWAS results in the UK Biobank.

The **quick instruction README file** of this tool, its source code and pre-loaded dataset [can be downloaded publicly here](https://drive.google.com/drive/folders/1lG6fKGYwLgJkKLj-ArnMZPNS-evsX5mg). Please Note: The latest updated *Version-2023-Feb-05* requires a few pre-loaded large datasets (i.e.: approx. 2GB), therefore we saved all source code and datasets in the [public online Google Drive](https://drive.google.com/drive/folders/1lG6fKGYwLgJkKLj-ArnMZPNS-evsX5mg) for users to download easily. Users just need download the whole folders into the local machine and run the *app.R* (i.e.: Rshiny file) on the [RStudio](https://www.rstudio.com). 

Accompanying paper:
> *flashfmZoom: a tool for joint fine-mapping and exploration of GWAS results in the UK Biobank* <br />
> Feng Zhou, Colin Starr, Adam S Butterworth, Jennifer L Asimit <br />
> The paper and its supplementary material can be downloaded here...

For more information, visit:
> flashfmZoom: http://...

## Overview
*flashfmZoom* is an all-in-one tool for analysis and interactive visualisation of potential causal genetic variants that underlie associations with quantitative traits from the UK Biobank. It offers a user-friendly interface and guides users in the selection of pleiotropic regions among subsets of 134 quantitative traits, such as cardiometabolic, hematologic, and respiratory traits. Users may then run single-trait fine-mapping, allowing for multiple causal variants, and leverage information between the traits using multi-trait fine-mapping to improve resolution. A series of interactive plots and downloadable tables are generated within flashfmZoom to identify potential causal variants that are shared or distinct between the traits; it also lists relevant literature for the traits and/or variants. Besides exploring traits that are well-known to be related, flashfmZoom encourages interactive exploration for the joint analysis of traits that may not often be considered together. This may reveal common aetiological pathways between traits related to different disorders.

## Availability and Implementation
*flashfmZoom* is an open-source software under the MIT license. It is available as an interactive web-based tool [https://github.com/fz-cambridge](https://github.com/fz-cambridge) and as an R package. Code and documentation are available at [https://github.com/fz-cambridge](https://github.com/fz-cambridge) and [https://github.com/jennasimit](https://github.com/jennasimit). Additional features can be downloaded as standalone R libraries to encourage reuse. 

## Installation
Users can directly use the online version of these tools without installing any packages or previous experience in programming languages. If users would like to run analyses in their local machines, then please download the codes from the [public online Google Drive](https://drive.google.com/drive/folders/1lG6fKGYwLgJkKLj-ArnMZPNS-evsX5mg) and open the Rshiny app in the local [RStudio](https://www.rstudio.com).

## Detailed installation steps
> MacOS:
> Linux:
> Windows:

## Examples
> Screenshots

## Authors
   - [Jennifer Asimit](https://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/a-to-g/jennifer-asimit/) (University of Cambridge)
   - [Adam Butterworth](https://www.phpc.cam.ac.uk/people/ceu-group/ceu-senior-academic-staff/adam-butterworth/) (University of Cambridge)
   - [Colin Starr](https://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/n-to-s/colin-starr/) (University of Cambridge)
   - [Feng Zhou](https://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/t-to-z/feng-zhou/) (University of Cambridge)

## Acknowledgements
The authors would like to thank the authors of KnockoffZoom (Sesia et al., 2020, 2021), echolocatoR (Schilder et al., 2020) and LocusZoom (Pruim et al., 2010; Boughton et al., 2020), as their clear software documentation and coding implementations were a key ingredient in the development of flashfmZoom. 

## Supplementary Material
See online appendix and README on (http:...), which also includes YouTube video demonstrations of the tool.

## Further references
> *FINEMAP: efficient variable selection using summary data from genome-wide association studies.* <br />
> Benner, C., Spencer, C. C., Havulinna, A. S., Salomaa, V., Ripatti, S., & Pirinen, M. (2016). <br />
> Bioinformatics, 32(10), 1493-1501. [https://doi.org/10.1093/bioinformatics/btw018](https://doi.org/10.1093/bioinformatics/btw018).

> *LocusZoom.js: interactive and embeddable visualization of genetic association study results.* <br />
> Boughton, A. P., Welch, R. P., Flickinger, M., VandeHaar, P., Taliun, D., Abecasis, G. R., & Boehnke, M. (2021). <br />
> Bioinformatics, 37(18), 3017-3018. [https://doi.org/10.1093/bioinformatics/btab186](https://doi.org/10.1093/bioinformatics/btab186).

> *The flashfm approach for fine-mapping multiple quantitative traits.* <br />
> Hernandez, N., Soenksen, J., Newcombe, P., Sandhu, M., Barroso, I., Wallace, C., Asimit, J.L. (2021). <br />
> Nat Commun 12, 6147. [https://doi.org/10.1038/s41467-021-26364-y](https://doi.org/10.1038/s41467-021-26364-y).

> *Fine-mapping genetic associations.* <br />
> Hutchinson, A., Asimit, J., Wallace, C. (2020). <br />
> Human Molecular Genetics, Volume 29, Issue R1, Pages R81–R88. [https://doi.org/10.1093/hmg/ddaa148](https://doi.org/10.1093/hmg/ddaa148).

> *JAM: a scalable Bayesian framework for joint analysis of marginal SNP effects.* <br />
> Newcombe, P. J., Conti, D. V. & Richardson, S. (2016). <br />
> Genet. Epidemiol. 40, 188–201. [https://doi.org/10.1002/gepi.21953](https://doi.org/10.1002/gepi.21953).

> *LocusZoom: regional visualization of genome-wide association scan results.* <br />
> Pruim, R. J., Welch, R. P., Sanna, S., Teslovich, T. M., Chines, P. S., Gliedt, T. P., ... & Willer, C. J. (2010). <br />
> Bioinformatics, 26(18), 2336-2337. [https://doi.org/10.1093/bioinformatics/btq419](https://doi.org/10.1093/bioinformatics/btq419).

> *echolocatoR: an automated end-to-end statistical and functional genomic fine-mapping pipeline. * <br />
> Schilder, B. M., Humphrey, J., & Raj, T. (2021). <br />
> Bioinformatics, 38(2), 536–539. [https://doi.org/10.1093/bioinformatics/btab658](https://doi.org/10.1093/bioinformatics/btab658).

> *Multi-resolution localization of causal variants across the genome. * <br />
> Sesia, M., Katsevich, E., Bates, S., Candès, E., & Sabatti, C. (2020). <br />
> Nature communications, 11(1), 1-10. [https://www.nature.com/articles/s41467-020-14791-2](https://www.nature.com/articles/s41467-020-14791-2).

> *False discovery rate control in genome-wide association studies with population structure. * <br />
> Sesia, M., Bates, S., Candès, E., Marchini, J., & Sabatti, C. (2021). <br />
> PNAS, 118(40), e2105841118. [https://doi.org/10.1073/pnas.2105841118](https://doi.org/10.1073/pnas.2105841118).

> *flashfm-ivis: interactive visualisation for fine-mapping of multiple quantitative traits. * <br />
> Zhou, F., Butterworth, A. S., & Asimit, J. L. (2022). <br />
> Bioinformatics, 38(17), 4238–4242. [https://doi.org/10.1093/bioinformatics/btac453](https://doi.org/10.1093/bioinformatics/btac453).
