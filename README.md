This repository contains the database and R script for the following systematic map of evidence

---

Jake M. Martin<sup>1,2,3,4</sup>, Marcus Michelangeli<sup>1,3,5</sup>, Michael G. Bertram<sup>1,3,4</sup>, Paul J. Blanchfield<sup>6</sup>, Jack A. Brand<sup>1,7</sup>, Tomas Brodin<sup>1</sup>, Bryan W. Brooks<sup>8,9</sup>, Daniel Cerveny<sup>1,10</sup>, Kate N. Fergusson<sup>3</sup>, Malgorzata Lagisz<sup>11</sup>, Lea M. Lovin<sup>1,8</sup>, Isaac Y. Ligocki<sup>12</sup>, Shinichi Nakagawa<sup>11</sup>, Shiho Ozeki<sup>3</sup>, Natalia Sandoval-Herrera<sup>1</sup>, Kendall R. Scarlett<sup>8,13</sup>, Josefin Sundin<sup>14</sup>, Hung Tan<sup>3,15</sup>, Eli S.J. Thoré<sup>1,16,17</sup>, Bob B.M. Wong<sup>3</sup>, Erin S. McCallum<sup>1</sup> Evidence of the Impacts of Pharmaceuticals on Aquatic Animal Behaviour EIPAAB a systematic map and open access database (*DOI to be added*)

---

## Overview

The R script is designed to act as a starting point for anyone who wishes to use the 'Evidence of the Impacts of Pharmaceuticals on Aquatic  Animal Behaviour' (EIPAAB) database for their own projects. 

In breif, to create the database we systematically searched two electronic databases (Web of Science and Scopus) and supplemented these with additional article sources. The search string followed a Population–Exposure–Comparison–Outcome (PECO) framework to capture articles that used an aquatic organism (population) to test the effects of a pharmaceutical (exposure) on behaviour (outcome). Eligible articles also needed a control group (comparison). Articles were screened in two stages: an initial screening of title and abstract, followed by full-text screening alongside data extraction. Decision trees were designed a priori to appraise eligibility at both stages. Information on study validity was collected but not used as a basis for inclusion.

## EIPAAB database structure
The 'Evidence of the Impacts of Pharmaceuticals on Aquatic  Animal Behaviour' (EIPAAB) database has 96 columns and 1754 rows. The columns represent various forms of metadata extracted from articles as dsiribed in Martin et al 2024.

The READ-ME.csv file explains what each metadata is, how it was extracted, what structure it has, and at what level it applies. I highly recommend you read the READ-ME.csv before conducting any of your own meta-anaylsis to make sure you have interoperated the data correctly.  

More generally, column names that start with 'validity' are metadata relating to study validity, those that start with 'specie's relate to species information (population), those that start with 'compound' relate to the chemical information (exposure), those that start with 'behav' relate to behaviour information (outcome). The order of columns reflects both the level the metadata is extracted at (i.e. article level or species by compound level; see level in READ-ME), as well as the general category of metadata (i.e. validity, species, compound, behaviour).

## Contact information
This script was authored by Jake M Martin (jakemartin.org)

Contact: jake.martin@deakin.edu or jake.martin@slu.se

## Affiliations
1. Department of Wildlife, Fish and Environmental Studies, Swedish University of Agricultural Sciences, Umeå, Sweden
2. School of Life and Environmental Sciences, Deakin University, Waurn Ponds, Australia
3. School of Biological Sciences, Monash University, Melbourne, Victoria, Australia
4. Department of Zoology, Stockholm University, Stockholm, Sweden
5. School of Environment and Science, Griffith University, Nathan 4111, Australia
6. Fisheries and Oceans Canada, Freshwater Institute, Winnipeg, Manitoba, R3T 2N6, Canada
7. Institute of Zoology, Zoological Society of London, London, United Kingdom
8. Department of Environmental Science, Baylor University, Waco, Texas 76798 USA
9. Guangdong Key Laboratory of Environmental Pollution and Health, School of Environment, Jinan University, Guangzhou, China
10. University of South Bohemia in Ceske Budejovice, Faculty of Fisheries and Protection of Waters, South Bohemian Research Center of Aquaculture and Biodiversity of Hydrocenoses, Zatisi 728/II, Vodnany, Czech Republic
11. Evolution and Ecology Research Centre, School of Biological, Earth and Environmental Sciences, University of New South Wales, Sydney, NSW, Australia
12. Department of Biology, Millersville University, Millersville, Pennsylvania, USA.
13. Environment Protection Authority, EPA Office of Water, Office of Science and Technology
14. Department of Aquatic Resources, Swedish University of Agricultural Sciences, Drottningholm, Sweden
15. Environment Protection Authority Victoria, EPA Science, Macleod, Victoria, Australia
16. TRANSfarm - Science, Engineering, & Technology Group, KU Leuven, Lovenjoel 3360, Belgium
17. Department of Biology, University of Namur, Namur, Belgium
