# proj_domain_populations
## Repository made for "Horizontal domain transfer within populations of closely related phages" master thesis project

### Aim of project

The "domain_populations" project has two objectives:

1. To analyse protein domains for phages in terms of their frequency of occurrence in a given proteome, to determine which domains are rare and may be evolutionarily important.
2. Create batch files with Genbank extension, with coordinated domains, for visualisation.

### How to handle the repository?

The repository consists of three scripts that, when run one after the other, produce results in the form of a **folder** with clusters of non-core domain co-ordinates and **illustrations** of rare, non-core domains. 

As input files for the scripts you need:

1. *ecod.develop283.domains.txt* file, downloaded from [ECOD database directories](http://prodata.swmed.edu/ecod/distributions/ecod.develop283.domains.txt) - this file describes all possible domains from the database - it is a snapshot of the state of the protein evolutionary conserved domains that are found throughout the ECOD database.
2. *hhblits-ecod.txt* file, stroing informations about discovered domains in each repseq, obtained by the script used to search the ECOD database through HMM algorithms (tool used: HHblits).
3. *name-table-full.txt* file, storing information about all repseqs, their cluster name, protein name and identificator from NCBI database, obtained thorugh script.
4. *surely.annot.proteins.txt*, contains data on the mapping of representative proteins to their functions, taken from the PHROGs database. Specifically, this file contains two columns - the identifier of the protein and the identifier of the function that has been predicted for the protein.
5. *annotation.indices.txt*, contains data on the mapping of representative proteins to their functions, taken from the PHROGs database. Specifically, this file contains three columns - function identifier, function name and function category.

All the necessary input files for the pipeline to work can be downloaded from the cloud [here](https://www.google.com/).

**IMPORTANT** Replace all file folder paths with your computer personalised paths.

### Questions and issues

All enquiries regarding the structure of scripts and repositories should be directed to email:

- maksnecki@gmail.com

Alternatively you can write in **Issues** tab, but problems or questions of the nature or the meaning of such a research project will be easier to explain by sending me an e-mail.
### Libraries needed and required to fire the scripts:
