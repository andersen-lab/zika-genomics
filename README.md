Andersen Laboratory  
The Scripps Research Institute  
Scripps Translational Science Institute  
http://andersen-lab.com/  
github@andersen-lab.com  

Zika Florida
--

### Coding-complete genomes
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
* Made with BEAST using the following parameters:
* Uncorrelated relaxed clock with lognormal distribution, CTMC rate prior.
* HKYg substitution model with (1+2),3 codon partitioning.
* SkyGrid, 50 parameters, time at last point = 2.
* 50,000,000 states.

###Folder Structure

```
.
├── alignments
├── consensus_sequences
│   └── downloaded_2016.09.11
└── trees
    └── beast_xml
```
