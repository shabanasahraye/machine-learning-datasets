# El Nino-Southern Oscillation (ENSO) Data
ENSO Related Monthly Climate Data (1950-2026)


### Context
ENSO is a periodic fluctuation (i.e., every 2–7 years) in winds and sea surface temperatures over the tropical eastern Pacific Ocean, affecting the climate of many parts of the world. It is one of the main drivers of interannual climate variability on Earth and influences global weather patterns, including temperature and precipitation anomalies. 

This dataset contains ENSO indicators and related data for analyzing and forecasting ENSO and its global impacts. 


### Content
The dataset contains ENSO-related climate data from 1950–2026, sourced from NOAA (National Oceanic and Atmospheric Administration) and related official climate datasets. 

#### ENSO Indicator Columns

- **ONI**
  - Oceanic Niño Index
  - 3-month running mean of Niño 3.4 SST anomalies
  - official ENSO classification index

- **RONI**
  - Relative Oceanic Niño Index
  - adjusted version of ONI
  - reduces baseline bias in SST anomalies
  - de-facto ENSO classification index used by NOAA 

- **Nino 3.4 SST**
  - Niño 3.4 Region Sea Surface Temperature
  - main ENSO monitoring region (5°N–5°S, 170°W–120°W)

- **Nino 3.4 SST Anomaly**
  - Niño 3.4 Region Sea Surface Temperature Anomaly
  -  best indicator of ENSO strength

- **MEI.ext**
  - Multivariate ENSO Index Extended
  - multivariate index combining SST, winds, pressure, OLR
  - captures full ENSO system behavior

- **MEI.v2**
  - Multivariate ENSO Index Version 2
  - improved version of MEI.ext with updated datasets
  - more robust ENSO representation

- **BEST**
  - Bivariate ENSO Timeseries
  - combines SOI + Niño 3.4 SST
  - balances atmospheric + oceanic ENSO signals

- **Nino 3 SST**
  - Niño 3 Region Sea Surface Temperature
  - Eastern Pacific ENSO region
  - captures classical El Niño warming

- **Nino 3 SST Anomaly**
  - Niño 3 Region Sea Surface Temperature Anomaly

- **Nino 4 SST**
  - Niño 4 Region Sea Surface Temperature
  - Western Pacific ENSO region
  - captures Modoki-type ENSO events

- **Nino 4 SST Anomaly**
  - Niño 4 Region Sea Surface Temperature Anomaly

- **Nino 1+2 SST**
  - Niño 1+2 Region Sea Surface Temperature
  - closest to South American coast
  - highly variable, responds strongly to El Niño

- **Nino 1+2 SST Anomaly**
  - Niño 1+2 Region Sea Surface Temperature Anomaly

- **TNI**
  - Trans-Niño Index
  - tracks ENSO development phase shift
  - measures spatial migration of warming

- **SOI**
  - Southern Oscillation Index
  - atmospheric ENSO component
  - Negative SOI = El Niño conditions

- **OLR**
  - Outgoing Longwave Radiation
  - proxy for cloudiness and convection
  - low OLR = strong convection (El Niño signals)

- **ENSO Precipitation Index**
  - measures rainfall anomalies in tropical Pacific
  - captures ENSO-driven precipitation shifts

- **PNA**
  - Pacific–North American Index
  - North Pacific–North America circulation pattern
  - ENSO affects its phase and strength

- **NOI**
  - Northern Oscillation Index
  - measures atmospheric pressure differences in Pacific
  - linked to ENSO-related circulation changes


#### Other columns:

- **ENSO Phase–Intensity (ONI-based)**
  - classification target variable for ENSO prediction
  - represents both the phase and intensity of ENSO conditions based on ONI <br>
    VSE → Very Strong El Niño <br>
    SE → Strong El Niño <br>
    ME → Moderate El Niño <br>
    WE → Weak El Niño <br>
    SL → Strong La Niña <br>
    ML → Moderate La Niña <br>
    WL → Weak La Niña <br>
    N → Neutral

- **ENSO Phase–Intensity (RONI-based)**
  - classification target variable for ENSO prediction
  - represents both the phase and intensity of ENSO conditions based on RONI

- **Global Temperature Anomaly (Land & Ocean)**
  - represents the global average temperature anomaly across land and ocean surfaces

- **Date**
  - format: MM-DD-YYYY

- **Month**
  - format: MMM
  - JAN–DEC

- **Year**
  - YYYY

- **Season (2-month)**
  - represents a 2-month rolling or grouped average
  - for indices like MEI.ext and MEI.v2

- **Season (3-month)**
  - represents a 3-month running mean
  - for indices like ONI and RONI

- **Season (12-month)**
  - represents a 12-month running mean
  - used for long-term ENSO variability and phase persistence 


### Acknowledgements
- NOAA – National Oceanic and Atmospheric Administration


### References

[1] NOAA Physical Sciences Laboratory (PSL), "Climate Indices: Monthly Atmospheric and Ocean Time Series." [Online]. Available: https://psl.noaa.gov/data/timeseries/month/

[2] NOAA Physical Sciences Laboratory (PSL), "Monthly Climate/Ocean Indices (Time-Series) at PSL." [Online]. Available: https://psl.noaa.gov/data/climateindices/list

[3] Golden Gate Weather Services, "El Niño and La Niña Years and Intensities Based on Oceanic Niño Index (ONI) " [Online]. Available: https://ggweather.com/enso/oni.htm

[4] Golden Gate Weather Services, "El Niño and La Niña Years and Intensities Based on Relative Oceanic Niño Index (RONI) " [Online]. Available: https://ggweather.com/enso/roni.htm
