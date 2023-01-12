# Gressier_2022
_Github repository for the scRNA-seq and scATAC-seq analyses of Gressier et al. 2022 by Jonas Schulte-Schrepping._

In this repository, you can find all the code that has been written by Jonas Schulte-Schrepping to analyze and visualize the scRNA-seq and scATAC-seq data presented in Gressier et al. 2022:
**CD4+ T cells select unique P65, IRF1 and FOS dependent responses in APC for integration into antiviral CD8+ T cell immunity**

For this project, single-cell transcriptomic and epigenetic profiles from CD14+ monocytes, myeloid DC and CD8+ T cells derived from scRNA-seq data originally published in Schulte-Schrepping et al., Cell 2020 (10.1016/j.cell.2020.08.001) and in Wilk et al., 2021 JEM (10.1084/jem.20210582) have been re-analyzed to investigate how T cell help regulates the way antigen-presenting cells (APC) integrate IFN-α/-β signals into effective CD8+ T cell immunity.

We also subjected PBMC from patients with neutralizing antibodies against Type I IFN described in Akbil et al. (10.1007/s10875-022-01252-2) to scRNA-seq and analyzed classical CD14+ monocytes from these patients as well as appropriate healthy and diseased controls without autoantibodies.

In addition, we performed an integrated analysis of a combined data set of 179.012 single-cell monocyte transcriptomes across 263 samples (39 control, 79 mild COVID-19 (WHO 1-3), 82 moderate COVID-19 (WHO 4-5), 52 severe COVID-19 (WHO 6-8), 11 severe COVID-19 with anti-Type I IFN antibodies (WHO 7-8) derived from 4 different cohorts including our own an data from Su et al. (10.1016/j.cell.2020.10.037), Van der Wijst et al. (10.1126/scitranslmed.abh2624) and Georg et al. (10.1016/j.cell.2021.12.040).

The scRNA-seq analysis have been performed in the docker container jsschrepping/r_docker:jss_R403_seurat4 and the scATAC-seq analysis in jsschrepping/r_docker:jss_R410_scEpi, which can be found [here](https://github.com/jsschrepping/r_docker).

All processed data sets (Seurat Objects) and respective code can also be found on FASTGenomics under [https://beta.fastgenomics.org/p/gressier_2022](https://beta.fastgenomics.org/p/gressier_2022).

(Image produced using biorender.com)

The scRNA-seq analysis have been performed in the docker container jsschrepping/r_docker:jss_R403_seurat4 and the scATAC-seq analysis in jsschrepping/r_docker:jss_R410_scEpi, which can be found [here](https://github.com/jsschrepping/r_docker).

![results](images/GraphicalAbstractGithub.png?raw=true "")
