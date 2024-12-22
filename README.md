# Thai Non-Glutinous Paddy Rice Price Analysis and Influencing Factors

The analysis of non-glutinous paddy rice prices in Thailand is crucial for understanding the dynamics of one of the country's most important agricultural commodities. This study aims to observe the factors influencing Non-Glutinous Paddy rice price., providing insights into the market conditions, production inputs, and socio-economic elements that shape price fluctuations. By utilizing machine learning, Linear Regrssion, ARCH and GARCH models will be developed to forecast rice prices based on different categories of features, Production Index, Export and Finance indicator,and Water and Fertilizer.


## Data Collection
Frequency : Monthly
Period : January 2006 to October 2024
Source : Central Bank of Thailand, Office of Agriculutural Economics, Trade Policy and Stategy Office, and Egat Water Intelligance Center

## Data Dictionary

| Feature Name            | Data Type   | Description                                                    |
|-------------------------|-------------|----------------------------------------------------------------|
| nonglu_price            | float64     | Price of Non-glutinous Rice Paddy at farm gate (Baht per ton)   |
| hommali_price           | float64     | Price of Thai Hom Mali rice Paddy at farm gate (Baht per ton)   |
| agri_prod_index         | float64     | Agriculture Production Index                                    |
| crops_prod_index        | float64     | Crops Production Index                                          |
| paddy_prod_index        | float64     | Rice Paddy Production Index                                     |
| nonglu_prod_index       | float64     | Non-glutinous Rice Paddy Production Index                       |
| hommali_prod_index      | float64     | Thai Hom Mali Rice Paddy Production Index                       |
| agri_export_value       | float64     | Export value of agricultural products (million USD)             |
| rice_export_value       | float64     | Export value of Rice (million USD)                              |
| rice_export_amount      | float64     | Export Amount of Rice (metric ton)                              |
| inflation               | float64     | Inflation Rate                                                  |
| cpi_rice                | float64     | Rice Consumer Price Index                                       |
| pol_rate                | float64     | Policy Rate                                                     |
| neer                    | float64     | Nominal Effective Exchange rate                                 |
| reer                    | float64     | Real Effective Exchange rate                                    |
| shock_event_1           | float64     | The begining of 2008 Food crisis                                |
| shock_event_2           | float64     | The end of 2008 Food crisis                                     |
| shock_event_3           | float64     | Indian Restrictions lifted on rice exports                      |
| shock_event_4           | float64     | Indian restrictions removed on non-basmati rice exports         |
| sirikit_water           | float64     | Volume of Water in Sirikit Dam (million cubic meters)           |
| bhumibol_water          | float64     | Volume of Water in Bhumibol Dam (million cubic meters)          |
| fertilizer_1            | float64     | Local Retail Price of 21-0-0 fertilizer (Baht per ton)          |
| fertilizer_2            | float64     | Local Retail Price of 46-0-0 fertilizer (Baht per ton)          |
| fertilizer_3            | float64     | Local Retail Price of 16-20-0 fertilizer (Baht per ton)         |
| fertilizer_4            | float64     | Local Retail Price of 16-16-8 fertilizer (Baht per ton)         |
| fertilizer_5            | float64     | Local Retail Price of 15-15-15 fertilizer (Baht per ton)        |
| fertilizer_6            | float64     | Local Retail Price of 13-13-21 fertilizer (Baht per ton)        |
| water_station_B10       | float64     | Level of water at station B10 (million cubic meters)            |
| water_station_C13       | float64     | Level of water at station C13 (million cubic meters)            |
| water_station_C2        | float64     | Level of water at station C2 (million cubic meters)             |
| water_station_G8        | float64     | Level of water at station G8 (million cubic meters)             |
| water_station_K10       | float64     | Level of water at station K10 (million cubic meters)            |
| water_station_K11A      | float64     | Level of water at station K11A (million cubic meters)           |
| water_station_Kgt3      | float64     | Level of water at station Kgt3 (million cubic meters)           |
| water_station_Kh103     | float64     | Level of water at station Kh103 (million cubic meters)          |
| water_station_Kh58A     | float64     | Level of water at station Kh58A (million cubic meters)          |
| water_station_Kh72      | float64     | Level of water at station Kh72 (million cubic meters)           |
| water_station_M6A       | float64     | Level of water at station M6A (million cubic meters)            |
| water_station_M7        | float64     | Level of water at station M7 (million cubic meters)             |
| water_station_N1        | float64     | Level of water at station N1 (million cubic meters)             |
| water_station_N67       | float64     | Level of water at station N67 (million cubic meters)            |
| water_station_Ny1B      | float64     | Level of water at station Ny1B (million cubic meters)           |
| water_station_P1        | float64     | Level of water at station P1 (million cubic meters)             |
| water_station_P17       | float64     | Level of water at station P17 (million cubic meters)            |
| water_station_S4B       | float64     | Level of water at station S4B (million cubic meters)            |
| water_station_Sw5A      | float64     | Level of water at station Sw5A (million cubic meters)           |
| water_station_Y17       | float64     | Level of water at station Y17 (million cubic meters)            |
| water_station_Y1C       | float64     | Level of water at station Y1C (million cubic meters)            |



# Result
1. The Linear Regression Model using Export and Finance features results the best forecast among the combination of model and feature categories (Highest R-squared)
2. International shock event features, 2008 Food crisis and India export restriction, have strong influence to Non-Glutinous Paddy Price 

# Future research 
1. Considering Competitors data (Indian and Vietnam). For example, Export value and Amount, Inflation rate, Food Security Index
2. Considering Thai Government Policy, subsidies and support programs. For example, Paddy Price Insurance.


