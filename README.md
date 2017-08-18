*Summary: Zika virus sequence data from the 2016 outbreak in Florida. [Data here](https://github.com/andersen-lab/zika-florida).*

#### Data
[Sequences](https://github.com/andersen-lab/zika-florida/tree/master/consensus_sequences) | [Alignments](https://github.com/andersen-lab/zika-florida/tree/master/alignments) | [Trees](https://github.com/andersen-lab/zika-florida/tree/master/trees) | [BAMs](https://www.dropbox.com/sh/87bnqj83mwgw8br/AADWjkfL5bZ22XvemlMOUhBOa?dl=0)

#### Samples

| Scripps ID | Patient ID | Sample type | Quality score | % Coverage | Location of infection |
| :---       |       :--- | :---        | :---          |       :--- | :---                  |
| FL001Sa    |        001 | Saliva      | ***           |      99.71 | Martinique            |
| FL008U     |        008 | Urine       | ***           |      90.07 | Puerto Rico           |
| FL010U     |        010 | Urine       | ****          |      97.69 | USA: Florida          |
| FL016U     |        016 | Urine       | ***           |      99.88 | Puerto Rico           |
| FL021U     |        021 | Urine       | ***           |      97.45 | USA: Florida          |
| FL022U     |        022 | Urine       | ***           |      97.77 | USA: Florida          |
| FL030U     |        030 | Urine       | ***           |      99.75 | USA: Florida          |
| FL032U     |        032 | Urine       | ***           |      99.75 | USA: Florida          |
| FL036Se    |        036 | Serum       | ***           |      99.73 | USA: Florida          |
| FL038U     |        038 | Urine       | ***           |      99.76 | USA: Florida          |
| FL039U     |        039 | Urine       | ****          |      99.75 | USA: Florida          |
| Hu0015Sa   |     Hu0015 | Saliva      | ***           |      99.75 | USA: Florida          |
| FL01M      |       7501 | Mosquito    | ****          |      99.75 | USA: Florida          |
| FL02M      |       7719 | Mosquito    | ****          |      99.74 | USA: Florida          |
| FL03M      |       7727 | Mosquito    | ****          |      99.83 | USA: Florida          |
| FL04M      |   16-10416 | Mosquito    | ****          |      99.72 | USA: Florida          |
| FL05M      |    16-3125 | Mosquito    | ****          |      99.74 | USA: Florida          |
| FL06M      |            | Mosquito    | ****          |      99.71 | USA: Florida          |
| FL08M      |     pool#8 | Mosquito    | ****          |      97.70 | USA: Florida          |
| ZC188Se    |  423568715 | Serum       | ****          |      98.26 | Colombia              |
| ZC192Se    |  423401315 | Serum       | ****          |      98.36 | Colombia              |
| ZC204Se    |  424439915 | Serum       | ****          |      99.74 | Colombia              |
| ZC207Se    |  423217515 | Serum       | ****          |      96.68 | Colombia              |
| ZC199Se    | 4238001315 | Serum       | ***           |      97.44 | Colombia              |
| Hu0046Sa   |     Hu0046 | Saliva      | ****          |      98.20 | Cuba                  |

#### Quality
```
**** Complete coding sequence, no apparent contamination in aligned bam file
***	Complete coding sequence, some contamination in aligned bam file (confident in consensus)
**	Partial coding sequence, no apparent contamination in aligned bam file
*	Partial coding sequence, some contamination in aligned bam file
```

#### Sequencing
* Library construction was performed using an amplicon-based approach [amplicon-based approach](https://docs.google.com/document/d/1PilT4w5jHO-ROsE8TL5WBGa0wSCdTHAsNl1LIOYiTgk).
* Sequencing was performed on the MiSeq.

#### Coding-complete genomes
* Downloaded from NCBI, ViPR, and NextStrain. Only new genomes are added to later folders.
* Consensus sequences sequenced in our lab are added to the root of the 'consensus_sequences' folder.

#### Alignments
* Created using MAFFT.
* Trimmed to just contain the ORFs.

#### Maximum likelihood trees
* Created using the fast algorithm in RAxML using 200 bootstraps.
* Orange = travel-associated cases; Red = local transmissions.
* We root trees on KX447517 from French Polynesia.

#### Time-scaled trees 
* Made with BEAST using the following parameters:
 * Uncorrelated relaxed clock with lognormal distribution, CTMC rate prior.
 * HKY<sub>&#915;</sub> substitution model with codon partitioning.
 * SkyGrid, 50 parameters, time at last point = 4.
 * 30,000,000 states.

**Disclaimer**. Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!
