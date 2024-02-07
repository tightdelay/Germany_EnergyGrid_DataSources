# Germany_TSO_geojson
German TSO geojson dataTransmission System Operator 


Links (11.01.2024):
|zone                 |    link                                                      |
|:-----------------|:----------------------------------------------------------|
|DE_50HZ      |     https://www.smard.de/app/map_data/50Hertz.geo.json   |
|DE_AMPRION   |     https://www.smard.de/app/map_data/Amprion.geo.json   |
|DE_TENNET    |     https://www.smard.de/app/map_data/TenneT.geo.json    |
|DE_TRANSNET  |     https://www.smard.de/app/map_data/TransnetBW.geo.json| 


```bash
├── GeoJson                                     -- geojson data from SMARD (retrieved 11.01.2024)
    ├── 50Hertz.geo.json                            -- https://www.smard.de/app/map_data/50Hertz.geo.json
    ├── Amprion.geo.json                            -- https://www.smard.de/app/map_data/Amprion.geo.json  
    ├── TenneT.geo.json                             -- https://www.smard.de/app/map_data/TenneT.geo.json 
    ├── TransnetBW.geo.json                         -- https://www.smard.de/app/map_data/TransnetBW.geo.json

├── powerplants.csv                                  -- https://www.bundesnetzagentur.de/SharedDocs/Downloads/DE/Sachgebiete/Energie/Unternehmen_Institutionen/Versorgungssicherheit/Erzeugungskapazitaeten/Kraftwerksliste/Kraftwerksliste_CSV.csv?__blob=publicationFile&v=2 (retrieved 05.02.2024)
├── requirements.txt                                -- required libraries
├── data                                            -- stores csv file 
├── plots                                           -- stores image files
└── src
    ├── prepare_source_data.ipynb                   -- preprocesses data
    ├── data_preparation.ipynb                      -- preparing datasets
    ├── model_tuning.ipynb                          -- tuning functions
    └── run_experiment.ipynb                        -- run experiments 
    └── plots                                       -- plotting functions                 
```