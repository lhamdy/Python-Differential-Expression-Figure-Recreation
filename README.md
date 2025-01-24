# Python-Differential-Expression-Figure-Recreation
Python recreation of 2 figures displaying differential expression data, using Python DESeq2.

The data for this project was pulled from “Comparative transcriptomic profiling reveals a role for Olig1 in promoting axon regeneration” by Fu et al., which looked at axon regeneration in mice,particularly focusing on finding genes that contribute to this regeneration. The first figure I chose to recreate from this paper was a volcano plot, created using Python DESeq2 and Matplotlib, the steps for which are outlined in hamdy_project2.ipynb. Since the original paper had done it's analysis using R DESeq2, I ran another differential expression analysis using R, outlined in deseq.Rmd, and saved the results to r_deseq2_output.csv, which were used to create another version of the volcano plot. The second figure I recreated was a heatmap, created using Seaborn clustermap, outlined in hamdy_project2.ipynb.

A full write-up for this project is included in the file titled "Project 2 Write Up".
