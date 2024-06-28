# Crain-Nevil-Genetics2024
Annotated DNA maps for Crain and Nevil et al., 2024

Generated and annotated by Markus Nevil

## Included files and descriptions

The following files are provided as SnapGene and Genbank files.

1. HisC locus annotated
    - Bongartz and Schloissnig, 2019 full histone locus sequence annotated. This annotation includes two retrotransposons that interrupt histone gene arrays and the Alu-like element present in the majority of the gene array repeats (Matuso and Yamazaki, 1989a, 1989b). Near the two ends, there may be additional divergent histone array sequences. Other than some hand-annotated arrays, all features were automatically detected if they had >80% similarity).
3. dHisC locus annotated
   - The dHisC locus was fully sequenced as a result of Oxford Nanopore long read sequencing experiments of heterozygotes. Individual reads were selected if they lacked endogenous histone genes and used to generate a consensus sequence with Medaka consensus. Features were determined by BLAST and Snapgene similarity (>80% similarity). Due to low read coverage, the exact sequence may not be represented on the nucleotide level (long read has high error rate). However, the structure of the locus is consistant with the expected. Thus while the overall structure of the locus will not change with further refinement, the specific sequence might.
5. dHisCcadillac locus annotated
   - The dHisCcadillac locus was determined by sequencing the repair construct to determine sequence and structure of the "empty" locus. Long read sequencing of transgenic mutants provided additional information to determine the flanking sequences as well as confirm the sequence of the core locus. Note: a DOC element (not present in the reference dm6) was found to be distal to the dHisCcadillac locus. This DOC element is also present on the parental dHisC chromosome, thus this mobile element entered prior to the CRISPR event.
7. VK33 annotated
   - The VK33 attP landing site was determined by searching long reads for the AttP and constructed with overlapping reads. The sequence was determined by Medaka consensus and has a high error rate due to the inherently high error rate of long read sequencing. The annotation was determined by BLAST to the dm6 genome.
