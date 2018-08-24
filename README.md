## Flight data for ML-prediction challenge at the TWIST2018-Hackdays

This repository contains data of planed and effective flight arrival and departure-times from / to the airport of Zurich for the entire year 2017. 

The R-Script **data_enrichment.R** contains the code used to add the airport coordinates, calculate approximative flight-distances, time-differences between scheduled and effective flight-times as well as information on weather-conditions around the airport provided by meteoswiss. The dataset does not yet contain information on general weather and atmospheric conditions other than those at the local scale. 

The RDS-file **twist_zrh.RDS** contains the resulting R-dataframe. For those relying on other tools than r, a csv-version of the dataset is also available: **twist_zrh.csv**

metadata.txt contains a detailed description of the variables contained in the file. 

# Titel
	Flights from / to Zurich Airport
- Description:
	Dataset of flights from / to Zurich airport enriched with data from the origin/destination airports, calculated distances as well as weather-data from meteoswiss.
- Publizierende Organisation	Specialist & Coordination Unit for Open Government Data of the Canton of Zurich
- E-Mail-Adresse für Fragen zum Datensatz	info@open.zh.ch
- Datum der erstmaligen Publikation des Datensatzes	24.08.2018
- Datum der letztmaligen Anpassung des Datensatzes	24.08.2018
- Sprache des Datensatzes	English
- Zeitliche Abdeckung des Datensatzes	01.01.2017 - 31.12.2017
- Aktualisierungsfrequenz des Datensatzes	exclusively for the TWIST-Hackathon
- Datum der erstmaligen Publikation der Primärdaten des Datensatzes	24.08.2018
- Nutzungsbedingung, unter der die Primärdaten wiederverwendet werden dürfen	Freie Nutzung

Further sources for weather data at global scale or atmospheric conditions:

- meteorogical conditions on the ground via NASApower: https://adamhsparks.github.io/nasapower/

- atmospheric conditions via: http://www.wmo.int/pages/prog/www/GOS/ABO/data/ABO_Data_Access.html#gts
