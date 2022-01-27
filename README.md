# Residential-Load-Dataet
## MicroFEWs project

The MicroFEWs project aims to improve food-energy-water system dynamics in the small cold region communities. One of the aspects of the project is to acquire and monitor data that is necessary to understand and characterize existing food-energy-water nexus in remote communities. For this reason, the power and energy flow around existing food, energy, and water infrastructure loads are metered and logged.

The dataset available in this repository is one such energy consumption dataset logged at one of the households in Fairbanks, AK using the IoTAwatt WiFi energy monitoring system. The household also has wastewater treatment installed on-premise. The original resolution of the dataset is 10 seconds which is downsampled to 10 minutes. The dataset is available from April 16, 2021, to September 17, 2021. The dataset contains active power consumption P in (Watts).

This dataset is used to train and test Hampel filter based two stage long short-term memory (LSTM) based recurrent neural network (RNN) to forecast residential energy consumption pattern.

Funding: The residential energy consumption data acquisition and monitoring is funded by the National Science Foundation Award #1740075 InFEWS/T3: MicroFEWs

For more details or questions about the dataset, contact Chinmay Shah (cshah@alaska.edu).
