#### Summary
Zika virus sequence data from the 2015-2018 epidemic in the Americas.

#### Data
[Sequences](https://github.com/andersen-lab/zika-florida/tree/master/consensus_sequences) | [Alignments](https://github.com/andersen-lab/zika-florida/tree/master/alignments) | [Trees](https://github.com/andersen-lab/zika-florida/tree/master/trees) | [BAMs](https://www.dropbox.com/sh/87bnqj83mwgw8br/AADWjkfL5bZ22XvemlMOUhBOa?dl=0)

#### Samples

| Scripps ID | Date       | Sample type | Quality score | % Coverage | Location of infection |
| :---       | :---       | :---        | :---          | :---       | :---                  |
| FL001Sa    | 2016.03.22 | Saliva      | ***           | 99.71      | Martinique            |
| FL008U     | 2016.06.21 | Urine       | ***           | 90.07      | Puerto Rico           |
| FL010U     | 2016.06.22 | Urine       | ****          | 97.69      | USA: Florida          |
| FL016U     | 2016.07.03 | Urine       | ***           | 99.88      | Puerto Rico           |
| FL021U     | 2016.07.19 | Urine       | ***           | 97.45      | USA: Florida          |
| FL022U     | 2016.07.16 | Urine       | ***           | 97.77      | USA: Florida          |
| FL030U     | 2016.08.02 | Urine       | ***           | 99.75      | USA: Florida          |
| FL032U     | 2016.08.05 | Urine       | ***           | 99.75      | USA: Florida          |
| FL036Se    | 2016.08.04 | Serum       | ***           | 99.73      | USA: Florida          |
| FL038U     | 2016.08.04 | Urine       | ***           | 99.76      | USA: Florida          |
| FL039U     | 2016.08.17 | Urine       | ****          | 99.75      | USA: Florida          |
| Hu0015Sa   | 2016.08.24 | Saliva      | ***           | 99.75      | USA: Florida          |
| FL01M      | 2016.08.22 | Mosquito    | ****          | 99.75      | USA: Florida          |
| FL02M      | 2016.08.23 | Mosquito    | ****          | 99.74      | USA: Florida          |
| FL03M      | 2016.08.23 | Mosquito    | ****          | 99.83      | USA: Florida          |
| FL04M      | 2016.09.04 | Mosquito    | ****          | 99.72      | USA: Florida          |
| FL05M      | 2016.09.09 | Mosquito    | ****          | 99.74      | USA: Florida          |
| FL06M      | 2016.09.20 | Mosquito    | ****          | 99.71      | USA: Florida          |
| FL08M      | 2016.10.05 | Mosquito    | ****          | 97.70      | USA: Florida          |
| ZC188Se    | 2016.01.16 | Serum       | ****          | 98.26      | Colombia              |
| ZC192Se    | 2016.01.07 | Serum       | ****          | 98.36      | Colombia              |
| ZC204Se    | 2016.01.06 | Serum       | ****          | 99.74      | Colombia              |
| ZC207Se    | 2016.01.09 | Serum       | ****          | 96.68      | Colombia              |
| ZC199Se    | 2016.01.10 | Serum       | ***           | 97.44      | Colombia              |
| Hu0046Sa   | 2017.04.18 | Saliva      | ****          | 98.20      | Cuba                  |
| FL046Se    | 2017.07.26 | Serum       | **            | 82.50      | Cuba                  |
| FL047U     | 2017.08.08 | Urine       | **            | 80.40      | Cuba                  |
| FL049U     | 2017.09.24 | Urine       | ****          | 96.00      | Cuba                  |
| FL051Se    | 2017.07.17 | Serum       | ****          | 98.40      | Cuba                  |
| FL052U     | 2017.08.05 | Urine       | **            | 86.50      | Cuba                  |
| FL055Se    | 2017.08.13 | Serum       | ****          | 96.80      | Cuba                  |
| FL057U     | 2017.07.17 | Urine       | **            | 93.80      | Cuba                  |
| FL082      | 2017-10-09 | Urine       | **            | 98.20      | Cuba                  |
| FL257      | 2018-01-18 | Urine       | **            | 98.30      | Cuba                  |

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

---
**Andersen Lab**  
The Scripps Research Institute  
La Jolla, CA, USA  
[data@andersen-lab.com](mailto:data@andersen-lab.com)
