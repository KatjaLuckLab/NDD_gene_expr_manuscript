
The NGSpipe2go pipelines created by the IMB-Bioinformatics Core Facility was used for re-processing the Kaessmann data, to match the GTEx v8 processing. The relevant files to reproduce the counts are: 

 - NGSpipe2go/pipelines/RNAseq/essential.vars.groovy
 - NGSpipe2go/pipelines/RNAseq/rnaseq.pipeline.groovy - The pipeline was run in two stages, QC and alignment were performed first and then RNA-SeQC was ran to reproduce the analysis similar to the GTEx v8. The corresponding module files are NGSpipe2go/modules/RNAseq/rnaseqc.*
 - NGSpipe2go/pipelines/RNAseq/targets.txt

Usage information on the NGSpipe2go pipelines created by the IMB-Bioinformatics Core Facility, can be seen in the repository: https://gitlab.rlp.net/imbforge/NGSpipe2go 