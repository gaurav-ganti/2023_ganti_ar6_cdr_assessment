# Evaluating gross CDR deployment in AR6 pathways
This repository accompanies the paper:
> Ganti, G., Gasser, T., Bui, M., Lamb, W., Minx, J., Schleussner, C., Gidden, M., Meeting global climate objectives requires scaling gross carbon removal. DOI: TODO

## Data and citations

To replicate the analysis here, you will need the following data files. Please update the file paths in the ```env.sample``` file we have provided and rename it to ```.env```

|File name|Link to file|
|---------|------------|
|`gidden_et_al_2022_ar6_reanalysis_data.csv`|https://data.ece.iiasa.ac.at/genie/|
|`gidden_et_al_2022_ar6_reanalysis_meta.csv`|https://data.ece.iiasa.ac.at/genie/|
|`AR6_Scenarios_Database_World_v1.1.csv`|https://data.ene.iiasa.ac.at/ar6/#/downloads|
|`AR6_Scenarios_Database_R5_regions_v1.1.csv`|https://data.ene.iiasa.ac.at/ar6/#/downloads|
|`AR6_Scenarios_Database_metadata_indicators_v1.1.xlsx`|https://data.ene.iiasa.ac.at/ar6/#/downloads|

### Data references
> Gidden, M. J., Gasser, T., Grassi, G., Forsell, N., Janssens, I., Lamb, W. F., Minx, J., Nicholls, Z., Steinhauser, J., & Riahi, K. (2023). Aligning climate scenarios to emissions inventories shifts global benchmarks. Nature, 1–7. https://doi.org/10.1038/s41586-023-06724-y

> Riahi, K. et al. Mitigation pathways compatible with long-term goals. in IPCC, 2022: Climate Change 2022: Mitigation of Climate Change. Contribution of Working Group III to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change (eds. Shukla, P. R. et al.) (Cambridge University Press, 2022). doi:10.1017/9781009157926.005.

> Byers, E. et al. AR6 Scenarios Database. (2022) doi:10.5281/zenodo.5886912.

## Note

Please refer to the ```README.md``` file in the `analysis` folder for instructions on individual analysis steps.

## Installation

```
$ conda env create --file environment.yml
$ conda activate ar6_cdr_assessment
```