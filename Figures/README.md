# R markdown notes and code for generating figures

* Data files necessary for running are either in supplemental tables or in the subdirectory: FigureData/
* All markdown files should run from current directory, except figure 5 which has associated data saved as an RData image.

Supplemental Tables 
* "Supptable3_tbgVSGexpression.csv" paper supplemental table detailing the highly expressed T.b. gambiense VSG expression level, N-terminal type as determined by HMM, and C-terminal type as determined by igraph network.
* "Supptable4_nterm_method_compare" paper supplemental table comparing the N-terminal domain typing results of three different methods for tb427 and patient VSG
* "Supptable5_tbrVSGexpression.csv" paper supplemental table detailing highly expressed T.b. rhodesiense patient VSG expression level and N-terminal domain type as determined by HMM

The HMM profile used for C-terminal BLASTp network analysis is also included in current directory. This can be used to find and extract the C-terminal domain from VSG protein fasta sequence using HMMscan.
