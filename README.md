# SWAT-Canopy-Interception
This repository contains an .exe file with a modified canopy interception and evaporation method for the SWAT model.

To run the model, the user needs to (1) drop the .exe into a TxtInOut SWAT project folder, and (2) calibrate the parameter "c" of equation 11. To change the value of c, the user can use the parameter canmx.hru in the default versions of SWAT. Calibrated values of c can be found in Table 3 for a wide range of physical landscape charactersicts.

Citation: Haas, H., Kalin, L., Yen, H., 2024. Improved forest canopy evaporation leads to better predictions of ecohydrological processes. Ecological Modelling 489, 110620. https://doi.org/10.1016/j.ecolmodel.2024.110620
