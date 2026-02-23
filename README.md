# LittleAuks_PairOverwintering

This repository is associated with the manuscript titled: "Together yet apart: subtle sex differences and pair cohesion in migrating and wintering strategies of a monomorphic seabird, the little auk (Alle alle)"

This repository is intended for the project on Little Auk pair overwintering. Firstly, we assessed sex differences in the little auks overwintering behaviour. Then, we planned to find out whether or not the pair stays together / meets along the way and how this may influence or is influenced by past and future breeding outcomes of the pair.

This repository is intended for the project on Little Auk pair overwintering. We would like to find out whether or not the pair stays together / meets along the way etc and how this may influence or is influenced by past and future breeding outcomes of the pair.

### 1-DataPreparation
This script creates the main data set for any follow-up scripts. I'm adding sex and nest information for any individual that misses this kind of information.

### 2-winteringCentroids
Here, we define the wintering centroids for the tracked individuals. Furthermore, the individuals are split into groups depending on their overwintering destinations (Icelandic Sea vs Labrador Sea).

### 3-KernelDensities-DensityPlots
In this script, we perform Kernel Density Estimations and create maps of the non-breeding distribution of the tracked individuals.

### 4-environmental_SST_AllColoniesAllYears
We are looking at the SST that the individuals encountered across all years of the study, and their differences between the overwintering locations and sexes.

### 6-within-pair_distances_FallMigration & 6-within-pair_distances_SpringMigration
This script calculates the within-pair distances per pair per year during fall/spring migration (in loops) using one mean estimated position per individual per day. We are looking at the months September to December and January to April for each year, respectively. (I excluded the month of May as the birds are already back at the colony and for 2023 there are big data gaps in it.)

### 7-distances_randomization
Here, we randomized the pairs to assess whether pairs are specifically formed due to their non-breeding behaviour and destinations or if it is random.

### 8-BreedingSuccess
Lastly, we looked at how breeding success influenced the non-breeding behaviour and vice versa.
