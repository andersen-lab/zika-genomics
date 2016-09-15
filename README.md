https://github.com/andersen-lab/zika-florida/tree/master/consensus_sequences

#### Coding-complete genomes
* Downloaded from NCBI, ViPR, and NextStrain. Only new genomes are added to later folders.
* Consensus sequences sequenced in our lab are added to the root of the 'consensus_sequences' folder.

### Alignments:
* Created using MAFFT.
* Trimmed to just contain the ORFs.

### Maximum likelihood trees
* Created using the fast algorithm in RAxML using 200 bootstraps.
* Orange = travel-associated cases; Red = local transmissions.
* We root trees on KX447517 from French Polynesia.

### Time-aware trees 
Made with BEAST using the following parameters:
* Uncorrelated relaxed clock with lognormal distribution, CTMC rate prior.
* HKYg substitution model with (1+2),3 codon partitioning.
* SkyGrid, 50 parameters, time at last point = 2.
* 50,000,000 states.

### Disclaimer 
Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!