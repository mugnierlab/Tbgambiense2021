# VSG ORF references for T.b. gambiense and T.b. rhodesiense patients

* ORFs assembled from illumina RNA-seq reads de novo using Trinity (https://github.com/trinityrnaseq/trinityrnaseq/wiki) and identified as VSGs using BLASTn within the VSG-seq python pipeline
  *  These VSG assemblies are used as reference for alignment with bowtie (http://bowtie-bio.sourceforge.net/index.shtml) and subsequent quantitation of VSG expression
* AllHATpatients_clusterReference.csv matches each Trinity sequence ID to a cluster assigned by cd-hit (Gambiense## for those assembled in gHAT patients and Rhodesiense## for rHAT) which allowed comparison of VSG expression between different patients. Sequences with >98% identity were considered the same VSG. T.b. gambiense and T.b. rhodesiense VSGs were never directly compared to each other.
