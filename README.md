# MicroFEWS-FBX-Residential-Load-Extraction-2021

This is a 5 month extraction from single residential load data for a house in Fairbanks Alaska and used to help train a machine learning algorithm. The data provided is from a larger data collection done from the NSF MicroFEWS project.  The MicroFEWs project aims to improve food-energy-water system dynamics in the small cold region communities. One of the aspects of the project is to acquire and monitor data that is necessary to understand and characterize existing food-energy-water nexus in remote communities. For this reason, the power and energy flow around existing food, energy, and water infrastructure loads are metered and logged.

The dataset available in this repository is one such energy consumption dataset logged at one of the households in Fairbanks, AK using the IoTAwatt WiFi energy monitoring system. The household also has wastewater treatment installed on-premise. The original resolution of the dataset is 10 seconds which is downsampled to 10 minutes. The dataset is available from April 16, 2021, to September 17, 2021.

This dataset is used to train and test long short-term memory (LSTM) based recurrent neural network (RNN) to forecast residential energy consumption pattern.

## License and Credits

This data used by this project was funded by the National Science Foundation Award #1740075 InFEWS/T3: Coupling infrastructure improvements to food-energy-water system dynamics in small cold region communities: MicroFEWs.

The data is copyright University of Alaska Fairbanks - Alaska Center for Energy and Power

This data is shared out under a [Creative Commons Share-Alike 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)
You may: 
* **Share** — copy and redistribute the material in any medium or format
* **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.
As long as:
* **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

For more details or questions about the dataset, contact Chinmay Shah (cshah@alaska.edu).
