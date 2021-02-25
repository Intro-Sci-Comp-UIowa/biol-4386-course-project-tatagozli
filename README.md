# Title
Erives AJ, Fassler JS (2015) Metabolic and Chaperone Gene Loss Marks the Origin of Animals: Evidence for Hsp104 and Hsp78 Chaperones Sharing Mitochondrial Enzymes as Clients. PLoS ONE 10(2): e0117192. https://doi.org/10.1371/journal.pone.0117192

# Reference
[Link](https://storage.googleapis.com/plos-corpus-prod/10.1371/journal.pone.0117192/1/pone.0117192.g001.PNG_L?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=wombat-sa%40plos-prod.iam.gserviceaccount.com%2F20210225%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210225T204941Z&X-Goog-Expires=3600&X-Goog-SignedHeaders=host&X-Goog-Signature=2ccd6885343547a26aeabf4fd1d473fbc7a804f94f793db3cf73fc16e77ac5b1394cc6a3c2bbe71c11d8c7da6663f46e538f15c233b16e23a75aef19da262a3106e622eb523452cc3721d8366ba2059ea774162d25cc1e0682cb6d9282ccfc9c924ad8d2b425b9c9c2b8a50203e97790440a4a643e745b8fae0f46f027cdca55a2427c15391b04941e22cc070b839a36f227dfe3e21e68410688fd10deb2ad545cbe0862bc9ec7c00756967effd16ce04a4eff1668dda9e1d5d08f799d9bab6fa84711c864b3002d91c76c97c4a1eb888915825d9b1733a4e3237793fcfbe8ac461330aa5fe34096333b3db4d213ffcfff6c2c7519a08b093fff0a678f1d89d5)

# Introduction 
The authors of this paper were interested in seeing which genes were lost in the evolution of animals. To do this they compared the genomes of closely related eukaryotes, such as yeast and choanoflagellates, to animals and found that twenty-four genetic functions retained in lower order eukaryotes but lost in animals. Most interestingly, they found two powerful molecular chaperones, Hsp78 and Hsp104, were abruptly lost during the evolution of unicellular organisms to animals. It is not clear why this occurred, but the authors suggest the loss of shared clients of Hsp78 and Hsp104 played a role.

# Figure 
![Figure 1](https://storage.googleapis.com/plos-corpus-prod/10.1371/journal.pone.0117192/1/pone.0117192.g001.PNG_L?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=wombat-sa%40plos-prod.iam.gserviceaccount.com%2F20210225%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210225T204941Z&X-Goog-Expires=3600&X-Goog-SignedHeaders=host&X-Goog-Signature=2ccd6885343547a26aeabf4fd1d473fbc7a804f94f793db3cf73fc16e77ac5b1394cc6a3c2bbe71c11d8c7da6663f46e538f15c233b16e23a75aef19da262a3106e622eb523452cc3721d8366ba2059ea774162d25cc1e0682cb6d9282ccfc9c924ad8d2b425b9c9c2b8a50203e97790440a4a643e745b8fae0f46f027cdca55a2427c15391b04941e22cc070b839a36f227dfe3e21e68410688fd10deb2ad545cbe0862bc9ec7c00756967effd16ce04a4eff1668dda9e1d5d08f799d9bab6fa84711c864b3002d91c76c97c4a1eb888915825d9b1733a4e3237793fcfbe8ac461330aa5fe34096333b3db4d213ffcfff6c2c7519a08b093fff0a678f1d89d5)

# Figure 1 Legend
(A) Heat map of twenty-seven genes (first twenty-seven rows with gene names) from the budding yeast S. cerevisiae (S. cer.) and their orthologs in related organisms with whole genome sequence assemblies and their closest matches in animals. Six of the twenty-seven yeast genes are the result of lineage-specific duplications in yeast (indicated by dark gray brackets, left of table), leaving twenty-four genetic functions either lost or not measurably conserved in metazoans. The heat map is based on the BLASTP expect values of the best match to the indicated yeast gene (see key, lower right of table). Species abbreviations: S. cer., Saccharomyces cerevisiae; S. pom., Schizosaccharomyces pombe; C. neo., Cryptococcus neoformans; P. gra., Puccinia graminis; B. den., Batrachochytrium dendrobatidis; C. owc., Capsaspora owczarzaki; M. bre., Monosiga brevicollis; S. ros., Salpingoeca rosetta; A. que., Amphimedon queenslandica; T. adh., Trichoplax adhaerens; M. lei., Mnemiopsis leidyi; N. vec., Nematostella vectensis; L. gig., Lottia gigantea; C. tel., Capitella teleta; H. rob., Helobdella robusta; D. mel., Drosophila melanogaster; and H. sap., Homo sapiens. Other abbreviations: Chytridio., Chytridiomycota; Placo., Placozoa; Ctenoph., Ctenophora; Ecdyso., Ecdysozoa; and Chor., Chordata. The last row is from an alternative screen for lost animal genes (see text) in which Amoebozoa PFAM domains that are absent in animals were identified (five genes already identified plus one new gene, PURB). (B) Close-up of the lost animal gene columns from panel A. This table shows either the taxonomic origin of a weak animal match, or the name of the gene if it is not directly related (i.e., not orthologous) to the named yeast gene (first column) for all matches with BLASTP expectation values < 1e-20. Most of the animal matches to the candidate lost genes correspond to lineage-specific horizontal gene transfers and/or environmental contaminants from unrelated (non-opisthokont) clades. Some matches correspond to non-orthologous genes such as ANKCLP (S2 Fig.) in the case of the eukaryotic clpB genes HSP78 and HSP104, or ACO1 in the case of LYS4 (Fig. 3). Only HIS2 might have been lost soon after early animal radiation based on the presence of a weak match in Trichoplax adhaerens. This gene is most similar to the version from Capsaspora and not to either of the two choanoflagellates, so it is of uncertain origin.

# My description of the figure
Figure 1 of this paper uses computational methods to identify genes and genetic functions retained in fungi and choanoflagellates but lost in animals

# Materials and Methods
Generate a manageable gene list using Ensembl's BioMart query engine to iteratively identify orthologs present in fungi but absent in Drosophila melanogaster and Homo sapiens

There should be 802 genes now. Query the Joint Genome Institute's (JGI) BLASTP Sever (genome.jgi.doe.gov) with each yeast protein to identify fungal proteins which match with protein sequences from the choanoflagellate M. brevicollis with a BLASTP E-value of 1.0E-30 or lower

There should be 210 genes now. Use a threshold E-value of 1.0E-10 to remove yeast proteins that either had no matches or were not detectable for the colonial choanoflagellate S. rosetta and the filasterean C. owczarzaki.

Also remove those that have E-values in animals smaller (i.e., better) than any of the three listed non-animal holozoans (the choanoflagellates and filasterean)

For animals, use the sponge Amphimedon queenslandica (NCBI), the ctenophore Mnemiopsis leidyi (NHGRI), the placozoan Trichoplax adhaerens (NCBI), and the lophotrochozoans Lottia gigantea, Capitella teleta, and Helobdella robusta, all of which have complete genome sequence assemblies.

With these genomic comparisons, there should be twenty-seven yeast genes that are largely retained outside of animals in the analyzed genomes.

Six of these genes (TRR1/TRR2, LYS20/LYS21, and SCT1/GPT2) correspond to lineage-specific duplications in yeast (connected genes in Fig. 1). Thus, twenty-four genetic functions are definitively lost in animals or at least not retained at the same level of conservation as they are in non-metazoans

Make a heat map based on BLASTP expect values of the best match to the indicated yeast gene

Figure 1B should show either the taxonomic origin of a weak animal match, or the name of the gene if it is not directly related (i.e., not orthologous) to the named yeast gene (first column) for all matches with BLASTP expectation values < 1e-20.
