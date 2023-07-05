# MLST

Constructing a whole genome multi-locus sequence typing (wgMLST) scheme involves several steps, including the selection of target loci, primer design, sequencing, and analysis. Here's a general overview of the process:

1. Define the target loci: Select a set of informative loci across the whole genome that will be used to differentiate between strains or species. These loci should be present in all strains of interest and show sufficient sequence diversity to discriminate between them.

2. Sequence database: Create or obtain a reference database containing the known alleles for each of the target loci. This database will be used as a reference for allele calling during analysis.

3. Primer design: Design primers specific to each target locus. The primers should be designed to amplify the desired loci across a broad range of strains or species. Primer design can be performed using various software tools or by manual design based on the available genome sequences.

4. Amplification and sequencing: Extract genomic DNA from the strains of interest and perform PCR amplification using the designed primers. The amplified products are then sequenced using a suitable sequencing platform, such as Illumina or PacBio.

5. Data analysis: Process the sequencing data to obtain the allele sequences for each target locus. This can be done using bioinformatics tools such as read mapping, de novo assembly, or amplicon sequencing analysis software. Compare the obtained sequences with the reference database to assign allele numbers to each locus.

6. Allele calling and profile creation: Based on the assigned allele numbers, create a profile for each strain by concatenating the allele numbers for all target loci. This profile represents the wgMLST profile for the strain.

7. Phylogenetic analysis: Use the wgMLST profiles to perform phylogenetic analysis, which allows you to compare the relatedness and evolutionary relationships between different strains. Various software tools are available for constructing phylogenetic trees based on wgMLST data, such as FastTree, RAxML, or IQ-TREE.

8. Database management: Establish a database to store the wgMLST profiles and associated metadata for each strain. This database will allow for easy comparison of new strains with the existing collection and facilitate further analysis.

It's important to note that constructing a wgMLST scheme can be a complex task, and it often requires a bioinformatics expert and access to appropriate computational resources. Additionally, the specific details of the process may vary depending on the software and tools used for analysis.

