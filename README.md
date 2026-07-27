# Data for "Energy: "Measuring the impact of rising temperatures on energy consumption to target adaptation planning"

The following data files contain data underlying the Climate Impact Lab Adaptation Roadmap Report, July 2026: **_Energy: Measuring the impact of rising temperatures on energy consumption to target adaptation planning_**

For more about the report, see [here](https://impactlab.org/research/energy-measuring-the-impact-of-rising-temperatures-on-energy-consumption-to-target-adaptation-planning/). Click [here](https://impactlab.org/wp-content/uploads/2026/07/Adaptation-Roadmap_Energy-2026.pdf) to download the report.

The Climate Impact Lab makes data publicly available under the CC BY 4.0 license.

## Data Summary:

Data is based on the methods summarized in Rode et al. (2021). The data are the impacts of climate change on the consumption of electricity and heating fuels in 2050 (i.e., 20-year average of annual impacts (2040-2059)) under an emissions trajectory consistent with 3°C of warming by the end of the century. (The 3°C warming level represents an increase in Global mean Surface Air Temperature (GSAT) of 3°C at 2100 relative to a pre-industrial time period (1850-1900).) Energy consumption projections are based on Shared Socioeconomic Pathway 2 (SSP2 v1.1, IIASA), which includes population and GDP into the future, and account for adaptation due to income growth.

- **Domain**: global
- **Resolution**: CIL impact regions (to download the shapefile and learn more about impact regions, visit [here](https://github.com/ClimateImpactLab/data-impact-region-shapefile))
- **Time period**: 2050 (2040-2059 average)
## Data files
1. CIL_Energy_July2026-region_data.csv
2. CIL_Energy_July2026-country_data.csv

### 1. CIL_Energy_July2026-region_data.csv
Mean change in consumption of electricity and heating fuels for all Impact Regions.

#### Data fields:

- `region_id` - Unique Impact Region identifier
    - Description: The first three digits of the identifier align to the 3-digit ISO code for the country in which the region is based (ISO 3166-1 alpha-3). There are 24,378 Impact Regions across the globe.
- `mean_electricity` - Mean change in consumption of electricity.
    - Unit: GJ/capita
    - Description: Mean change in electricity consumption due to climate change. Negative values represent a net decrease in consumption. Positive values indicate a net increase in consumption.
- `mean_heatingfuels` - Mean change in consumption of heating fuels.
    - Unit: GJ/capita
    - Description: Mean change in heating fuels consumption due to climate change. Negative values represent a net decrease in consumption. Positive values indicate a net increase in consumption.
- `region_name` - Name of Impact Region
    - Description: Name of the impact region, which is based on ADM2 names.

### 2. CIL_Energy_July2026-country_data.csv
Population-weighted average of mean change in electricity and heating fuels consumption for all Impact Regions in specified countries. Populations are based on the SSP2 v1.1 IIASA projections for 2050.

#### Data fields:

- `Code` - 3 digit ISO country code
- `mean_electricity` - Population-weighted average of mean change in consumption of electricity for all Impact Regions within country borders.
- `mean_heatingfuels` - Population-weighted average of mean change in consumption of heating fuels for all Impact Regions within country borders.
----------
## References

Rode, Ashwin, et al. “Estimating a Social Cost of Carbon for Global Energy Consumption.” Nature 598, 308–314 (2021). https://doi.org/10.1038/s41586-021-03883-8
