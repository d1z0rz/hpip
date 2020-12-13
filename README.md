# Eurostat-HPIP
House Price Index Prediction
 
Repository contains all files corresponding to the course project for [UT Introduction to Data Science](https://courses.cs.ut.ee/2020/ids/fall)

_Note: Data used in the project is taken from [eurostat database](https://ec.europa.eu/eurostat/data/database)._

## Project Content

- ### Structure
   ```
   project-folder
   └── data - datasets
   ```

- ### Provided Data
	- [house_price_index](https://ec.europa.eu/eurostat/databrowser/view/prc_hpi_a/default/table?lang=en): House price index (2015 = 100) - annual data
	- [unemployment](https://ec.europa.eu/eurostat/databrowser/product/view/une_rt_a?lang=en): Unemployment by sex and age – annual data
	- [income](https://ec.europa.eu/eurostat/databrowser/product/view/ilc_di03?lang=en):  Mean and median income by age and sex - EU-SILC and ECHP surveys
	- [air_transport_national](https://ec.europa.eu/eurostat/databrowser/view/avia_tppa/default/table?lang=en): Passenger air transport over national territory (including territorial sea) - million passenger-km
	- [tax_revenues](https://ec.europa.eu/eurostat/databrowser/view/env_ac_tax/default/table?lang=en): Environmental tax revenues
	- [average_working_hours](https://ec.europa.eu/eurostat/databrowser/view/lfsa_ewhun2/default/table?lang=en): Average number of usual weekly hours of work in main job
	- [managment_waste](https://ec.europa.eu/eurostat/databrowser/view/env_wassd/default/table?lang=en): Management of waste by waste management operations
	- [pupulation_by_education](https://ec.europa.eu/eurostat/databrowser/product/view/edat_lfse_03?lang=en): Population by educational attainment level
	- [waste_electrical](https://ec.europa.eu/eurostat/databrowser/view/env_waselee/default/table?lang=en): Waste electrical and electronic equipment (WEEE)
	- [crime_area](https://ec.europa.eu/eurostat/databrowser/product/view/ilc_mddw03?lang=en): Crime, violence or vandalism in the area
	- [resource_prodictivity](https://ec.europa.eu/eurostat/databrowser/view/env_ac_rp/default/table?lang=en): Resource productivity
	- [air_pollutants](https://ec.europa.eu/eurostat/databrowser/view/env_air_emis/default/table?lang=en): Air pollutants by source sector (source: EEA)
	- [air_emissions](https://ec.europa.eu/eurostat/databrowser/view/env_ac_aeint_r2/default/table?lang=en): Air emissions intensities by NACE Rev. 2 activity
	- [human_science](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=hrst_st_ncat&lang=en): Human resources in science and technology 
	- [broadband_households](https://ec.europa.eu/eurostat/databrowser/view/isoc_bde15b_h/default/table?lang=en): Broadband and connectivity - households
	- [e_techs](https://ec.europa.eu/eurostat/databrowser/view/isoc_bde15cbc/default/table?lang=en): E-banking and e-commerce
	- [life_expectancy](https://ec.europa.eu/eurostat/databrowser/view/demo_mlexpec/default/table?lang=en): Life expectancy by age and sex

- ### Data preparation
  [Notebook](https://github.com/d1z0rz/hpip/blob/master/Dataset_Formatting.ipynb)
- ### Data Analysis and Visualization
  [Notebook](https://github.com/d1z0rz/hpip/blob/master/Correlations%20and%20visualisation.ipynb)
- ### Models and Results
  [Notebook](https://github.com/d1z0rz/hpip/blob/master/Models.ipynb)

