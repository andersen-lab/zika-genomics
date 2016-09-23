#### Data
[Sequences](https://github.com/andersen-lab/zika-florida/tree/master/consensus_sequences) | [Alignments](https://github.com/andersen-lab/zika-florida/tree/master/alignments) | [Trees](https://github.com/andersen-lab/zika-florida/tree/master/trees) | [BAMs](https://www.dropbox.com/sh/87bnqj83mwgw8br/AADWjkfL5bZ22XvemlMOUhBOa?dl=0)

#### Samples
| Scripps ID | Patient ID | Sample type | Quality score | Coverage |     Depth |
| :---       |       :--- | :---        | :---          |     :--- |      :--- |
| ZF1        |        001 | Saliva      | ***           |    97.16 |  59286.05 |
| ZF8        |        008 | Urine       | ***           |    85.96 |  18712.87 |
| ZF10       |        010 | Urine       | ****          |    97.66 |  30635.73 |
| ZF16       |        016 | Urine       | ***           |    100.0 |  76803.85 |
| ZF21       |        021 | Urine       | ***           |    97.64 |  56788.40 |
| ZF22       |        022 | Urine       | *             |    96.98 |  53493.29 |
| ZF30       |        030 | Urine       | ***           |    99.74 |  62811.74 |
| ZF32       |        032 | Urine       | ***           |    98.35 |  55852.93 |
| ZF36       |        036 | Serum       | *             |    92.66 |  46827.35 |
| ZF39       |        039 | Urine       | ****          |    99.76 |  77655.23 |
| ZL2        |     Hu0015 | Saliva      | ***           |    98.41 |  96506.56 |
| ZM1        |       7501 | Mosquito    | ****          |    98.95 | 156292.44 |
| ZM2        |       7719 | Mosquito    | ****          |    98.47 | 151795.35 |
| ZM3        |       7727 | Mosquito    | ****          |    99.97 | 154790.10 |

### Quality
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
 * HKY<sub>&#915;</sub> substitution model with (1+2),3 codon partitioning.
 * SkyGrid, 50 parameters, time at last point = 2.
 * 30,000,000 states.

**Disclaimer**. Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!