# Sequence-homology-evaluation
This program evaluates the homology of 20-nt sequence to be served as CRISPR target and aims to determine the one most homologous with a satisfying crRNA spacer structure.

In the program, we provided an example evaluating the sequence homology of HIV-1. The reference sequence (NC001802.1) can be obtained from https://www.ncbi.nlm.nih.gov/nuccore/9629357. The sequencing records of HIV-1 were obtained from NCBI Virus Database, which are provided in the FASTA files and can also be accessed via 
(https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Nucleotide&VirusLineage_ss=Human%20immunodeficiency%20virus%201,%20taxid:11676&utm_source=nuccore&utm_medium=referral

The Python package ViennaRNA needs to be installed before executing the program. Please use this command for installation:
pip install ViennaRNA 
More information can be found via the link: https://pypi.org/project/ViennaRNA/
