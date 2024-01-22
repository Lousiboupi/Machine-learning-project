# Production data forecast using data-driven approaches 

The relationship between petrophysical parameters, production conditions and hydrocarbon volumes is non-linear. It can be challenging to propose a relationship between them with conventional mathematical approaches. Therefore, data-driven approaches, such as Machine Learning, can capture the relationship between these parameters, and propose predictions of produced volumes. ​

This mini-project focus on developing predictions using production data from a single well in the Volve field. The independent variables for this problem include downhole pressure, temperature and fluid production volumes. Participants are encouraged to apply diverse supervised ML techniques to forecast the hydrocarbon production of a well in the Volve field. ​

**Case Study:**
**Proposed Machine Learning Methods:** Linear regression / Ridge regression / Random Forest / Neural networks (Deep Learning) 

## The data 

The dataset includes: 

- DATEPRD: Date of observation
- WELL_BORE_CODE: Wellbore identifier
- NPD_WELL_BORE_CODE: Wellbore code (Norwegian Petroleum Directorat) 
- NPD_WELL_BORE_NAME: Wellbore name (Norwegian Petroleum Directorat) 
- NPD_FIELD_CODE: Field code (Norwegian Petroleum Directorat) 
- NPD_FIELD_NAME: Field name (Norwegian Petroleum Directorat) 
- NPD_FACILITY_CODE: Facility code (Norwegian Petroleum Directorat) 
- NPD_FACILITY_NAME: Facility name (Norwegian Petroleum Directorat) 
- ON_STREAM_HRS: Total hours on stream (per day)
- AVG_DOWNHOLE_PRESSURE: Average Downhole Pressure
- AVG_DOWNHOLE_TEMPERATURE: Average Downhole Temperature
- AVG_DP_TUBING: Average Differential Pressure of Tubing 
- AVG_ANNULUS_PRESS: Average Annular Pressure
- AVG_CHOKE_SIZE_P: Average Choke Size Percentage
- AVG_CHOKE_UOM: Unit Of Measurement
- AVG_WHP_P: Average Well Head Pressure
- AVG_WHT_P: Average Well Head Temperature
- BORE_OIL_VOL: Oil Volume from Well
- BORE_GAS_VOL: Gas Volume from Well
- BORE_WAT_VOL: Water Volume from Well
- BORE_WI_VOL: Water Volume Injected 
- FLOW_KIND: Type of flow (production / injection)
- WELL_TYPE: Type of Well (oil production / water injection)




The data is licensed under the Equinor Open Data Licence.

Details for the Volve Field and the entire dataset can be found at: https://www.equinor.com/en/what-we-do/norwegian-continental-shelf-platforms/volve.html
