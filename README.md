# Title
Erives AJ, Fassler JS (2015) Metabolic and Chaperone Gene Loss Marks the Origin of Animals: Evidence for Hsp104 and Hsp78 Chaperones Sharing Mitochondrial Enzymes as Clients. PLoS ONE 10(2): e0117192. https://doi.org/10.1371/journal.pone.0117192

# Reference
[Link](https://storage.googleapis.com/plos-corpus-prod/10.1371/journal.pone.0117192/1/pone.0117192.g001.PNG_L?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=wombat-sa%40plos-prod.iam.gserviceaccount.com%2F20210225%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210225T204941Z&X-Goog-Expires=3600&X-Goog-SignedHeaders=host&X-Goog-Signature=2ccd6885343547a26aeabf4fd1d473fbc7a804f94f793db3cf73fc16e77ac5b1394cc6a3c2bbe71c11d8c7da6663f46e538f15c233b16e23a75aef19da262a3106e622eb523452cc3721d8366ba2059ea774162d25cc1e0682cb6d9282ccfc9c924ad8d2b425b9c9c2b8a50203e97790440a4a643e745b8fae0f46f027cdca55a2427c15391b04941e22cc070b839a36f227dfe3e21e68410688fd10deb2ad545cbe0862bc9ec7c00756967effd16ce04a4eff1668dda9e1d5d08f799d9bab6fa84711c864b3002d91c76c97c4a1eb888915825d9b1733a4e3237793fcfbe8ac461330aa5fe34096333b3db4d213ffcfff6c2c7519a08b093fff0a678f1d89d5)
[Link 2](https://static-content.springer.com/esm/art%3A10.1038%2Fs41467-018-04136-5/MediaObjects/41467_2018_4136_MOESM4_ESM.xlsx)

# Introduction and Abstract
The authors of this paper were interested in seeing which genes were lost in the evolution of animals. While the expansion of genes, particularly transcription factors, in animals has been well-studied, the loss of genes from single-celled eukaryotes to animals has been poorly studied. Understanding which genes were lost is important because it may lend insight into the context, origin, and constraints associated with new transcription programs in animals.

They predicted 27 genes were maintained in non-animal eukaryotes but lost in animals. To test this hypothesis, they used BLASTP to compare the fungal (S. cerevisiae) homolog of those genes with 17 other organisms from fungi and holozoa. Their results confirmed their hypothesis. However, they only looked at 7 non-animal genomes and 10 animal genomes. Since that time, many more genomes have been sequenced. This project expands on their finding by using BLASTP to compare the S. cerevisiae genes to the 64 genomes in Paps et al., 2018.

# Original  Figure 
~[Figure 1](https://ibb.co/6JfKtNV)
![Figure 1](https://i.ibb.co/mFMnyS1/original-figure.png)

# Figure 1 Legend
(A) Heat map of twenty-seven genes (first twenty-seven rows with gene names) from the budding yeast S. cerevisiae (S. cer.) and their orthologs in related organisms with whole genome sequence assemblies and their closest matches in animals. Six of the twenty-seven yeast genes are the result of lineage-specific duplications in yeast (indicated by dark gray brackets, left of table), leaving twenty-four genetic functions either lost or not measurably conserved in metazoans. The heat map is based on the BLASTP expect values of the best match to the indicated yeast gene (see key, lower right of table). Species abbreviations: S. cer., Saccharomyces cerevisiae; S. pom., Schizosaccharomyces pombe; C. neo., Cryptococcus neoformans; P. gra., Puccinia graminis; B. den., Batrachochytrium dendrobatidis; C. owc., Capsaspora owczarzaki; M. bre., Monosiga brevicollis; S. ros., Salpingoeca rosetta; A. que., Amphimedon queenslandica; T. adh., Trichoplax adhaerens; M. lei., Mnemiopsis leidyi; N. vec., Nematostella vectensis; L. gig., Lottia gigantea; C. tel., Capitella teleta; H. rob., Helobdella robusta; D. mel., Drosophila melanogaster; and H. sap., Homo sapiens. Other abbreviations: Chytridio., Chytridiomycota; Placo., Placozoa; Ctenoph., Ctenophora; Ecdyso., Ecdysozoa; and Chor., Chordata. The last row is from an alternative screen for lost animal genes (see text) in which Amoebozoa PFAM domains that are absent in animals were identified (five genes already identified plus one new gene, PURB). (B) Close-up of the lost animal gene columns from panel A. This table shows either the taxonomic origin of a weak animal match, or the name of the gene if it is not directly related (i.e., not orthologous) to the named yeast gene (first column) for all matches with BLASTP expectation values < 1e-20. Most of the animal matches to the candidate lost genes correspond to lineage-specific horizontal gene transfers and/or environmental contaminants from unrelated (non-opisthokont) clades. Some matches correspond to non-orthologous genes such as ANKCLP (S2 Fig.) in the case of the eukaryotic clpB genes HSP78 and HSP104, or ACO1 in the case of LYS4 (Fig. 3). Only HIS2 might have been lost soon after early animal radiation based on the presence of a weak match in Trichoplax adhaerens. This gene is most similar to the version from Capsaspora and not to either of the two choanoflagellates, so it is of uncertain origin.

# My description of the figure
Figure 1 of this paper uses computational methods to identify genes and genetic functions retained in fungi and choanoflagellates but lost in animals. The left column is the list of genes predicted by the Ensembl pipeline to be conserved in fungi and choanoflagellates, but absent in animals. The boxes are the log of the e-values. The red boxes indicate a close BLASTP match with the yeast gene, and the blue boxes represent a weak to no match. This figure clearly shows that these genes are conserved in fungi and choanoflagellates and absent in animals (metazoans). There is a weak match in some metazoans with Hsp104 and Hsp78, but this is a nonfunctional variant of the gene.

# My Project 
This is a powerful figure, but lots of other genomes have been sequenced since this figure was made by Erives and Fassler. These genomes can be found in Paps et al., 2018. My objective is to redo their BLASTP analysis with more genomes, including more non-animal eukaryotes (besides fungi and choanoflagellates), and more animal genomes.

# Materials and Methods
1. Obtain the protein sequences for the 27 yeast genes in FASTA format from the supplemental figures of Erives and Fassler, 2015.
2. Obtain the list of sequenced genomes from Paps et al., 2018
3. Use the RefSeq_protein database in NCBI BLASTP to check for alignments between the 27 candidate genes and the sequenced genomes. For genomes not available in the RefSeq database, use the non-redundant database
4. Put the E-values in Microsoft excel, and obtain the log of the e-values. Enter an e-value of 1 for no matches (log of 1 is 0), and a manually enter a value of -200 for matches with an e-value of 0
5. To make the heat map use the conditional formatting feature in Excel. Set -200 as red, -100 as yellow, and the highest value as blue.
6. For the trimmed figure, remove genomes (columns) from the heat map with no BLASTP matches.
7. Copy and paste the heat map cells into Microsoft paint
8. Save the file as a JPEG

# My Figure 
~[My Figure](https://ibb.co/tBXxkKn)
![My Figure](https://i.ibb.co/8McdTsG/Data-Untrimmed.jpg)

~[Trimmed Version](https://ibb.co/LJYV1Dy)
![Trimmed Version](https://i.ibb.co/F0mRzk1/Data-Trimmed.jpg)



