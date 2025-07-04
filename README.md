# Climate Variables from SENAMHI Augusto Weberbauer Station (Cajamarca, Peru), 1994–2024

This repository contains daily climate data collected over 31 years (1994–2024) from the **SENAMHI Augusto Weberbauer** meteorological station, located in **Cajamarca, Peru**. The dataset includes several key atmospheric variables that are essential for environmental and climate studies.

## Contents

- `dataset_raw_senamhi30years.xlsx`: Original raw data file as obtained from the station's archive.
- `dataset_preprocessed_senamhi30Year.xlsx`: Cleaned version of the dataset with missing values handled and standardized formats.
- `Dataset_Preprocess_Senamhi30Year.ipynb`: Jupyter notebook used to clean and process the raw data.
- `LICENSE`: License under which the dataset is distributed.
- `README.md`: This documentation file.

## Climate Variables

The dataset contains the following daily variables:

| Variable               | Description                       | Units             |
|------------------------|-----------------------------------|-------------------|
| `DailyPrecipitation`   | Daily precipitation               | mm                |
| `AverageTemperature`   | Mean daily air temperature        | °C                |
| `RelativeHumidity`     | Average daily relative humidity   | %                 |
| `AtmosphericPressure`  | Daily atmospheric pressure        | hPa               |
| `WindSpeed`            | Average daily wind speed          | m/s               |
| `SunshineHours`        | Daily sunshine duration           | hours             |

## Processing Details

All preprocessing steps, including handling of missing data, data type normalization, and column renaming, are documented in the [`Dataset_Preprocess_Senamhi30Year.ipynb`](./Dataset_Preprocess_Senamhi30Year.ipynb) notebook.

## Citation

If you use this dataset in your research or application, please cite it as:

> Valencia-Castillo, E., & Rodriguez-Avila, S. (2025). *Daily Climate Variables from the SENAMHI Augusto Weberbauer Station (Cajamarca, Peru), 1994–2024* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.15803716


## License

This dataset is made available under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to use, share, and adapt the data, provided appropriate credit is given.

---

**Authors and Affiliations**  
- Edwin Valencia-Castillo — Universidad Nacional de Cajamarca  
- Sandra Rodriguez-Avila — Universidad Nacional de Cajamarca  

**Contact**:  
- Edwin: [evalencia@unc.edu.pe]  
- Sandra: [srodriguez@unc.edu.pe]

