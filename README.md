# scRNA-pre-processing
A pre-processing pipeline in Linux / Shell for high throughout scRNA-seq analysis using publicly available data sets. The pipeline is composed of the following steps: 

1. Quality control (fastqc)
2. Transcript trimmings (fastp)
3. Transcript alignment (hisat2)
4. Transcript sorting (samtools)
5. Transcript indexing (samtools)
6. Deduplication (sambamba)
7. Read count quantification (stringtie)
8. Transcriptome merging (stringtie)
9. Gene count quantification (stringtie)